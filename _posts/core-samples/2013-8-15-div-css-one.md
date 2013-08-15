---
layout: post
category : github_blog
tags : [intro,beginner,jekyll,githubblog]
---
{% include JB/setup %}

对第一次专门做前端的我，给我一张psd图让我切图，还真有点茫然，不知道从何做起，拿到这张psd图，然后一个流程是怎样的。
叫兽，只告诉我就是切成html，我知道要切成html，因为我理解的html比较肤浅就是所谓的html代码.听到这，我就纳闷了，资源已经有了，
切好的又都是table标签的布局的html代码，根本没用。因为我们通常是用div+css布局。那我就觉得这样为什么还要切呢。但是，叫兽也是很无语，
给我一张图，就是让我切成html，他理解的比较深入，他的意思应该是包括html的各种元素。我实在没办法，就照着自己想的，
自己用webstorm2+zencoding纯手写div+css的布局。后面有遇到问题，就请教典哥，典哥很认真的跟我讲了一下整个流程。灰常感谢。
叫兽也安排了另外一个同事具体的讲了一下切图的整个流程，很感谢这个课，讲的很好，让我对切图有了进一步的了解。
下面就总结下我自己对切图这部分的理解和心得


### 切图的流程：

- **弄清需求one**   
	1.首先要弄清，这个是手机端还是PC端的，PC端一般最小宽度是960px
	2.看下有几张设计图：认真观察设计图，要分析几个问题
	
	（1）设计图是否合理
	（2）是否有通用模块可以拿出来共用
	（3）是否要支持ie6
	（4）整体的字体大小，背景，链接；一般手机上默认字体是16px，PC默认字体是12px，微软雅黑的
	
- **写html**  
        git是本地和github上的库之间的传输工具。要先安装这个git工具，后期上传下载github.com上的库的内容都要用git命令
        下载地址:<https://help.github.com/articles/set-up-git>,可以在这个网址上去下载window上的git工具
- **css**    
        jekyll是一种静态网站生成器，这是在github上建立博客的前提。有关jekyll的教程：官网-<http://jekyllrb.com/>；
        中文教程：<http://higrid.net/c-art-blog_jekyll.htm#baseurl>
- **优化图片**    
        DevKit是windows平台下编译和使用本地C/C++扩展包的工具。它就是用来模拟Linux平台下的make,gcc,sh来进行编译。
        但是这个方法目前仅支持通过RubyInstaller安装的Ruby.这个是jekyll本地搭建环境必需的。RubyInstaller的下载地址：
        <http://rubyforge.org/frs/?group_id=167>;DevKit的下载地址：<https://github.com/oneclick/rubyinstaller/downloads/>

                    
### 网上其他博客遇到的一些问题：

- **第一篇博客one**  
        <http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html>这是我研究怎样写github博客看的第一篇文章。也照做了，
        但是遇到了一些问题，在执行“$ git checkout --orphan gh-pages”这步的时候，遇到了“You are on a branch yet to be born”；
        后面我就现在github.com上先建立了这个库jekyll_demo，就顺利通过了。解决了这个问题，跟着步骤，分支gh-pages都生成了，所有的页面
        也上传上去了，但是访问的时候，就是报404错误。这篇博客最终还是没试验成               
- **第二篇博客two**  
        因为第一篇博客没成功，后来问了下同事，推荐了一个博客，确实不错，<http://www.mceiba.com/develop/jekyll-introduction.html>;
        这篇博客下面的3分钟搭建Jekyll Blog，在git bash上对着敲那些命令，就可以了。但是这个过程中我遇到了一个问题，就是在执行
        $ git push origin master这个命令的时候，会报permission denied就是没有权限的意思了。这个是ssh key的问题。可以参考官方的
        <https://help.github.com/articles/generating-ssh-keys>进行解决，解决好后，重新用git bash工具进入要提交的目录，敲下这些命令
        ，访问username.github.com就可以顺利看到我们熟悉的`Hello   World`了 

### github上写博客的步骤：

*  **在本地搭建jekyll环境**  
        可以参考下<http://www.cnblogs.com/purediy/archive/2013/03/07/2948892.html>              
*  **在_post文件夹里面写自己的文章**    
        怎么写文章可以参考下，<https://github.com/plusjade/jekyll-bootstrap.git>这个clone下来后的代码 ,参考[markdown标签](http://wowubuntu.com/markdown/)  
*  **本地测试jekyll**  
    在安装好的ruby控制台上面,进入到项目的目录下，执行这个命令jekyll serve。声明下：我看到网上这些命令$ jekyll --server，是不成功的，
    我是直接输入jekyll serve这个命令后就可以执行了。这个命令输完之后，在浏览器上输入http://localhost:4000，就可以访问了。_site目录
    是最终的静态网页.在访问的时候可能出现乱码问题，修改下_includes/themes/default.html的编码就可以了，改成gb2312。还有遇到一些中文标题，列表无效，一个标题里面要
	含有英文才可以正常有列表的样式。
*  **git提交**  
        最后使用git工具提交到github.com上       
        从github.com下载文件的git命令如下:   
		<pre><code>git clone https://github.com/zms91/---.git</code></pre>
        从本地上传文件到github.com的git命令:
		
		
        git init
        git add .
        git commit -m 
        git push
    

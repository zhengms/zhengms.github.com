---
layout: post
category : github_blog
tags : [intro,beginner,jekyll,githubblog]
---
{% include JB/setup %}

�Ե�һ��ר����ǰ�˵��ң�����һ��psdͼ������ͼ�������е�ãȻ����֪���Ӻ������õ�����psdͼ��Ȼ��һ�������������ġ�
���ޣ�ֻ�����Ҿ����г�html����֪��Ҫ�г�html����Ϊ������html�ȽϷ�ǳ������ν��html����.�����⣬�Ҿ������ˣ���Դ�Ѿ����ˣ�
�кõ��ֶ���table��ǩ�Ĳ��ֵ�html���룬����û�á���Ϊ����ͨ������div+css���֡����Ҿ;�������Ϊʲô��Ҫ���ء����ǣ�����Ҳ�Ǻ����
����һ��ͼ�����������г�html�������ıȽ����룬������˼Ӧ���ǰ���html�ĸ���Ԫ�ء���ʵ��û�취���������Լ���ģ�
�Լ���webstorm2+zencoding����дdiv+css�Ĳ��֡��������������⣬����̵�磬��������ĸ��ҽ���һ���������̡��ҳ���л��
����Ҳ����������һ��ͬ�¾���Ľ���һ����ͼ���������̣��ܸ�л����Σ����ĺܺã����Ҷ���ͼ���˽�һ�����˽⡣
������ܽ������Լ�����ͼ�ⲿ�ֵ������ĵ�


### ��ͼ�����̣�

- **Ū������one**   
	1.����ҪŪ�壬������ֻ��˻���PC�˵ģ�PC��һ����С�����960px
	2.�����м������ͼ������۲����ͼ��Ҫ������������
	
	��1�����ͼ�Ƿ����
	��2���Ƿ���ͨ��ģ������ó�������
	��3���Ƿ�Ҫ֧��ie6
	��4������������С�����������ӣ�һ���ֻ���Ĭ��������16px��PCĬ��������12px��΢���źڵ�
	
- **дhtml**  
        git�Ǳ��غ�github�ϵĿ�֮��Ĵ��乤�ߡ�Ҫ�Ȱ�װ���git���ߣ������ϴ�����github.com�ϵĿ�����ݶ�Ҫ��git����
        ���ص�ַ:<https://help.github.com/articles/set-up-git>,�����������ַ��ȥ����window�ϵ�git����
- **css**    
        jekyll��һ�־�̬��վ��������������github�Ͻ������͵�ǰ�ᡣ�й�jekyll�Ľ̳̣�����-<http://jekyllrb.com/>��
        ���Ľ̳̣�<http://higrid.net/c-art-blog_jekyll.htm#baseurl>
- **�Ż�ͼƬ**    
        DevKit��windowsƽ̨�±����ʹ�ñ���C/C++��չ���Ĺ��ߡ�����������ģ��Linuxƽ̨�µ�make,gcc,sh�����б��롣
        �����������Ŀǰ��֧��ͨ��RubyInstaller��װ��Ruby.�����jekyll���ش��������ġ�RubyInstaller�����ص�ַ��
        <http://rubyforge.org/frs/?group_id=167>;DevKit�����ص�ַ��<https://github.com/oneclick/rubyinstaller/downloads/>

                    
### ������������������һЩ���⣺

- **��һƪ����one**  
        <http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html>�������о�����дgithub���Ϳ��ĵ�һƪ���¡�Ҳ�����ˣ�
        ����������һЩ���⣬��ִ�С�$ git checkout --orphan gh-pages���ⲽ��ʱ�������ˡ�You are on a branch yet to be born����
        �����Ҿ�����github.com���Ƚ����������jekyll_demo����˳��ͨ���ˡ������������⣬���Ų��裬��֧gh-pages�������ˣ����е�ҳ��
        Ҳ�ϴ���ȥ�ˣ����Ƿ��ʵ�ʱ�򣬾��Ǳ�404������ƪ�������ջ���û�����               
- **�ڶ�ƪ����two**  
        ��Ϊ��һƪ����û�ɹ�������������ͬ�£��Ƽ���һ�����ͣ�ȷʵ����<http://www.mceiba.com/develop/jekyll-introduction.html>;
        ��ƪ���������3���ӴJekyll Blog����git bash�϶�������Щ����Ϳ����ˡ����������������������һ�����⣬������ִ��
        $ git push origin master��������ʱ�򣬻ᱨpermission denied����û��Ȩ�޵���˼�ˡ������ssh key�����⡣���Բο��ٷ���
        <https://help.github.com/articles/generating-ssh-keys>���н��������ú�������git bash���߽���Ҫ�ύ��Ŀ¼��������Щ����
        ������username.github.com�Ϳ���˳������������Ϥ��`Hello   World`�� 

### github��д���͵Ĳ��裺

*  **�ڱ��شjekyll����**  
        ���Բο���<http://www.cnblogs.com/purediy/archive/2013/03/07/2948892.html>              
*  **��_post�ļ�������д�Լ�������**    
        ��ôд���¿��Բο��£�<https://github.com/plusjade/jekyll-bootstrap.git>���clone������Ĵ��� ,�ο�[markdown��ǩ](http://wowubuntu.com/markdown/)  
*  **���ز���jekyll**  
    �ڰ�װ�õ�ruby����̨����,���뵽��Ŀ��Ŀ¼�£�ִ���������jekyll serve�������£��ҿ���������Щ����$ jekyll --server���ǲ��ɹ��ģ�
    ����ֱ������jekyll serve��������Ϳ���ִ���ˡ������������֮���������������http://localhost:4000���Ϳ��Է����ˡ�_siteĿ¼
    �����յľ�̬��ҳ.�ڷ��ʵ�ʱ����ܳ����������⣬�޸���_includes/themes/default.html�ı���Ϳ����ˣ��ĳ�gb2312����������һЩ���ı��⣬�б���Ч��һ����������Ҫ
	����Ӣ�Ĳſ����������б����ʽ��
*  **git�ύ**  
        ���ʹ��git�����ύ��github.com��       
        ��github.com�����ļ���git��������:   
		<pre><code>git clone https://github.com/zms91/---.git</code></pre>
        �ӱ����ϴ��ļ���github.com��git����:
		
		
        git init
        git add .
        git commit -m 
        git push
    

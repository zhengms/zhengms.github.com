---
layout: post
category : github_blog
tags : [intro,beginner,jekyll,githubblog]
---
{% include JB/setup %}

���������о�github������ôŪ����ô��github��д���ͣ�д���Ǵ��ͨ���׶��Ĳ��ͣ�������һ��Ѵ���.
�����кܶ������Ĳ��ͣ�����ͨ���ο����ϵ�һЩ���½���Լ���ʵ�ʴӲ��ᵽ���һ����ʵ�ֳɹ��ģ��Լ�һ����
�����ڼ䣬�����ܶ����⣬������ˡ��������ҷ��������������о��ɹ���ѧϰ��һЩ�ĵã��𲽽���github���͵Ĳ��衣
���о������ϵ�һЩ���������������һЩ���⡣������ܵ���windowϵͳ��


### Ҫ�õ���һЩ���ߺ�֪ʶ��

- **github.com**   
	    ������<https://github.com/>���վ����ע����˺ţ������Ӧ�ö���İ���ɡ������ǰ��
- **git**  
        git�Ǳ��غ�github�ϵĿ�֮��Ĵ��乤�ߡ�Ҫ�Ȱ�װ���git���ߣ������ϴ�����github.com�ϵĿ�����ݶ�Ҫ��git����
        ���ص�ַ:<https://help.github.com/articles/set-up-git>,�����������ַ��ȥ����window�ϵ�git����
- **jekyll**    
        jekyll��һ�־�̬��վ��������������github�Ͻ������͵�ǰ�ᡣ�й�jekyll�Ľ̳̣�����-<http://jekyllrb.com/>��
        ���Ľ̳̣�<http://higrid.net/c-art-blog_jekyll.htm#baseurl>
- **DevKit**    
        DevKit��windowsƽ̨�±����ʹ�ñ���C/C++��չ���Ĺ��ߡ�����������ģ��Linuxƽ̨�µ�make,gcc,sh�����б��롣
        �����������Ŀǰ��֧��ͨ��RubyInstaller��װ��Ruby.�����jekyll���ش��������ġ�RubyInstaller�����ص�ַ��
        <http://rubyforge.org/frs/?group_id=167>;DevKit�����ص�ַ��<https://github.com/oneclick/rubyinstaller/downloads/>
- **markdown** 
        markdown�������Ϊһ���﷨�����Ŀ���ȥ��ѭ�����﷨��Ȼ�����jekyll�����Ļ���ȥ���������﷨ ,markdown�﷨˵��<http://wowubuntu.com/markdown/> 
                    
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
    

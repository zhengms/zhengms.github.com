---
layout: post
category : github_blog
tags : [intro,beginner,jekyll,githubblog]
---
{% include JB/setup %}

����һЩcss��js�����飬����û�������о����ر��Ǹ�������λ��display��line-height�⼸��һֱû�������������ʱ���������ȥ����һ�¡�������
���˵�һЩ��⡣���Եĵط����ָ��


### Ҫ���ļ���֪ʶ�㣺

- **����float**   
	�����Ҫ����������ļ��ַ���  
- **��λposition**  
        ��λ������relative��absolute��fixed��Ĭ����static
- **display**    
        inline��block��inline-block���������Լ���ie6�µı��֣�visibility��display������
- **line-height**    
        �и߾��к;��еķ���
- **ie6�µ�haslayout**        
         ie6�µ�layout�Ĵ��� 
              
### ����֪ʶ�����Ҫ�ط�: 

- **����float**   
	 ������Ҫ������������Ĺ�������Ϊ����Ԫ�ػᱻ�Ƴ��ĵ������ᵼ����Χdiv�߶����أ���Ӱ�첼�֡�
	 ���ԣ�һ���ڸ���֮���Ҫ����ִ������������������ֵ�ʱ��������Ҹ�����ͨ����д�Ҹ�������д�󸡶���
	 �����г�������������ķ��� 
	 
	 (1)&lt;div style="clear:both"&gt;&lt;/div&gt;   
	    ���ַ�������������Ժã����Ǿ���Ҫ��Ӷ���ı�ǩ   
	 (2)&lt;br  style="clear��both"/&gt;  
	 (3)ie6��:   
	          
	          #outer{display:inline-block}  
	          *html #outer{height:1%}  
	          #outer {display:block}   
	 (4){overflown:hidden����auto}  
	   ��ie6�»���Ҫ�۸�zoom:1������layout���Ż���Ч ������λһ���û������ 
	 (5)�����������.clrfix:  
	             �ڸ���Ԫ���ϼ�������clrfix����ie6��Ҳ��Ҫ����zoom:1������layout��  
	             
	             .clrfix
	          {
	          content:".";
	          height:0;
	          visibility:hidden;
	          display:block;
	          clear:both;
	          }
- **��λposition**   
        positionĬ�ϵ���static��fixed��ie6���ǲ�֧�ֵġ�absolute��fixed�������ĵ����ģ�relative������ռ���ĵ��ռ�ġ���ʹ��absolute
        ��λ��ʱ������ȥ�Ҹ������õ�position�����Ե�Ԫ����Ϊ��׼������ƫ�ơ����û�ҵ����������������ڡ���relative������ڱ���Ԫ��
        ���ڵ�ԭ��λ�ý���ƫ�Ƶġ��������������֮��z-index�Ż���Ч��һ��position�������z-indexʹ�õġ�z-indexԽ����Խ����һ��  
- **display**  
         display���õ���inline,block,inline-block��inline���Խ��鼶Ԫ�ر������Ԫ�أ�block���Խ�����Ԫ�ر�ɿ鼶Ԫ�ء�inline-block
         ������һ��Ԫ��������������ͬʱ�п�����ʡ�display��visibility�������ǣ�`display`��ռ���ĵ�λ�ã�`visibility`��ռ���ĵ��ռ䣬
         ie6�µ�inline-block��ʵ��û�õġ����ǿ��Դ���ie6��layout��������ie6��Ҫ�ı������Ϳ鼶Ԫ�أ���Ҫ������css����д�Ż���Ч�����磺

         div{display:inline-block}
         div{display:inline} 
- **line-height** 
         line-height��height��������ʵ���������ǳſ�һ���߶ȵġ�һ��Ԫ�����û�����ø߶ȣ�ȴ�и߶ȵ�ԭ�������Ϊ����line-height��
         ie6�£�height����Ҫʹ��haslayout��height���ò���auto���κ�ֵ���ǿ��Դ���layout�ġ�����line-height����Ҫlayout����Ч�ġ�  
            ��1�����ǳ��õ�һ���иߵĵط����ǵ������־��е����⣺    
                 ����line-height��heightһ���߾Ϳ��������ݾ����ˡ�  
            ��2��������һ�¾��еļ��ַ����� 
                  `margin:0 atuo`���ڶ�DIV��ľ��ж�λ����IE�������á�    
                  `text-align:center`����DIV�е����ݵĶ�λ����IE������ 
                  ���´�������������������ʹDIV��ǩˮƽ����:  
                  
                  <body style="text-align:center">  
                  <div style="width:80px;margin:0 auto"></div>  
                  </body>   
	 (4)ֱ����body���ø߶���û�õģ���Ϊ�߶��ǲ��̳еģ�Ҫ������С��ȣ������������ټ�һ��div�������������div�Ŀ��Ϊ960px  
- **ie6�µ�haslayout**  
          ��1��ie6�´���layout��Ԫ�ؼ�Ԫ�ص�ֵ��  
           
           position:absolute
           float:left/right
           display:inline-block
           width:any value other than auto
           height:any value other than auto
           zoom:1   
	 (2)ie7�´���layout��Ԫ�أ�  
	 
	   <pre><code>
	   overflow
	   overflow-x
	   overflow-y
	   min-width
	   max-width
	   min-height
	   max-height</code></pre>
	 
          
           
           
    
            
                         
                             
         

         
        

                     
         
         
          
        

       
	          
  
	         
	    
	   	 

      
      
    

key: fblog-deepure  
title: fblog  
domain: http://mysite.com  

======

A theme for farbox。
暂时未兼容farbox自带评论，因为用不到这部分，更新时间不定。


---
###site.md配置说明  

	title: 衣不如新
    weibo: uid=1932250983&verifier=a0fe8b1d   
    rpost: 8  
    duoshuo: motype  
    keywords: 前端设计
    analytics: <script type="text/javascript">var _gaq=_gaq||[];_gaq.push(['_setAccount','XXXXXXXX']);_gaq.push(['_setDomainName','motype.org']);_gaq.push(['_trackPageview']);(function(){var ga=document.createElement('script');ga.type='text/javascript';ga.async=true;ga.src=('https:'==document.location.protocol?'https://ssl':'http://www')+'.google-analytics.com/ga.js';var s=document.getElementsByTagName('script')[0];s.parentNode.insertBefore(ga,s);})();</script>  
    
 weibo: 使用新浪个人工具生成的iframe标签中，截取类似代码即可。注意不能漏了verifier字段  
 rpost： 有此项配置时侧栏显示最近文章，最大值20
 duoshuo: 侧栏最新评论使用的多说，字段值为多说的short_name  
 keywords: meta 的keywords属性
 analytics ：由于统计差异太大，无法提取ID，但基本上为一段script脚本，可以将脚本压缩成一行，填入site.md  
 
###链接类主题   
当文章头部有link标签时，文章列表内的标题将直接链到该link  
 
    Title:协议森林by-Vamei
    Date: 2013-02-21 21:18:54  
    link: http://www.cnblogs.com/vamei/archive/2012/12/05/2802811.html  
    tags: 互联网协议  

###Feedback
http://motype.org/post/design/theme-farbox  
https://github.com/deepure/fblog/issues

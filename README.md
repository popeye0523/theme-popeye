# 介绍
这原本是Jekyll-Bootstrap的twitter模版，我在上面修改了一些个性化的东西

# 改动
1. 将post模版内容部分拉宽，分成了左中右三块，左为新浪微博秀，中为博客内容，右为零散内容。
2. 在post页面增加了一部分读取yaml中自定义css和javascript的功能。
  > 用法：
  > 1. 在网站根目录下建立css和javascript文件夹
  > 2. 在post头部加上相关css的配置,例如：
  >    <code>  
    javascript:  
    \- /javascript/jquery.js  
    \- /javascript/violet.js  
</code>
3. 

# 使用说明
1. _includes/themes/popeye/post.html里面hardcode了我的微博iframe，使用时需要修改为自己的。微博iframe生成链接：[微博秀](http://app.weibo.com/tool/weiboshow)
2. _includes/themes/popeye/post.html里面hardcode了我的GitHub Repos、二维码之类的东西，同样，使用时需修改或删除。
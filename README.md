## HTML5阅读器
- 项目中分为数据获取模块和数据处理模块。
- 项目中为了减少访问DOM节点，增加页面性能，把访问到的节点缓存到对象中。
- 项目中为了解决AJAX的跨域问题，用JSONP来加载外部JSON数据。此项目也修复了多个Bug。


## 技术点
- 页面布局运用了HTML/CSS/CSS3/HTML5
- 本地JSON数据的加载使用的是Zepto的GET方法
- 跨域数据的请求使用JQuery的JSONP技术
- 为了减少请求次数ICON图标使用的是Base64格式的图片
- 用HTML5的localStorage代替cookie
- AJAX异步请求
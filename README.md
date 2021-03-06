#Amango•芒果微信公众号管理开发框架

>简介：芒果微信公众号管理框架是基于Onethink开源框架进行的二次开发，它继承Onethink的基本CMS管理理念，丰富了对微信公众号管理的更好得支持。
因此，它既可以兼容Onethink的插件也支持微信插件。本系统专注于单个微信公众号的管理，但它又不同于其他微信公众号管理系统。对于微信公众号管理而言，无论你是使用者，还是插件开发者，它对于大家而言都是“新鲜”的。注重单公众号管理的个性化的实训，因此，它的部分理念是独树一帜的。如果你是匠心独运你的微信公众号，不妨来体验它，它将带给你新的微信公众号管理视角！(以下内容只是针对微信公众管理)
加入我们群吧 163556458
[使用手册][http://www.amango.net/]

##对于使用者来说
* 对于信息调用：微信回复支持全站调用任意cms内容
* 对于资源调用：微信素材统一管理机制
* 对于关键词：微信关键词高级自定义(在芒果这，关键词=用户请求+自定义响应)，您可以自定义关键词激活时间，分组，权限，主题等等...，此外，为了资源重复利用，我们的可以通过请求和响应的拖拽式绑定组装任意你想要的关键词
* 对于关注者：自定义关注者所在分组，积分体制，用户分组所拥有的权限
* 对于运营方面：微信支持任意位置植入任意内容，无论你是图文消息，文本消息，语音消息，地理消息等等，我们可以自行定义任意时间段植入任意内容
* 对于前端页面：我们统一了插件与资讯界面风格，增强了用户中心以及自动登录

##对于开发者来说(仅仅针对微信插件)
* 对于插件/资讯前台：采用自动响应的Amaze UI作为我们的Css框架，开发者可以采用模板渲染统一风格，为了更好地结合微信浏览器，我们内置了分享以及相关js控制显示
* 对于微信端出来开发：我采用简洁的插件文件夹布局，更加简洁明了，针对微信控制器处理的开发，我们将更多的方法独立封装自定调用【creat_url自动创建插件URL，lock上下文模块锁定，error/success快捷回复...等等】，在这里，无需手写繁杂的代码，只需配置rules就可以进行关键词自动匹配，自动截取，自动定位到你的操作，让你的精力更多投入到功能开发而不是枯燥的关键词逻辑判断

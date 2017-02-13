#微信小程序调研
-----
Last update:　201702131335

##索引
- #### [什么是微信小程序？](#whatIsWeChatLiteApp)
- #### [小程序的优势和不足？](#advantagesAndDisadvantages)
- #### [小程序能为我们带来什么？](#value)
- #### [ACN哪些功能适合使用小程序开发？](#whatCanWeDo)
- #### [注册流程](#registration)
- #### [开发流程](#develop)
- #### [发布流程](#release)
- #### [运营](#operation)
- #### [数据统计和分析](#dataStatisticsAndAnalysis)
- #### [风险规避！](#riskAversion)
- #### [小程序列表](#liteAppLists)
- #### [相关文档](#documentation)

##<a name="whatIsWeChatLiteApp"></a>什么是微信小程序
- 官方：
微信小程序是一种全新的连接用户与服务的方式，它可以在微信内被便捷地获取和传播，同时具有出色的使用体验。

- 张小龙
小程序是一种不需要下载安装即可使用的应用，它实现了应用**触手可及**的梦想，用户扫一扫或者搜一下即可打开应用。也体现了**用完即走**的理念，用户不用关心是否安装太多应用的问题。应用将无处不在，随时可用，但又无需安装卸载。
- 通俗理解

##小程序与服务号的区别
<img src="https://i.imgur.com/oJRuEKF.png">

##<a name="advantagesAndDisadvantages"></a>小程序的优势和不足

#####小程序的优势
- 无需安装
- 直接调用微信的API
- 相比HTML5应用操作更流畅，用户体验好
- 借助微信在移动端的跨平台能力实现了小程序的移动端跨平台

#####小程序的不足
- 无应用商店
- 不做订阅
- 不能主动推送消息
- 不能分享到朋友圈
- 不能做游戏
- 引流效果差
- 和公众号相互独立账号，弱关联
- 可以调用的API有限
- 需要微信官方审核



#####小程序与其他类型应用对比
|开发成本|维护更新|用户体验|安装方式|跨平台|功能|综合评分|
|--------|--------|---------|---------|---------|---------|---------|
|[Native App](https://en.wikipedia.org/w/index.php?title=Native_app&redirect=no)(原生应用)|高|复杂|优|App Store|差|优|C|
|[Web App](https://en.wikipedia.org/wiki/Web_application#Definition_and_similar_terms)(HTML5应用)|低|简单|中|无需安装|优|中|A|
|[Hybird App](http://developer.telerik.com/featured/what-is-a-hybrid-mobile-app/)(混合应用)|中|简单|良|App Store(Web无需安装)|优|中|B+|
|[Wechat Lite App](https://mp.weixin.qq.com/cgi-bin/wx)(微信小程序)|低|简单|良|无需安装|良|差|B|

##<a name="whatCanWeDo"></a>小程序能为我们带来什么

###小程序希望做线下弱连接的入口

###小程序适用场景

**小程序对一些使用频率低的工具类产品是一个很好的平台，无须安装、触手可及、用完即走、无须卸载。**
#####适合的应用场景
工具类应用

#####不适合的应用场景
交互复杂的应用
功能复杂的应用
内容类应用

<blockquote>
目前，包括去哪儿、携程、摩拜单车等App都做了首批小程序，这些小程序功能都有所“缩水”，并不能完全替代App。
</blockquote>

##<a name="advantagesAndDisadvantages"></a>ACN哪些功能适合使用小程序开发

<blockquote>
张小龙在揭开小程序神秘面纱时举的例子，是两个线下连接场景：一是公交车站扫码得知到站时间；二是汽车站扫码买票。在连接人与人、人与服务、人与商业方面都已经有成熟的产品和服务，但连接人和物品还进展缓慢。没有被电子化的物品怎么连接？最实惠和便利的入口便是二维码，而小程序就是要做这个连接。
</blockquote>

#####ACN适合使用小程序开发的功能
- 价格计算器
- 仪表盘

##<a name="registration"></a>如何注册小程序
[注册流程](https://mp.weixin.qq.com/wxopen/waregister?action=step1)


##<a name="develop"></a>开发小程序
[小程序信息完善及开发前准备](https://mp.weixin.qq.com/debug/wxadoc/introduction/#小程序信息完善及开发前准备)


#####小程序render方式
-	在 iOS 上，小程序的 javascript 代码是运行在 JavaScriptCore 中，是由 WKWebView 来渲染的，环境有 iOS8、iOS9、iOS10
-	在 Android 上，小程序的 javascript 代码是通过 X5 JSCore来解析，是由 X5 基于 Mobile Chrome 37 内核来渲染的
-	在 开发工具上， 小程序的 javascript 代码是运行在[nwjs](https://github.com/nwjs) 中，是由 Chrome Webview 来渲染的

#####开发语言
WXML 不是 HTML
WXSS 也不是完整的CSS
Javascript 不是完整的ECMAScript 6

#####Troubleshoot

##<a name="release"></a>发布流程
微信小程序的发布需要腾讯进行审核，审核通过之后才可以进行发布。

[微信小程序认证指引](https://mp.weixin.qq.com/debug/wxadoc/product/renzheng.html#一、申请微信认证入口)

##<a name="operation"></a>运营
#####用户路径
微信搜索->小程序
线下扫码->小程序
已安装用户->发现->小程序->历史记录
好友推荐->小程序
公众号关联->小程序

<blockquote>根据张小龙的解释，用户与小程序之间不存在粘度关系，用户只能对其访问，而唯一产生数据也只有访问量一项。此外，小程序还不支持推送通知，仅能在获得用户授权后，发布少量后续通知。</blockquote>

[微信小程序平台运营规范](https://mp.weixin.qq.com/debug/wxadoc/product/index.html?t=201729)

##<a name="dataStatisticsAndAnalysis"></a>数据统计和分析
小程序数据分析，是面向小程序开发者、运营者的数据分析工具，提供关键指标统计、实时访问监控、自定义分析等，帮助小程序产品迭代优化和运营。

<img src="https://mp.weixin.qq.com/debug/wxadoc/analysis/image/weanalytics/2_2.png?t=2017117">
[微信小程序数据分析](https://mp.weixin.qq.com/debug/wxadoc/analysis/index.html?t=2017119)


##<a name="riskAversion"></a>风险规避
- 内容审核
	[微信运营规范](https://mp.weixin.qq.com/debug/wxadoc/product/index.html?t=201726)限制了小程序的应用范围，而且被腾讯的审核制度制约着。
    <blockquote>微信小程序的服务范围需与实际填写的类目和标签一致，也需和自身所提供的服务一致，且不应超出小程序平台的类目库范围。如游戏、直播、虚拟物品购买功能等均尚未开放。</blockquote>

- 小程序内部bug
	小程序目前还不够完善，目前还存在很多bug，[更新日志](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/new.html)列出了已经修复的一些bug。开发过程中遇到小程序本身的bug只能等待官方修复，可以在[开发者社区](https://developers.weixin.qq.com)向微信官方提交bug。

- 小程序命名
	小程序搜索入口目前是不支持模糊搜索的，所以小程序的命名一定要比较容易记忆，一旦发布之后再修改名字就会带来很多麻烦。

- 支付限制
	支付 === 微信支付
	由于支付接口的限制，涉及到支付的部分只支持微信支付，相当于限制了用户选择支付的方式，小程序并不适合支持多种支付方式的应用场景。

- 大小限制
	源码打包限制1m大小限制了小程序的应用场景。

##<a name="liteAppLists"></a>小程序列表
<img class="size-full wp-image-780497 aligncenter" src="https://i.imgur.com/K1EQO8B.png" alt="rankvol2-01" width="750" height="1075" sizes="(max-width: 750px) 100vw, 750px">
<img class="size-full wp-image-780498 aligncenter" src="http://ifanr-cdn.b0.upaiyun.com/wp-content/uploads/2017/01/rankvol2-02.png" alt="rankvol2-02" width="750" height="1050" sizes="(max-width: 750px) 100vw, 750px">
<img class="size-full wp-image-780499 aligncenter" src="http://ifanr-cdn.b0.upaiyun.com/wp-content/uploads/2017/01/rankvol2-03.png" alt="rankvol2-03" width="750" height="1019" sizes="(max-width: 750px) 100vw, 750px">
<img class="size-full wp-image-780500 aligncenter" src="http://ifanr-cdn.b0.upaiyun.com/wp-content/uploads/2017/01/rankvol2-04.png" alt="rankvol2-04" width="750" height="1019" sizes="(max-width: 750px) 100vw, 750px">
<img class="size-full wp-image-780501 aligncenter" src="http://ifanr-cdn.b0.upaiyun.com/wp-content/uploads/2017/01/rankvol2-05.png" alt="rankvol2-05" width="750" height="1000" sizes="(max-width: 750px) 100vw, 750px">
<img class="size-full wp-image-780502 aligncenter" src="http://ifanr-cdn.b0.upaiyun.com/wp-content/uploads/2017/01/rankvol2-06.png" alt="rankvol2-06" width="750" height="1019" sizes="(max-width: 750px) 100vw, 750px">
<img class="size-full wp-image-780503 aligncenter" src="http://ifanr-cdn.b0.upaiyun.com/wp-content/uploads/2017/01/rankvol2-07.png" alt="rankvol2-07" width="750" height="1000" sizes="(max-width: 750px) 100vw, 750px">
<img class="size-full wp-image-780504 aligncenter" src="http://ifanr-cdn.b0.upaiyun.com/wp-content/uploads/2017/01/rankvol2-08.png" alt="rankvol2-08" width="750" height="1019" sizes="(max-width: 750px) 100vw, 750px">
<img class="size-full wp-image-780505 aligncenter" src="http://ifanr-cdn.b0.upaiyun.com/wp-content/uploads/2017/01/rankvol2-09.png" alt="rankvol2-09" width="750" height="1000" sizes="(max-width: 750px) 100vw, 750px">
<img class="size-full wp-image-780506 aligncenter" src="http://ifanr-cdn.b0.upaiyun.com/wp-content/uploads/2017/01/rankvol2-10.png" alt="rankvol2-10" width="750" height="1075" sizes="(max-width: 750px) 100vw, 750px">

##<a name="documentation"></a>相关文档
- 	[开发文档](https://mp.weixin.qq.com/debug/wxadoc/dev/index.html)
- 	[开发者工具](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/download.html)
- 	[FAQ](https://mp.weixin.qq.com/debug/wxadoc/api/devtools/qa.html)
-	[第三方小程序商店](https://minapp.com/miniapp/)
-	[小程序“惊艳”亮相，创业者们的狂躁与迷思](http://www.tmtpost.com/2556382.html)
-	[对抗微信，支付宝牌“小程序”也来了](http://www.tmtpost.com/2557765.html)
-	[微信小程序的价值是什么？](https://www.zhihu.com/question/50875544)
-	[微信小程序，不可不知的一二三四](http://guoze.me/2016/10/16/wechat-app/)
-	[我们真的需要“小程序”么？HTML5 老兵如是说](http://cn.technode.com/post/2016-09-23/wechat-html5/)
-	[对于小程序的一些零散思考](https://github.com/newteo/team-blog-repo/issues/37)
-	[Progressive Web Apps: Escaping Tabs Without Losing Our Soul](https://infrequently.org/2015/06/progressive-apps-escaping-tabs-without-losing-our-soul/)
-	[张小龙发表公开演讲 让关于小程序的疑问都有了答案](http://www.cbnweek.com/articles/normal/15397+&cd=1&hl=en&ct=clnk&gl=sg)
-	[微信“小程序”来了，短期不可高估，长期不可低估](http://36kr.com/p/5053378.html)
-	[微信小程序在微信APP里如何运行的？](https://segmentfault.com/a/1190000007473513)
-	[微信小程序与H5的区别](https://segmentfault.com/a/1190000007388966)
-	[张小龙2017年微信公开课全文](http://tech.sina.com.cn/i/2016-12-28/doc-ifxyxury8931704.shtml?cre=techpagepc&mod=f&loc=2&r=9&doct=0&rfunc=31)
-	[小程序来了，微信、商家和用户能干什么？](http://tech.sina.com.cn/i/2017-01-10/doc-ifxzkfuh6521708.shtml?cre=techpagepc&mod=f&loc=9&r=9&doct=0&rfunc=31)
-	[]()
-	[]()
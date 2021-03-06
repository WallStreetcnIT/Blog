# Blog
### 欢迎来到华尔街见闻技术团队的博客！
华尔街见闻是中国领先的互联网金融服务提供商，为用户提供金融资讯、数据、策略、和交易服务，

旨在帮助中国投资者理解世界，更好地做好投资决策。

Github主页: [WallStreetcnIT](https://github.com/WallStreetcnIT/ "Title")

博客地址:[华尔街见闻技术团队blog](https://wallstreetcnit.github.io/ "Title")

新浪微博: [华尔街见闻技术团队](http://weibo.com/5977281147/profile?topnav=1&wvr=6/ "Title")
####Our team is young and active, welcome to join us!

##华尔街见闻技术部 交流分享会（二）
####时间：2016年7月28日 13:00-14:00
####地点：智造局一期307华尔街见闻中会议室
####主题：动画养成记
####主讲人：王雨威 [个人主页](https://github.com/JeasonWong "Title") 
---
####**观点：想让自己的github变得star多多吗？那就做动画吧！**
---
_引言: github吸星大法_

[示例一](https://github.com/ldoublem/LoadingView 
"Title") 
[示例二](https://github.com/android-cjj/JJSearchViewAnim 
"Title")
[示例三](https://github.com/daimajia/NumberProgressBar
"Title") 

[大神排行榜](http://githuber.cn/rank "Title")

[优秀设计资源](https://dribbble.com "Title")

_举例详解 [BezierLoadingView](https://github.com/JeasonWong/BezierLoadingView)_

![效果](http://i4.buimg.com/cdd5a4a8f0233650.gif)

- 圆周运动
 * 圆点坐标：(x0,y0)
 * 半径：r
 * 角度：a0
 * 则圆上任一点为：（x1,y1）
 * x1 = x0 + r * cos(ao * 3.14 /180 )
 * y1 = y0 + r * sin(ao * 3.14 /180 )
 

- 贝塞尔曲线
  * [QQ气泡](https://github.com/wangjiegulu/DraggableFlagView "Title")
  
       <img src='https://raw.githubusercontent.com/wangjiegulu/DraggableFlagView/master/screenshot/draggableflagview.gif' height='500px'/>

  * [礼物冒泡特效](https://github.com/Yasic/QQBubbleView "Title")
  
     ![](http://diycode.b0.upaiyun.com/photo/2016/55b80c4c270e41e429c468973f215cc7.gif)


- 三角函数

_实践成果展示 [SubmitButton](https://github.com/SparkYuan/SubmitButton "Title")_


---
##华尔街见闻技术部 交流分享会（一）
####时间：2016年7月14日 13:00-14:00
####地点：智造局一期307华尔街见闻大会议室
####主题：优秀工程师与架构
####主讲人：崔晨 
---
####**观点：一个优秀的程序员，三分写代码，七分靠思考。**
---
_亮点1: 不进行 code review 的团队不是好团队_

不少创业公司和开发团队会纠结是否要执行 code review，一方面希望改进代码质量，另一方面也担心因此拖慢项目进度。事实上，在软件开发中质量和效率往往并不是二选其一的关系。能产出高质量代码的团队通常效率也非常高。用一个简单的方法判断，就是比较优化成本与收益。对于一些刚刚起步的小公司，成本大于收益，那我们不提倡过度优化；但对于大中型企业或者由小向大过渡的企业，code review 是十分必要的。因为代码规范了以后会给未来发展打下坚实的基础，也能保证项目的质量。

这里提到一个概念－－持续集成（Continuous integration）。
大师Martin Fowler对持续集成是这样定义的:持续集成是一种软件开发实践，即团队开发成员经常集成他们的工作，通常每个成员每天至少集成一次，也就意味着每天可能会发生多次集成。每次集成都通过自动化的构建（包括编译，发布，自动化测试）来验证，从而尽快地发现集成错误。通俗一点儿说：就是指对于开发人员的每一次代码提交，都自动地把Repository中所有代码Check out到一个空目录，并且自动运行所有Test Case。如果成功则接受这次提交，否则告诉所有人，这是一个失败的Revision。这样做可以减小风险、减少手动过程、灵活生成构建结果、增强项目的可见性。

我们可以用Jenkins搭建持续集成环境：[jenkins官网](https://jenkins.io/index.html "Title") 
 
_亮点2: 好的架构要针对相应的场景，不看实际情况空谈架构都是耍流氓_

_亮点3: SOA治理_

要理解SOA(Service-Oriented Architecture)治理，即面向服务的体系结构治理，推荐IBM官方的SOA简介：[SOA治理的定义及需要治理的理由](http://www.ibm.com/developerworks/cn/webservices/ar-servgov/ "Title") 
举个例子，对于我们华尔街见闻这种互联网金融公司来说，我们是存在数据依赖的。如果我们的A股数据来源出现了问题，那我们就没有办法进行数据分析，自己的业务就会陷入瘫痪。那如何应对这种情况就是SOA治理所要考虑的问题。

---
**成长得益于有意识的思维方式，积极思考的人才是紧跟时代潮流的人**

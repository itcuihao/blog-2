我一直认为，对于程序员来说，写一天代码不算什么，也许这只是解决了一个bug，或者干脆就没能搞定。一周的时间学习内容页有限，可能是一两个困扰已久的知识点终于悟透了，也可能是新学了某个知识点。但是和一个月前的自己相比，总是感觉自己进步颇大，和一年前的自己相比，就有一种判若两人的感觉了。2015就要过去了，我想有必要总结一下这一年来的收获得失。

# 从小白开始

从去年年底正式开始写iOS开始，到大约三四月份，一直在开发自己的第一个iOS应用，现在回顾那段时间的博客，主要是关于UI方面的总结，以及一些常见错误的解决方法。在这个过程中了解了怎么处理HTTP请求和Json解析(没错，当时还不知道HTTP请求是什么)，图片的异步加载与缓存，`UIScrollview`和`UITableView`这些稍微“高端”一些的UI控件。也开始接触了定时器、内存管理等知识。APP上架以后我就天真的以为自己已经把iOS学得差不多了。

# 第一次失败

五月份的时候做过两个小的项目，一个APP上架(广告赚了将近200)，一个Xcode插件在Github，然后兴冲冲的去面了一家公司。待遇是12K+包吃住，虽然也没觉得自己达到这个水平，不过真正到了第二轮被拒的时候还是有一些小伤感。面试虽然没过，却还是有些收获：

1. 逐渐开始过渡到用Google查资料，平时关注Objc.io并RSS订阅各个大牛的技术博客，偶尔在StackOverflow提个问题。总的来说就是层次提高了，获取知识的来源拓宽了。这一点至今让我受益匪浅。

2. 关于UI方面的一些细节，以前做项目，只想着效果OK就可以，面试官问我怎么处理图片的拉伸问题我就一问三不知。还有一些比较底层的知识，比如`CoreGraphis`、`CoreAnimation`等也是之前欠缺的。

3. 以前只会嘴上喊MVC模式，实际代码中VC负责一切。被面试官一下子问个正着。现在严格遵循MVC模式，而且学习了MVVM模式，写了几篇分析ReactiveCocoa源码的文章：[ReactiveCocoa详解](http://blog.csdn.net/column/details/reactivecocoa.html)。可惜对函数式编程的思想还是不够熟练，在项目中用了一两次之后就暂时搁置了，听说美团在用RAC。

# 第二次失败

面试结束后，把面试过程中遇到的问题总结了一下，又投了一份简历。可能是运气不错，我准备的问题被问到了好几个，也有可能是那个创业公司比较缺人，所以成功的拿到了Offer。当时谈了400一天，后来因为晚上加班，最后实际给了440一天（大二就月入过万了，当时还是有点小骄傲）。六月份开始入职，但是问题来的比工资快。现在想来主要是这几点：

1. 不适应身份的转变。企业是企业，学校是学校，在学校的团队里，自己是技术leader同时还身兼产品经理。自己定好需求再实现。但是在公司里，产品经理的需求一日三变，写完的代码leader看技术实现，产品经理看效果，美工检查UI布局。由于以前基础太不扎实，态度也比较敷衍，所以这么一来漏洞百出，顾此失彼。

2. 心态不够好。刚开始干劲十足，但总是被PM改需求，被leader批评。后来慢慢的也有些失望，甚至是抵触。其中的过程比较复杂，至今也不太能理清楚，

总的来说，第二次失败的原因有两个。一是自己技术水平不够，这里有代码规范问题也有iOS开发上的问题，二是太以自我为中心，如果当时能多站在公司的角度考虑问题，也许情况就不是那样。后来和公司的关系越来越僵，最后九月初选择了提前离职，回到学校继续钻研技术。

回到学校之后的整整两个月都没有看技术。半主动离职让我开始怀疑自己，虽然对公司的领导、氛围小有愤懑，但毕竟自己的问题更加严重。于是选择了逃避，每天玩游戏、看电影，甚至去大连旅游了一趟。回家呆了一段时间，再回学校已经是11月，感觉逃避也不是办法，只是还是要一点点学。

# 读书

15年读了不少好书，收益颇丰。实习期间看完了《Effective Objective-C 2.0》和《Objective-C高级编程》，对不少基础知识，比如ARC、block和GCD都有了更加深入的了解。

实习的时候还看了一本《老码说编程之玩转Swift江湖》，当时Swift还是1.x版本。从这一点来说，我是个不合格的实习生。实习期间路上、晚上都在看书，导致白天精力不济。因为当时的思想还是利用实习期间多学技术，但创业公司要求的其实是实习生为他创造效益。

11月读了《程序员的自我修养》，对程序的运行和操作系统有了更透彻的理解。读完之后写了一篇[读后感](http://www.jianshu.com/p/47156b4259ed)。12月的Swift 2开源，感觉Swift是大势所趋，所以开始学习objc出版的"Advanced Swift"，同时自己也写了它的[中文翻译版](http://www.jianshu.com/p/18744b078508)，后来有人提醒我版权问题，所以已经暂停原文翻译了，后面的几篇文章都是对原文进行加工和总结后得出的。

阅读和翻译英文书的收获非常大，对很多的知识的理解比直接阅读中文教程要深刻的多，同时也大幅度提高了自己阅读英文教程的能力。

# 收获

最大的收获，莫过于Swift的学习了，了解基本语法的同时，有机会也会自己看一下已经开源的部分的实现原理。

磨刀不误砍柴工，我减少了很多写项目的时间，希望把基础知识弄扎实，因为很多bug往往来自于对某个概念的错误理解。与其一知半解的去解决bug，不如先掌握知识。所以在读书的同时，我也开始深入的思考iOS开发的一些基础知识：

* AutoLayout和UIScrollview的联合使用
* UIScrollview性能优化
* GCD和NSOperationQueue
* UIView的生命周期
* Swift与OC在复制对象时的异同
* Swift与OC闭包的异同

感谢Google上的各种资料，我完成了自己的[Xcode插件](https://github.com/bestswifter/XcodeCareer-Plugin)，用来统计在Xcode中所有写过的代码行数和写代码时间，不过好像有隐藏的bug，后来也就不维护了。因为看过《程序员的自我修养》，对一些底层的知识有了浅显的了解，所以在Google的帮助下，自己破解了一款收费应用：[一个数字的魔法——破解Mac软件之旅](http://bestswifter.com/blog/2015/11/24/%5B%3F%5D-ge-shu-zi-de-mo-fa-po-jie-macruan-jian-zhi-lu/)

仔细想想，其他乱七八糟的东西也学了不少，实习期间相当长的时间在做C++项目，写了一个静态库分别给OC和Java调用，所以也稍微了解了一下C++。发现了CSDN博客的一个bug，又去了解了一下Python，写了一个脚本把自己积分刷到了第一。学校有安卓的课，所以不得不写了个[安卓应用](https://github.com/bestswifter/MathModeling-Android)，也算是了解了一些简单的Java和安卓开发。年底的时候注册了bestswifter域名，搭建了[个人博客](http://bestswifter.com/)，虽然注定要被打脸，但也希望能够鞭策自己。

# 2016年的计划

1. 文章要继续阅读和翻译英文书籍。目前Advanced Swift翻译了三分之二，一月份估计可以结束。下一个目标或许还是Objc的书：Core Data。事实上总是有读不完的好书的。

2. 阅读优秀的博文。实际上今年2015年的很多时间浪费在一些低质量的文章上，不仅学不到知识，还把自己弄得晕头转向。NSHispter和Objc.io有非常多优秀的文章，足够在2016年好好拜读了。

3. 技术与基础。有些知识点还没来得及学习，有些学过但是长期不用已经忘了，目前想到的涉及这几点：响应者链与事件处理、KVO、几种消息传递机制的比较、Runtime、NSUrlSession、CALayer等等等等。虽然要学的太多，不过一直很喜欢一句话：“怕什么真理无穷,进一寸有一寸的欢喜”。

4. 大学期间就该做大学里该做的事，比如读书。目前想到的是《代码整洁之道》、《图解TCP/IP协议》，如果有空希望可以深入了解Mac与iOS操作系统。

5. 实习。目前对创业公司有了一定了解，希望能够到一家大公司实习几个月。

虽然任务浩繁，不过总得尽力完成，希望一年后的自己与现在判若两人！
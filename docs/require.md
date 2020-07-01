
欢迎各位同学来到这里参观，这可能不是一个中规中矩的 Java 后端教程，文笔会比较随意，大家就当小说看吧，如果你已经是大牛了，就没必要浪费时间了，如果你是一个即将从事 Java 开发或者刚刚入门，或者做过两三年，感觉技术尚浅，可以拿来看看。

必须要说的是，我也不是什么大牛，只不过比各位多几年经验而已，本系列内容也是多来自于我自身学习经验，并不会面面俱到，只会介绍到我认为的重点部分。望同学各自斟酌，取中精华，去之糟粕。

我刚毕业的时候做的是 .NET,做企业级项目，后来才转的 Java，浪费了好几年的大好时光（其实也不是浪费，每段经历都有它的意义，当然过程中学习了 Python）,转到 Java 之前也略懂一点基本语法，没有过渡期，直接开始做项目的，虽说 C# 和 Java 语法很像，但学过语言的都知道，学会语法只需要很短的时间，比如两天，但 Java 生态远比 .NET 复杂。所以说，我也是从零开始自学过来的，略有一点心得，分享出来，供各位同学参考。

如果你有什么建议或者疑问，也可以关注我的公众号「古时的风筝」，或者直接加我的微信。公众号回复『666』有完整的后端学习知识图谱高清大图。

![古时的风筝](https://tva1.sinaimg.cn/large/007S8ZIlly1gfd6gx54haj314z0npafp.jpg)

## 学习方式

### 先泼一盆冷水

学习技术可不是读两本书、读几篇文章、买几个付费专栏、甚至收藏好多学习资料就可以了，想的没，

### 坚持和拒绝拖延

**我觉得这两点很重要**

**1、开发之路没有捷径，只有不停的学习，不停的写代码，不停的总结，坚持下去，量变引起质变，除非你天赋异禀。**

道理虽然浅显，但能付诸实践的人少之又少。就算开始实践了，能坚持下去的人就更少了。很多人坚持一段时间，觉得付出并没有得到对应的回报，慢慢就放弃了。哪儿有那么快，世界上没有银弹，绝大多数人的成功都是厚积薄发，一夜成名的只是极少数。

要学会延时满足，你现在的付出基本不会在明天有收获，也很有可能在下个月、甚至明年都看不到收获，但是，必定在将来的某一时刻帮助到你。

**2、种一棵树最好的时间是10年前，其次是现在。学习也是一样，从现在开始动手，不要等到明天。**

拒绝拖延，马上开始。说的容易，做起来难。别看我在这大言不惭、一本正经的说着，其实我就是个严重的拖延症患者（手动尴尬）。


### 基础重要吗

当然重要了，谁说不重要你把他叫来，我跟他聊聊。

如果同学你还在学校没有毕业，那真的要恭喜你了，甚至有点实名羡慕你，因为你有大把的时间夯实基础。这里所说的基础不仅包括 Java 基础或者一门编程语言的基础，更多的是包括计算机原理、网络、操作系统、数据结构、算法，甚至是数学和英语。学霸可以路过左转了，假设你不是学霸，而且将来想从事软件开发的话，举个例子，你可能会成为一名开发工程师或者是一个算法工程师，但是两者的薪资是有差别的，算法工程师薪资要高出普通开发的薪资的，这就要求你有牢固的数学基础、数据结构基础、算法基础了。

并不是说，普通的开发工程师就不需要牢固的基础知识了，比如数据结构吧，刚开始工作的时候你可能并不会意识到数据结构的重要，也不想去研究它，但是，随着开发的时间变长，你会慢慢发现它真的很重要，所以说，与其你意识到了再去补，不如在有时间的时候直接把基础打牢固。其它的比如网络、操作系统这些，总有一天你会用到，相信我，很重要。

举几个例子：
1. 比如计算机原理中的简单概念，二进制的补码、反码操作这些，有一天你可能在某段厉害的源码中看到它的妙用。
2. 网络知识，最起码你要把 7 层网络模型搞清楚，TCP/UDP/HTTP 彻底搞明白。
3. 操作系统，除非你是搞微软的那套开发，否则基本上服务器都会用 Linux，Linux 的常用命令、软件安装配置要搞明白，越早越好。


### 广度和深度选哪个
天赋异禀的大牛和自由开发者不在此列，我们只说职场中的普通开发者。

一定要在某个方向上进行深度研究和学习，如果有可能，达到这个领域的顶尖选手。也就是先追求深度。切忌这块儿研究几天、那块研究几天，到头来注定是竹篮打水。

深度是你职业生涯上升的基石，比如从初级开发到高级开发，再到技术专家，而广度更多的是你到达某一高度后，才需要考虑的。

实话说吧，我刚毕业那两年就是那种求广度不求深度的典型反面，那时候我学过以下的内容，那时候我还在做 .NET 开发，除了 .NET 的内容外，我还学过：
- Python : 当然这个还是有用的，现在还在用；
- JavaScript: 那时候没有 Vue、React，有点话那时候肯定就学了，不过也有好处，我现在自己也 ；
- Android：那时候安卓正火，什么火学什么，典型的反面；
- Cocos2d-X：做游戏开发的，用 C++ 写；
- Lua:不知道为啥要学它，那时候还不用 OpenRestry,不用定制 Lua 脚本；
- 还有其他程序无关的
真的，奉劝各位，学这么多没用，尤其是在你还没有一项足以拿的出手的技术的时候。

如果你是 Java 开发工程师，那么一定要对 Java 进行深度学习，除了基础知识外，多线程、JVM 也要很好的掌握，不要只停留在 CRUD 的水平。就拿找工作面试开始，大厂几乎没有全栈工程师这种岗位，只要初创型公司才有，所以，如果你想进大厂，那一定要有亮点。

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ggbc6m6mkmj30u00v7aeq.jpg)



### 只懂理论没有用

开发这一行，只看书、看博客是没用的，必须要实践，要动手写代码。`talk is cheap, show me the code!`公司不需要理论专家，需要能够解决问题的人。解决问题的能力都不是天生的，一定是经验的积累和平时的不停实践得来的。


## 学习路线

![](https://tva1.sinaimg.cn/large/007S8ZIlly1gfohpn7op8j30u07mfb29.jpg)
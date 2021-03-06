# 第一篇	产品架构即产品未来

<p style="text-indent:2em">无论是平台型产品还是基础型产品，都需要明白架构即未来。在产品投入开发之前，难免见到部分产品经理是这么处理需求的：结合市场分析需求可行性-市场调研-竞品分析-梳理功能点-评估功能点-随即投入开发。合情合理，但不专业。这样导致大家埋头做了很多，但存在了太多冗余无用的缓存，增加了产品管理难度，甚至耗费了大量的资源去做无用维护。</p>

<p style="text-indent:2em">在拿到一个需求点之后，其实我们可以花上一到两天的时间“肆意挥霍”。比如出去走走，感受自然，看看世界万物运行的规则。比如去网上随意翻阅信息，浏览行业头条，娱乐花边。把自己在固定的工作环境、流程中释放出来，我信奉浪漫主义。接下我们要做的就是头脑风暴，把自己看到的、想到的拼凑起来。产品规划也需要先上天后入地，我们需要思考的是，这个产品6个月、1年、3年、5年、甚至10年之后，我们期望它会变成什么样子，尽情想象，越"花哨"越好。因为大家都知道想法和实践之间的落差，100%的想法，最终可能只有20%的实践。所以为什么不把100%提高到200%呢？而且千万不要觉得节点范围太长，要知道体系越庞大的团体，在行动前就会面临极大的组织、沟通、决策成本，但极有可能出现实际投入项目工期很短的现象。况且大脑随意想象是一件很有趣的事情。</p>

<p style="text-indent:2em">规划先行，如何做产品规划？规划就是指导某个节点上的工作事项（做什么）和工作方法（怎么做）。就短期而言，规划也完成了里程碑的工作。除了上述看似不靠谱的浪漫主义，结合时间节点去分解分步，我们还缺了最重要的一步——主流校准。想法可以天花乱坠，但规划一定要遵守规则：用户期望、产品定位、产品owner期望、企业/团队愿景、行业大势。</p>

<p style="text-indent:2em">而后架构产品，如何做产品架构？首先要明白什么是产品架构，如今我们做产品，周边环境的高度我们是无法自知的，而稳定的架构，保证了产品不断拔高的可能性。产品信息架构主要有层级结构、自然结构、线性结构、矩阵结构（请参阅《用户体验要素》—Jesse James Garrett），至于选择什么样架构，我们需要了解架构背后的模式和原理，并结合产品特性。</p>

![β-地动仪产品发展的三个阶段](https://user-images.githubusercontent.com/20765716/47069957-cb84d000-d222-11e8-9c24-bca263ebc463.png "β-地动仪产品发展的三个阶段")
<p style="text-align: center; color: #949494;font-size: 14px;">β-地动仪产品发展的三个阶段</p>


<p style="text-indent:2em">我们在不同阶段梳理需求，整理功能点的时候，会发现功能点是会不断调整的。这种调整可能是为了弥补早期产品规划出现的漏洞，也可能是为了配合主流业务的转型。我们可以用“版本”这个词去理解这种现象，无论是小版本的迭代，还是大版本的迭代，页面布局、功能结构、核心表达基本上是不变的。兼容性在架构中是最基本也是最重要的，再坚固的城墙也需要炮台，兼容性会让我们的产品攻守自如。</p>

<p style="text-indent:2em">产品架构贯穿了产品的底层建设和上层建设，从基础系统交互设计、到业务组件设计、到功能模块设计、到页面版式设计，从功能设计到最终的面向用户。</p>

![产品架构由下而上，最终面向用户](https://user-images.githubusercontent.com/20765716/47071934-6e3f4d80-d227-11e8-9ab6-38c46150a545.png "产品架构由下而上，最终面向用户")
<p style="text-align: center; color: #949494;font-size: 14px;">产品架构由下而上，最终面向用户</p>

![β-地动仪产品架构侧视图](https://user-images.githubusercontent.com/20765716/47072259-48ff0f00-d228-11e8-82d8-b882f9e16161.png "β-地动仪产品架构侧视图")
<p style="text-align: center; color: #949494;font-size: 14px;">β-地动仪产品架构侧视图</p>


<p style="text-indent:2em">而我们可以把导航作为产品架构的第一步，网页中的导航栏和app中的tab是一样的，我们单从导航这个部分，就可以快速了解产品主要承担的工作—<b>功能分区</b>。</p>

> <b>三步完成产品架构</b>
> 1. <b>功能点列举：</b> 这里列举出来的是具体的功能点，部分会成为二级、三级导航栏/菜单；
> 2. <b>按相关性分类：</b> 通过这个操作大致可以归纳出产品模块，也就是一级导航栏/菜单；
> 3. <b>优先级排列：</b> 这么做是为了符合用户使用习惯和用户期望。

<p style="text-indent:2em">就使用习惯而言，例如阅读习惯从左到右，鲜艳的颜色会刺激眼球.相比log5（25）=2，用户更喜欢1+1=2。就用户期望而言，可以先解决痛点，再挠挠痒点，再激发兴奋点。人天生不爱动脑子，这不是惰性，人的大脑结构生来就是这么设计的。</p><p style="text-indent:2em">真正好的架构是需要在实践中打磨的，不能完全依赖于理论设计。</p>
# 机器学习设计模式的必要性

在工程学科中，许多设计模式得到了很好的实践，并且成为了一些常见问题的解决方案。这些设计模式蕴含着领域专家的知识和经验，供所有相关领域的从业者遵循。而本书则是记录了机器学习的设计模式，这些设计模式是我们在与数百个机器学习团队的合作过程中所观察到的

## 什么是设计模式？

克里斯托弗·亚历山大（Christopher Alexander）和五位合著者在一本极具影响力的书《A Pattern Language》（牛津大学出版社，1977年）中，将模式的思想和一系列经过验证的模式，引入了建筑领域。在他们的书中，他们对253种模式进行了分类，书中对模式的介绍如下：

> Each pattern describes a problem which occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing it the same way twice.
>
> 每种模式都描述了一个，在我们的环境中反复出现的问题，然后描述了，该问题解决方案的核心是什么，这样就可以多次使用该解决方案，而不必重复走的弯路。
>
> …
> Each solution is stated in such a way that it gives the essential field of relationships needed to solve the problem, but in a very general and abstract way — so that you can solve the problem for yourself, in your own way, by adapting it to your preferences, and the local conditions at the place where you are making it.
>
> 每一个解决方案都是以同一种方式表述的，即它给出了解决问题所必要的条件，但却是以一种非常普遍和抽象的方式描述的，这样的好处在于，你就可以根据你的偏好和当前所拥有的条件，来调整解决问题的具体方案

例如，在建造房屋时，有这样一对模式——照亮每个房间的两侧和六英尺阳台，这一对模式融入了人类的细节。想想你家里，你最喜欢的房间和最不喜欢的房间。你喜欢的房间两面墙都有窗户吗？你最不喜欢的房间呢？克里斯托弗·亚历山大说：

> Rooms lit on two sides, with natural light, create less glare around people and objects; this lets us see things more intricately; and most important, it allows us to read in detail the minute expressions that flash across people’s faces….
>
> 房间两侧均采用自然光照明，减少人和物体周围的眩光；这让我们看事情更复杂；而且最重要的是，它让我们能够详细阅读人们脸上闪现的细微表情…。


# JavaFx 常见问题总结
`													`由我问我我我整理

部分内容可能有误，还请指出。

注意！本文出现的所有J8均指代jdk8，请勿过度分析

版本：2024.01.04——v0.3

1. 如何解决：错误: 缺少 JavaFX 运行时组件, 需要使用该组件来运行此应用程序
   1) 参见5.a.i
   1) 使用Idea的javafx插件新建javafx项目
   1) 使用j8（万物始于j8）
   1) ~~你不会百度一下？你不会bing一下？你不会谷歌一下？你不会gpt一下？~~
1. 如何打包JavaFx程序为可执行程序
   1) 参考[JavaFX项目构建为可执行文件 | reine's blo(reineishyanami.github.io)](https://reine-ishyanami.github.io/article/blogs/java/javafxPackage.html)
1. Spring能集成JavaFx 吗？
   1) 参考[SpringBoot整合JavaFX | reine's blog (reine-ishyanami.github.io)](https://reine-ishyanami.github.io/article/blogs/java/javafxSpringboot.html)
   1) 你还可以尝试自己动手丰衣足食。
   1) ~~丫离了Spring就不会写Java了？~~
1. 依赖下载太慢了怎么办？
   1) 换源
      1. Maven参考: [Maven 仓库 | 菜鸟教程 (runoob.com)](https://www.runoob.com/maven/maven-repositories.html)
      1. Gradle 参考：同上，参见文末附。
   1) 向群友求助，群友可以给你jar，你安装进本地maven仓库
   1) ~~魔法，向霍格沃兹递交魔法使用申请~~
1. 我不会写JavaFx咋办
   1) 学
      1. 安装教程：[JavaFX 入门 (openjfx.io)](https://openjfx.io/openjfx-docs/#install-javafx) 
      1. 甲骨文教程：[JavaFX：JavaFX 发行版 8 入门 - 目录 (oracle.com)](https://docs.oracle.com/javase/8/javafx/get-started-tutorial/index.html) j8生万物（javafx没有太大的更新，不用担心过时问题。）
      1. OpenJFx文档教程：

[JavaFX 文档项目 (fxdocs.github.io)](https://fxdocs.github.io/docs/html5/) （我没看过，我不做评价）

1. 国外博客教程：
   1. [JavaFX Tutorial (jenkov.com)](https://jenkov.com/tutorials/javafx/index.html) 简短，需要较强的java基础
1. 油管视频教程：
   1. [JavaFX Software - YouTube](https://www.youtube.com/playlist?list=PL4h6ypqTi3RR_bhBk6PtLfD83YkaJXXxw) （我没看过，不做评价）
1. B站视频教程：
   1. <https://www.bilibili.com/video/BV1Qf4y1F7Zv> 较为简短，内容不是很全面
   1. <https://www.bilibili.com/video/BV1Mr4y1C7pn> 较为简短，内容比较实战需要基础，废话有点，这个up也更新FXGL（fx的2d游戏引擎）教程
   1. <https://www.bilibili.com/video/BV1fW41167RP> 内容全面，啥都讲了，只需java基础即可，~~废话大王~~
1) ~~使用红红的票票（￥￥￥人民币），让*连屁股都可以卖的*群友写~~
1. JavaFx能打包成安卓应用吗？
   1) Gloun说能，请参考其官方网站的教程（鄙废物dog不会，也不敢推荐别的教程）
1. JavaFX可以可视化编辑页面吗
   1) 可以，使用scenebuilder+fxml
1. Scenebuilder有汉化吗？
   1) ~~就几个单词还记不住了？那你学个j8~~
   1) 可以自己动手丰衣足食
   1) https://pan.baidu.com/s/11pWBZ3uQSRZbuMS8POkLCw?pwd=2ke5 

csdn（部分）汉化的8.5版本，来自csdn 

目前只整理了这些，并不全面，如有问题还请指出！

附：

推荐使用Gradle ，不会的群里有pdf——Java高级技术之Gradle








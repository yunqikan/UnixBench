UnixBench是一款开源的云服务器跑分脚本，十分方便快捷。

简介

UnixBench于1983年在莫纳什大学（Monash University）首次启动，它是一种简单的合成基准测试应用程序。然后由Byte Magazine进行了扩展。Jon Tombs和原始作者Ben Smith，Rick Grehan和Tom Yager的Linux mod。这些测试通过将Unix系统的结果与通过在基准系统（SPARCstation 20-61，额定值为10.0）上运行代码而设置的一组分数进行比较，来比较Unix系统。

David C. Niemi对该程序进行了相当长时间的维护，并进行了一些重大修改和更新，并生产了UnixBench 4。后来，他将该程序交给Ian Smith进行维护。Ian随后进行了一些重大更改，并将其从版本4修订为版本5。

感谢Ian Smith对5.1.3之前的版本进行管理。从下一个版本（5.2）开始，Anthony F. Voellm将帮助维护代码库。一旦有足够的拉取请求以保证有新的发布，就会发布这些发布。

一般过程如下：

打开一个宣布即将发布新版本的错误。
dev分支上的所有内容都将运行。
代码将从dev分支移入main并被标记。Bug发行版本随着Subversion的增加而增加，主要功能的更改将增加主要版本。

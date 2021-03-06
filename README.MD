# TDD实战@保龄球
![Build](https://github.com/xpbootcamp/tdd-bowling/workflows/Build/badge.svg)


## 开发环境
 - JDK1.8+
 - JUnit 5



## 用户故事
请你设计一个计算保龄球比赛一局总得分的程序，保龄球的计分规则如下：

- 每一局总共有十轮，每轮一开始会有十支球瓶，球手可以扔两次球，目标就是用尽量少的球把全部球瓶击倒。
- 如果第一球就把全部的球瓶都击倒了，也就是STRIKE，画面出现“X”，就算完成一轮了，所得分数是10分再加后面两球的倒瓶数，
- 如果第一球没有全倒，就要再打一球，如果第二球将剩下的球瓶全都击倒，也就是SPARE，画面出现“/”，也算完成一格，所得分数为10分再加下一格第一球的倒瓶数，
- 如果第二球也没有把球瓶全部击倒的话，那分数就是第一球加第二球倒的瓶数，没有奖励（bonus），再接着打下一格。依此类推。
- 第十轮有机会扔三次球。如果在第十轮出现STRIKE或者SPARE，则球手可再加打第三球。
- 全部十轮的得分相加就等于这一局的总得分。


## 参考资料
- [JUnit 5用户指南](https://sjyuan.cc/junit5/user-guide-cn/)
- [Gradle 用户指南](https://docs.gradle.org/current/userguide/userguide.html)
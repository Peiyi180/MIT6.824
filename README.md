# 简介

一直在断断续续的学习mit 6.824 分布式系统这门课程。分布式系统是现在计算机软件系统中不可避免的一种架构，了解分布式系统对于构建任何大型分布式应用，对于理解分布式程序的运行，对于优化分布式程序的运行环境都有一定的帮助。

mit6.824 这门课程可以说是明星课程了，主讲老师是Robert Morris，这个看起来平易近人的小老头，是个传奇人物【1】。能够听这样的传奇人物叨叨十几个小时，本身就是一种享受，更何况Robert教授能够一种理论联系实际的方式，将主流的分布式系统软件讲的浅显易懂。

美中不足的是，这门课程是全英文，甚至英文字幕都没有。对于国内的同学来说，如果英文没有足够好，很难较好的理解这门课程。因此我计划将这门课程翻译成中文文字版。**我将在语句通顺的前提下，尽量还原课程的内容**，希望可以帮助大家学习到这门课程。如果你的英语不是那么好，建议阅读完文字再去看视频相关的课程。

这门课程总共有20节课，4个实验，实验都是基于golang完成，课程配套了实验相关的测试用例，动手完成实验可以加深对于相关知识的理解。所有课程内容可以在【2】找到。

每一节课都在80分钟左右，大概会有6-9个知识点，我会按照独立的知识点将每节课拆分成6-9个小节。

对于文中出现的错别字，错误的描述，恳请大家发现后指出，我将改正。

【1】[https://zh.wikipedia.org/wiki/%E7%BD%97%E4%BC%AF%E7%89%B9%C2%B7%E6%B3%B0%E6%BD%98%C2%B7%E8%8E%AB%E9%87%8C%E6%96%AF](https://zh.wikipedia.org/wiki/%E7%BD%97%E4%BC%AF%E7%89%B9%C2%B7%E6%B3%B0%E6%BD%98%C2%B7%E8%8E%AB%E9%87%8C%E6%96%AF)

【2】[https://pdos.csail.mit.edu/6.824/schedule.html](https://pdos.csail.mit.edu/6.824/schedule.html)

## 如果

* 你发现了翻译的错误，或者想把剩下几节课程的翻译补上，可以向关联的[github](https://github.com/huihongxiao/MIT6.824)提交PR
* 你觉得我做的还不错，可以关注我的[知乎](https://www.zhihu.com/people/xiao-hong-hui-15)，并给我一个点赞。
* 还想学习其他IT相关知识，我还做了一些其他的翻译：
  * MIT6.s081 - 操作系统：[github](https://github.com/huihongxiao/MIT6.S081)；[gitbook](https://mit-public-courses-cn-translatio.gitbook.io/mit6-s081/)
  * MIT6.829 - 计算机网络 （只有前三章，已停更）：[github](https://github.com/huihongxiao/MIT6.829)；[gitbook](https://mit-public-courses-cn-translatio.gitbook.io/mit6.829/)
  * TCP拥塞控制：[github](https://github.com/huihongxiao/TCP-Congestion-Control-A-Systems-Approach)；[gitbook](https://mit-public-courses-cn-translatio.gitbook.io/tcp-congestion-control-a-systems-approach/)

## _声明_

_此次翻译纯属个人爱好，如果涉及到任何版权行为，请联系我，我将删除内容。文中所有内容，与本人现在，之前或者将来的雇佣公司无关，本人保留自省的权利，也就是说你看到的内容也不一定代表本人最新的认知和观点。_

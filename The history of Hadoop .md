## History of Hadoop
---

### 这段历史起源于一个人 ------ Doug Cutting

![image](https://github.com/HaijunMa/Learnig_Hadoop/raw/master/image/0.jpg) | ![image](https://github.com/HaijunMa/Learnig_Hadoop/raw/master/image/2.png)

---

- **Doug Cutting**在1981年进入斯坦福大学学习，在大一大二期间已学习物理、地理等常规理论知识，
所以说他并不是一开始就决心投身 IT 行业的，因为学费的压力，Cutting 开始意识到，自己必须学习
一些更加实用、有趣的技能。这样，一方面可以帮助自己还清贷款，另一方面，也是为自己未来的生活做打算。
因为斯坦福大学座落在 IT 行业的“圣地”硅谷，所以学习软件对年轻人来说是再自然不过的事情了。大学生活很快
就结束了。

---
- **1986年2月**去了一家语音技术研究中心，做研究助理.在这做了1年5个月后离职了。
---
- **1987年6月**去了Xerox PARC,做研究人员，在这个研究中心诞生了许多创造性的研发成果：个人计算机Xerox Alto、
激光打印机、鼠标、以太网；图形用户界面、Smalltalk、页面描述语言Interpress（PostScript的先驱）、图标、
下拉菜单、所见即所得文本编辑器、语音压缩技术等。Xerox当时的激光扫描仪上跑着三个不同的操作系统，其中有一
个操作系统还没有屏幕保护程序，Cutting 就开始为这套系统开发屏幕保护程序。由于这套程序是基于系统底层开发的，
所以其他同事可以给这个程序添加不同的主题。这份工作给了Cutting 一定的满足感，也是他最早的“平台”级的作品。
这段时间让他在搜索技术的知识上有了很大提高。他花了四年的时间搞研发，这四年中，他阅读了大量的论文，同时，
自己也发表了很多论文，用 Cutting 自己的话说——“我的研究生是在 Xerox 读的。”在这里待了5年2个月后，又离开了。

---
- **1992年7月**加入了苹公司，担任高级技术专家，负责研发当时的一款苹果OS，后来这款OS取消了，Cutting也就离开了，
在这里待了3年10个月。
---
- **1996年4月**他又加入了Arichtext,担任首席工程师，并负责 Excite搜索引擎。就在他任职Arichtext期间，
还发生过一个小故事。当时Google的两个创始人拉里·佩奇和谢尔盖·布林这两个年轻人曾去拜访这家公司，并向他们兜售自己的搜
索技术，但当时他们的 Demo 只检索出几百万条网页，Excite 的工程师们觉得他们的技术太小儿科，于是就在心里鄙视一番，把他
们给送走了。但故事并未到此结束，这两个年轻人回去之后痛定思痛，决定自己创业。于是，1998年他们开了一家自己的搜索公司，
取名为 Google。尽管 Xerox 让 Cutting 积累了不少技术知识，但他却认为，自己当时搞的这些研究只是纸上谈兵，没有人试验过
这些理论的可实践性。于是，他决定勇敢地迈出这一步，让搜索技术可以为更多人所用。

---
- **1997 年底**，Cutting 开始以每周两天的时间投入，在家里试着用 Java 把这个想法变成现实，不久之后,Lucene 诞生了。之所以
叫Lucene，是因为取自他的妻子和外祖母中间的名字。作为第一个提供全文文本搜索的开源函数库，Lucene 的伟大自不必多言。之后，
Cutting 再接再厉，在 Lucene 的基础上将开源的思想继续深化。

---
- **2000年**的时候迎来了第一次互联网泡沫，大量的互联网企业在这场泡沫中破产倒闭。也包括Cutting供职的这家Arichtext公司。
Cutting此时事业了，然后去了两家互联网公司InfraSearch和Grand Central做首席工程师，都任职一年后就离职了。失业的他
只能靠写点技术专栏文章赚赚稿费。

---
- **2002年**他联合他的伙伴Mike Cafarella,当时两人觉得以后搜索被一个大公司给一统天下是一个很可怕的事情, 这家公司掌握信息入口,
能翻手为云覆手为雨。所以决定自己搞一个开源的搜索引擎出来, 于是说干就干, 干了个项目叫Nutch。Nutch也是建立在Lucene上的。
两人吭哧吭哧干了一年之后, 终于把这个系统干到能支持1亿网页的抓取, 索引和搜索了。但是当时的网站差不多就有10亿, 网页数量是万
亿这个规模。这两哥们也没多想, 就是干, 继续把网页量给干到下一个数量级。

---
- **2003年10月**，Google在一次会议上公布了一篇GFS的论文，Google的技术只给他们自己的工程师用，当时的GFS是C++实现的，于是他们用Java实现了。
---
- **2004年12月**，Google又公布了一篇MapReduce的论文，他们两又 都用Java实现，并添加到Nutch项目中，命名NDFS。
---
- 这时的Nutch只是跑在20 - 40个节点之上，他们两意识到只有将Nutch跑在上千个节点上才会发挥它的潜力，同时仅靠他两的能力是不够。出于对时间成
本的考虑，在从 Architext 离职四年多后，Cutting 决定结束这段 Freelancer 的生涯，找一家靠谱的公司，进一步完善Nutch的性能。他先后面试了几
家公司，其中也包括 IBM，但 IBM 似乎对他的早期项目 Lucene 更感兴趣，至于Nutch则不置可否。他表示不开心, 就去问Yahoo愿不愿意要Nutch, 人家
Yahoo有自己的搜索引擎, 也不愿意要Nutch。不过Yahoo考虑了一下, 说虽然不要你的搜索系统, 但是你底层那几个GFS/MapReduce那些东西还是挺有用的嘛, 
要不你过来弄这个? Dog Cutting也就从了, 于是把底层系统剥离出来, 把自己儿子的一个大象的玩具的名字Hadoop赋予了这个项目。

..........................................................................![image](https://github.com/HaijunMa/Learnig_Hadoop/raw/master/image/1.png).........................................................................................

---
- **2006年**加入了雅虎。但是到目前为止, Hadoop其实还不能称之为一个独立的大数据项目, 顶多只能称之为一个搜索系统的子项目, 因为他只有一个应用方, 
就是搜索。当系统进入Yahoo了以后,项目逐渐发展并成熟了起来。首先是集群规模, 从最开始的几十台机器的规模发展到能支持上千个节点的机器, 中间做了
很多工程性质的工作, 然后是除搜索以外的业务放,Yahoo逐步将自己的广告系统的数据挖掘相关工作也迁移到了hadoop上面来, 进一步成熟化了hadoop系统。
当有多个用户方在使用hadoop系统的时候, 又必须要增加qos调度队列等机制, 也必须要增加数据安全认证授权机制等等, 各种功能都加到hadoop上面来的时候, 
hadoop就算是真正成熟起来了。必须要称道的一点是, 在成熟化整个系统的过程当中, yahoo一直都将hadoop做成一个开源软件, 而不是自己的私有软件。

---
- **2008年的时候**, 一位Google的工程师Christophe Bisciglia负责了Google跟IBM合作的一个自然科学项目（大规模集群计算）, 这哥们发现要把当时的Hadoop
放到任意一个集群中去运行时一件很困难的事情, 虽然项目是开源的， 但是当时其实主要是yahoo在用, 想要将hadoop商业化推给更多团队在用, 可能想要进一步
的动作将其从开源带到业界。于是这哥们就拉了几个好基友, 一块成立了一个专门商业化hadoop的公司: Cloudera。这个公司做了很多事情, 连接了开源和业界的
鸿沟, 为hadoop生态的发展做出了非常重要的贡献。为了更好的提供外围服务, cloudera基于开源的Hadoop版本提供了另外一个叫CDH的Hadoop版本。

---
- **在2009年**Cutting也离开了Yahoo，加入了这家公司，同时还进入了The Apache Software Foundation。
---
- **在2011年**Yahoo将hadoop团队专门成立了一个子公司Hortonworks专门提供hadoop相关的服务。Baldeschwieler这哥们作为这个公司的老板。
Hortonworks这个公司跟Cloudera不一样, Hortonworks不再单独提供一个版本的hadoop给用户选择, 而是完全基于和更新开源版本。但是他提供很牛B的
三陪服务, 已经为很多公司, 比如微软, Teradata, Rackspace 合作搭建他们自己的开源hadoop集群, 并在业界形成了很好的口碑。

---
 - 就是这样，一个原本不打算成就IT事业的人在误打误撞之后凭借自己的天赋成就了自己的一片天地。


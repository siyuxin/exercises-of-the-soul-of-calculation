# exercises-of-the-soul-of-calculation
# 计算之魂思考题探讨
<a href="url"><img src="https://github.com/siyuxin/exercises-of-the-soul-of-calculation/blob/main/images/book.jpg" height="280" width="210" ></a>

## 项目背景
《计算之魂》是《数学之美》姊妹篇，是吴军博士时隔近10年在科技领域的重磅新作。在本书中，作者将人文历史与计算机科学相结合，通过一些具体的例题，分10个主题系统地讲解了计算机科学的精髓。全书的例题+思考题超100道，这些例题是作者面试求职者时用到的考题，或是头部计算机公司和金融企业的面试题。


我们将共读《计算之魂》并围绕这些思考题进行交流探讨，项目持续约1年，过程中会邀请《计算之魂》策划者等大咖，甚至吴军老师来直播分享，一起培养计算思维的方式，了解 IT 产业的技术特点、掌握信息时代特殊的做事方法，通过思维的碰撞与具体的例子，从“术”的层面获得“道”的层面的提升。


## 任务安排
首次组队学习活动，围绕第一章展开共读

|   Task   |      内容     |   时间   |
|----------|:-------------:|:------:|
| Task01   |  阅读1.1,1.2并输出笔记，完成思考题1.1，1.2 | 8-15 —— 8-20 |
| Task02   |  阅读1.3并输出笔记，完成思考题1.3   | 8-20 —— 8-27 |
| Task03   |  阅读1.4.1,1.4.2并输出笔记，完成思考题1.4 | 8-27 —— 9-3 |
| Task04   |  阅读1.4.3与附录并输出笔记，完成思考题1.4 | 9-3 —— 9-10 |

## 拓展资料
书籍配套视频：https://space.bilibili.com/431850986/channel/collectiondetail?sid=619198<br>
书籍第一章在线阅读（感谢吴军老师授权开源）:https://linklearner.com/datawhale-homepage/#/learn/detail/107<br>
第一章共读活动读者分享讲义（by CELFS）:https://rf8j0i8s4f.feishu.cn/file/boxcn1foj2Y0pHLpD1NCbEJtR7b

## 思考题安排 

### 引子 计算的本质——从机械到电子
思考题0.1   如何通过指令控制，将一副扑克牌编程一种简单的计算机？ //01-02<br>
思考题0.2   利用“与非”（AND-NOT）运算实现布尔代数中的与、或、非三种运算。 /02<br>
思考题0.3   如果计算的本质是机械运动，那么信息处理和能量就存在一个对应关系。比如，
我们可以计算一下1946年的ENIAC消耗1度电( 1千瓦时)能完成多少次计算，今天的华为P30手机消耗1度电能完成多少次计算。 /018<br>
思考题0.4   在数字计算机出现之前曾经出现过模拟计算机，如何证明后者等价于前者的某个子集?  /022<br>

### 第1章 毫厘千里之——大O概念
思考题1.1   世界上还有什么产品类似于计算机，是软硬件分离的?  /028<br>
思考题1.2   如果一个程序只运行一次，在编写它的时候，你是采用最直观但是效率较低的算法，还是依然寻找复杂度最优的算法?  /034<br>
思考题1.3<br>
Q1.将上述例题1.3的线性复杂度算法写成伪代码。<br>
Q2.在一个数组中寻找-一个区间，使得区间内的数字之和等于某个事先给定的数字。( AB、FB、LK等公司的面试题，后面会解答。<br>
Q3.在一个二维矩阵中，寻找一个矩形的区域，使其中的数字之和达到最大<br>
值。(例题1.3的变种，硅谷公司真实的面试题。） /045 <br>
思考题1.4   <br>
Q1.赛跑问题( GS )。 /056  <br>
Q2.区间排序。 /057<br>

### 第2章 逆向思考——从递推到递归
思考题2.1 有n级台阶，每次能够上k级，有多少种不同的攀登方法?
提示:走到第n级，上-次可能处在第n-1、n -2...n-k级。 /072<br>
思考题2.2  <br>
Q1.修改中序遍历算法22,将它变成先序遍历或者后序遍历的算法。  /079<br>
Q2. (二叉排序树)有这样一串数字5, 2,8,0, 10, 7, 18, 20, 30, 12, 15, 1,我们将它们建成一一棵二叉排序树。二叉排序树满足下面的条件。 /079-080<br>
思考题2.3   <br>
Q1.写出简单计算器的伪代码( AB、FB等） /086<br>
Q2.回旋打印二叉树的节点 (作者使用过的面试题)。 /086<br>
思考题2.4   <br>
Q1.二叉树的最大深度(也被称为树的高度)是从根节点到最远的叶子节点的
节点数。请写一个判定任意二叉树最大深度的算法。  /092<br>
Q2.如何在一个二叉排序树中找到第二大的元素?    /092<br>


### 第3章 万物皆编码——抽象与表示
思考题3.1  给定一个集合，如何输出它的幂集?   /104<br>
思考题3.2   /110<br>
思考题3.3  设计一种编码方法，用8位二进制数(一个字节)表示浮点数。/114<br>
思考题3.4  在网页搜索中，要记录每一个关键词出现的网页，以及关键词在网页中的位置，如何设计对这个信息的编码，让每个关键词的索引总长度最短?  /18<br>
思考题3.5   Q1、Q2.   /112<br>
思考题3.6  如果我们采用本节存储稀疏矩阵的方法存储了两个矩阵，如何实现矩阵的加法运算  /130<br>
练习题  /131-132

### 第4章 智能的本质——分类与组合
思考题4.1   有两类模式A和B，如果A被识别为了B，损失是10；如果B被识别为了A,损失是1。这两个模式之间的边界应该如何划定?  /140<br>
思考题4.2<br>
Q1.如何制作一个色情网站或者垃圾邮件发送者的黑名单? <br>
Q2.如何判断一个网页是否是色情网页?   /147<br>
思考题4.3   在拼音输入法中，如何根据拼音，或者部分拼音，快速找到相应的汉字，以及包含该汉字的词?   /153<br>
思考题4.4   北京的街道通常是横平竖直的。假如你站在某个十字路口，需要往东、往北各走N个街区，有多少种不同的走法?   /161<br>

### 第5章 工具与算法——图论及应用
思考题5.1   除了上面举的例子，你能否举出五个其他的现实世界中的例子，可以用抽象的图来描述?  /172<br>
思考题5.2  Q1、Q2  /176<br>
思考题5.3  Q1  /188<br>
思考题5.4    /198<br>
思考题5.5   Q1、Q2   /203<br>

### 第6章 化繁为简——分治思想及应用
思考题6.1   /218<br>
思考题6.2   /231<br>
思考题6.3   /238<br>
思考题6.4   如何用多台服务器实现大矩阵求逆?  /246<br>

### 第7章 权衡时空——理解存储
思考题7.1  /265<br>
思考题7.2层次 /274<br>
思考题7.3如果我们想要提供一个特殊的搜索服务一找出 NBA历史上三分球命中率在
0.23到0.32之间的人，如何建立索引?   2/78<br>

### 第8章 并行与串行——流水线和分布式计算
思考题8.1  /283-284<br>
思考题8.2  /286<br>
思考题8.3  Q1、Q2  /295<br>

### 第9章 状态与流程——等价性与因果关系
思考题9.1   /304-305<br>
思考题9.2   /311<br>
思考题9.3   /318<br>

### 第10章 确定与随机——概率算法及应用
思考题10.1  <br>
Q1优惠卷问题  /324-325<br>
Q2  优惠卷扩展问题  /325<br>
Q3  雨滴问题   /325<br>
思考题10.2  Q1、Q2  /329<br>
思考题10.3   /336-337<br>

### 第11章 理论与实战——典型难题精解
思考题11.1  Q、Q2   /351<br>
思考题11.2  倒装句问题  /382-383<br>
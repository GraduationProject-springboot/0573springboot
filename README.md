# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0573springboot宿舍管理系统_o4dvi--论文

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1eMbYemE1U?p=71)


# 第一章 概述
## 1.1 研究背景
近些年，随着中国经济发展，人民的生活质量逐渐提高，对网络的依赖性越来越高，通过网络处理的事务越来越多。随着宿舍管理的常态化，如果依然采用传统的管理方式，将会为工作人员带来庞大的工作量，这将是一个巨大考验，需要投入大量人力开展对宿舍管理等相关工作进行管理，单一且反复的操作容易出错且不易被察觉，工作人员对此风险并不能完全归避。利用现代信息技术，设计开发一款宿舍管理系统，能够极大的节省人力物力、提高工作效率、降低工作成本。
## 1.2研究目的及意义
本论文拟采用计算机技术设计并开发的宿舍管理系统，主要是为宿舍提供服务。使得的用户可依据、时间、地点或者其他特定条件，筛选出符合的信息，给用户提供更符合实际的合理化建议，再为用户提供服务。本课题的意义在于，用户能通过使用宿舍管理系统，提高用户的工作效率和服务质量，进而提高用户的体验感。
## 1.3国内外发展现状
相比于国内，国外的线上管理系统建设比较早，在上世纪就已经很先进，但受七十年代的经济危机影响，导致部分国家发展缓慢，但也有些发达国家走群众路线，全面发展网络技术。

在国内，线下管理系统已经特别完善，它基于计算机技术，让系统具有信息化、科学化、自动化等特性。在计算机的辅助下，国内该类系统可使管理者提高信息的复用率，对数据的处理、备份等方面也有了显著的效率提升，这种有效的工作可使管理者能更快的做好决定，也实现了“无纸化”的信息管理方式。由于其功能特别完善，也导致系统比较庞大，所以在了解该类系统的功能、操作后，决定开发一款宿舍管理系统，它的功能小，但是操作简单、快速、准确的特点，也体现了设计它的意义。
## 1.4 研究内容
1. 调研：通过网络、图书馆等渠道调查该课题的参考资料。
1. 系统需求分析：对参考资料分类整理，设想需求与功能，再研究实现功能所需的开发工具、技术、数据库等。
1. 系统概要设计：设计功能模块、流程、数据库模型、表与字段间的关系等。
1. 系统实现：对系统用户以文字加截图的形式进行精细化分解。
1. 系统测试：测试的作用和好处，测试的具体操作步骤，分析需求与测试结果是否一致。
## 1.5本文的结构
本论文分为六个章节。

第一章，绪论，其包含课题背景及意义，现国内外的发展现状，本课题要研究的内容，所使用开发工具的描述等信息。

第二章，主要介绍了系统的开发技术。

第两章，先讲述功能需求分析，再讲述系统可行性分析和流程图的设计。

第四章，是系统设计原理，功能模块设计和数据库设计。

第五章，详情讲述每个界面的正确操作步骤。

第六章，该章讲述了测试的目的以及测试过程及用例。

最后对论文进行总结，包括致谢和参考文献等内容。


# `	`第二章 开发工具及技术介绍
此次管理系统的关键技术和架构由B/S结构、java技术和MySQL数据库，是本系统的关键开发技术，对系统的整体、数据库、功能模块、系统页面以及系统程序等设计进行了详情的研究与规划。
## 2.1 Java编程语言
Java语言的发展距今己有二十多年的历史，Java在众多编程开发语言中依然稳居排名前两，这离不开Java技术体系的众多开发优势，相对比于其他编程开发语言而言，Java语言[}so]的入门使用非常简单，Java集成了丰富的类库和封装类，能够使开发者非常方便调用，拥有强大的技术基础作为支撑，非常适合大型软件的开发。由于Java语言是一门面向对象的编程语言，因此程序员只需要掌握基本的语法规则和清晰的编程思路便可以较好地开发应用程序。除此之外，由于Java语言具有跨平台和可移植性强的开发优点，因此可以在Android的应用程序开发中发挥其重要作用。在大型的软件项目开发中应用Java技术较为广泛，能够为企业项目需求提供成熟的解决方案。

常用的计算机程序编程语言有Java语言、Python语言、C语言以及C++语言。由于Java语言具有成熟的技术架构以及较为广泛的应用范围，因此深得编程人员的喜爱。

Java语言提供了try-catch异常处理、垃圾自动回收、内存动态分配等强大功能机制，Java语言具备简单性、健壮性、可移植性、多线程等优点，Java语言的强大特性能够降低软件后期的维护成本以及有效缩短软件研发周期，节省了企业的软件开发成本。本论文研究的宿舍管理案例项目正是以成熟的Java编程语言为基础的宿舍管理系统项目开发语言。
## `  `2.2 MySQL数据库
MySQL是Oracle公司旗下的一个开源的关系型数据库管理系统(Relational Database Management System, RDBMS)}44} o MySQL支持使用多线程，充分利用了CPU的计算资源，可以选择InnoDB, MyISAM和MEMORY等作为存储引擎，提供了丰富的数据库管理工具。在索引功能的加持下，其具有非常高的查询效率，并支持主从、多节点集群等高可用部署模式。MySQL凭借其低廉的成本、可靠的数据库服务和出色的性能，目前己经成为绝大多数企业在进行项目开发时的首选关系型数据库。MySQL的体系结构如图2-1所示，具体可分为网络连接层、服务层、存储引擎层和系统文件层，分别完成建立连接、SQL解析与执行、数据存储与提取和数据交互等功能。

![](/md/blog.002.png)

图2-1 MySQL体系结构图
## 2.3 SPRINGBOOT 框架
Spring Boot是由Pivotal的开发团队在2013年开发的一个免费、轻量级、开源的系统框架。SpringBoot的主要设计思想是约定大于配置，因此SpringBoot在设计时几乎达到零配置。SpringBoot集成了业界的开源框架。

SpringBoot是一个非常强大的后台框架，因为SpringBoot的开发基本上不需要写配置文件，所以利用SpringBoot来构建系统的后台环境，在SpringBoot的YML配置文件中写项目启动端口，项目就可以启动了。项目的Java和静态文件由SpringBoot管理。
## 2.4 B/S架构
B/S结构就是指系统客户端与服务器分离，客户端通过浏览器访问服务端进行操作[10]。

B/S结构目前广泛应用于绝大部分系统搭建中，这种结构摒弃C/S结构客户端服务端不分离的缺点，具有更多的优势：

（1）跨平台性：B/S的标准由标准化组织确立，适用于绝大多数的系统搭建，通用于应用之间。

（2）低维护成本：客户端和服务器端分离，减轻了两端的压力，尤其是客户端，对客户端设备，硬件、软件要求都比较低，并且系统需要升级或维护时，只需要在服务器端升级或维护就可以，使相应的费用减少。
# 第三章 系统分析
## 3.1功能需求分析
需求分析的首要任务是要分析用户的需求，知道用户存在的一些情况，并且要明确用户的使用状况，然后设计规划解决的问题。其中在使用定性的分析以及定量的分析，从这两个方面获取用户的需求。一方面定性的分析获得的应该是用户的基本需求，能够发现现在人们的习惯要求。所以定性的需要主要是为了多与用户交流，从而更为深刻的了解一些存在的需求问题；定量的分析则是发现一些潜在的用户，并且获得不一样的反馈内容。所以定量的需求要让用户来阐述一些情况，一定让使用者清晰的进行客观的描述，这样才能够比较全面的获得用户的需求所在。

其中获得用户需求以后，就要可以将用户需求设计为系统的功能模块。在能及时的分析和发现有关需求的情况下，需要系统同时的跟进需求设计。在宿舍管理过程中还需要创建需求工作的数据分析，以便于后面的分析做总结。写入一个需求的报告内容，其中需要包含完整的描述需求、以及功能需求、模型等后续开发过程中还需要用到的部分资料。

需求的分析中用户需求就是比较的重要，而且可以通过各种的路径，以及各用户对于系统的功能需求，你需要对这些内容做出整理以及分类，然后分析这些需求的现实情况下的可能原因，还需要有认真的分析过程，结合现实的情况下最终做出一系列的需求资料。在有关用户的期望分析中能够明确一些可能实现的情况，宿舍管理功能是许多个可以测试的功能相结合的，正是由于这些功可以使得用户能够更加积极的提供出需求，让系统功能可以变得更加的完善。这样就可以保证所有设计的功能模块都是可以用到的，而且也是可测试的，对于后续系统的开发能够有比较关键的作用，也能快速完成用户所提供的需求。 
## 3.2系统可行性分析
### 3.2.1技术可行性
该系统使用java技术开发，MySQL数据库同Springboot框架联合开发并实现。对于以上描述的技术，在当代都是较为成熟的技术和平台，虽然它们都有自已的体系，但在程序员的眼里，它们的配合度是很高的，网上的相关博客中每个创建项目的帖子，它们都会出现，数据库负责管理数据，开发工具负责管理项目，技术负责代码的框架，既相互独立，又相互依赖。以上描述的工具、技术都已转化为自身的技能，所以从技术角色考虑是可行的，工作人员对于技术的关注度并不高，只要程序可用即可。
### 3.2.2 经济可行性
经济可行性，可分为两种，支出和收入，该系统属于研究型毕业设计，所以收入部分暂不考虑。支出可分为，设备、场地、开发环境、人力、时间等一切需考虑的因素，所有信息都是影响形成系统的一部分。设备：只需一台笔记本电脑，配套的输入设备；场地：暂定为图书馆与校内的自习室；开发环境：良好；人力：自身、指导老师、同学；时间：从选题到毕业为止，大约八个月。从以上描述可知，大部分条件已经满足，所以该系统不会存在经济方面的问题，所以是可行的。
### 3.2.3社会可行性
社会可行性，广义而讲可涉及到道德方面、法律方面、社会方面，每个方面都会影响系统的形成[12]。本系统的是独立且没有任何传播性质的信息，更涉及不到道德层面，法律层面；本系统也没有触发法律，没有赌博、黄色等类型信息，同时也是遵从国家法律，不会显示任何触发法律层面的信息；社会方面，该系统是为方便客户提供更好的服务，是轻量级的宿舍管理系统，会为人们带来快速并有效查询的功能，也是具有贡献意义的。总体而言，该系统也是具有社会可行性的。
## 3.3 系统用例分析
宿舍管理系统综合网络空间开发设计要求。目的是将传统管理方式转换为在网上管理，完成宿舍管理的方便快捷、安全性高、交易规范做了保障，目标明确。宿舍管理系统可以将功能划分为管理员功能和学生功能。

（1）管理员关键功能包括对系统首页、个人中心、学生管理、宿舍信息管理、宿舍分配管理、水电费管理、进入宿舍管理、出入宿舍管理、维修信息管理、卫生信息管理、考勤信息管理、留言板、交流论坛、系统管理等进行管理。管理员用例如下：

![](/md/blog.003.png)

图3-1 管理员用例图

（2）学生关键功能包括对首页、交流论坛、宿舍公告、留言板、后台管理、个人中心等进行浏览。学生用例如下：

![](/md/blog.004.png)

图3-2 学生用例图
## 3.4系统流程分析
流程图是用具体的图形符号和相应的线条来表示系统执行的整个过程。因为这种图可以很容易地描述系统的一系列过程，所以它的所有图形符号都是比较关键的，基本上一个图形符号可以表示一个过程的一个步骤。流程图不仅提供了一个比较完整、全面的实施过程，而且可以发现整个团队协同设计过程中可能存在的缺陷和不足，便于在后续过程中及时对系统进行修正和改进。

通过流程图可以对系统的需求和相关流程进行分析，可以详情细分为各个部分的设计。对于设计人员来说在开发过程中要能够以流程图为基础，能够快速的提高自己的逻辑思维，并且也能够指导后续的操作在系统设计中最重要的部分就是程序的设计，然后具体的编写程序，流程图是设计过程中的重要工具，下面是流程图的部分设计。
### 3.4.1 登录流程图
登录流程是该系统的第一个流程，登录的第一步是输入账号、密码登录，系统会验证账号与密码是否正确，正确时系统会判断账号类型再进入不同的后台；不正确时，会返回到登录的第一步，输入用户重新执行登录流程。该流程如图3-3所示：

![](/md/blog.005.png)

图3-3登录流程图
### 3.4.2 添加新用户流程图
添加新用户的流程是先查询新用户名是否已存在，如已有该用户名，需重拟用户名并同时输入新用户的其它信息，添加新用户到数据库时会先验证数据是否完整，信息都正确且完整时，返回并刷新用户列表；信息不正确时，会返回输入信息的那一步。该流程如图3-4所示：

![](/md/blog.006.png)

图3-4添加新用户流程图


# 第四章 系统设计
## 4.1系统设计原理
设计原理，是指一个系统的设计由来，其将需求合理拆解成功能，抽象的描述系统的模块，以模块下的功能。功能模块化后，变成可组合、可拆解的单元，在设计时，会将所有信息分解存储在各个表中，界面不会显示所有定义的字段。在设计时，会有几大要求，抽象、模块化、信息隐藏、耦合低、内聚等特性，本系统的设计也符合以上几大特性。制作和显示流程都属于程序员需要分析研究的一部分[13]。每个模块都是相对独立的，系统前台不显示账号操作权限范围外的信息。
## 4.2功能模块设计
该章节的功能模块设计，只是大概描述了系统的所有功能模块，将功能按权限来讲解。系统总体功能如图4-1所示：

![](/md/blog.007.png)

图4-1 系统总体功能图
## 4.3 数据库设计
### 4.3.1数据库设计原则
学习程序设计，如果想要了解数据库管理系统或者是按照系统接口的要求制作的，就必须创建一个数据库管理系统模型，用来存储数据，这样在进行应用程序编程的过程中，就不需要加载操作系统页面的信息，从而提高整个系统的工作效率。在数据库管理系统中承载着众多的数据，应该说，一个管理信息系统的建设中心和基地，也为建设管理信息系统和信息管理系统提出了新的查询、删除、修改和操作功能，使管理信息系统建设可以快速查询需要的数据，而不是直接从代码中查找。信息库管理系统由各个组成部分的信息表按照具体的方法进行准确的归并、排序和组成信息库管理系统。
### ` `4.3.2数据库E-R图设计
E-R图即实体-联系图，主要作用是提供了解显示数据类型存在的联系的途径，是藐视现实世界的概念模型，其关键要素是实体型、属性、联系。以下是本系统主要的实体属性图如下所示。

学生实体如图4-2所示：

![](/md/blog.008.png)

图4-2学生实体属性图

宿舍信息实体如图4-3所示：

![](/md/blog.009.png)

图4-3宿舍信息实体属性图

宿舍分配实体如图4-4所示：

![](/md/blog.010.png)

图4-4宿舍分配实体属性图

水电费实体如图4-5所示：

![](/md/blog.011.png)

图4-5水电费实体属性图

宿舍公告实体如图4-6所示：

![](/md/blog.012.png)

图4-6宿舍公告实体属性图

### 4.3.3数据库表结构设计
该系统采用的数据库是MySQL，根据该系统的数据存储特点进行数据库关系表的设计。下面是该系统中关键部分关系表的详情信息。

表4-1：交流论坛

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|帖子标题|||
|content|longtext|4294967295|帖子内容|||
|parentid|bigint||父节点id|||
|userid|bigint||用户id|||
|username|varchar|200|用户名|||
|avatarurl|longtext|4294967295|头像|||
|isdone|varchar|200|状态|||

表4-2：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-3：维修信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|biaoti|varchar|200|标题|||
|sushemingcheng|varchar|200|宿舍名称|||
|susheleixing|varchar|200|宿舍类型|||
|susheloudong|varchar|200|宿舍楼栋|||
|fangjianhao|varchar|200|房间号|||
|xueshengxuehao|varchar|200|学生学号|||
|xueshengxingming|varchar|200|学生姓名|||
|weixiuriqi|date||维修日期|||
|weixiuneirong|longtext|4294967295|维修内容|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||

表4-4：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-5：token表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|userid|bigint||用户id|||
|username|varchar|100|用户名|||
|tablename|varchar|100|表名|||
|role|varchar|100|角色|||
|token|varchar|200|密码|||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|expiratedtime|timestamp||过期时间||CURRENT\_TIMESTAMP|

表4-6：卫生信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|sushemingcheng|varchar|200|宿舍名称|||
|susheleixing|varchar|200|宿舍类型|||
|susheloudong|varchar|200|宿舍楼栋|||
|fangjianhao|varchar|200|房间号|||
|xueshengxuehao|varchar|200|学生学号|||
|xueshengxingming|varchar|200|学生姓名|||
|weishengqingkuang|varchar|200|卫生情况|||
|dengjiriqi|date||登记日期|||
|xiangqing|longtext|4294967295|详情|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||

表4-7：出入宿舍

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|sushemingcheng|varchar|200|宿舍名称|||
|susheleixing|varchar|200|宿舍类型|||
|susheloudong|varchar|200|宿舍楼栋|||
|fangjianhao|varchar|200|房间号|||
|xueshengxuehao|varchar|200|学生学号|||
|xueshengxingming|varchar|200|学生姓名|||
|churushijian|datetime||出入时间|||
|xiangpian|longtext|4294967295|相片|||

表4-8：关于我们

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|subtitle|varchar|200|副标题|||
|content|longtext|4294967295|内容|||
|picture1|longtext|4294967295|图片1|||
|picture2|longtext|4294967295|图片2|||
|picture3|longtext|4294967295|图片3|||

表4-9：宿舍分配

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|sushemingcheng|varchar|200|宿舍名称|||
|susheleixing|varchar|200|宿舍类型|||
|susheloudong|varchar|200|宿舍楼栋|||
|fangjianhao|varchar|200|房间号|||
|xueshengxuehao|varchar|200|学生学号|||
|xueshengxingming|varchar|200|学生姓名|||
|chuangweihao|varchar|200|床位号|||
|fenpeiriqi|date||分配日期|||
|beizhu|longtext|4294967295|备注|||

表4-10：水电费

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|sushemingcheng|varchar|200|宿舍名称|||
|susheleixing|varchar|200|宿舍类型|||
|susheloudong|varchar|200|宿舍楼栋|||
|fangjianhao|varchar|200|房间号|||
|yuefen|varchar|200|月份|||
|shuifei|float||水费|||
|dianfei|float||电费|||
|zongjine|float||总金额|||
|xueshengxuehao|varchar|200|学生学号|||
|xueshengxingming|varchar|200|学生姓名|||
|dengjishijian|date||登记时间|||
|xiangqing|longtext|4294967295|详情|||
|ispay|varchar|200|是否支付||未支付|

表4-11：宿舍公告

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|longtext|4294967295|图片|||
|content|longtext|4294967295|内容|||

表4-12：留言板

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||留言人id|||
|username|varchar|200|用户名|||
|avatarurl|longtext|4294967295|头像|||
|content|longtext|4294967295|留言内容|||
|cpicture|longtext|4294967295|留言图片|||
|reply|longtext|4294967295|回复内容|||
|rpicture|longtext|4294967295|回复图片|||

表4-13：考勤信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|sushemingcheng|varchar|200|宿舍名称|||
|susheleixing|varchar|200|宿舍类型|||
|susheloudong|varchar|200|宿舍楼栋|||
|fangjianhao|varchar|200|房间号|||
|yuefen|varchar|200|月份|||
|xueshengxuehao|varchar|200|学生学号|||
|xueshengxingming|varchar|200|学生姓名|||
|wanguitianshu|int||晚归天数|||
|queqintianshu|int||缺寝天数|||
|qingjiatianshu|int||请假天数|||
|dengjishijian|date||登记时间|||
|beizhu|longtext|4294967295|备注|||

表4-14：进入宿舍

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|sushemingcheng|varchar|200|宿舍名称|||
|susheleixing|varchar|200|宿舍类型|||
|susheloudong|varchar|200|宿舍楼栋|||
|fangjianhao|varchar|200|房间号|||
|xueshengxuehao|varchar|200|学生学号|||
|xueshengxingming|varchar|200|学生姓名|||
|jinrushijian|datetime||进入时间|||
|zhaopian|longtext|4294967295|照片|||

表4-15：学生

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|xueshengxuehao|varchar|200|学生学号|||
|mima|varchar|200|密码|||
|xueshengxingming|varchar|200|学生姓名|||
|xingbie|varchar|200|性别|||
|touxiang|longtext|4294967295|头像|||
|xueshengdianhua|varchar|200|学生电话|||
|banji|varchar|200|班级|||
|zhuanye|varchar|200|专业|||

表4-16：宿舍信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|sushemingcheng|varchar|200|宿舍名称|||
|susheleixing|varchar|200|宿舍类型|||
|susheloudong|varchar|200|宿舍楼栋|||
|fangjianhao|varchar|200|房间号|||
|kezhurenshu|varchar|200|可住人数|||
|yizhurenshu|varchar|200|已住人数|||
|youchuangwei|varchar|200|有床位|||
|gengxinshijian|date||更新时间|||
|xiangqing|longtext|4294967295|详情|||













# 第五章 系统功能实现
## 5.1系统功能实现
当人们打开系统的网址后，首先看到的就是首页界面。在这里，人们能够看到宿舍管理系统的导航条和系统简介等；系统首页界面如图5-1所示：

![34ce49b5a6ca2d71601e0510403f9ed](/md/blog.013.jpeg)

图5-1 系统首页界面

学生注册：在学生注册页面的输入栏中输入学生注册信息进行注册操作；学生注册界面如图5-2所示：

![00f731487c7a8a1266c7430aa79d608](/md/blog.013.jpeg)

图5-2学生注册界面

交流论坛：在交流论坛页面的输入栏中输入标题进行查询，可以查看到交流论坛详细信息，并进行查看帖子内容、点击评论操作；如图5-3所示：

![33f670eff6fb84d668fb549a8b6b7e7](/md/blog.014.jpeg)

图5-3交流论坛详细界面

宿舍公告：在宿舍公告页面的输入栏中输入标题进行查询，可以查看到宿舍公告详细信息；如图5-4所示：

![c23ef839fe532cc42994e4409cf2e07](/md/blog.015.jpeg)

图5-4宿舍公告详细界面

个人中心：在个人中心页面输入个人信息可以进行更新信息操作，还可以对我的收藏进行详细操作；如图5-5所示：

![83465144fe34b78a154dc17d1652e30](/md/blog.016.jpeg)

图5-5 个人中心界面

## 5.2后台模块实现
系统用户登录，在登录页面选择需要登录的角色，在正确输入用户名和密码后，进入操作系统进行操作；如图5-6所示：

![c7a5f63f948f179a0f37b987671f21c](/md/blog.013.jpeg)

图5-6系统登录界面
#########
### 5.2.1管理员功能实现
管理员进入主界面，主要功能包括对系统首页、个人中心、学生管理、宿舍信息管理、宿舍分配管理、水电费管理、进入宿舍管理、出入宿舍管理、维修信息管理、卫生信息管理、考勤信息管理、留言板、交流论坛、系统管理等进行操作。管理员主界面如图5-7所示：

![e226f7337001707f8605a94d2692721](/md/blog.013.jpeg)

图5-7 管理员主界面

学生管理：管理员点击学生管理。在学生页面输入学生学号、学生姓名进行查询、新增或删除学生列表，并根据需要对学生详情信息进行详情、修改或删除操作；如图5-8所示：

![a34a1f15637a28cb742b3fb30bd5daf](/md/blog.013.jpeg)

图5-8学生管理界面

宿舍信息管理：管理员点击宿舍信息管理。在宿舍信息页面输入宿舍名称，选择宿舍类型、有床位进行查询、新增或删除宿舍信息列表，并根据需要对宿舍详情信息进行详情、分配、修改或删除操作；如图5-9所示：

![e3d0da988e6e92527443133a72ad054](/md/blog.013.jpeg)

图5-9宿舍信息管理界面

宿舍分配管理：管理员点击宿舍分配管理。在宿舍分配页面输入宿舍名称、学生姓名进行查询或删除宿舍分配列表，并根据需要对宿舍分配详情信息进行详情、水电费、考勤、修改或删除操作；如图5-10所示：

![6617068a6064e2ea3c0b52c1e09039f](/md/blog.013.jpeg)

图5-10宿舍分配管理界面

水电费管理：管理员点击水电费管理。在水电费页面输入宿舍名称、学生姓名进行查询或删除水电费列表，并根据需要对水电费详情信息进行详情、修改或删除操作；如图5-11所示：

![f2047e864b72dc255a8b604d126ffe7](/md/blog.013.jpeg)

图5-11水电费管理界面

进入宿舍管理：管理员点击进入宿舍管理。在进入宿舍页面输入宿舍名称进行查询或删除进入宿舍列表，并根据需要对进入宿舍详情信息进行详情、修改或删除操作；如图5-12所示：

![770cb4582bcd1484b0246d9a37cb7ad](/md/blog.013.jpeg)

图5-12进入宿舍管理界面

出入宿舍管理：管理员点击出入宿舍管理。在出入宿舍页面输入宿舍名称进行查询或删除出入宿舍列表，并根据需要对出入宿舍详情信息进行详情、修改或删除操作；如图5-13所示：

![eb65d8dba154a8b17500d5760934c50](/md/blog.013.jpeg)

图5-13出入宿舍管理界面
#########
维修信息管理：管理员点击维修信息管理。在维修信息页面输入标题，选择是否通过进行查询、删除或批量审核维修信息列表，并根据需要对维修详情信息进行详情、修改或删除操作；如图5-14所示：

![8c741f9516be1360a0cb55eaa32d363](/md/blog.013.jpeg)

图5-14维修信息管理界面
#########
卫生信息管理：管理员点击卫生信息管理。在卫生信息页面输入宿舍名称，选择卫生情况、是否通过进行查询、删除或批量审核卫生信息列表，并根据需要对卫生详情信息进行详情、修改或删除操作；如图5-15所示：

![865f0347ddff7f91c950c49fb266e66](/md/blog.013.jpeg)

图5-15卫生信息管理界面
#########
考勤信息管理：管理员点击考勤信息管理。在考勤信息页面输入宿舍名称、月份进行查询或删除考勤信息列表，并根据需要对考勤详情信息进行详情、修改或删除操作；如图5-16所示：

![a3e74e8c095c23763d7d07c9895f70c](/md/blog.013.jpeg)

图5-16考勤信息管理界面

交流论坛：管理员点击交流论坛。在交流论坛页面输入帖子标题进行查询或删除交流论坛列表，并根据需要对交流论坛详情信息进行详情、修改、查看评论或删除操作；如图5-17所示：

![f08d53f8715b6c99de45b5fd5c1558d](/md/blog.013.jpeg)

图5-17交流论坛界面
#########
系统管理：管理员点击系统管理。在宿舍公告页面输入标题进行查询、新增或删除宿舍公告列表，并根据需要对宿舍公告详情信息进行详情、修改或删除操作，还可以对关于我们、轮播图管理和系统简介进行详细操作。如图5-18所示：

![f08d53f8715b6c99de45b5fd5c1558d](/md/blog.013.jpeg)

图5-18系统管理界面
#########
### 5.2.2学生功能实现
学生登录进入系统可以对系统首页、个人中心、宿舍分配管理、水电费管理、进入宿舍管理、出入宿舍管理、维修信息管理、卫生信息管理、考勤信息管理等功能进行操作。学生主界面如图5-19所示：

![0da440faa20a2428adc330a71ffd68e](/md/blog.013.jpeg)

图5-19学生主界面














# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50297wxapp微信小程序的企业职工薪资查询系统设计与实现

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 绪论
## 1.1课题开发背景
网络和科技的进步以及人们生活条件的提高都让小程序技术越来越平民化，深入日常生活中。网络更是成为生活的必备条件，大到国家单位、科研项目，小到大街小巷都充斥着网络的身影。在日常办公中，计算机起到了文字编辑、打印、信息检索、统计等的作用。使用小程序可以使日常繁杂的信息进行科学的加工，使信息变得更加的有序、可利用。小程序技术已成为热门。

正是因为网络、科技、小程序技术使现代人的生活和工作变得便利、轻松，给实体行业带来了巨大的冲击。企业的日常工作也遇到了前所未有的挑战。现如今，对于工资信息的管理有很多的局限性，究其原因是因为工资管理的根本是信息的运动。在新时代的环境下，传统的管理方式不再满足用户的需求，难以管理现代的工作。传统的管理方式不仅跟不上时代的发展，还不能实现最基本的工作要求，例如对于工资的统计还停留在花费大量的时间进行手动审核，这种方式辐射范围非常有限，效果也非常不好。对于基本工作信息的管理也还是采用人工管理，人工管理出错率大，效率低。对于信息的传递都需要经过多人审核才可以完成，想要定期进行分析和总结更是难上加难。因为每种信息之间的关系错综复杂，在定期的统计和查询中就会出现重复出现的问题，对工作人员来说工作压力非常大。
## 1.2课题研究现状
现在企业中已有一些公司使用了基本的管理软件，这些软件都是依靠客户端，只可以特定人员使用，不能实现信息的共享。虽然可以帮助工作人员减少工作量，但从根本上还是无法满足用户的需求。这些软件都还是基于网络发展之初的要求，没有利用现代网络的技术，体现不了更为实用的功能。依靠客户端的系统开发时没有考虑园际化的问题，所以也满足不了国际化的要求。最近几年来，我国网络快速发展，传统的管理方式也越来越适应不了新时代的要求，在处理大量信息时表现不足，开发一个依托现代技术、网络技术的基于微信小程序的企业职工薪资查询系统迫在眉捷。这类管理系统将会改变企业人事管理的现状。
## 1.3课题开发目的与意义
想要改变员工工资管理的现状，就需要采用更为先进的管理方式。本基于微信小程序的企业职工薪资查询系统就是在新时代发展下开发的。本系统的开发非常有意义，体现了行业的创新。本系统是以信息管理为主导，而信息管理就是行业最大的问题，可以极大的提高工作效率。工资信息的信息化管理是目前员工管理的核心，解决了信息化的问题就可以使员工管理更进一步。开发本系统可以使工资信息更加的清晰、透明，便于管理人员操作。使用本系统可以使管理工作实现部分自动化，减少人工，提高正确率。

本系统是将网络技术和现代的管理理念相结合，根据工资信息的特点进行重新分配、整合形成动态的、分类明确的信息资源，实现了工资信息的自动化，减少人工管理过程，为管理人员的决策提供帮助。使用新型的管理系统已成为时代的标志，本系统可以提高员工工资管理的竞争力，提高信息统计效率，使工作人员的管理工作更加轻松。
## 1.4课题开发主要内容
本课题的主要内容包括管理员和员工两个部分，管理员负责员工相关信息的管理，包括工资信息、部门基本信息、员工的考勤信息和工作安排信息以及员工信息的管理；员工可以查询工资、考勤、工作安排、公告资讯的信息，可以修改个人信息和进行交流讨论。本基于微信小程序的企业职工薪资查询系统满足了员工和管理人员双方的要求，符合了信息化现代的要求。
## 1.5论文结构安排
本论文分为四个部分，摘要、外文翻译部分，目录部分，正文部分和致谢、参考文献部分。其中正文部分包括：

1. 绪论，从课题开发的背景、现状等进行阐述证明课题开发的意义和目的；
1. 系统分析，从系统开发可能遇到的所有问题进行提前分析，确定系统设计时可以进行解决；
1. 系统设计，进行系统功能的设计和数据库的设计；
1. 系统实现，进行系统界面和功能的详情实现阐述；
1. 系统测试，测试部分为正文的最后一部分，此部分是保证系统准确性、稳定性的重要方法。

























# 第2章 系统分析
## 2.1系统使用相关技术分析介绍
本基于微信小程序的企业职工薪资查询系统采用微信小程序软件进行调试运行，在代码编写中采用Java语言，数据库采用MySQL软件，在设计中采用了SSM框架。以下分为几节进行阐述。
### 2.1.1Idea环境介绍
Idea软件最大的不同就是集成了开发JavaEE所需要的所有插件，比如jdk，tomcat，可以直接使用，不需要单独进行配置，对于新手来说非常的友好，而且还可以直接进行编码，测试，然后发布。最大的特点是增加了智能助手，开发过程中可以进行代码提示，自动检查，更加的智能化。
### 2.1.2Java语言介绍
Java语言跟c++语言非常的相似，可以说是从c++上进行衍生出来的一个新型开发语言，他充分吸收了其他语言的优点，而避开了它们的缺点，使编程语言更加的简单，而且Java系统非常的小，摒弃掉了之前的运算符重载，然后造成的卡顿现象，然后添加了垃圾自动清理，增加了开发的简单和可靠性。当然了Java最大的特点是平台独立性，只要可以支持Java虚拟机环境，就可以直接运行所有程序，而且还是面向对象开发的技术，有很好的封装行，采用了动态编码技术，可以使程序更好的呈现。可以多线程进行运行，用户随时可以加入新的 实例然后不影响整体程序执行，使开发更有灵活性。
### ` `2.1.3MySQL数据库介绍
MySQL数据库最初是由瑞典MySQL AB公司进行开发出来的，后来被SUN公司进行了收购，然后进行了一系列的优化改进，最后被oracle公司收购。MySQL数据库是一种关系型数据库，而且采用的是开发式结构，支持大多的平台，而且功能很多，性能很高。MySQL数据库最大的特性就是把自己所编译好的数据进行单独存放，而不是跟传统数据库一样，全部放到一起，这样的话就保证了数据的安全性和灵活性，大大的提供了数据的访问速度，当用户需要调取数据时候可以直接通过sql语句进行查询。
### 2.1.4微信开发者工具
本工具是用来开发微信小程序的应用软件，通过本应用软件可以运行借助微信软件的项目。微信开发者工具为开源的软件可以在网上找到下载地址，安装包包括32位和64位，安装时非常简单，也不占用电脑内存。微信开发者工具是现在开发公众号、小程序最常用的工具。
### 2.1.5微信小程序分析
[微信](_blank)小程序，[小程序](https://baike.baidu.com/item/%E5%B0%8F%E7%A8%8B%E5%BA%8F)的一种，英文名Wechat Mini Program，是一种不需要下载安装即可使用的[应用](https://baike.baidu.com/item/%E5%BA%94%E7%94%A8)，它实现了应用“触手可及”的梦想，用户扫一扫或搜一下即可打开应用。全面开放申请后，主体类型为企业、政府、媒体、其他组织或个人的开发者，均可申请注册小程序。微信小程序、微信订阅号、微信服务号、[微信企业号](https://baike.baidu.com/item/%E5%BE%AE%E4%BF%A1%E4%BC%81%E4%B8%9A%E5%8F%B7/14691335)是并行的体系。
### 2.1.6 SSM框架介绍
SSM（Spring+SpringMVC+MyBatis）框架集由Spring、MyBatis两个开源框架整合而成（SpringMVC是Spring中的部分内容），常作为数据源较简单的web项目的框架。Spring就像是整个项目中装配bean的大工厂，在配置文件中可以指定使用特定的参数去调用实体类的构造方法来实例化对象。也可以称之为项目中的粘合剂。SpringMVC在项目中拦截用户请求，它的核心Servlet即DispatcherServlet承担中介或是前台这样的职责，将用户请求通过HandlerMapping去匹配Controller，Controller就是具体对应请求所执行的操作。SpringMVC相当于SSH框架中struts。mybatis是对jdbc的封装，它让数据库底层操作变的透明。mybatis的操作都是围绕一个sqlSessionFactory实例展开的。mybatis通过配置文件关联到各实体类的Mapper文件，Mapper文件中配置了每个类对数据库所需进行的sql语句映射。
## 2.2系统需求分析
在当今信息化社会发展的条件下人们越来越追求自动化，员工工资组成的多样化是现代企业常用的工资发放手段。这种情况下就造成多种信息的暴增，如果还是采用传统的管理方式势必会造成信息的拥堵，用户的烦躁，工作水平的降低。

本基于微信小程序的企业职工薪资查询系统采用了SSM框架进行设计，结构了网络的技术，可以单独运行，不再需要固定的客户端。可以实现工资信息的快速管理，保证了工作水平，提高用户的好评率。
### 2.2.1系统性能要求分析
系统的性能要求包括服务器和客户机两部分，主要是对系统存储和后续存储的要求，还有对系统运行的速度和系统的安全性进行考虑。对于系统的性能要求还需要操作的流畅性、理解性以及可靠、维护性。用户使用本系统时要求系统非常好理解，便于用户的操作。售后人员使用本系统时要求系统可读和便于测试。可靠性则指的是系统的准确和运行稳定，在尽可能的情况下利用所有的工具可以使上述要求得到最大的满足。
## 2.3系统可行性分析
可行性分析主要是分析本系统是否有开发的必要性，是否存在开发难度，是否能实现一定的商业价值，所以主要是从技术可行性，经济可行性，法律可行性等方面进行研究分析。
### 2.3.1技术可行性
开发本系统采用目前比较主流的Java开发语言，具有很好的扩展性和平台兼容性，而且功能非常强大，易操作。技术采用微信小程序技术，微信小程序可以实现手机操作。本系统最大的特点就是本系统采用SSM框架进行开发，SSM可以不受本机系统的限制，可以把数据存放到服务器，用户可以直接通过浏览器进行系统访问，对于用户来说非常的简单省事。所以从技术层面考虑是非常可行的。
### 2.3.2法律可行性
本系统没有抄袭市面上的任何网站、系统，不管是界面风格，还是后台代码，都是自己原创，所以不存在版权方面的纠纷，而且开发环境都是开源的，开源共享的，所以不管是硬件方面还是软件方面都不存在侵权行为，在法律上是完全可行的。
### 2.3.3操作可行性
本系统采用的全是可视化操作界面，不管是对于系统的管理者还是用户者，都可以在没有任何编程背景的基础下进行系统操作，而且系统界面还存在各种功能提示，用户都可以简单操作，所以在操作可行性上是可行的。
## 2.4系统流程分析
本系统的流程为先进行登录，在登录中需要输入账号和密码并选择相对应的身份才可以登录成功，管理员登录后的功能主要为管理，员工登录后的功能主要为查看。本系统中的主要功能有工资信息、考勤信息、工作安排信息、部门信息，公告信息等，在本系统中员工也可以修改个人资料和参与论坛讨论。用户登录流程图如下图2.1所示：

![](/md/blog.001.png)

图2.1用户登录流程图

员工发布帖子的流程图如下图2.2所示：

![](/md/blog.002.png)

图2.2员工发布帖子流程图

系统操作的整体流程如下图2.3所示：

![](/md/blog.003.png)图2.3系统操作流程图
## 2.5系统用例分析
本系统的主要角色为管理员和员工，管理员的用例包括员工管理、考勤管理、部门信息、工资信息、工作安排管理、交流论坛管理等。管理员的用例图如下图2.4所示：

![](/md/blog.004.png)

图2.4管理员用例图

员工的用例包括浏览工资信息、部门信息，工作安排信息、考勤信息以及修改个人资料、发布帖子。员工用例图如下图2.5所示：

![](/md/blog.005.png)

图2.5员工用例图



# 第3章 系统设计
## 3.1系统总体结构设计
一个好的设计不止是功能完整，操作流畅，还要符合用户的审美和界面的友好。在进入正式系统实施前，不可缺少的步骤为系统的总体结构设计，本系统为实用性的系统，所以开发的功能都是针对工资信息相关的。本系统的结构可以分为管理员界面和员工功能界面。本系统的总体结构图如下图3.1所示：![](/md/blog.006.png)             图3.1基于微信小程序的企业职工薪资查询系统的功能结构图
## 3.2系统开发步骤
系统的开发步骤可以分为系统开发、系统规划和系统实施。每一步都是在上上步的基础上进行的，不能跳级，在下一级进行时，不会对上一级的工作进行大的改变。所以就需要在每一级设计时充分保证正确才可以进行一下级的设计。这种开发步骤是最省时省力的方法，是经过国内外长久实践得出的最有效方法。
## 3.3数据库设计
### 3.3.1数据库概念结构设计
数据库的概念结构设计就是需要在系统分析的过程中分析开发本系统是要做什么，然后设计出大的框架，根据大的框架把系统进行转换成怎么做的物理模型。然后再进行设计。

`　　`在所有的系统设计中数据库的设计占有举足轻重的地位，选择合适的数据库软件进行设计非常重要。因为本系统的功能非常有针对性，没有进行扩展，所以本系统采用小型轻便的MySQL软件进行设计。数据库的安全保障着系统里数据的安全，本系统的主要数据为部门信息、工资信息、考勤信息以及员工信息等。本系统的ER关系图如下图3.2所示：

![](/md/blog.007.png)

图3.2实体关系ER图

（1）管理员的属性包括编号、用户名和密码，管理员的ER图如下图3.3所示：

![](/md/blog.008.png)

图3.3管理员信息ER图

（2）部门信息主要为管理员进行管理，员工进行浏览，部门信息的属性包括标题、内容、添加时间等，详细的部门信息ER图如下图3.4所示：

![](/md/blog.009.png)

图3.4部门信息ER图

(3)工资信息的属性包括编号、职位、月份等，工资信息的ER图如下图3.5所示：

![](/md/blog.010.png)

图3.5工资信息ER图

(4)考勤信息的属性包括编号、月份和扣除工资等，考勤信息ER图如下图3.6所示：
## ![](/md/blog.011.png)
图3.6考勤信息ER图

(5)员工信息属性包括用户名、年龄、手机号、职位、部门编号等，员工信息ER图如下图3.7所示：

![](/md/blog.012.png)

图3.7员工信息ER图
### 3.3.2数据库逻辑结构设计
数据库的逻辑结构设计也可以称为数据库表的设计，一般情况下采用第三范式进行设计，因为数据库的概念结构可以单独使用，不特定于某个数据库所以就需要对数据库的概念结构进行转换，从上节的数据ER图转换出本系统的数据库表，主要包括管理员信息表、员工信息表、工资信息表、部门信息表、考勤信息表等，具体的数据库表如下表3.1－3.10所示：

表3.1 bumen


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|bumen|varchar|200|||||是|||
表3.2 config


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|name|varchar|100|||||否|||
|3|value|varchar|100|||||是|||



表3.3 forum


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|title|varchar|200|||||是|||
|4|content|longtext||||||否|||
|5|parentid|bigint|20|||||是|||
|6|userid|bigint|20|||||否|||
|7|username|varchar|200|||||是|||
|8|isdone|varchar|200|||||是|||
表3.4 gongzixinxi


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|gongzibianhao|varchar|200|||||是|||
|4|gongzibiaoti|varchar|200|||||是|||
|5|fengmian|varchar|200|||||是|||
|6|fafangshijian|datetime||||||是|||
|7|jibengongzi|float||||||是|||
|8|shifagongzi|float||||||是|||
|9|gongzizhangdan|longtext||||||是|||
|10|yuangongzhanghao|varchar|200|||||是|||
|11|yuangongxingming|varchar|200|||||是|||
|12|bumen|varchar|200|||||是|||
表3.5 gongzuoanpai


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|anpaibianhao|varchar|200|||||是|||
|4|biaoti|varchar|200|||||是|||
|5|fengmian|varchar|200|||||是|||
|6|anpaishijian|datetime||||||是|||
|7|anpaixiangqing|longtext||||||是|||
|8|yuangongzhanghao|varchar|200|||||是|||
|9|yuangongxingming|varchar|200|||||是|||
表3.6 kaoqinxinxi


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|kaoqinbianhao|varchar|200|||||是|||
|4|kaoqinbiaoti|varchar|200|||||是|||
|5|fengmian|varchar|200|||||是|||
|6|kaoqinshijian|date||||||是|||
|7|kaoqinzhuangtai|varchar|200|||||是|||
|8|kaoqinxiangqing|longtext||||||是|||
|9|yuangongzhanghao|varchar|200|||||是|||
|10|yuangongxingming|varchar|200|||||是|||
表3.7 news


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|title|varchar|200|||||否|||
|4|introduction|longtext||||||是|||
|5|picture|varchar|200|||||否|||
|6|content|longtext||||||否|||
表3.8 token


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|userid|bigint|20|||||否|||
|3|username|varchar|100|||||否|||
|4|tablename|varchar|100|||||是|||
|5|role|varchar|100|||||是|||
|6|token|varchar|200|||||否|||
|7|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|8|expiratedtime|timestamp||||||否|CURRENT\_TIMESTAMP||
表3.9 users


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|username|varchar|100|||||否|||
|3|password|varchar|100|||||否|||
|4|role|varchar|100|||||是|管理员||
|5|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
表3.10 yuangong


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|yuangongzhanghao|varchar|200|||||否|||
|4|mima|varchar|200|||||否|||
|5|yuangongxingming|varchar|200|||||否|||
|6|xingbie|varchar|200|||||是|||
|7|yuangongdianhua|varchar|200|||||是|||
|8|touxiang|varchar|200|||||是|||
|9|bumen|varchar|200|||||是|||



# 第4章 系统实现
## 4.1登录功能模块的实现
登录功能包括员工登录和管理员登录，在登录界面设计中包括用户名和密码的检验。用户名和密码的检验过程由数据库自动完成，此过程需要1秒左右。首先由用户填写账号和密码，然后点击登录系统，数据库自行对用户名和密码进行对比，所填写数据正确方能进行登录，所填写数据错误则需要返回登录界面重新登录。用户登录界面的设计运行界面效果如下图4.1所示：

![](/md/blog.013.png)

图4.1用户系统登录界面效果
## 4.2 首页界面的实现
首页界面是最直接的展示，用户可以对系统进行最直接的了解。在本功能界面里可以看到背景图片、功能导航栏以及时间、当前用户等。首页界面的运行效果界面如下图4.2所示：

![](/md/blog.014.png)

图4.2首页界面的运行效果 
## 4.3工作安排管理信息模块实现 
工作安排信息是工资的重要组成部分，管理员可以添加工作安排信息，员工可以查询工作安排信息，工作安排管理信息功能的界面实现效果如下图4.3所示：

![](/md/blog.015.png)

图4.3管理员查询工作安排信息功能实现界面
## 4.4 员工信息管理功能的实现
员工信息管理功能分为管理员管理员工信息和员工自己管理自己的信息两种，管理员可以看到员工的各项基本信息，可以删除员工的基本信息。添加员工信息功能的界面实现效果如下图4.4所示：

![](/md/blog.016.png)

图4.4添加员工信息功能界面实现效果
## 4.5 工资信息管理功能的实现
系统里展示的工资信息都是由管理员在系统进行添加和维护的，管理员可以上新工资信息，也可以修改工资信息，当工资信息被淘汰时也可以直接进行删除，工资信息管理功能的界面实现效果如下图4.5所示：

![](/md/blog.017.png)

图4.5工资信息管理功能的运行效果界面

管理员添加工资信息的效果图如下图4.6所示：

![](/md/blog.018.png)

图4.6添加工资信息的界面效果
## 4.6部门管理功能的界面设计实现
部门信息功能为员工查询管理员添加管理，管理员可以根据部门的名称进行查询搜索。部门管理信息功能的界面实现效果如下图4.7所示：

![](/md/blog.019.png)

图4.7部门管理信息功能的界面实现效果
## 4.7考勤功能的界面设计
考勤信息也是由管理员负责管理，员工可以查看考勤信息，管理员添加考勤信息的实现界面如下图4.8所示：

![](/md/blog.020.png)

图4.8管理员添加考勤信息实现界面
## 4.8交流论坛功能的实现
管理员可以审核帖子信息，员工可以发布帖子信息。交流论坛功能的实现界面如下图4.9所示：

![](/md/blog.021.png)

图4.9交流论坛管理功能的实现
## 4.9我的功能实现界面
在我的界面里可以查询工资信息、工作安排信息、考勤信息、我发布的帖子和发布帖子。我的功能实现界面如下图4.10所示：

![](/md/blog.022.png)

图4.10我的功能实现界面
#











# 系











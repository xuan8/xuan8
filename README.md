# <p align="center">网络课程设计报告</p>

<p align="center">学院：信息科学技术学院</p>
<p align="center">班级：1752603</p>
<p align="center">学号：175260214</p>
<p align="center">姓名：彭璇</p>
<p align="center">时间：2020.6.18</p>

## 目录	
一、背景分析

二、 目标分析	

三、工程概况	

四、布局说明	

五、需求分析	

1、 需求调查	

2、用户需求分析	

3、网络需求分析	

六、网络性能需求分析	

1  网络结构需求分析	

2  拓扑结构需求分析	

3  网络节点需求分析	

七、网络链路及连接介质需求分析	

八、设备参数分析	

1.1、核心层路由器	
![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMm2teyKYi7vg*ksomfbNpTCGWyFYKGwAdLlJwpoa8a25u6E47zIRxnGVtzz2PwGn2g!!/mnull&bo=pAJWAAAAAAADB9I!&rf=photolist&t=5)

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMvGYsJo9Gy0HB*V2rKhvFUd7JUEwEAP1Tne*vwpYnQzx6frh7gdd62QjClKRaWn30w!!/mnull&bo=fgI4AwAAAAADB2U!&rf=photolist&t=5)

1.2、汇聚层交换机	

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMrEag3FG4leqwM0QkdG6YshRbfU75MQBet9rIXrws6P12xxd1RMF7vPI6F1j9j8k8A!!/mnull&bo=5QLmAQAAAAADByI!&rf=photolist&t=5)

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMmR8TxosGU.THNRnBFbVZbTImq7iwCtJRJT03Ws8Mwxz3A2Swp3PordGacEznMU7zA!!/mnull&bo=cgLyAgAAAAADB6I!&rf=photolist&t=5)

1.3、接入层交换机	
![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMrR9iuMqU0h3e743KyO1g2sgtDzyykdAaOz4.8Vd8nfd89dVjD2y63wqiTODPC9OCw!!/mnull&bo=2wLSAQAAAAADByg!&rf=photolist&t=5)

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMnpEvpfAJTnvxcdByfwAw8j2pdZX2xOgjH*fYjOuEItilKqQ.vNbNXceolkH86DMoA!!/mnull&bo=cwLFAgAAAAADB5Q!&rf=photolist&t=5)

2.1核心层路由器	

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMiLhLxzewv*b4EgcrRXjJmViqYMSb41gobLEj4FPJJ.5wPvkWUnz1r7OlocEkh4LvA!!/mnull&bo=8AIAAgAAAAADB9I!&rf=photolist&t=5)

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMktF5k5iz2rQmsAy9kPMkiYciuk1ZB5cS65A3eQ9R*E5NwYJbtzqove8XxckJmhadg!!/mnull&bo=XgLLAgAAAAADB7c!&rf=photolist&t=5)

2.2汇聚层交换机	

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMpJ9lkYNG6CX*c.jNnnnXA.IImIxr2eoab9c.UVSSlaQjWbiEIyaVRD0v1L6heUmMw!!/mnull&bo=6AK9AQAAAAADB3Q!&rf=photolist&t=5)

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMtewQLts*iatQ3t8Y.AQtyINU.3rgFG7vuPJdHPr5lU.tJ9c4..TLp.j87eZO14ZGg!!/mnull&bo=cwIUAwAAAAADB0Q!&rf=photolist&t=5)


2.3接入层交换机	

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMo6jTNJMeZ.k4Cbbw0WByTWP2nxaftvZEhzd2eVXc*ahCLruzGkpn4eeOpaMl5.7Ow!!/mnull&bo=8wHPAgAAAAADBx0!&rf=photolist&t=5)

3、静电地板	

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMibiC8lRZNk85JSbWIW7DbLfnw1Zb8LyvXEdPHdxTXuoUf8WuA*phm7qYZg64eY0PA!!/mnull&bo=DgNZAQAAAAADB3c!&rf=photolist&t=5)

4、UPS（山特C3KS）	

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMgRH00KF8iJe3cLqFS5h6KVj6e0K9.X2jal94I5*fBXs7Nb3HbEoCb5HPxqM1CFp5Q!!/mnull&bo=fQNvAgAAAAADBzE!&rf=photolist&t=5)

5、挂墙机柜	

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMgRH00KF8iJe3cLqFS5h6KVj6e0K9.X2jal94I5*fBXs7Nb3HbEoCb5HPxqM1CFp5Q!!/mnull&bo=fQNvAgAAAAADBzE!&rf=photolist&t=5)

6、设备间机柜	

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMo5FIJE1U6nwnzUC1NXL6rLGoYIISTCdR**IZW8QJG5yX8fY.cg83Et4N9TUrpNMyg!!/mnull&bo=.QLvAQAAAAADBzc!&rf=photolist&t=5)

![](http://m.qpic.cn/psc?/V136EAip4YJo8G/yjRt0f3d7*S2CnJxsjXCMvgRbuIhlfQbLGgY6fRjbNpqPgfxVh0X*kYubTzcXE80kceKCFm3ctsCrToVnUd5hw!!/mnull&bo=3wJrAgAAAAADB5Y!&rf=photolist&t=5)

7、光电转换器	

8、桥架（防火桥架 托盘式桥架）（1米15元）*66*2*5=9900元	

9、信息插座（德力西开关插座面板 网线插座电脑插座网络信息插座86型雅白）

11、网线	

12、配线架	

13、尾纤	

九、项目金额预算	

预算一、（华为设备）	

预算二、（H3C设备）	

十、参考资料	

一、背景分析

随着Internet的迅速发展，全世界正在利用计算机网络进行各种通讯，办公室的应用也已经开始普及，使用的技术也日趋成熟，它们不但能够传输传统的文本、图像等数字信息，也包括视频、音频在内的多媒体综合信息。传统的办公模式正在逐步向无纸化方向发展，把一些传统的业务移植到网络上来做已是人心所向、大势所趋。学生宿舍楼的综合布线系统也因此变得尤为重要。要满足学生们在宿舍内连接互联网的需求，创造良好的网络环境。

二、 目标分析 
 
通过vlan来覆盖整个学生公寓楼，从而使每个宿舍更好的链接网络，建设一个高速、安全、可靠、可扩充的网络系统，实现学生宿舍园区学生对Internet的访问以及宿舍间信息的高度共享、传递。

三、工程概况 

8幢公寓有五层楼240个宿舍每层48个宿舍，其中，一楼有宿管一间，设备间一间。该公寓楼共有239个学生宿舍，每间宿舍8个人。根据学生需求，每间宿舍2个信息插座的要求配置综合配线系统共需要478个信息点。

|学生浏览网页名称|对流量要求|访问频率|
|:---|:---:|---:|
|1|37|74|
|2|38|76|
|3|38|76|
|4|38|76|
|5|38|76|
|合计|113|226|

该公寓长（每件宿舍长3米）*（共计22个）=66米  

宽（3+3+2）=8米  

高（每间宿舍高3米）*（共计5层）=15米  

四、布局说明  

该公寓楼有5层楼，每层48个宿舍，其中一楼有宿管间一间，设备间一间。

每间长宽3米 长3米 过道宽 2米 共有22间

公寓长（22*3=66）宽（3+2+3=8米）

高（每层高（3米）共5层 （3*5=15米）

网线每层外（（66*38）=2508）+内（5+4=9）= 2517米

网线总计 2517*5=12585（大约13000）米

五、需求分析 

1、 需求调查 

学校宿舍楼是人群密集区域，用户数较多，数据流量大，业务需求量较大，vlan应同时兼顾覆盖和容量， 支持现在以及未来数据、控制等信息高速传输的要求。通过宿舍楼的上网情况调查，做了如下总结： 
|学生浏览网页名称|对流量要求|访问频率|
|:---|:---:|---:|
|学院主页|一般|高|
|迅雷下载|高|高|
|HTTP页面浏览|高|高|
|网络web页面发布|低|高|
|视频播放，如土豆网|高|低|
|教育网|普通|较高|
|上网聊天|普通|较低|
|打游戏，如英雄联盟|低|高|

2、用户需求分析 

经调查，宿舍楼网络的需求可概括如下： 

（1）功能需求 

数据通信：实现计算机与终端、计算机与计算机之间的数据传输，是计算机网络最基本的功能，也是实现其他功能的基础。如电子邮件、传真、远程数据交换等。 
资源共享：实现计算机网络的主要目的是资源共享，一般情况下，网络中可共享的资源有软件资源、硬件资源和数据资源，其中数据资源最为重要。 
远程传输：分布在较远的用户可以互相传输数据信息，互相交流、协同工作。 

（2）性能需求

实现学生宿舍园区学生对Internet的高速、安全访问以及宿舍间信息的高度共享、传递。通过数据链路冗余备份技术实现网络的稳定可靠性； 
要达到低负载、高带宽、最简单、最有效要求； 网络提供足够的带宽； 
确保物理层、链路层、网络层稳定、可靠； 
不以牺牲网络性能为代价，实现病毒和攻击的防护、用户接入控制、路由协议安全。

（3）管理需求 

网络的管理需求主要是针对宿舍网络的管理者进行的，主要包括对于网络的管理、对于信息安全的管理。这就需要有管理软件的支持，还应注意布线时间的可靠性以及质量是不是良好。同时，网络应具有灵活性，这样便于更换或者添加新的网络设备。 网络管理软件具备对接入层交换设备进行远程造作的能力，提供网络管理的简易性和集中性。 网络管理的信息服务系统迅速发展，由于采用www技术，打破了原有信息服务的范围。

3、网络需求分析  

3.1网络应用的主要类型：

1）www服务：负责远程服务管理及WEB站点的管理。 

2）E-Mail服务：负责各个用户的邮件管理。

3）FTP服务：提供各种上传、下载资源等功能。

3.2网络安全性需求分析 

1） IP和MAC地址的可变性而导致的冒用合法用户上网的问题。

2） 操作系统和应用软件的漏洞，造成网络安全的问题。

3） 用户安全意识不强及计算机水平有限而导致的安全性问题。

六、网络性能需求分析

1  网络结构需求分析 

根据该项目的实际情况，网络采用接入层，汇聚层，核心层。根据对该校项目功能需求分析得出采用3层结构才能满足用户的需求和其他人员的使用需求，采用总线型结构加网状结构的网络拓扑。由于采用大型交换机技术，为了避免广播风暴带来不必要的带宽影响，因此要采用VLAN进行工作组的划分，防止网络安全发生，隔离有关危害信息对学生的影响，应采用防火墙过滤有关外网信息。 为广大学生和老师提供一个安全的交流平台。   
中心机房到汇聚层节点采用1000兆光纤（单模）连接，汇聚层到接入层采用百兆的五类线连接。通常考虑，数据信息点的接入用交换10/100/1000Mbps自适应以太网端口接入，以便能较经济的提供较高的带宽。

2  拓扑结构需求分析  

依据现场的勘察分析，该项目应采用总线和星型相结合的网路拓扑。

3  网络节点需求分析  

由于网络接入层，汇聚层，核心层节点位置的地理分布情况是，网络接入层节点设置在用户建筑物内，因为接入层终端设备（PC）较多，所以将汇聚层节点设置在接入层一起。因为接入用户较多，且是内部交换网络，因此网络节点设备交换机要采用高性能，具备大型交换能力的设备。同时考虑到内网用户数据的安全性要求不高并加大网络建设和管理成本，但是为了改善主干链路数据流量的压力，增强网络性能，把外网的信息先通过防火墙过滤，再接入路由器对信息分流，传递到每层。

七、网络链路及连接介质需求分析  

该项目的网络连接设备因根据实际的情况而定，由于该项目即在一栋建筑物内，路由器之间的连线用双绞线，楼层的垂直布线用双绞线，楼层之间的连线用双绞线走地线，可以得出： 网络主干链路采用光纤传输介质。 网络主干链路采用地下走线的方式。
实际连接距离为1千米满足网络需求。 

八、设备参数分析

网络主干链路最大设备参数分析  校园网中采用的网络设备有，路由器、交换机、防火墙、配线架、双绞线，室外光缆，室内光缆，尾纤，信息插座，信息模块，水晶接头，机柜，配线架，配线箱，桥架等。

1.1、核心层路由器(华为AR2220)

1.2、汇聚层交换机（华为S5700-28C-SI）

1.3、接入层交换机（华为S5700S-52P-LI）

2.1核心层路由器（H3C MSR 30-20）

2.2汇聚层交换机（h3c S5500-24P-SI）

2.3接入层交换机（H3C S5120-52P-LI）
 
3、静电地板

4、UPS（山特C3KS）

总计2409

5、挂墙机柜

总计：429元

6、设备间机柜

总计：500元

7、光电转换器

总计：700元

8、桥架（防火桥架 托盘式桥架）（1米15元）*66*2*5=9900元

总计：9900元

9、信息插座（德力西开关插座面板 网线插座电脑插座网络信息插座86型雅白）

（24.81*226）=5 607.06元

总计：5610元

10、Pvc管（联塑线槽PVC电线槽4分6分8分24*14 39*19 59*22电线槽2.8米/条 8分59*22 长2.8米）选择8分59*22 长2.8米 每米20元 

总计：20*9*226=40680米

11、网线（由于使用1000mbps以太网所以使用六类线）

（山泽（SAMZHE）SZ-6305 工程级六类高速网线 305米）每米（799/305）元*13000=34 357总计：需大约（34357元）

12、配线架(思诺亿舟（SNIT）配线架24口 电话配线架 超五类网络配线架 理线架 六类网络配线架 六类24口配线架)1个369元

总计：369元

13、尾纤（胜为（shengwei）FSC-106 电信级光纤跳线 ST-SC单模单芯 收发器尾纤 3米）

总计：17元

九、项目金额预算

预算一、（华为设备）

|名称|金额|数量|
|:---|:---:|---:|
|核心路由器|8268|1|
|汇聚交换机|5699|1|
|接入交换机|4549|12|
|静电地板|200|9|
|UPS|2409|1|
|挂墙机柜|429|5|
|设备间机柜|500|1|
|光电转换器|700|1|
|桥架|15|660|
|信息插座|24.81|226|
|PVC管|20|2034|
|网线|799|43|
|配线架|369|1|
|尾纤|17|1|

预算二、（H3C设备）

|名称|型号|金额预算|数量|合金|
|:---|:---:|:---:|:---:|---:|
|核心路由器|3CMSR|30-20|7920|1|7920|
|汇聚交换机|华为 h3c S5500-24P-SI|7500|1|7500|
|接入交换机|H3C S5120-52P-LI|4939|12|59268|
|静电地板|贝塔斯全钢全静电地板|200|9|1800|
|UPS|山特K3KS|2409|1|2409|
|挂墙机柜|图腾挂机柜WM.6404|429|5|2145|
|设备间机柜|大唐保镖A3.6612|500|1|500|
|光电转换器|友讯（D-Link）DEG-872|700|1|700|
|桥架|托盘式桥架|15|660|9900|
|信息插座|德力西|24.81|226|5607.6|
|PVC管|联塑|20|2034|40680|
|网线|山泽|799|43|34357|
|配线架|斯诺亿舟|369|1|369|
|尾纤|胜为|17|1|7|

十、参考资料
本文档中的部分设备的单价来源于中关村在线（www.zol.com.cn）、淘宝（www.taobao.com）和天猫（https://www.tmall.com）等网站。

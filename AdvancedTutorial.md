进阶教程
========

本章节主要介绍游戏的主要内容 Deploy, Link, Field 以及摧毁敌对 Portal 等相关内容。这部分是玩家在 L3 之后进行的主要游戏内容。  

Deploy Resonator
--------------

无论是看到一个白色的无主 Portal，或者是摧毁了敌对阵营对 Portal 的占领，通常都会选择 Deploy Resonator 以 Capture Portal。而之后的 Link 也要求两侧的 Portal 必须 Deploy 所有的 Resonator。  

Deploy 操作要求 Portal 必须在玩家脚下的黄圈范围内，选择 Portal，点击 Deploy Status后，在新的界面里点击空的槽后选择下方对应的 Resonator 即可。每个玩家在每个 Portal 部署的不同等级的 Resonator 数量上有限制，具体参见 [Ingress 道具介绍][ingress_items_intro]。  

<img src="http://ghostflying-static.qiniudn.com/ingress_attack_SelectDeployResMarked.png" width="192" height="320" />
<img src="http://ghostflying-static.qiniudn.com/ingress_attack_deployRes.png" width="192" height="320" />  




Deploy Mod
----------

玩家可以给同阵营的 Portal Deploy Mod，操作方法类似于 Resonator，区别主要在于选择完 Portal 后点击的是 Mod Status，关于各种 Mod 的功能和使用，参见 [Ingress 道具介绍][ingress_items_intro]。  

对每一个 Portal，每个玩家最多只能同时 Deploy 2个 Mod。  

<img src="http://ghostflying-static.qiniudn.com/ingress_attack_deployedMod.png" width="192" height="320" /> 

Link
----

Link Portal 是建立 Field 的前提，建立 Link 有一定的限制条件，具体如下  

+ 建立 Link 的 Portal 必须均归属己方阵营  
+ 无论起始和结束，Portal 必须插满 Resonator（即每个 Portal 均拥有8个 Resonator）  
+ 起始 Portal 必须在 Link 建立者的黄圈范围内，目标 Portal 必须在起始 Portal 的 Link 范围内（在 Deploy Status 页面可以看到）  
+ 建立者需要持有目标 Portal 的 key，且每次 Link 都会消耗一把，关于 key 的积累，参见 [Ingress 道具介绍][ingress_items_intro]  
+ 试图建立的 Link 不能穿越任何已经存在的 Link 和 Field  
+ 不能从 Field 内部的 Portal 向其它Portal Link  
+ 任何 Portal 最多只能 Link 到 8个其它 Portal，但被 Link 不受限制  

确认满足以上条件后，点开起始 Portal 的详情页面，在左下方选择 Link 按钮，稍作等待后便会在地图上显示附近可以 Link 的Portal，也可以在右侧点击 key 标志展开后选择自己拥有 key 且满足条件的 Portal。如果 Link 失败，下方会显示失败原因，可据此排除问题。  

<img src="http://ghostflying-static.qiniudn.com/ingress_attack_PressLinkMarked.png" width="288" height="384" />
<img src="http://ghostflying-static.qiniudn.com/ingress_attack_LinkSelectMarked.png" width="288" height="384" /> 
<img src="http://ghostflying-static.qiniudn.com/ingress_attack_LinkSelect2Marked.png" width="288" height="384"/> 
<img src="http://ghostflying-static.qiniudn.com/ingress_attack_LinkSelect3Marked.png" width="288" height="384"/> 
<img src="http://ghostflying-static.qiniudn.com/ingress_attack_EstablishingLinkMarked.png" width="288" height="384"/> 


建立 Field
----------

当3个 Portal 两两建立 Link 后，便会自动建立 Field。Field 是阵营争夺的主要目标，根据 Field 大小的不同，会有不同的 MU，但获得的 AP 不变。  

<img src="http://ghostflying-static.qiniudn.com/ingress_attack_FieldCreatedMarked.png" width="288" height="384" /> 


Recharge
--------

当 Portal 被 Capture 后，根据当前剧情的变化，所有 Resonator 的 XM 都会定时发生 Decay （目前是在每天 Portal 被 Capture 的时间 Decay 20%）。因此，为了保证 Portal 长期占领，需要对 Portal 进行 Recharge。除了走到 Portal 附近进行 Recharge 外，常用的方式是远程充电。该方式要求玩家持有被 Recharge 的 Portal 的 key，且根据距离有一定的充电效率和极限距离限制。  

近距离充电和 Deploy 操作类似，当 Portal 处于控制范围内时，点击详情页面的 Recharge 即可，而远程充电需要从物品栏里找到对应 Portal 的 key，从此进入 Portal 的详情页以点击 Recharge，也可通过 COMM 里的链接进入。Recharge 时，既可以选择 Recharge All 对所有 Resonator 进行统一充电，也可以单独选择每一个 Resonator 进行 Recharge。  

<img src="http://ghostflying-static.qiniudn.com/ingress_rechargeSelect.png" width="288" height="384"/>
<img src="http://ghostflying-static.qiniudn.com/ingress_rechargeAll.png" width="288" height="384"/>
<img src="http://ghostflying-static.qiniudn.com/ingress_rechargeAlling.png" width="288" height="384"/>
<img src="http://ghostflying-static.qiniudn.com/ingress_rechargeSingle.png" width="288" height="384"/>


摧毁敌对阵营 Portal
-------------------

除了部分玩家较少的区域，绝大部分区域里，Poratl 通常都处于被占领的状态，对于敌对阵营的 Portal，摧毁并占领是常见的选择。此节主要为相关内容教学。  

### 战前检查

考虑到玩家能使用的道具等级限制，建议在选择攻击目标时检查 Portal 的 resonator 等级，通常不建议攻击拥有超过自己等级2级以上的 resonator 的 Portal。  

攻击 Portal 需要使用 XMP，建议检查物品以保证有足够数量和等级的 XMP 库存以完成攻击。此外，由于 Portal 反击和 XMP 消耗的问题，攻击 Portal 会消耗大量 XM，建议携带足够的 Power Cube。  

### 寻找 Resonator 的位置

攻击 Portal 实际攻击的是 Portal 上 Deploy 的 Resonator，由于低等级的 XMP 攻击范围较近，且随着距离增加伤害衰减较为明显，因此寻找到 Resonator 的位置就显得很有必要。通常可以从地图上看到 Resonator 到 Portal 的连线，但如果附近 Portal 比较密集，较难区分不同 Portal 的 Resonator 时，可点击 Portal 详情页面的 Deploy Status，在其中选择 Resonator 查看具体的位置。  

<img src="http://ghostflying-static.qiniudn.com/ingress_attack_FindResLocation.png" width="192" height="320" /> 

### 攻击策略选择

当等级较低时，建议选择尽量靠近 Resonator 的位置开始攻击，而等级较高时（L6 或 L7 以上），可选择 Resonator 的中心，通常即 Portal 的位置开始攻击。  

### 开始攻击

#### XMP

使用 XMP 攻击是绝大部分场合下的选择，在游戏主界面任一处长按，上滑选择 Fire XMP，出现选择界面后选择对应等级的 XMP，点按 Fire 即可。  

<img src="http://ghostflying-static.qiniudn.com/ingress_attack_long_press.png" width="192" height="320" />
<img src="http://ghostflying-static.qiniudn.com/ingress_attack_selectXMP.png" width="192" height="320" />

#### Ultra Strike

US 的使用和 XMP 类似，区别主要在 US 的攻击范围远小于 XMP，需要非常接近攻击目标才能有明显的效果。  


#### ADA/JARVIS

毒的使用和前两者有一定不同，需要从物品栏里选择使用，然后再选择目标 Portal，毒的使用会消耗目标 Portal 等级 × 1000 的 XM，且**不会获得任何 AP**。通常仅建议在必要时使用，非常规选择。  

<img src="http://ghostflying-static.qiniudn.com/ingress_attack_JARVISPrepared.png" width="192" height="320" />
<img src="http://ghostflying-static.qiniudn.com/ingress_attack_JARVISSelect.png" width="192" height="320" />
<img src="http://ghostflying-static.qiniudn.com/ingress_attack_JARVISprogress.png" width="192" height="320" />
<img src="http://ghostflying-static.qiniudn.com/ingress_attack_JARVISPregress2.png" width="192" height="320" />
<img src="http://ghostflying-static.qiniudn.com/ingress_attack_selectXMP.png" width="192" height="320" />

### 集气

XMP 和 US 的一种使用方法，长按 Fire 键，会出现从大到小不断变化的黄圈，在内侧释放时可以获得伤害加成，越靠近内侧越高，最高为 20%。  

<img src="http://ghostflying-static.qiniudn.com/ingress_attack_hold_marked.png" width="192" height="320" />

### MOD

Mod 会显著影响到攻击 Portal 的难度，面对有较多防御性 Mod 的 Portal 时，建议低级玩家量力而行。各 Mod 的具体作用见 [Ingress 道具介绍][ingress_items_intro]。 Mod 在被攻击时有一定概率被摧毁，除 Shield 外均表现飞出 Portal 的动画，Shield 被摧毁时则表现为护盾闪烁红色。  

<img src="http://ghostflying-static.qiniudn.com/ingress_attack_Mod_Marked.png" width="192" height="320" />
<img src="http://ghostflying-static.qiniudn.com/ingress_attack_ShieldDestroyedMarked.png" width="192" height="320" />

### 反击

Portal 被攻击时会对攻击者进行反击，在 Portal 较为密集的区域或 Portal 上存在攻击性道具时，反击会对玩家造成较大伤害，此时应注意自己的 XM 槽，适时使用 Power Cube 补充 XM。  

当 XM 被反击清空时，会出现雪花屏现象，此时玩家不能进行攻击, Hack 等操作，直到补充 XM 为止。  

<img src="http://ghostflying-static.qiniudn.com/ingress_attack_emptyXM.png" width="192" height="320" />

如果反击伤害过高，可采用使用较低等级 Power Cube 或 Recycle 少量低等级道具，令 XM 仅满足 XMP 消耗的方法避免消耗太多 Power Cube。  

### 攻击结果说明

<img src="http://ghostflying-static.qiniudn.com/ingress_attack_AttackResult.png" width="192" height="320" />

[ingress_items_intro]: https://github.com/GhostFlying/ingress-tutorials/blob/master/ItemsIntro.md


Ingress XM Anomaly Guide（未完成）
========
本部分来自http://www.zhihu.com/people/lanyusea
什么是 Ingress XM Anomaly ？
--------------
<img src="https://lh4.googleusercontent.com/-bMwhgemIzQ0/VNy7w41s_WI/AAAAAAAAIII/gsui5CTu0ZM/s0-d-ip/15%2B-%2B1" width="510" height="600" />

准备阶段
--------------
活动开始前，Ingress 会公布城市内比赛的三个区域范围以及所属的cell，同时公开活动规则和计分规则。玩家会提前组织报名，分配好任务。
<img src="http://pic1.zhimg.com/2fc28b4b6bba7a9bb2a7f210424aa5d4_b.jpg" />

进行时
--------------
每轮活动前5min（或15min），NIA会宣布区域内的volatile portal，capture他们拿到的分值更高（一般是10倍于普通portal）。其余的portal就是普通的 non-volatile portal 了。在Darsana之前，volatile公布是通过Google Doc，官方会在比赛开始前5min将Google Doc的地址通过Google+ 公开分享，大家要主动去查看然后进行人员的适当调动。在Darsana时候volatile已经可以直接在 Ingress 游戏界面和 intel 地图内显示了，方便很多。如图：
<img src="http://pic3.zhimg.com/7dfd70d9c34e0b39119588d6a0dcba12_b.jpg" />
<img src="http://pic3.zhimg.com/12d5cb9ba966ef361992ef9e297ab3f6_b.jpg" />

技巧
--------------
#从参与者的角度

带足你的装备，如果你是没有既定角色（炸弹手，depolyer）的白板，那建议xmp/res/cube 尽量 1000/800/200 配置。portal key尽量减少装备。mod理论上很重要，但实际上除非出现压倒性优势，不然根本没有机会depoly（蓝绿白切的太快了），或者下去就成灰了。
cube不需要太多，因为绝大部分的xm消耗是使用道具所致，在被portal反击而损失xm无需考虑。

xmp要8级，但res低级要好过高级，因为算分的规则是占住就有分，不看portal等级。
并且在如下图的环境中，不论多少级的res基本上都顶不住1s，但高等级却需要更多的xm你会更加频繁切回菜单使用power cube。
<img src="http://pic1.zhimg.com/e3d1bc55bf86c6a099735af27a617f34_b.jpg" />
同时要注意必须要主动点按portal以更新数据，这样才可以保证可以继续进行操作。

#从调度者的角度

先手优势非常重要，基本上这轮开始前portal是哪个阵营的哪个阵营就会胜利。而且在 Jarvis／ADA 加上了 1h 的 cd 之后先手优势更加明显，Cassandra13 的时候绿军在活动开始的整点 Jarvis 掉蓝portal 然后无差别 fire xmp。规则修改后的 Recursion，绿军的 Jarvis 的行动全部已失败告终，因为上一个小时已经 Jarvis/ADA 过了。在 Helios 的时候14点是第一轮，12:55 蓝军将所有蓝portal Jarvis掉，等到13:55再 ADA 返。

参考信息
-------------
报名表：https://docs.google.com/forms/d/16KaFtTOvmU2GhZl4ehUm0l82SQ5WOvSN3O9g3ohbBwY/viewform?c=0&w=1

#职位名称

 就仅仅是参加过而已, 没有具体职位(General anomaly experience)
 计划人(Planning)
 认证人员, 检查某位特勤是否可信(Vetting)
 地图制作员(Map Making)
 调度员(Dispatch)
 Intel 情报人(Intel)
 Cluster 作战小队(Cluster Teams)
 Volatile 作战小队(Volatile Teams)
 自行车作战小队(Bike Team)
 Cluster 连 Field 小队(Cluster Fielding, Linking)
 巨型 Field 计划队(BAF Fielding)
 特别行动组(Special Ops)
 风中一匹狼(Lone Wolf)


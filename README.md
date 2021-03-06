#### 用途说明

![](https://gitee.com/ClimbSnailQ/Project_Image/raw/master/OtherProject/SwipingCard_mini.jpg)

![实物图](./Figure/SwipingCard_mini.jpg)

此为校园一卡通刷卡器，用于内置FR射频电路的校园SIM卡。

上述的此类卡称之为_RF-USIM_。

本刷卡器只涉及硬件，无需软件程序即可工作，故本工程为PCB工程。(使用_Altium Designer_绘制)

#### 制作背景

	2015年本人大一，初入校园就发现了食堂付款以及图书馆进出都需要使用与学校合作的联通卡进行支付。
	然而，问题来了。那时候的部分手机只是单卡单待`如当时的iphone`，而常用的手机卡非校园一卡通,以及各种原因不方便使用此类USIM卡。
	陆续发现一些朋友购买简易的手机`简称"小手机"`，专门用于食堂以及图书馆的进出使用，十分不便。
	
	为此，制作了本款迷你刷卡器来代替`小手机`的使用。


#### 性能指标
> 测试过联通RF-USIM卡3秒启动（实测）。
> 这款刷卡器体积小巧以及充满电后连续使用达50天以上。

#### 预览图

![](https://gitee.com/ClimbSnailQ/Project_Image/raw/master/OtherProject/SwipingCard_PCB_3D.png)

![PCB_3D](./Figure/SwipingCard_PCB_3D.png)

![](https://gitee.com/ClimbSnailQ/Project_Image/raw/master/OtherProject/SwipingCard_mini2.jpg)

![实物图](./Figure/SwipingCard_mini2.jpg)

#### 设计方案
1. 使用已淘汰价格低廉的M590E模块。
2. 使用TP4056锂电池管理芯片进行充放电。
3. Micro USB公头、Micro USB母座、Type-C三个充电接口，其中Micro USB公头、Type-C三个接口支持OTG充电。

#### 铭牌信息

			  校园一卡通刷卡器
	通用版：
		开机：插进手机充电口或充电宝，状态灯
				   闪烁3s后进入正常工作状态。
		关机：直接从供电设备上拔下即可。
	充电版额外功能：
		使用内置电池供电:将开关拨到ON。为
		省电，使用完毕后开关拨到OFF(关机)。
		使用手机或充电宝供电的同时也为设备
		充电。正常充电时，红灯常亮。充满时绿
		灯常亮。


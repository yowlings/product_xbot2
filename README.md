# Xbot2机器人材料
## 关于重德智能科技
### 公司简介
浙江重德智能科技有限公司是一家专注于机器人软件平台研发和设计的机器人科技公司。公司依托于中科院软件所共同成立的联合实验室及多位行业专家，在协同网络、操作系统、人机交互、人工智能、云计算与大数据等多个学科方向上积累的多项核心和前瞻技术。
### 核心产品
目前公司的核心产品包括：面向高校、科研院所的**Xbot系列科研应用平台**、**机器人导航解决方案**、**共享机器人**以及面向学校、机器人从业者的基于ROS的机器人教学平台<strong>睿思学院（ROSAcademy）</strong>。
### 解决方案
公司能够根据客户的场景需求，基于平台设计和客户化进行定制研发，提供解决方案并设计交付满足客户需求的智能机器人本体、云端以及配套设备。例如，根据办公室、居家、展览馆、会议室、大型商场的应用特点及需求，公司基于Xbot移动机器人平台提出了面向室内移动机器人的SLAM和导航解决方案，已在多个室内场景成熟应用。
### 公司愿景
重德智能致力于将更好的机器人教学内容和更优质、稳定的机器人学习、实验、应用平台提供给更多的机器人学习与研究人员，让机器人学习和应用变得更简单、更高效、更实用。

## Xbot2机器人概述
xbot系列机器人是国科睿思科技出品的一款包含机器人硬件平台、软件平台和操作系统支持三方面在内的机器人平台解决方案。该机器人经历了xbot1与xbot2两代机器人的开发与改进，目前已完全支持室内环境中的所有的机器人相关传感器接入和机器人应用。该平台自带运动控制系统、二维激光雷达点云测距、超声测距、红外测距、升降平台控制器、高清摄像头（RGB、深度可选）以及机器人视觉伺服云台。另外，由于机器人搭载了高性能的处理器和N系列高性能显卡，支持cuda加速以及运行绝大部分运算需求较高的应用，并且对于ROS的完全支持使得机器人可以接入任何支持ROS框架的硬件传感器或者其他开源软件。xbot2机器人平台将是您室移动内机器人应用的不二选择。
###	稳定、可靠的运动控制
Xbot机器人运动电机采用先进的PID鲁棒性控制算法，提供十分稳定、可靠的机器人运动控制，配以高减速比的高精度电机，机器人运动速度可控制到0.01m/s的精度，最小速度达0.01m/s，最大速度超2m/s。具有加速时间短，制动效果明显等的多方面优秀特性。
###	完备的驱动软件支持
我们为Xbot机器人提供完备的驱动软件，采用国际通用的驱动软件框架和通信协议，能够提供50Hz频率以上的数据心跳包传输和快速精准地数据编码解码功能，使机器人的运动状态控制精度到达20ms以上，从而机器人能够更加迅速地相应用户算法的控制。
###	自主建图定位与导航（可选）
Xbot机器人具备室内环境下的自主建图定位与导航功能，该功能让机器人在室内实现完全自主的同步建图和定位，从而机器人能够根据用户需求，在任意位置之间自由穿梭行走，同时在导航过程中精准避障，全自主规划行走路径。
###	超长续航与自主充电
Xbot机器人配备高达60Ah的超大容量电池，续航时间最高可达15小时。同时支持用户预约返回充电和自主返回充电模式，机器人智能管理自身的能量，在能量不足时自动返回充电桩充电。
###	高性能计算能力
Xbot机器人配备高性能的CPU计算能力和超强的GPU计算能力，支持cuda加速，运行超大场景的openpose算法速度达3fps以上，为您的应用计算提供强大的支持。
###	ROS系统全支持
Xbot机器人软件框架专为ROS系统定制，可运行ROS系统下的所有软件和算法，运动控制和规划算法完全支持ROS系统协议，为更多的学习和开发者提供通用的算法验证和应用落地的平台。

## Xbot2机器人参数
### 版本配置
| 指标项 | 高配版 | 中配版 | 低配版 
| - | - | - | - |
| 可靠测距范围 |	0.05~25m|	0.05~10m|	8m
扫描频率|	15HZ	|15Hz|	10Hz
数据点数量|	13000/s|	13000/s|	4000/s
FOV	|270°|	270°|	360°
CPU	|Intel Core i7-7700|	2x丹佛+4xA57|	2x丹佛+4xA57
内存|	8GB|	8GB|	8GB
显卡|	NVIDIA GTX1060|	Pascal|	Pascal
显存|	3GB|	2GB|	2GB
SSD大小	|512GB|	32GB+256GB|	32GB+128GB
电池容量	|24V/30AH*2	|24V/15AH*2	|24V/10AH*2
续航时长	|12h|	15h	|10h
红外测距范围|	4~30cm*3 	|4~30cm*3|	10~80cm*3
超声测距范围	|20~600cm*3	|20~600cm*3	|20~600cm*3
单臂自由度	|6|	4|	4
触控平板|	Android|	Android|	Android|
视觉模组|高清RGBD|	RGBD|	双目高清
### 机器人对比
| 指标项 |	软件所Xbot	|ZEUS	|速感科技Qbot	|Double
|-|-|-|-|-|
标准载重(kg)|	50|	25|	40|	0
续航时长(h)|	>8|	>8|	4~8|	4
移动速度（m/s）	|0~1|	0.3,0.4,0.5|	0~2|	0~0.5
2D障碍物检测半径（m）|	20|	15|	指定范围0.5	|无
3D障碍物检测	|有|	无	|无|	无
可升降平台|	有	|无|	有	|有
视觉伺服云台	|有	|无	|无|	有
自主建图定位与导航（SLAM）|	有|	有	|无|	无
动态避障	|有	|有	|无	|无
二次开发接口	|有|	无|	有|	无
ROS标准开发支持	|有	|无|	无|	无
控制方式	|速度指令|	全封闭控制|	速度指令|	远程视频遥控

## Xbot2机器人产品清单
1. Xbot2机器人本体一台
2. 产品使用说明书一套
3. 机器人开发SDK说明文档与教程一套

## Xbot2实景应用视频
1. [多机器人三维仿真](https://v.qq.com/x/page/c0527bf4tbr.html)
2. [xbot办公室场景同步定位与地图构建](http://v.qq.com/page/l/j/r/l05274m5gjr.html)
3. [xbot机器人搭载腾讯优图人脸识别](http://v.qq.com/page/n/q/7/n0524qudvq7.html)
4. [xbot机器人动态避障效果](http://v.qq.com/page/m/1/9/m05244j0419.html)

## 相关文档教程与应用
### 机器人驱动包ROS WIKI开源

### 机器人配套教程


### 控制APP
Android：

访问https://fir.im/vuez或扫描以下二维码下载

![xbot](data:image/png;base64,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)
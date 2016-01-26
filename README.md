# 基本资料


| 姓名 | 性别 |电话 |E-mail |博客
|----------|----------|----------|----------|----------|
|  刘浩 |  Male |17704051924|v2top1@163.com|http://www.cnblogs.com/lyleLH

###  教育背景
| 时间 | 机构 |专业|学位|证书
|----------|----------|----------|----------|----------|
|  2010-2014 |  长江大学|地球物理学|地球物理学学士| CET-4

###  工作经历
| 时间 | 公司 |职位|岗位
|----------|----------|----------|----------|
|  2014.11--2015.03 | 第一代驾（深圳沃时诺）科技公司||iOS工程师
|  2015.04--2015.07 | 航通北斗信息科技公司|iOS组长(3人小组)|iOS工程师
|  2015.08--2016.04| 广东酷配电子商务|iOS组长(4人小组)|iOS工程师




# 项目经验

## `第一代驾司机端`  `2014.11-2015.03`

`v1.0`  
- 司机通过司机端等待后台自动派单或者客服手动排单（后台系统还不完备的时候），推送到司机端，开始代驾流程，并完成订单。

`业务点`    
- a.地图定位，导航，和路线规划，均采用百度的Api
- b.推送和本地通知

- c.等待时间计算和费用计算(与后端交互)

- d.订单生成和完成及状态改变

- e.支付流程

`主要职责`    

- 单人负责司机客户端的编码设计和产品开发
- 初期主要是实现各业务功能的demo，此时后端也在大改版，后端技术由c#全面转向java
- 参与接口定义和产品需求评审

- `后公司破产，项目未立项随即夭折`


## `航通守护者`  `2015.04-2015.07`

`v1.0-v1.1`    廉价的外包手上拿回来的项目，呵呵。

- 主要负责  历史轨迹模块，实时定位模块，电子围栏模块 三个模块融合在一个类中实现的功能的重构  : D

`v2.0`   重新开发  
- 项目属于航天科技旗下子公司家庭业务模块的主要项目，主要和公司的多款针对小孩和老人的定位追踪器配合使用，app使用者可以查询并显示硬件的历史轨迹和实时定位，app使用者可以在地图上设置电子围栏，追踪器越界会触发警告，推送到用户。

`技术要点`  
- 负责app的架构设计和实现，采用mcv架构，使用单列和协议等设计模式对控制器层，模型层和视图层解耦合

- 负责项目结构的基类设计，使用继承实现代码的高复用性

- a. 对网络层基类进行封装，继承AFN的面对参数的封装思想，保留HTTP的GET和POST方法，使用代理和block两种回调方式来通知控制器

- b.对模型层基类进行封装，设计常用的数据处理方法，针对定义好的接口封装MJExtension，拥有代理属性，可以指向控制器或者其他对象，实现MJExtension提供的多个方法，实现自动json解析和转模型时改属性名和制定数组元素类型和对象类型的方法，方便转换

- c.对view 层进行封装，view基类拥有回调用的协议和block属性，可通信到控制器。


- 多语言打包和上架

- 熟练掌握继承百度地图SDK，高德地图SDK,和 google Map SDK


		
### `UUAID` `珠宝卫视`等等项目的维护和扩展及重构  `2015.04-2015.07`

## `酷配养车`  `2015.08-2015.10`
## `酷配养车商家版`  `2015.11-2016.01`
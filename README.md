# iOS-Homework7-MotionAlarm

## 应用程序功能概要

* 本程序模拟了一个简易闹钟

* 该闹钟只利用本地通知模拟闹铃功能

* 关掉闹钟的方式为：

  * 利用训练的GestureClassfier检测三种motion之一的动作若干次
  * 若该动作持续完成到了设定的次数，则闹钟可以关闭（回到普通界面）

* 本地通知图示如下：

  <img src="/Users/strivin/Desktop/IMG_0082.PNG" alt="IMG_0082" style="zoom:20%;" />

***

## 闹钟列表页说明

* 闹钟列表页为该程序的首页

* 以tableView的形式展示了用户设置的各个闹钟

* 每个闹钟的cell包括：

  * 时间label
  * 重复星期label
  * 闹钟提示label
  * 是否开启该闹钟的switch

* 点击右上角的+号可以添加新闹钟

* 点击左上角的Edit可以删除闹钟

* 点击任意一个闹钟cell可以编辑该闹钟

* 该页图示如下：

  <img src="/Users/strivin/Desktop/IMG_0085.PNG" alt="IMG_0085" style="zoom:20%;" />

***

## 闹钟设置页说明

* 闹钟设置页即为闹钟列表页点击+号或者点击任意一个闹钟cell进入的页面

* 可以对闹钟的详情进行添加或者修改

* 设置从上往下依次为：

  * 闹钟的时间wheel
  * 星期重复buttons
  * 动作模式wheel
  * 动作次数slider
  * 闹钟提示label

 * 该页图示如下：

   <img src="/Users/strivin/Desktop/IMG_0086.PNG" alt="IMG_0086" style="zoom:20%;" />

***

 ## 闹钟启动页说明

 * 该页是闹钟响起之后会进入的页面
 * 该页面从上往下依次显示：
  * 动作模式的名称label
  * 动作的计数label
  * 动作完成的progressBar
  * 动作是否完成的button(**一旦完成，即从灰色的不可响应，转变为蓝色的可响应，点击之便可回退到闹钟列表页**)
 * 该页图示如下：

<img src="/Users/strivin/Desktop/IMG_0083.PNG" alt="IMG_0083" style="zoom:20%;" />

<img src="/Users/strivin/Desktop/IMG_0084.PNG" alt="IMG_0084" style="zoom:20%;" />

***

***




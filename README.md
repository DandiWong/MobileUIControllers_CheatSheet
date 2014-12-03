MobileUIControllers_CheatSheet——移动控件列表中文速查表
===

> 这是用于产品经理、交互设计师速查移动终端上开发时所需要的系统控件的速查表。

##0 目录
[TOC]

##1 iOS系统控件列表

###1 视图UIView和UIWindow
iPhone视图的规则是：一个窗口，多个视图。
 
####1.1 显示数据的视图
下面几个类可在屏幕上显示信息：

1. UITestView : 将文本段落呈现给用户并允许用户使用键盘输入自己的文本。可设置可编辑或不可编辑，使用单一字号和单一字体。
2. UILabel : 实例呈现标签样式的只读文本视图。
3. UIImageViews : 显示图片。
4. UIWebView : 显示HTML,PDF或其他高级Web内容。
5. MKMapViews : 向应用程序中嵌入地图。
6. UIScrollView : 实例支持呈现比正常应用程序窗口大小大一些的内容，滚动条。

####1.2 作出选择的视图
1. UIAlertView : 最多只展示两三个选项。
2. UIActionSheet : 三个以上。

####1.3 控件
控件是用户触摸转换为回调触发器的屏幕对象。

1. UIButton : 实例提供了屏幕按钮
2. UISegmentedControl : 提供了一行大小相等的按钮。
3. UISwtich : 提供了一个简单的哦二进制空间。该类呈现开关选择。
4. UISlider : 用户通过沿着一个水平工具条环东至十七就可以从一个指定范围内选择一个值。
5. UIScrollView : 用户能够在页面间移动。
6. UIPageControl : 提供了一席类小圆点，它们展示单枪页面并让用户导航到后面或者前面的页面。
7. UITextField : 循序输入文字的控件。

####1.4 表格和拾取器
表格呈现一个滚动的选择列表。

1. UITableView :  
 
####1.5 栏
1. UINavigationBar : 它出现在很多界面顶部，用来提供导航状态。
2. UItabBarController : 
3. UISerchDisplayController : 
 
####1.6 进度和活动
1. UIActiveityIndicatorView : 提供了纺锤样式的轮，在处理任务期间显示。该轮告诉用户，任务将在某一时间点完成，但是不确定合适完成。
2. UIProgreessView : 提供一个从左象右捉奸填满的进度条，指示任务的进度情况。
 
###2 视图控制器UIViewController
视图控制器可以集中进行某些视图管理。  
视图控制器不是视图，它们是没有可视化表示的抽象类，只有视图提供可视画布。

####2.1 UIViewController
  1. UIViewController是视图控制器的父类，使用它来管理主视图。
  2. 管理每个主页面的生命周期 : 从开始到结束并且要考虑视图生命期内可能要相应的变化。
  3. 设置视图的外观和它显示的子视图。
  4. 响应正在显示或消失的视图。

####2.2 导航仪控制器UINavigationController
  导航仪控制器允许你在树状视图层次结构间上下导航。

####2.3 并行控制器UITabBarController

####2.4 表格控制器UITableViewController
  UITableViewController提供了一个标准的已连接UITableView实例并自动将委托和数据源设为指向自己。
  UISearchBar提供了一个内置搜索框，搜索显示控制器是一种表格视图。
  NSFetchedRsultsController可以从Core Data存储库中获取的对象填充UITableView。
 
####2.5 地址簿控制器
  地址簿用户界面框架（AddressBookUI.framework）提供了几个试图控制器，允许你从地址簿中选择某个人。
 
####2.6 图片选择控制器UIImagePickerController
  允许用户从内置相册中选择图片或者使用摄像头拍照或录制视频。
 
####2.7 邮件撰写MFMailCompseViewContriller
   MFMailCompseViewContriller允许你创建用户可以直接在程序中定制邮件消息。
 
####2.8 对等选取器GKPeerPickerController
   用于发现和链接其他的iphone。
 
####2.9 Media Play控制器
   允许选择和播放音乐和电影

##2 Android系统控件列表

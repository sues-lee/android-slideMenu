# android-slideMenu
A slide menu component like QQ5.0
##效果图：
![](https://github.com/sues-lee/android-slideMenu/blob/master/ScreenShots/slideMenuGif1.gif)
##简介：
    该项目实现了类似QQ5.0的侧滑菜单效果，支持直接拖动以及侧滑手势，同时可以用按钮控制菜单的开关。

##用法:
* 将 `res/layout/activity_main.xml` 中的布局文件复制到你的项目中，在内部的LinearLayout中放置你的主界面布局。
* 将`left_menu.xml`替换为你自己的菜单布局文件。
* 将`SlideMenu.java`复制到你的项目中

##注意:
* SlideMenu控件有名为`app:rightPadding`的自定义属性，意为菜单部分右侧到屏幕的距离，默认为`150dp`。
* 可以调用SlideMenu中的`openMenu()`和`closeMenu()`方法开关菜单，`toggleMenu()`方法切换菜单的开关状态。

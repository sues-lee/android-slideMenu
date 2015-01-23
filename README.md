# android-slideMenu
A slide menu component like QQ5.0
##效果图：
![](https://github.com/sues-lee/android-slideMenu/blob/master/ScreenShots/slideMenuGif1.gif)
###简介：
    该项目实现了类似QQ5.0的侧滑菜单效果，支持直接拖动以及侧滑手势，同时可以用按钮控制菜单的开关。

###用法:
1. clone此项目至本地
* 将本项目添加为你的项目的依赖，具体方法见：[on the stackoverflow][1]
* 在布局文件根节点加入slidemenu的根节点

        xmlns:slidemenu="http://schemas.android.com/apk/res-auto"

    可以在布局文件中使用`slidemenu:rightPadding`属性，用于设置左侧菜单布局的右边距
* 将 `res/layout/activity_main.xml` 中的布局文件复制到你的项目中，在内部的LinearLayout中放置你的主界面布局。
* 将`left_menu.xml`替换为你自己的菜单布局文件。
* 在onCreate方法(或fragment中的 onCreatView方法)中绑定本控件
    menu = (SlideMenu)findViewById(R.id.slideMenu);
* 使用SlideMenu中的`openMenu()`和`closeMenu()`方法开关菜单，`toggleMenu()`方法切换菜单的开关状态。

### Developed By

* lixu

* Email：859518963@qq.com

### Licence

MIT
http://opensource.org/licenses/MIT





[1]:http://stackoverflow.com/questions/18656023/androidstudio-module-dependencies-in-gradle

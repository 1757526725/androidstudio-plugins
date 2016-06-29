AndroidStudio 优秀插件汇总
====================

欢迎大家推荐好的 Android 开源项目，可直接[Commit](https://github.com/dreamlivemeng/androidstudio-plugins/wiki "请遵守<内容添加及编辑规范>")，欢迎`Star`、`Fork` :)  
## 第一部分 插件的介绍  
Google 在2013年5月的I/O开发者大会推出了基于IntelliJ IDEA Java IDE上的Android Studio。AndroidStudio是一个功能齐全的开发工具，还提供了第三方插件的支持。让开发人员更快速更好的开发程序。  

## 第二部分 插件的安装
- in Android Studio: go to `File → Settings → Plugins → Browse repositories` and search for `插件名` 

_or_

- in Android Studio: go to download it jar and install  `File → Settings → Plugins → Install plugin from disk` 

## 第三部分 插件的汇总   

#### 一、优秀插件  
1. Android ButterKnife Zelezny  
ButterKnife是一个专注于Android系统的View注入框架,可以减少大量的findViewById以及setOnClickListener代码，可视化一键生成。
####PS:效果图就不贴了，打开插件下载地址和源码地址都能看见，而且数据多了加载效果图蛮卡的。  
插件下载地址：https://plugins.jetbrains.com/plugin/7369?pr=androidstudio  
插件源码地址： https://github.com/avast/android-butterknife-zelezny  
插件教程：http://blog.csdn.net/dreamlivemeng/article/details/51261170  
推荐指数：五星  

1. GsonFormat  
GsonFormat是一个快速格式化json数据,自动生成实体类参数的插件。  
插件下载地址：https://plugins.jetbrains.com/plugin/7654?pr=androidstudio    
插件源码地址：https://github.com/zzz40500/GsonFormat    
插件教程：http://blog.csdn.net/dreamlivemeng/article/details/51262538  
推荐指数：四星  

1. Android Drawable Importer  
为了适应所有Android屏幕的大小和密度，每个Android项目都会包含drawable文件夹。任何具备Android开发经验的开发人员都知道，为了支持所有的屏幕尺寸，你必须给每个屏幕类型导入不同的画板。Android Drawable Importer插件能让这项工作变得更容易。它可以减少导入缩放图像到Android项目所需的工作量。Android Drawable Importer添加了一个在不同分辨率导入画板或缩放指定图像到定义分辨率的选项。这个插件加速了开发人员的画板工作。  
插件下载地址：https://plugins.jetbrains.com/plugin/7658?pr=androidstudio  
插件源码地址：https://github.com/winterDroid/android-drawable-importer-intellij-plugin  
插件教程地址：http://blog.csdn.net/lee_sire/article/details/49684385    
推荐指数：三星  

1. android-selector-chapek / SelectorChapek for Android  
根据资源自动生成相应的selector。  
插件下载地址：https://plugins.jetbrains.com/plugin/7298  
插件源码地址：https://github.com/inmite/android-selector-chapek   
推荐指数：三星  

1. Android Parcelable code generator  
快速实现Parcelable接口的插件。  
插件下载地址：https://plugins.jetbrains.com/plugin/7332?pr=  
插件源码地址：https://github.com/mcharmas/android-parcelable-intellij-plugin/  
插件教程地址：http://blog.csdn.net/kroclin/article/details/40902721  
推荐指数：四星  

1. Markdown support
Markdown 是一种可以使用普通文本编辑器编写的标记语言，通过类似HTML的标记语法，它可以使普通文本内容具有一定的格式。  
插件下载地址：https://plugins.jetbrains.com/plugin/7793  
插件文档地址：https://github.com/JetBrains/intellij-plugins/tree/master/markdown  
推荐指数：四星  

1. Android Postfix completion  
可根据后缀快速完成代码。  
插件下载地址：https://plugins.jetbrains.com/plugin/7775?pr=  
插件教程地址：http://blog.jetbrains.com/idea/2014/03/postfix-completion/  
推荐指数：五星  

1. AndroidAccessors  
快速实现get和set方法的插件。  
插件下载地址：https://plugins.jetbrains.com/plugin/7496?pr=  
插件文档地址：https://github.com/jonstaff/AndroidAccessors  
推荐指数：三星  

1. Lifecycle Sorter  
可以根据Activity或者fragment的生命周期对其生命周期方法位置进行先后排序。  
插件下载地址：https://plugins.jetbrains.com/plugin/7742?pr=  
插件源码地址：https://github.com/armandAkop/Lifecycle-Sorter  
推荐指数：五星  

1. ADB WIFI
无需root就能wifi调试。  
插件下载地址：https://plugins.jetbrains.com/plugin/7856?pr=  
插件源码地址：https://github.com/layerlre/ADBWIFI  
推荐指数： 五星  

1. ADB Idea  
adb 调试工具,Uninstall App、Kill App、Start App、Restart App、Clear App Data、Clear App Data and Restart
插件下载地址：https://plugins.jetbrains.com/plugin/7380?pr=  
插件源码地址：https://github.com/pbreault/adb-idea/  
推荐指数：五星  

1. CodeGlance  
最大的用途：可用于快速定位代码。  
插件下载地址：https://plugins.jetbrains.com/plugin/7275?pr=  
插件源码地址： https://github.com/Vektah/CodeGlance  
推荐指数：五星  

1. JSONOnlineViewer  
可实现直接在android studio中调试接口数据，可以选择请求类型，自定义请求头及请求体，json数据格式化后展示  
插件下载地址：https://plugins.jetbrains.com/plugin/7838?pr=  
推荐指数：四星  

1. FindBugs-IDEA  
通过FindBugs帮你找到隐藏的bug及不好的做法。  
插件下载地址：https://plugins.jetbrains.com/plugin/3847?pr=  
插件源码地址：https://github.com/andrepdo/findbugs-idea/tree/master  
推荐指数：四星  

1. jimu Mirror  
这是一个可以让你在真实的设备上迅速测试布局的插件。jimu Mirror允许在设备上预览随同编码更新的Android布局。
插件下载地址：https://plugins.jetbrains.com/plugin/7517?pr=    
插件教程地址：http://www.itnose.net/detail/6204426.html  
推荐指数：四星  

1. JavaDoc   
添加注释，可自定义模板。  
插件下载地址：https://plugins.jetbrains.com/plugin/?idea_ce&pluginId=7157  
插件源码地址：https://github.com/setial/intellij-javadocs  
推荐指数： 五星  

1. Android strings.xml tools  
可以用来管理Android项目中的字符串资源。它提供了排序Android本地文件和添加缺少的字符串的基本操作。虽然这个插件是有限制的，但如果应用程序有大量的字符串资源，那这个插件就非常有用了。  
插件下载地址：https://plugins.jetbrains.com/plugin/7498?pr=  
插件源码地址：https://github.com/constantine-ivanov/strings-xml-tools  
推荐指数：五星  

1. Robotium Recorder  
Robotium Recorder是一个自动化测试框架，用于测试在模拟器和Android设备上原生的和混合的移动应用程序。Robotium Recorder可以让你记录测试案例和用户操作。你也可以查看不同Android活动时的系统功能和用户测试场景。  
插件下载地址：https://plugins.jetbrains.com/plugin/7513?pr=  
插件官方网址：http://robotium.com/  
推荐指数：四星  

1. Android Holo Colors Generator  
通过自定义Holo主题颜色生成对应的Drawable和布局文件  
插件下载地址：https://plugins.jetbrains.com/plugin/7366?pr=  
插件源码地址：https://github.com/jeromevdl/android-holo-colors-idea-plugin  
推荐指数：四星  

1. lint-cleaner-plugin  
删除未使用的资源,包括String字符串,颜色和尺寸。  这是一个Gradle插件，所以如何配置可以去github的源码上看。  
插件源码地址：https://github.com/marcoRS/lint-cleaner-plugin  
推荐指数：四星  

1. codota  
该网站搜集了大量的代码，号称超过700W的代码实例。提供了chrome和as插件。  
插件下载地址：https://plugins.jetbrains.com/plugin/7638?pr=  
插件官方网址：https://www.codota.com/  
推荐指数：五星  

1. ECTranslation   
一个androidstudio上面的翻译插件（将英文翻译为中文）。   暂时只能以jar的方式安装。jar下载地址以及使用方法在github上的源码地址上都有详细描述。  
插件源码地址：https://github.com/Skykai521/ECTranslation  
推荐指数：四星  

1. Android File Grouping Plugin   
该插件可自动将前缀相同的文件归类显示到同一文件目录下，但不会因此而移动文件或创建文件夹。  
插件下载地址：https://github.com/dmytrodanylyk/folding-plugin/releases  
插件源码地址：https://github.com/dmytrodanylyk/folding-plugin    
推荐指数： 四星  

1. PermissionsDispatcher  
一个针对API 23，可在`Activity/Fragment`中快速生成`Runtime Permissions`代码的插件。  
插件下载地址：https://plugins.jetbrains.com/plugin/8349  
插件源码地址：https://github.com/shiraji/permissions-dispatcher-plugin    
推荐指数： 四星  

1. Android code Generator  
Android Studio/IntelliJ IDEA的安卓代码生成插件，帮助提高app的开发速度。可以从layout生成Activity类、Fragment类、Adapter类，从menu.xml生成menu代码等。  
插件下载地址：https://plugins.jetbrains.com/plugin/7595?pr=   
插件源码地址：https://github.com/tmorcinek/android-codegenerator-plugin-intellij  
插件教程：（中文版）http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2016/0523/4294.html、（英文版）http://tmorcinek.github.io/android-codegenerator-plugin-intellij/  
推荐指数：五星  

1.  .ignore  
项目中，每次add，commit的时候有可能会把Module生成的一些build文件/本地配置文件/iml文件提交上去。可以通过gitignore解决，如果你不想提交的文件，就可以在创建项目的时候将这个文件中添加即可，将一些通用的东西屏蔽掉。  
插件下载地址：https://plugins.jetbrains.com/plugin/7495?pr=androidstudio  
插件源码地址：https://github.com/hsz/idea-gitignore  
推荐指数：四星  

1. checkstyle-idea  
CheckStyle-IDEA 是一个检查代码风格的插件，比如像命名约定，Javadoc，类设计等方面进行代码规范和风格的检查，你们可以遵从像Google Oracle 的Java 代码指南 ，当然也可以按照自己的规则来设置配置文件，从而有效约束你自己更好地遵循代码编写规范。  
插件下载地址：https://plugins.jetbrains.com/plugin/1065?pr=androidstudio  
插件源码地址：https://github.com/jshiell/checkstyle-idea  
推荐指数：四星  

1. Android Methods Count  
统计Android依赖库中方法的总个数。 (一个dex只能接受的65K并不是指方法数超过65K而报的错,而是指引用计数超过65K)  
插件下载地址：https://plugins.jetbrains.com/plugin/8076?pr=androidstudio  
推荐指数：四星  

1. Sexy Editor  
设置代码性感背景图，还是比较强悍的。  
插件下载地址：https://plugins.jetbrains.com/plugin/1833?pr=androidstudio  
插件源码地址：https://github.com/igorspasic/idea-sexyeditor    
推荐指数：五星  

1. AndroidProguardPlugin  
Android一键生成项目混淆代码插件，现在jetbrains还在审核只能下载进行安装了，不能通过as插件直接搜索安装。因为混淆时很多同学比较头疼的一个事情，所以给5星。  
插件下载地址：https://raw.githubusercontent.com/zhonghanwen/AndroidProguardPlugin/master/AndroidProguard.zip  
插件源码地址：https://github.com/zhonghanwen/AndroidProguardPlugin  
推荐指数：五星  

1. Android Studio Prettify  
从布局文件一键生成对view的声明。（不适用注解，形式为findviewById的方式）  
插件下载地址：https://plugins.jetbrains.com/plugin/7405  
插件源码地址：https://github.com/Haehnchen/idea-android-studio-plugin  
推荐指数：四星  


Thanks
------
* Everyone who has contributed code and reported issues!


关于作者
------
* QQ群：490832714  
* Email：dreamlivemeng@gmail.com  












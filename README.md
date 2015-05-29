## 安装及配置
1 官网下载

2 安装
Android Studio路径 C:\Program Files\Android\Android Studio
Android SDK路径 C:\Users\lifeix\AppData\Local\Android\sdk

ANDROID_HOME C:\Users\lifeix\AppData\Local\Android\sdk
Android Studio配置路径 C:\Users\lifeix\.AndroidStudio

3 DownLoading Components
下载不了报错 
解决办法
打开Android Studio安装目录的bin目录下面的idea.properties文件，添加一条禁用开始运行向导的配置项
C:\Program Files\Android\Android Studio\bin\idea.properties
disable.android.first.run=true 

4 工作目录
C:\Users\lifeix\AndroidStudioProjects\MyApplication
替换成
D:\AndroidStudioProjects\MyApplication

4 Gradle的配置
Gradle下载的位置 C:\Users\lifeix\.gradle\wrapper

5 修改主题
File Settings Appearance

6 更改代码字体
File Settings Editor Colors&Fonts 
注意Scheme name，首先需要Save As，保存一个自己的名字，然后修改字体和大小即可。

7 设置项目的文件和编码格式
首先，我们要有一个项目，然后选中项目，打开Preferances，分别设置IDE Encoding、Project Encoding、Default encoding 。推荐都设置为UTF-8。

8 Failed to resolve: com.android.support:appcompat-v7:22.+
解决办法

9 修改JDK和SDK的路径？
File OtherSettings DefaultProjectStructure

10 设置显示代码行数
在左侧的地方右键，选中Show Line Numbers即可

11 JetBrains Decompiler
?

12 Studio一个窗口只能有一个项目 一般切换到“project”模式

13 自动导包
File Settings Editor -> Auto Import -> Java
勾选3个框

14 更改背景色
色调：85。饱和度：1 2 3。亮度：2 0 5
204 232 207

15 添加系统字体
1 找到Adnroid Studio安装目录下lib文件夹中的resources.jar文件。
2 双击fonts文件夹，点击添加选择需要添加的字体
存在问题 以后再看

16 Android Studio中添加重载函数的方法
右击----Generate---Override Method---选择要重载的函数。

17 快捷键
注释 Ctrl + /
取消注释

18 格式化代码
Ctrl + Alt + L






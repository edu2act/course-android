<img src="./image/logo.png" height="50" /> 

# Android Studio 安装教程



#### 1. 将Android Studio压缩包进行解压。

<img src="./image/01.png" height="150" /> 

#### 2. 解压后得到如下文件夹。

<img src="./image/02.png" height="150" /> 

#### 3. 将上一步解压得到的`android-studio`文件夹拷贝到期望Android Studio的路径下，例如下图。

<img src="./image/03.png" height="150" /> 

#### 4. 拷贝完成之后，将老师上传到群文件中的`AndroidSDK.7z`压缩文件进行解压，得到如下`AndroidSDK`文件夹，此文件夹内容为Android SDK文件。

<img src="./image/21.png" height="100" /> 
<img src="./image/22.png" height="100" /> 

#### 5. 将上一步解压得到的文件夹剪切到准备存放Android SDK文件的路径下，注意路径中不允许出现中文、特殊字符及空格，例如下图，存放Android SDK文件夹的路径为C盘根目录。

<img src="./image/23.png" height="250" /> 

#### 6. 回到刚才存放Android Studio的目录，打开`android-studio\bin`目录，可以看到如下两个应用程序，根据自身操作系统情况，选择一个双击打开AndroidStudio。如期望之后打开方便可右键点击建立桌面快捷方式。

<img src="./image/04.png" height="250" /> 

#### 6. 在弹出的`Complete Installation`窗口中，勾选`Do not import settings`选项，之后点击`OK`按钮。

<img src="./image/05.png" height="150" /> 

#### 7. 在如下提示框中，点击`Cancel`按钮。

<img src="./image/06.png" height="100" /> 

#### 8. 进入`Welcome`界面后，直接点击`Next`按钮。

<img src="./image/07.png" height="400" /> 

#### 9. 在`Install Type`界面，选择`Custom`选项，然后点击`Next`按钮。

<img src="./image/08.png" height="400" /> 

#### 10. 在`Select UI Theme`界面，在两个主题中选择喜欢的主题，然后点击`Next`按钮。

<img src="./image/09.png" height="400" /> 

#### 11. 在`SDK Components Setup`界面，在`Android SDK Location`的路径下选择刚才存放Android SDK的本地路径，点击`Next`按钮。（注意选择完路径之后最好将电脑网络断开，否则可能会进行缺失文件的下载，由于是连接国外服务器下载，可能会等待比较长的时间）

<img src="./image/10.png" height="400" /> 

#### 12. 在`Verify Settings`界面，直接点击`Finsh`按钮。

<img src="./image/11.png" height="400" /> 

#### 13. 在`Downloading Components`界面，直接点击`Finsh`按钮。

<img src="./image/12.png" height="400" /> 

#### 14. 此时显示的是Android Studio的主界面，点击`Start a new Android Studio project`按钮，创建一个新的Android Studio项目。

<img src="./image/13.png" height="400" /> 

#### 15. 在`Create Android Project`界面，填入项目名称相关信息，点击`Next`按钮。

<img src="./image/14.png" height="400" /> 

#### 16. 在`Target Android Devices`界面，勾选`Phone and Tablet`，表示创建的是手机或平板项目，并选择项目所支持的Android最低版本，点击`Next`按钮。

<img src="./image/15.png" height="400" /> 

#### 17. 在`Add an Activity to Mobile`界面，选择`Empty Activity`，表示创建一个空的Activity项目，点击`Next`按钮。

<img src="./image/16.png" height="400" /> 

#### 18. 在`Configure Activity`界面，填入Activity与Layout名称，此处无需修改使用默认名称即可，点击`Finish`按钮完成创建（如果没有`Finish`按钮，则点击`Next`按钮）。

<img src="./image/17.png" height="400" /> 

#### 19. 如果此时你的窗口中显示下面浮动窗口，请耐心等待下载完成，因为是第一次创建项目，Android Studio会进行Gradle工具下载。（如果按照前面步骤的要求进行了断网操作，此处是无需下载的，为时已晚，耐心等待。）

<img src="./image/19.png" height="70" /> 

#### 20. 项目创建成功时，会显示下面窗口，可直接点击`Close`按钮关闭浮在最上层的`Tip of the Day`窗口。

<img src="./image/18.png" height="400" /> 

#### 21. 观察当前的窗口，会发现提示`Gradle project sync failed.`的提示，此时问题产生的原因是前面将网络断开了，Android Studio找不到Gradle工具（网络连接不通畅也会出现此问题），Gradle在群文件中可下载，无需在线下载。

<img src="./image/20.png" height="400" /> 

#### 22. 找到在群文件中下载的`gradle-4.4-all.zip`文件，然后找到`C:\Users\当前用户名\.gradle\wrapper\dists\gradle-4.4-all\9br9xq1tocpiv8o6njlyu5op1（一长串字符）`文件夹，会发现其中有两个`gradle-4.4-all.zip.`开头的文件，将这两个文件删掉，并把前面下载`gradle-4.4-all.zip`文件拷贝到此目录。

<img src="./image/24.png" height="150" />

#### 23. 文件拷贝完成之后，将电脑网络连接，然后点击提示框中的`Try Again`按钮，等待Gradle工具对项目依赖包进行下载（第一次创建项目才会出现此情况，之后创建无需再次下载，下载时间由网络情况决定，耐心等待）。

<img src="./image/25.png" height="230" />


#### 24. 项目创建完成后，接下来便是运行项目了，运行Android项目有两种选择，一种是运行在真机环境下，另一种是运行在PC上的Android模拟器环境下。如果使用真机直接跳过本步骤（直接跳转到步骤33），如果使用Android模拟器，首先在群文件中下载`x86_64-26_r11.zip`文件（本文件是Android Studio 中的AVD模拟器创建时所需系统文件，下载速度较慢故采用离线安装方法，今后如想安装其它版本AVD模拟器可在线安装）。

<img src="./image/29.png" height="130" />

#### 25. 在解压后的文件中找到`x86`文件夹，然后拷贝到`Android SDK目录\system-images\android-26\default\`文件夹下，如图所示。

<img src="./image/30.png" height="70" />

#### 26. 关闭Android Studio，然后重新打开Android Studio，点击右上角的`AVD Manager`按钮。

<img src="./image/26.png" height="70" />

#### 27. 在`Your Virtual Devices`界面，点击`Create Virtual Device`按钮，创建一个AVD虚拟机。

<img src="./image/27.png" height="400" />

#### 28. 在`Choose a device definition`界面，选择`Phone`，然后选择某一机型，点击`Next`按钮。

<img src="./image/28.png" height="400" />

#### 29. 在`Select a system image`界面，选择`x86 Images`标签，然后选择列表中的`Oreo`（API Level=26，ABI=x86，Target=Android 8.0），此系统版本对应前面拷贝的离线系统文件，此选项后面没有Download标识，然后点击`Next`按钮。

<img src="./image/31.png" height="400" />

#### 30. 在`Verify Configuration`界面，输入AVD模拟器名称，点击`Finsh`按钮。

<img src="./image/32.png" height="400" />

#### 31. 在`Your Virtual Devices`界面，能够发现刚刚创建的AVD虚拟机已经出现在列表中，点击AVD虚拟机的运行按钮，运行该虚拟机。

<img src="./image/33.png" height="400" />

#### 32. 在AVD虚拟机启动之后，可以看到如下虚拟机界面。

<img src="./image/34.png" height="400" />

#### 33. 回到Android Studio界面，点击运行按钮。

<img src="./image/35.png" height="70" />

#### 34. 在弹出的`Select Deployment Target`窗口中，选择运行项目的设备（真机或虚拟机），然后点击`OK`按钮。

<img src="./image/36.png" height="200" />

#### 35. 如果弹出如下`Instant Run`窗口，点击`Install and Continue`按钮，并等待下载完成即可。

<img src="./image/37.png" height="100" />

#### 36. 运行成功之后，便可以在你的设备上看到如下界面。

<img src="./image/38.png" height="400" />



![河北师范大学软件学院](../../../image/logo.png)



#### 常见问题：无法创建新项目

如创建新项目点击`Finsh`后无反应，并提示如下类似信息，则说明Android Studio中创建新项目的模板文件损坏。

```
com.android.tools.idea.templates.FreemarkerUtils$TemplateProcessingException: java.io.FileNotFoundException: Template "root://gradle-projects/NewAndroidProject/root/settings.gradle.ftl" not found.

```

#### 解决办法：

重新拷贝一份Android Studio安装文件，重新解压并覆盖之前文件。有时也可能是解压软件造成的，此时可更换一个解压软件进行尝试。
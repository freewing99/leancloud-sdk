# 欢迎使用AVOS Cloud

本教程将会向您展示如何使用AVOS Cloud Android SDK开发一个简单的移动应用。

# 申请AVOS Cloud帐号

如果您还未拥有AVOS Cloud的帐号，请访问 [http://avoscloud.com](http://avoscloud.com) 申请开发人员帐号。

请注意，目前中国区和美国区的数据并不能互通。 


![apply account](images/apply-account.png)


# 创建基于AVOS Cloud的移动App

![create app](images/create-app.png)


# 查看app keys

![app keys](images/app-keys.png)

app keys将会在您的代码中使用到，同时请注意保管好您的app keys，以免给您的应用带来损失。

# 下载SDK

```
git clone git@github.com:avos/avoscloud-sdk.git
```


# 打开示例工程

### 使用IntelliJ Idea导入


![import project](images/intellij-import.png)



### 修改AppKey和AppId

![update keys](images/android-keys.png)


### 北美节点

在v2.6.4以后，SDK开始支持北美节点，如果您需要切换到北美节点，请将avoscloud_us_ssl.bks 放到您的项目/res/raw/目录下，以保证SSL根证书能够被成功加载




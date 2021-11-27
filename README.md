# 原神启动器Plus

### 说明：（请认真阅读）

1. 本启动器实现部分完全开源，并不存在后台操作，联网部分仅仅为版本、公告检测

2. 本启动器使用到的修复SDK的资源为B站官方客户端中提取的DLL，用途是启动游戏后的B站专属登录窗口，如果不信任可以不使用或者自行寻找同名资源替换
   ![SDK.png](https://i.loli.net/2021/11/27/aeGz87ADEmJSg5C.png)
   
   #### 修复SDK的dll文件PCGameSDK.dll[本文件仅为B站端的时候起作用]的Hash值：
   
   ```html
   [MD5:81EE1D7755B8611AC98B334E0BBCD3D2]
   ```
   ```html
   [SHA256:88030B01A9E2B4A1032DEA3FA8A17DF30C8AEB5A7614F1CFA02C898C5B4371EA]
   ```
   
3. 本启动器使用的国际服资源包[GlobalFile.pkg]为国际服与国服使用Beyond Compare对比提取后进行打包，实际为zip格式文件，如不信任可以不使用



### 主界面：（模仿官方大小排布设计）

![启动器.png](https://i.loli.net/2021/11/27/7S2xjzlpf1sLMO6.png)

#### 点击右侧图片样式的按钮支持快速直达游戏内保存的相片/截图目录

支持自定义启动器背景：将1280×730分辨率（或同等比例）的png格式图片改名bg.png放置Config目录下打开启动器即可

### 设置界面：
![设置.png](https://i.loli.net/2021/11/27/1XhG6fdj3APJHts.png)  
支持选择B服、官服、国际服和自定义任意分辨率启动，后期可能加入解锁FPS限制的选项（鸽~~)  


## 版本更新：
### 1.0.1

1. 启动器首次发布  

### 1.0.2

1. 修复游戏安装在系统盘的权限问题

2. 增加了首次官服转换哔哩哔哩服游戏

   提示MihoyoSDK未初始化报错的解决方法

### 1.0.3

1. 增加了启动器版本更新功能

2. 整合了mihoyosdk的文件至启动器中

3. 增加了对国际服的切换支持【需下载切换资源包GlobalFile.pkg】

   资源包下载地址：[下载资源包](https://pan.baidu.com/s/1-5zQoVfE7ImdXrn8OInKqg) 访问密码：etxd

## [点击下载](https://github.com/DawnFz/Genshin-LauncherDIY/releases)
#### ~~提示：1.0.2版本为纯脱机程序，没有加入更新功能，预计下个版本加入。~~

### 正在准备的功能：

1. 官服转换哔哩哔哩服[完成]
2. 修复MihoyoSDK缺失【PCGameSDK.dll】[完成]
3. 增加对国际服的支持[完成]
4. 切换服时自动保存上一个服的用户凭证注册表，以便选择快速登录[制作中]

其他待补充  

[TOC]

## 创建项目
```
cordova create HelloWorld
```
## 添加平台
### 添加平台
```
cordova platorm add ios
cordova platorm add android
```
### 查看添加的平台
```
cordova platform ls
```
### 删除平台
```
cordova platform rm android
```
## 编译
### 编译所有版本
```
cordova build
```
### 编译单独平台
```
cordova build ios
```
## 运行
```
cordova run ios
```

## 插件
### 搜索插件
```
cordova plugin search bar code
```
### 添加插件
方式一: 框架
```
cordova plugin add org.apache.cordova.device
```
方式二: 地址
```
cordova plugin add https://github.com/apache/cordova-plugin-console.git
```

### 添加的插件列表
```
cordova plugin ls
```
### 移除插件
```
cordova plugin rm org.apache.cordova.console    
```

### 常用插件
```
cordova plugin add org.apache.cordova.device                   //设备API

cordova plugin add org.apache.cordova.network-information  //网络（事件）

cordova plugin add org.apache.cordova.battery-status      //电池（事件）

cordova plugin add org.apache.cordova.device-motion     //加速器

cordova plugin add org.apache.cordova.device-orientation     //罗盘

cordova plugin add org.apache.cordova.geolocation         //定位

cordova plugin add org.apache.cordova.camera                 //摄像头

cordova plugin add org.apache.cordova.media-capture     //媒体文件处理

cordova plugin add org.apache.cordova.media                   //媒体文件处理

cordova plugin add org.apache.cordova.file                        //文件访问

cordova plugin add org.apache.cordova.file-transfer          //文件传输

cordova plugin add org.apache.cordova.dialogs                 //对话框

cordova plugin add org.apache.cordova.vibration              //震动

cordova plugin add org.apache.cordova.contacts               //联系人

cordova plugin add org.apache.cordova.globalization       //全球化

cordova plugin add org.apache.cordova.splashscreen       //闪屏

cordova plugin add org.apache.cordova.inappbrowser             //打开新的浏览器窗口

cordova plugin add org.apache.cordova.console                //调试控制台
```

## cordova 升级
 升级cordova后需要升级平台
### 升级cordova 
```
npm update -g cordova
```
### 升级平台
```
cordova platform update ios
```










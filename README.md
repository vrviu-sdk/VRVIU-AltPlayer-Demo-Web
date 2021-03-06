# AltPlayer-SDK-Web

[![](https://img.shields.io/badge/Powered%20by-vrviu.com-brightgreen.svg)](https://vrviu.com)

## 版本
V1.0

## 功能说明
支持FLV格式普通视频点播以及直播功能，其中直播是网络主播实时推送的视频流，用户能够及时看到主播的画面。点播是播放云端或者本地的文件。

* **播放器格式支持**：目前只能支持FLV格式视频或者HTTP-FLV格式视频流。

* **协议支持**：支持HTTP-FLV协议，以及本地文件的播放。

* **接口简单全面**：实现播放接口简单，可快速实现播放。

* **兼容性**：目前主要支持PC上Chrome，Firefox，Microsoft Edge等主流浏览器，移动端只有Android Chrome支持。

* **渲染类型**：支持普通2D视频点播直播。



## Demo展示
链接地址：https://rs1-pv.vrviu.com/h5/v1.3/index.html 


## 导入SDK
### 1. 开发准备
下载最新的VRVIU_AltPlayer.min.js以及VRVIU_AltPlayer.min.css

### 2. 导入SDK
##### 2.1 新建Html文件导入js-sdk以及css文件
```html
<!DOCTYPE html>
<html lang="en">
<head>
        <meta charset="utf-8">
        <title></title>
        <meta name="description">
        <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
        <meta name="apple-touch-fullscreen" content="yes">
        <meta name="x5-fullscreen" content="true">
        <meta name="x5-page-mode" content="app">  
        <meta name="full-screen" content="yes">
        <meta name="format-detection" content="telephone=no">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
        <title></title>
        <link rel="stylesheet" href="./dest/ready/css/VRVIU_AltPlayer.min.css">
        <script src="./dest/ready/js/VRVIU_AltPlayer.min.js"></script>
</head>
<body>

</body>
</html>
```

##### 2.2 配置工程权限
引入新建js文件配置相关参数及权限

```javascript
<script src="./dest/ready/js/AltPlayer_Configure.min.js"></script>

//AltPlayer_Configure.min.js

new VRVIU_AltPlayer({
        url:"https://img.vrviu.com/static/media/VRVIU_AltPlayer_Demo.flv",
        AppId :'vrviu_altsdk',
        AccessKeyId :'730c029686b86a332facca0bb1a9f53a',
        BizId :'altsdk_web_demo',
        AccessKeySecret:"14d90ef1ee2be9f6c3469f46e2a3e566",
        isLive:false
})
```




## 配置参数表
 |参数|说明|是否必填|类型|
 |:---|:---|:---|:---|
 |url|需要播放的视频或者直播流地址|必填|String|
 |isLive|播放的是否是直播|必填|Boolean|
 |AppId|分配给用户的ID，可通过 www.vrviu.com 填写表单或者联系客服申请|必填|String|
 |AppId|分配给用户的ID，可通过 www.vrviu.com 填写表单或者联系客服申请|必填|String|
 |AccessKeyId|分配给用户的ID，可通过 www.vrviu.com 填写表单或者联系客服申请|必填|String|
 |BizId|分配给用户的ID，可通过 www.vrviu.com 填写表单或者联系客服申请|必填|String|
 |AccessKeySecret|分配给用户的ID，可通过 www.vrviu.com 填写表单或者联系客服申请|必填|String

## 商务合作
电话：0755-86960615

邮箱：business@vrviu.com

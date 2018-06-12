# cordova-sharesdk-demo

### 概述

此demo在[cordova-sharesdk-demo](https://github.com/zhaolin0801/cordova-sharesdk-demo.git) 基础上添加微信，微博，QQ平台的客户端授权登录功能，目前插件仅支持android和ios平台。

### 配置

1. 创建平台

   ```
   cd ~/yourpath/cordova-sharesdk-demo
   cordova platform add ios android
   ```

2. 添加cordova-plugin-sharesdk插件

   ```
   cordova plugin add cordova-plugin-sharesdk --variable SHARESDK_ANDROID_APP_KEY=xxxx --variable SHARESDK_IOS_APP_KEY=xxxx --variable WECHAT_APP_ID=xxxx --variable WECHAT_APP_SECRET=xxxx --variable WEIBO_APP_ID=xxxx --variable WEIBO_APP_SECRET=xxxx --variable WEIBO_REDIRECT_URL=http://xxxx --variable QQ_IOS_APP_ID=xxxx --variable QQ_IOS_APP_HEX_ID=xxxx --variable QQ_IOS_APP_KEY=xxxx
   ```
   
为了方便大家查看demo，可使用以下值代入上述对应的xxxx。如果无法使用，请自行重新申请。

```
SHARESDK_ANDROID_APP_KEY: 1ae3baffc4bd0
SHARESDK_IOS_APP_KEY: 1ae3afb94daf0
WECHAT_APP_ID: wx956a3cabf7faf4bf
WECHAT_APP_SECRET: 8bd89564a1d0c35443c1d019073a6982
WEIBO_APP_ID: 568898243
WEIBO_APP_SECRET: 38a4f8204cc784f81f9f0daaf31e02e3
WEIBO_REDIRECT_URL: http://www.sharesdk.cn
QQ_ANDROID_APP_ID: 100371282
QQ_ANDROID_APP_KEY: aed9b0303e3ed1e27bae87c33761161d
QQ_IOS_APP_ID: 100371282
QQ_IOS_APP_HEX_ID: 05FB8B52
QQ_IOS_APP_KEY: aed9b0303e3ed1e27bae87c33761161d
```

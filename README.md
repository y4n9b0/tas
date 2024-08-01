# tas
Tencent auth &amp; share, include QQ &amp; WeChat

## WeChat
官网：[微信开放平台](https://developers.weixin.qq.com/doc/oplatform/Mobile_App/Access_Guide/Android.html)

添加 maven 仓库
```groovy
buildscript {
    repositories {
        mavenCentral()
    }
}
```

引入依赖
```groovy
dependencies {
    api 'com.tencent.mm.opensdk:wechat-sdk-android:6.8.28'
}
```

## QQ
官网：[QQ 互联](https://wiki.connect.qq.com/)

QQ 不提供在线依赖，需要手动下载 jar 包
[SDK 下载](https://wiki.connect.qq.com/sdk%e4%b8%8b%e8%bd%bd)
# daniuPlayerLicense
大牛播放模块（daniuPlayer）授权配套模块

联系大牛商务，获取授权后的iOS和Android双平台的sdk包。

Android：

1、将Android的sdk提供的arm64-v8a和armeabi下的“libSmartPlayer.so”文件替换到/zip/android/daniuPlayerLicense/target对应目录下。

2、同时将armeabi下面的文件复制一份到target根目录下。

3.将/zip/android/daniuPlayerLicense文件夹压缩为daniuPlayerLicense.zip。

4.以上就制作好了安卓的授权模块包。

iOS：

1、将iOS的sdk提供的“libSmartPlayerSDK.a”文件复制到/zip/ios/daniuPlayerLicense/target目录下。

2、将/zip/ios/daniuPlayerLicense文件夹压缩为daniuPlayerLicense.zip。

3.以上就制作好了iOS的授权模块包。


#本配套模块的的App授权应用名称如下：

Android：SmartPlayerSDKDemo

iOS：自定义loader  （使用Apicloud默认证书时）

备注：需要你在Apicloud的“云编译”设置“应用名称”。如果你iOS有自己的证书，必须设置应用名称为以上对应名称。
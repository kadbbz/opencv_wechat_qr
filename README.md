# opencv_wechat_qr

armeabi_v7a,arm64_v8a,x86,x84_64 so全部修复

so lib work on armeabi_v7a,arm64_v8a,x86,x84_64 work well


最强二维码扫码识别引擎诞diy...

Best qr scan function from opencv & wechat...

移植微信二维码扫码功能到Android上

Complile WeChat Qr Scan engine with Android


请使用Master 分支
Please use master branch

文章链接
https://blog.csdn.net/wang382758656/article/details/114762661

[演示apk下载](https://github.com/woshiwzy/opencv_wechat_qr/blob/master/qrdemo-release.apk)

新版本的Android Studio 导入项目可能导致so加载错误，建议arm64-v8a下的包用(if_error_use_this_lib)libopencv_java4.so替代之前的
for unkown reason new android studio version will cause so link error please use (if_error_use_this_lib)libopencv_java4.so repalce before so under folder arm64-v8a

效果

![image](./demo.png)
![image](./hc.png)
![image](./vc.png)

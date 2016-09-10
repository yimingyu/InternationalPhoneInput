# InternationalPhoneInput
类似微信注册时的国际手机号输入控件

![image](https://github.com/yimingyu/InternationalPhoneInput/blob/master/ScreenShots/Screenshot_2016-09-10-20-53-15.png)
![image](https://github.com/yimingyu/InternationalPhoneInput/blob/master/ScreenShots/Screenshot_2016-09-10-20-52-29.png)


图片资源和部分代码参考了 [IntlPhoneInput](https://github.com/AlmogBaku/IntlPhoneInput)

主要修改：
1、修复了IntlPhoneInput中初始时如果获取到手机号则功能失常的Bug。
2、选择国家和区号的形式从原IntlPhoneInput中Spinner改成Activity,实现方法是在View的onAttachedToWindow方法中注册广播接收器接收CountrySelectorActivity发送的结果。






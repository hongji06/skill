# wtm学习笔记

## wtm swagger集成开启

> 方法一：StartUp.cs 找到Configure，在app.UseWtmSwagger()中传入一个参数false，即app.UseWtmSwagger(false)
> 方法二：appsettings.json中将IsQuickDebug设置为true

## 多语系问题

> wtmplus vue3 进到主页的时候切换多语言是正常，点进菜单后再切换多语言就不会在右上角切换语系显示。

![](./images/i18n_swicth_bug.gif)
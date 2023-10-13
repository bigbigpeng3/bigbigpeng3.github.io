# 一日一技[01] iOS Android如何去广告？




## 为什么要去广告？



手机每天打开App就是开屏广告，白白浪费人生中的几秒钟时间。进入App后还有海量广告内容等你来发现。什么？你不想看？App可不是你开发的哦。

{{< admonition tip "为什么你们要去广告?" >}}

还有同学为大公司考虑的，比如你们都把广告去掉了。没有人点击广告了，公司不盈利了，App就会下架啊。本篇文章只讨论具体的技术实现。

{{< /admonition >}}

{{< admonition note "去广告的方式持久问题。" >}}

去广告的方式方法随时都有可能失效。因为大家都是凭爱好在开源。写去广告的规则是没有收入的。大家如果觉得有条件的可以支持一些开源的项目。

{{< /admonition >}}

## 1 iOS去广告

### 1.1 iOS 网络模式去广告

目前来说Quantumult X 是比较流行的科学App。同时它也可以添加自定义规则。而且网络上去广告的资料更多。

一些关于iOS去广告的链接：

[V2ex ios 有类似李跳跳的 软件吗,就是启动广告自动跳过的](https://www.v2ex.com/t/934331)

[V2ex iOS 屏蔽开屏广告，除了卸载 APP，圈 X 是最优解了吗？](https://www.v2ex.com/t/943662)

#### 1.1.1 Quantumult X

Quantumult X 是 iOS 系统即苹果手机系统下的代理软件客户端，功能强大且支持多种代理协议。

##### 首先，你需要一个美区ID

网络上很多了，我就不献丑了。

[注册美区ID](https://zhuanlan.zhihu.com/p/367821925?dt_dapp=1 )

注册成功后，在App store上登录美区ID，注意是 ***App store***。不是iCould。

##### 其次，如何下载Quantumult X？

在美区的App store直接搜索 Quantumult X即可。7.99刀。

如果你遇到了充值问题。可以通过咸鱼找找答案。

也可以通过支付宝购买美区store的礼品卡。

[App Store美区用支付宝购买礼品卡教程](https://zhuanlan.zhihu.com/p/591446073)

这里有一篇文章写的很好，里面包含了如何科学。如果你有机场链接是最好的了。

[Quantumult X 新手教程](https://www.evan888.top/1990/)

##### 最后，如何去广告？

新手先看这个视频，里面有比较完整的新手教程。

[Quantumult X 去广告规则和京东签到，圈x使用教程](https://www.youtube.com/watch?v=bW7DxHsMzdI&list=LL&index=1&pp=gAQBiAQB)

然后是规则问题，这里推荐两个：

[毒奶自用，懒人配置文件（Quantumult X）：去广告分流规则、Tiktok解锁重写、VSCO解锁、神机分流、blackmatrix7分流规则。](https://github.com/limbopro/Profiles4limbo)



[墨鱼规则](https://github.com/ddgksf2013)



### 1.2 iOS 无障碍/自动点击去广告 

{{< admonition note "无" >}}

暂时没有(也许是我不知道) 非越狱可用的软件/方法。

{{< /admonition >}}

## 2 Android去广告

### Android 网络模式去广告



Adguard

https://adguard.com/en/adguard-android/overview.html



### Android 无障碍/自动点击去广告 

李跳跳(已被xx大公司告上了法庭) ，动手能力强的可以自己找找最后的2.2正式版。

另一个是开源项目。

https://github.com/gkd-kit/gkd

贴一个官方的下载链接

[蓝奏云](https://lisonge.lanzouy.com/b06e1zoef) 密码: gkd



## 3 软路由

{{< admonition note "关于软路由" >}}

优点：配置好后，全家的设备都可以享用。

缺点：无法适应移动设备的需求。在家以外就没有办法使用了。更适合家里的电脑，电视机，等等，不需要移动的。另外就是配置不好会影响整个家庭的网络，会引起家人的愤怒，不建议在不稳定的情况搭建。

{{< /admonition >}}

因为我对软路由研究不够透彻，各位同学自己找找方案吧。







---
description: 通过VMware Workstation
coverY: 0
---

# 在PC上安装macOS虚拟机

## 开始之前

您可以参阅[其他人的教程](http://mp.weixin.qq.com/s?\_\_biz=MzIxOTE5MDY5Mw==\&mid=2650891941\&idx=1\&sn=a0e3624fdc8aaaeb0e0053f7d7e62a86\&chksm=8c2ac26fbb5d4b79a30163c2c3c4a50694dd224f1dd576cbb0f91e3d39c41b20fbb64f0bd8b9\&scene=21#wechat\_redirect)，因笔者水平有限，您目前正在阅读的这篇教程可能有纰漏之处。

您可以前往[这个链接](https://www.123pan.com/s/0pMUVv-892x)（在下文也有给出）找到所需的macOS镜像。

## 环境准备

安装前打开任务管理器查看是否开启虚拟化。如果虚拟化未启用，需要在BIOS界面设置。如果是笔记本用户请查询你的笔记本型号；主机用户百度主板型号。

<figure><img src=".gitbook/assets/1.png" alt=""><figcaption></figcaption></figure>

## 安装VMware Workstation并解锁

VMware Workstation Pro 16安装包点击[这个链接](https://download3.vmware.com/software/wkst/file/VMware-workstation-full-16.0.0-16894299.exe)即可下载（官方链接，请放心下载）。

运行下载得到的安装包。经过一段时间后，您会看到这个窗口：

<figure><img src=".gitbook/assets/vmw install.png" alt=""><figcaption></figcaption></figure>

点击“下一步”，您需要阅读并同意VMware的EULA。

建议您阅读并同意后，勾选“我接受许可协议中的条款”，点击“下一步”。

<figure><img src=".gitbook/assets/Eula.png" alt=""><figcaption></figcaption></figure>

安装过程基本就是一直下一步，最后结束的时候输入密钥。

![](<.gitbook/assets/diy install.png>)  这页不需要额外设置。

![](.gitbook/assets/exp.png)   建议取消勾选两个复选框（分别点击两个带对勾的方框）。

![](<.gitbook/assets/quick (1).png>)  这页不需要额外设置。

![](.gitbook/assets/preped.png)  现在您可以点击“安装”开始安装VMware Workstation。

![](.gitbook/assets/install.png)  等待安装进度完成。

![](.gitbook/assets/lisence.png)  安装进度完成后，点击“许可证”来输入许可证。

因版权等问题，关于安装包、密钥的其他事项请查阅[这个链接](https://www.ssymon.com/archives/vmware-download-key)。

盗版软件是一种<mark style="color:red;">**非法行为**</mark>。

**《中华人民共和国刑法修正案（十一）》**规定：

**以营利为目的**，有下列侵犯著作权或者与著作权有关的权利的情形之一，违法所得数额较大或者有其他严重情节的，处三年以下有期徒刑，并处或者单处罚金；违法所得数额巨大或者有其他特别严重情节的，处三年以上十年以下有期徒刑，并处罚金：

（一）未经著作权人许可，复制发行、通过信息网络向公众传播其文字作品、音乐、美术、视听作品、计算机软件及法律、行政法规规定的其他作品的；

（二）出版他人享有专有出版权的图书的；

（三）未经录音录像制作者许可，复制发行、通过信息网络向公众传播其制作的录音录像的；

（四）未经表演者许可，复制发行录有其表演的录音录像制品，或者通过信息网络向公众传播其表演的；

&#x20;（五）制作、出售假冒他人署名的美术作品的；

（六）未经著作权人或者与著作权有关的权利人许可，故意避开或者破坏权利人为其作品、录音录像制品等采取的保护著作权或者与著作权有关的权利的技术措施的。

如果您

值得一提的是，VMware Inc. 对于个人用户的盗版行为持睁一只眼闭一只眼的态度。

![](<.gitbook/assets/input lis.png>)

![](.gitbook/assets/success.png)



## 解锁安装macOS

VMware Workstation 原生不支持安装macOS，需要使用其他程序解锁这个限制。

本次解锁使用的工具为GitHub上的 unlocker:[ https://github.com/DrDonk/unlocker/releases](https://github.com/DrDonk/unlocker/releases)

如果您不会使用Github，或上方链接不能下载，请点击[这个链接](https://www.123pan.com/s/0pMUVv-092x)（123云盘）来下载。

解锁前请先去任务管理器关闭VMware程序，同时在服务中关闭所有vm开头的服务（解锁完成后请再打开）。

<figure><img src=".gitbook/assets/2.png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/3.jpg" alt=""><figcaption><p>关闭VM开头的服务</p></figcaption></figure>

解锁压缩包之后, windows文件夹 -> 以管理员权限运行 unlock -> 任意键关闭

解锁不成功的可以尝试另一个解锁工具: [https://github.com/paolo-projects/unlocker](https://github.com/paolo-projects/unlocker)



## 在VMware Workstation中安装macOS

<mark style="color:red;">**不要下载下面这个文件！这个文件似乎不能在VMware Workstation中正常引导；未来我们会另制作一个正常的ISO文件。**</mark>

~~请前往这个链接下载macOS Mojave的可引导镜像文件(Bootable ISO)。~~这个文件是由Apple Inc.官方工具生成的，没有对Apple的文件进行修改，不侵犯Apple Inc.的版权。

#### 致歉

这个ISO文件是笔者从可引导的U盘制作的镜像。令人感到疑惑的是，U盘可以在电脑上正常引导，而ISO文件则不能在workstation上引导，却可以在Fusion（Mac上的vmware虚拟机平台）上引导。笔者使用的是Mac和Fusion，因此并未发现这个问题。在此笔者向各位读者致歉。



如果您不知道什么是`可引导镜像文件`，请查阅：[什么是macOS苹果系统引导版镜像?](https://www.loveswo.com/53.html)

如果您质疑为什么使用macOS Mojave，请查阅：[MacOS的Mojave和Catalina有什么不同的体验？](https://www.zhihu.com/question/349685707)

（还没写完）


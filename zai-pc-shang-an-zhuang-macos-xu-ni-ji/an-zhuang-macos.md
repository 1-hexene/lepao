---
description: 在VMware Workstation中
---

# 安装macOS

{% hint style="info" %}
在虚拟机内，macOS的性能有一定的折损。

因此，卡顿是正常的现象，尤其是当您的电脑本身性能较弱时。
{% endhint %}

现在，您应该能看到Apple的标志，如下方模拟图片绘制的。

<figure><img src="../.gitbook/assets/LOAD-MACOS.png" alt=""><figcaption></figcaption></figure>

等待虚拟机开机，您会看到如下画面：

此时，如果您希望使用简体中文，请选择“简体中文”，然后点击下方的箭头。

<figure><img src="../.gitbook/assets/choose-LANG.PNG" alt=""><figcaption></figcaption></figure>

您会看到如下画面。此时，请您点击“磁盘工具”，然后点击“macOS实用工具”窗口右下角的“继续”。

<figure><img src="../.gitbook/assets/DISKUTIL.PNG" alt=""><figcaption></figcaption></figure>

您会看到如下画面。

您需要点击macOS中窗口的左边栏（在下文中，如果没有特殊说明，边栏、顶栏等一概指的是macOS中的）内的“VMware Virtual SATA...”驱动器，再点击窗口顶栏中的“抹掉”图标。

<figure><img src="../.gitbook/assets/SELECT-VIRTUAL-DISK.PNG" alt=""><figcaption></figcaption></figure>

如果您没有看见上述的“VMware Virtual SATA...”驱动器，请点击窗口左上角的“显示”图标，然后在下拉菜单中点击“显示所有设备”，如下图所示。

<figure><img src="../.gitbook/assets/SHOW-ALL-DEV.PNG" alt=""><figcaption></figcaption></figure>

点击“抹掉”后，您会看到如图所示的窗口：

<figure><img src="../.gitbook/assets/CLEAR-DISK.PNG" alt=""><figcaption></figcaption></figure>

请点击“格式”下拉菜单，将其更改为“APFS”，如下图所示。

<figure><img src="../.gitbook/assets/SELECT-APFS.PNG" alt=""><figcaption></figcaption></figure>

值得一提的是，如果您如笔者一样有强迫症，那么建议您在“名称”栏填入“Macintosh HD”。这个名称不会给电脑带来任何性能提升，但是“Macintosh HD”是每一台苹果电脑出场时默认的硬盘名称。

{% hint style="warning" %}
请不要修改“方案”一栏，否则会导致您的虚拟机无法启动。
{% endhint %}

<figure><img src="../.gitbook/assets/RENAME-DISK.PNG" alt=""><figcaption></figcaption></figure>

显示“抹掉进程结束”后，点击“完成”。

<figure><img src="../.gitbook/assets/CLEAR-COMPLETE.PNG" alt=""><figcaption></figcaption></figure>

现在您会看到这块硬盘已经被格式化为APFS分区系统。

<figure><img src="../.gitbook/assets/CLEAR-COMPLETE-2.PNG" alt=""><figcaption></figcaption></figure>

点击窗口左上角的红色圆圈，关闭“磁盘工具”。您会回到“macOS实用工具”窗口。此时，请您点击“安装macOS”，然后点击“macOS实用工具”窗口右下角的“继续”。

<figure><img src="../.gitbook/assets/SELECT-INSTALLER.PNG" alt=""><figcaption></figcaption></figure>

短暂加载后，您会看到如图窗口。请点击“继续”上方的箭头。

<figure><img src="../.gitbook/assets/OSX-INSTALLER-0.PNG" alt=""><figcaption></figcaption></figure>

如图所示是macOS的EULA。请务必阅读并同意，然后点击“同意”。

{% hint style="info" %}
EULA的第一行指出，macOS Mojave供在Apple品牌系统上使用，因此在Windows上安装macOS违反了Apple Inc. 的EULA。

以下的图片均为模拟绘制，而非实际的截图。
{% endhint %}

<figure><img src="../.gitbook/assets/OSX-INSTALLER-1.PNG" alt=""><figcaption></figcaption></figure>

此时，安装程序会询问您选择安装到哪个分区。请按图片中的顺序点击。

<figure><img src="../.gitbook/assets/OSX-INSTALLER-3.PNG" alt=""><figcaption></figcaption></figure>

此时，macOS开始安装。请您等待。安装完成后，虚拟机会自动重新启动来进行下一阶段的安装。

<figure><img src="../.gitbook/assets/OSX-INSTALLER-4.PNG" alt=""><figcaption></figcaption></figure>

重启后，您会看到如下画面。请您耐心等待，不要关闭虚拟机的电源，关闭电源会导致安装失败。

<figure><img src="../.gitbook/assets/OOBE-INSTALL.PNG" alt=""><figcaption></figcaption></figure>

值得一提的是，macOS中的“剩余大约一分钟”往往是不准确的，您可能要等待数倍于一分钟的时间。这时如果进度条没有变化，死机的可能性并不大。建议您不要尝试关闭虚拟机的电源或强制重启。

<figure><img src="../.gitbook/assets/last-1min.PNG" alt=""><figcaption></figcaption></figure>

进度完成后，虚拟机将自动重启，macOS开机时会有一个进度条。进度条走完就会开机。

这一次开机时，进度条走完后会进入系统首次设置环节。

<figure><img src="../.gitbook/assets/reboot-TO-SYSTEM.PNG" alt=""><figcaption></figcaption></figure>

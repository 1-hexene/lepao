# macOS的首次使用设置

## 设置macOS

如果您看到了如下界面，那么恭喜您，您已经完成了macOS安装的大部分，现在已经到了最后一步。

<figure><img src="../.gitbook/assets/welcome-to-macos.PNG" alt=""><figcaption></figcaption></figure>

如果您希望将国家设置为中国大陆，那么请您将国家菜单下拉至底部，中国大陆在菜单的最后一位。

点击“继续”，您需要设置键盘和输入法。设置好输入法后，请点击“继续”。

<figure><img src="../.gitbook/assets/keyboard.PNG" alt=""><figcaption></figcaption></figure>

此时您会看到“数据与隐私”界面。这页不需要设置，阅读完成后点击继续即可。

<figure><img src="../.gitbook/assets/osx-privacy.PNG" alt=""><figcaption></figcaption></figure>

在接下来的页面中，请选择“现在不传输任何信息”，然后点击“继续”。选择其他任何选项均可能会导致死机。

<figure><img src="../.gitbook/assets/transport-to-this-mac.PNG" alt=""><figcaption></figcaption></figure>

此时会提示您使用Apple ID登录。笔者强烈建议您选择“稍后设置”，如图所示。因为在一台虚拟机上登录您的Apple ID有一定会导致您的Apple ID被Apple Inc. 认为是黑苹果用户而拉黑。

<figure><img src="../.gitbook/assets/later-use-apple-id.PNG" alt=""><figcaption></figcaption></figure>

接下来，请您阅读并同意软件许可协议。

<figure><img src="../.gitbook/assets/osx-items.PNG" alt=""><figcaption></figcaption></figure>

接下来，您需要创建一个电脑账户。笔者建议您使用一个弱密码，例如1234。这种环境下的虚拟机遭到入侵的概率极低，使用易记的密码能大大减少您输入密码的时间。

<figure><img src="../.gitbook/assets/osx-account.PNG" alt=""><figcaption></figcaption></figure>

接下来的“快捷设置”页面中，建议您点击“自定设置”，来禁用Apple对这台电脑的数据分析。

如果您点击“继续”，则会一步跳转到最后一步设置。

<figure><img src="../.gitbook/assets/quick-settings.PNG" alt=""><figcaption></figcaption></figure>

建议您取消勾选定位服务（默认情况下，macOS并没有勾选）。

<figure><img src="../.gitbook/assets/osx-location (1).PNG" alt=""><figcaption></figcaption></figure>

您需要选择时区。点击上方的地图可以粗略选择您的时区，再点击下拉菜单可以精确选择最接近的城市。

<figure><img src="../.gitbook/assets/osx-time-zone.PNG" alt=""><figcaption></figcaption></figure>

接下来您会看到“分析”页面。笔者建议您取消勾选共享分析。

<figure><img src="../.gitbook/assets/osx-analytics.PNG" alt=""><figcaption></figcaption></figure>

接下来，请您选择深色或浅色外观，然后点击“继续”。

<figure><img src="../.gitbook/assets/osx-appearance.PNG" alt=""><figcaption></figcaption></figure>

值得一提的是，我们使用的macOS Mojave并没有根据时间自动调整深色浅色外观的功能。这个功能在Mojave之后的版本Catalina（10.15）中推出了。

<figure><img src="../.gitbook/assets/osx-adidas.PNG" alt=""><figcaption></figcaption></figure>

点击继续后，macOS将进行设置，之后会直接进入桌面。

<figure><img src="../.gitbook/assets/osx-desktop.PNG" alt=""><figcaption></figcaption></figure>

## 安装VMware Tools

此时，请您点击VMware Workstation界面下方的黄色条内的“安装Tools”按钮。

如果您没有看见这个黄色条，请您VMware Workstation菜单栏中的“虚拟机”，然后点击下拉菜单中的“安装VMware Tools”。

<figure><img src="../.gitbook/assets/install-vmware-tools.PNG" alt=""><figcaption></figcaption></figure>

如果出现下图提示，则您需要将macOS安装光盘弹出。

![](../.gitbook/assets/cannot-inject.PNG)

请您按住macOS内的光盘标志，然后将其拖动到“废纸篓”上，如下图所示：

<figure><img src="../.gitbook/assets/动画.gif" alt=""><figcaption></figcaption></figure>

现在，请您再次点击“安装VMware Tools”，就可以进行安装了。

请稍等一会，macOS内会自动弹出Tools的安装程序，如下图所示。


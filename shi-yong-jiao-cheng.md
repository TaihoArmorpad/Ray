# 配置教程

{% hint style="info" %}
[点此查看Android设备视频教程](http://v2ray.taihowaifu.top/Android.mp4)
{% endhint %}

{% hint style="info" %}
[点此查看Windows设备视频教程](http://v2ray.taihowaifu.top/Windows.mp4)
{% endhint %}

{% tabs %}
{% tab title="节点选择" %}
我需要访问Youtube,Google,Twitter等网站：使用**洛杉矶**节点。

我需要访问公主链接,DMM等日本应用：使用**东京**节点。

我需要访问公主链接,DMM等日本应用，但东京节点无法连接：使用**东京绕行**节点。
{% endtab %}

{% tab title="洛杉矶" %}
| 配置名称 | 输入内容 |
| :--- | :--- |
| 服务器地址 | la.taihowaifu.top |
| 端口 | 443 |
| 用户ID | 参见"获取我的用户ID" |
| 额外ID | 233 |
| 加密方式 | aes-128-gcm |
| 传输协议 | kcp |
| 别名 | 洛杉矶\(也可自定\) |
| 伪装类型 | none |
| 伪装域名 | \(留空\) |
| 路径 | \(留空\) |
| 底层传输安全 | \(留空\) |
{% endtab %}

{% tab title="东京" %}
| 配置名称 | 输入内容 |
| :--- | :--- |
| 服务器地址 | tokyo.taihowaifu.top |
| 端口 | 443 |
| 用户ID | 参见"获取我的用户ID" |
| 额外ID | 233 |
| 加密方式 | aes-128-gcm |
| 传输协议 | kcp |
| 别名 | 东京\(也可自定\) |
| 伪装类型 | none |
| 伪装域名 | \(留空\) |
| 路径 | \(留空\) |
| 底层传输安全 | \(留空\) |
{% endtab %}

{% tab title="东京绕行" %}
**除非迫不得已，您不应使用东京绕行节点。**

**东京绕行节点拥有最糟糕的延迟、网络速度和连接稳定性。**

| **配置名称** | 输入内容 |
| :--- | :--- |
| 服务器地址 | tokyobypass.taihowaifu.top |
| 端口 | 445 |
| 用户ID | 参见"获取我的用户ID" |
| 额外ID | 233 |
| 加密方式 | aes-128-gcm |
| 传输协议 | kcp |
| 别名 | 东京绕行\(也可自定\) |
| 伪装类型 | none |
| 伪装域名 | \(留空\) |
| 路径 | \(留空\) |
| 底层传输安全 | \(留空\) |
{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="获取我的用户ID" %}
{% hint style="info" %}
[点此获取用户ID](http://v2ray.taihowaifu.top/)
{% endhint %}

您需要在"QQ号码"一栏中输入您的QQ号码。

您还需要在"密码"一栏中输入您购买服务时预留的密码。

无论如何，请不要与他人共享您的用户名、密码及用户ID，这将给服务器带来更大负担和更大风险。然而，我们欢迎您向更多用户推荐购买本服务。
{% endtab %}

{% tab title="安装文件" %}
{% hint style="info" %}
[点此获得Android应用](http://v2ray.taihowaifu.top/V2ray.apk)
{% endhint %}

{% hint style="info" %}
[点此获得Windows程序](http://v2ray.taihowaifu.top/V2ray.zip)
{% endhint %}

{% hint style="info" %}
[点此获得MacOS程序](http://v2ray.taihowaifu.top/V2rayX.app.zip)
{% endhint %}

{% hint style="info" %}
[点此下载iOS安装文件](http://v2ray.taihowaifu.top/Shadowrocket.ipa)后使用 [爱思助手](https://www.i4.cn/) 导入
{% endhint %}
{% endtab %}

{% tab title="绕行规则：直连的Domain或IP" %}
`valve.com,steampowered.com,aliyun.com,windowsupdate.com,origin.com,ubisoft.com`
{% endtab %}
{% endtabs %}




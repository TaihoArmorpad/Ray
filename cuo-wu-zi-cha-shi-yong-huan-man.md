# 错误自查-使用缓慢

当遇到使用问题时，您应先按照本页进行自查。如遇到无法解决的问题，请跳至"技术支持"页。

请按照本页面提供的自查步骤依次操作。对不同的问题，相同操作的优先级不同。

## 〇、自查须知

在按照本文档进行自查前，您需要知道：

* 服务不能达到您本地网络速度最高值是正常现象，这是因为ISP的出口策略各不相同。

只有在出现下述情况之一时，您才应该按照本文档操作：

* 您可以连接并使用本服务，如访问 [Google](https://www.google.com/)
* 速度过慢导致无法正常使用
* 曾经速度正常，突然变慢到不可接受的程度
* 无法访问某特定网站
* 服务出现奇怪的卡顿且严重影响使用体验

## 一、本地网络初筛

您应先检查您的设备是否可以**正常连接互联网**。

* [ ] 访问您确定在线的国内测速网站，如 [测速网](http://www.speedtest.cn/) 。

### `如果速度低于通常值...`

`您应立即排查本地网络情况，如局域网内是否有高用量用户等，并联系您的网络服务商提供技术支持。`

## 二、定位问题

在确定可以正常连接互联网后，您应找出问题类型。

* [ ] 访问下述网站并测试速度，它们都很**慢**吗？ [Speedtest](https://www.speedtest.net/)、[Fast](https://fast.com/)、[Google](https://www.google.com/search?q=Google+Logo&source=lnms&tbm=isch&sa=X&ved=0ahUKEwiUlOD5xb3gAhWP_lQKHTu0DGMQ_AUIDigB&biw=1920&bih=1007)、[Youtube](https://www.youtube.com/)。

`是：继续  |  否：`[`三、特定网站`](http://ray.taihowaifu.top/ray/cuo-wu-zi-cha-shi-yong-huan-man#san-te-ding-wang-zhan)\`\`

* [ ] 网速**波动**是否严重？如 50Mbps → 10Mbps → 1Mbps → 50Mbps
* [ ] 访问多图网站时偶尔像掉线一样**无法加载**，刷新后恢复正常？
* [ ] 下载大文件时提示"**下载错误**"？

`是：`[`四、断流`](http://ray.taihowaifu.top/ray/cuo-wu-zi-cha-shi-yong-huan-man#si-duan-liu)  `|  否：继续`

* [ ] 在每天的**特定时间**前后\(如22:00\)固定出现缓慢问题？
* [ ] 缓慢时的网速是否**相对稳定**？如保持在1Mbps

`是：`[`五、QoS`](http://ray.taihowaifu.top/ray/cuo-wu-zi-cha-shi-yong-huan-man#wu-qos)  `|  否：`[`六、其它问题`](http://ray.taihowaifu.top/ray/cuo-wu-zi-cha-shi-yong-huan-man#liu-qi-ta-wen-ti)\`\`

## 三、特定网站

首先，您应确保该网站没有遇到技术问题且可以正常访问。

您需要知道：

* 本服务可"加速"的网站受**地区限制**，例如洛杉矶节点可能不擅长加速台湾网站。
* 本服务并非为加速网络游戏而优化，加速体验可能**差**于直连。
* 本服务并非为访问地区限制网站而优化，可能无法访问某些**特殊网站**。

您可以尝试：

* [ ] 更换节点\(除东京绕行\)
* [ ] 更改本地网络环境，例如从Wi-Fi切换到4G
* [ ] 将该网站域名添加到 代理规则 中
* [ ] 修改[DNS](http://ray.taihowaifu.top/ray/wen-yu-da#dns-shi-shen-me-wo-wei-shen-me-yao-xiu-gai-ta)
* [ ] 等待数分钟后重试

## 四、断流

针对断流，用户能做的不多，但您依然可以尝试：

* [ ] 更改本地网络环境，例如从Wi-Fi切换到4G
* [ ] 修改[DNS](http://ray.taihowaifu.top/ray/wen-yu-da#dns-shi-shen-me-wo-wei-shen-me-yao-xiu-gai-ta)
* [ ] 更换节点\(除东京绕行\)
* [ ] 重启路由器与调制解调器

## 五、QoS

{% hint style="info" %}
[QoS是什么？](http://ray.taihowaifu.top/ray/wen-yu-da#qos-shi-shen-me-ta-dui-wo-you-na-xie-ying-xiang)
{% endhint %}

针对QoS，用户能做的不多，而且QoS通常伴随断流，但您依然可以尝试：

* [ ] 更改本地网络环境，例如从Wi-Fi切换到4G
* [ ] 修改[DNS](http://ray.taihowaifu.top/ray/wen-yu-da#dns-shi-shen-me-wo-wei-shen-me-yao-xiu-gai-ta)
* [ ] 更换节点\(除东京绕行\)
* [ ] 重启路由器与调制解调器

## 六、其它问题

您可能遇到了罕见问题，您应立即提交技术支持并按照页面格式输入您遇到的问题。


# 适用于三星 Galaxy 5G 移动 Wi-Fi SCR01 (SM-H412J)

## 参考链接：

1. XDA Forum Support:<a href="https://forum.xda-developers.com/t/please-help-me-to-get-5g-connection-on-galaxy-5g-mobile-wi-fi-scr01.4469827/">点击跳转</a>
2. Compiled OTA Updates:<a href="https://app.box.com/s/hn55vxnurdkvg6zlu8r2nixwhl7f0dg7">点击跳转</a>
3. Device Update Changelog:<a href="https://doc.samsungmobile.com/SCR01/KDI/doc.html">点击跳转</a>

## 完整的设备规格：

> **CPU: **MediaTek Dimensity 720 (MT6853)
>
> **Android系统:**Android 11 with OneUI 3.0 (w/o Google Play Services)
>
> **运行内存:**2.5GB RAM
>
> **存储:** 32GB Internal Storage
>
> **WiFi协议:**WiFi 5 (802.11ac)
>
> **电池容量:**5000mAH Battery
>
> **屏幕**:5.3" (1480x720) LCD Display
>
> **网络频段Network bands:**
>
> 5G: n28 / n41 / n77 / n78  *(电信联通的N78,海外地N77,移动N41,广电N28)*
>
> 4G: LTE FDD: B1 / B3 / B17 / B18 TDD: B41 *(B1电信B3联通,B1/3移动广电)*
>
> 可解锁频段Disabled Bands that can be enabled:
>
> 4G: B7 / B38

## 一些解锁

```
Enable 4G Band B7 & B38启用4G锁定频段
1. 进入“服务模式”
2. 点击“UE 设置和信息>设置>协议>AS>下一页>美国 LTE B7 和 B38 设置>”。
	2.1. 在“LTE B7 和 B38 设置”上，点击“在美国启用 LTE B7B38”
	2.2. 将显示一条消息“功能应用成功，请重新启动”。
	2.3. 重新启动以应用设置。
```

```
How to Band Lock锁定频段
1. 进入“服务模式”
2. 点按“UE 设置和信息>设置>协议>NAS>网络控制>频段选择>频段选择 SIM 1”。
3. 到达那里后，您可以进入“LTE 频段首选项”和“NR 频段首选项”并选择您本地可用的网络频段。
```

```
为非日本运营商解锁 5G 模式
1. 进入“服务模式”
2. 点击“UE设置和信息>设置>协议>NR”。
	2.1. 在“NR 配置”上，首先点击“允许列表控制”，然后点击“允许列表关闭”。 将显示一条消息“应用成功”，然后返回“NR 配置”。
	2.2. 返回“NR 配置”，点击“NR5G/NSA 模式控制”并点击“SA/NSA 启用”。 将显示一条消息“功能应用成功，请重新启动”。
	2.3. 重新启动以应用设置。
```


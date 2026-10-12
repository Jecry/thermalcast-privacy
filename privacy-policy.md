# 飞伞天气 隐私政策

**最后更新：2026 年 10 月 8 日**
**生效日期：2026 年 10 月 8 日**

本政策适用于 Android 应用「飞伞天气」（英文名 ThermalCast，包名 `com.thermalcast.app`，以下简称"本应用"），由开发者 **jenson**（以下简称"我们"）提供。

---

## 一、核心原则

我们深知位置与飞行数据对你而言是敏感的。本应用的设计原则是：

> **能在设备本地完成的处理，绝不离开设备。**

本政策中的每一条陈述，都以代码中的实际行为为准；代码中不存在的行为，我们不会写进政策。

---

## 二、我们不做什么

- **没有账号系统。** 本应用无需注册，我们不收集你的姓名、手机号、邮箱或任何身份信息。
- **不含广告 SDK。** 未集成 AdMob 或任何广告平台，不读取广告标识符（GAID）。
- **不含第三方统计分析 SDK。** 未集成 Firebase Analytics、友盟、神策等。
- **不含崩溃上报 SDK。** 未集成 Crashlytics、Bugly 等。
- **不使用蓝牙。** 本应用**不申请任何蓝牙权限**，不会扫描、连接或读取任何外接设备（如外接变率报警器）。相关代码与权限声明均已移除。
- **当前版本没有任何付费功能。** 不提供订阅、应用内购买或任何收费内容，也**未初始化任何支付 SDK**，因此不会产生、存储或传输支付与订阅数据。
- **我们不读取设备标识符。** 不读取 Android ID、IMEI、广告标识符或任何可用于追踪的设备标识。
- **我们没有自己的数据服务器。** 你使用本应用产生的任何数据都不会上传到我们控制的任何服务器。

---

## 三、会离开设备的数据（只有两类）

整个应用中，会通过网络发送到外部的数据**只有下面两类**，且都只包含完成请求所必需的最小信息。

### 1. 位置坐标 → Open-Meteo

| 项目 | 说明 |
|---|---|
| 发送内容 | 场地的经纬度数值 |
| 用途 | 获取该场地的天气预报、风廓线与地形高程 |
| 传输方式 | HTTPS |
| 是否包含身份或设备标识 | **否**，请求中只有坐标数值 |
| 何时发生 | 仅在你查看某个场地的天气时 |

**你可以拒绝**：位置权限是完全可选的。拒绝授权后，你仍可手动添加或选择飞行场地来查看天气，仅"定位当前位置"与"自动记录轨迹"功能不可用。

### 2. 地图瓦片请求 → OpenFreeMap

地图底图使用 OpenFreeMap 的矢量瓦片（地图数据来自 OpenStreetMap）。瓦片请求由地图组件在浏览地图时发出，**可能暴露你所在的大致区域**。该请求同样不包含身份或设备标识。

除以上两类外，**没有任何其他数据离开你的设备**。

---

## 四、只留在设备上的数据

| 数据 | 处理方式 | 是否上传 |
|---|---|---|
| 传感器数据（气压计、加速度计、指南针） | 实时处理，用于变率计算与起飞/落地判断 | **否**（不存储、不上传） |
| 飞行轨迹与飞行记录（时间、经纬度、高度、气压） | 保存在设备本地数据库 | **否** |
| 场地配置 | 保存在设备本地 | **否** |
| 相机图像 | 仅用于扫描二维码同步配置，本地即时解码 | **否**（不保存、不上传） |
| 功能使用次数统计 | 写入设备本地存储 | **否** |

**关于系统备份**：本地数据库会随 Android 系统备份（Auto Backup）保存到**你自己账号下**的 Google 云空间。该备份由 Google 管理，**我们无法访问**。你可以在系统「设置 → 系统 → 备份」中关闭。

---

## 五、第三方服务清单

| 服务 | 用途 | 接收的信息 | 隐私政策 |
|---|---|---|---|
| Open-Meteo | 天气预报、风廓线与地形高程数据 | 经纬度坐标 | https://open-meteo.com/en/terms |
| OpenFreeMap | 地图底图瓦片（数据来自 OpenStreetMap） | 瓦片请求（可推断大致地区） | https://openfreemap.org/ |

当前版本**不存在**支付、广告、统计或崩溃上报类的第三方服务。

---

## 六、数据存储与保留

| 数据 | 存储位置 | 保留期限 |
|---|---|---|
| 飞行轨迹与飞行记录 | 设备本地 | 直到你在应用「设置 → 数据与隐私」中清空，或卸载应用 |
| 场地配置 | 设备本地 | 直到你卸载应用 |
| 传感器数据 | 不存储（实时处理） | — |
| 使用统计计数 | 设备本地 | 直到你卸载应用 |

我们**没有**任何形式的数据服务器，因此不存在"我们的数据库中保留你的数据"这一情形。

---

## 七、你的权利与控制

- **撤回位置权限**：系统「设置 → 应用 → 飞伞天气 → 权限」
- **清空飞行记录**：在应用「设置 → 数据与隐私」中清空全部飞行记录与轨迹
- **彻底删除全部数据**：卸载应用即可清除所有本地数据
- **咨询与删除请求**：发送邮件至下方联系邮箱，我们会及时处理

---

## 八、儿童隐私

本应用面向滑翔伞运动爱好者，**不面向 13 岁以下儿童**，我们不会主动收集儿童的个人信息。若你发现儿童向我们提供了信息，请联系我们删除。

---

## 九、飞行安全声明

本应用提供的天气信息、飞行评分与变率报警**仅作为辅助参考，不构成飞行决策的唯一依据**。滑翔伞飞行具有固有风险，请务必以现场实际情况、当地法规与自身专业判断为准。

---

## 十、政策更新

本政策如有变更，我们将在应用内与本页面同步更新，并修改页首的"最后更新"日期。重大变更会以应用内公告方式提示。

---

## 十一、联系我们

如对本政策有任何疑问或要求，请联系：

**邮箱：chengjmx@gmail.com**

---

*English version follows below.*

---

# ThermalCast Privacy Policy

**Last updated: October 8, 2026**
**Effective date: October 8, 2026**

This policy applies to the Android application "ThermalCast" (飞伞天气, package `com.thermalcast.app`), provided by developer **jenson** ("we", "us").

Every statement below reflects actual behaviour in the code. We do not claim practices the app does not implement.

## Our Core Principle

> **Anything that can be processed on your device stays on your device.**

## What We Do NOT Do

- **No account system.** No registration; we never collect your name, phone number, or email.
- **No advertising SDKs.** No AdMob, no ad identifiers (GAID).
- **No third-party analytics SDKs.** No Firebase Analytics or similar.
- **No crash-reporting SDKs.** No Crashlytics, Bugly or similar.
- **No Bluetooth.** The app **does not request any Bluetooth permission** and never scans for, connects to, or reads from external devices (such as an external vario). The related code and permission declarations have been removed.
- **No paid features in the current version.** No subscriptions, no in-app purchases, no paid content. **No payment SDK is initialised**, so no payment or subscription data is created, stored or transmitted.
- **No device identifiers.** We do not read Android ID, IMEI, advertising identifiers, or any identifier that could be used for tracking.
- **No data servers of our own.** No data you generate is ever uploaded to servers we control.

## Data That Leaves Your Device (only two kinds)

**1. Location coordinates — sent to Open-Meteo.**
With your permission we read your device location to fetch the forecast, wind profile and terrain elevation for a flying site. Latitude/longitude are sent over HTTPS to **Open-Meteo** solely to retrieve weather data — no identity or device identifiers are included. This happens only when you view the weather for a site. Location permission is optional; without it you can still add and select flying sites manually.

**2. Map tile requests — sent to OpenFreeMap.**
The map uses OpenFreeMap vector tiles (map data from OpenStreetMap). Tile requests are made while browsing the map and **may reveal your approximate region**. They contain no identity or device identifiers.

Nothing else leaves your device.

## Data That Stays On Your Device

| Data | How it is handled | Uploaded? |
|---|---|---|
| Sensor data (barometer, accelerometer, compass) | Processed in real time for vario computation and takeoff/landing detection | **No** (never stored or transmitted) |
| Flight tracks and logs (time, coordinates, altitude, pressure) | Stored in the on-device database | **No** |
| Site configuration | Stored on device | **No** |
| Camera images | Used only to scan QR codes for configuration sync; decoded locally | **No** (never saved or transmitted) |
| Feature usage counters | Written to local storage | **No** |

**About system backup:** the local database may be included in your Android system backup (Auto Backup) stored in **your own** Google account space. That backup is managed by Google and **we cannot access it**. You can turn it off in Settings → System → Backup.

## Third-Party Services

| Service | Purpose | Data received | Privacy policy |
|---|---|---|---|
| Open-Meteo | Weather forecast, wind profile and terrain elevation | Latitude/longitude | https://open-meteo.com/en/terms |
| OpenFreeMap | Map tile base layer (map data from OpenStreetMap) | Tile requests (approximate region inferable) | https://openfreemap.org/ |

The current version includes **no** payment, advertising, analytics or crash-reporting third-party services.

## Data Retention

Flight logs and site configurations remain on your device until you delete them in-app or uninstall the app. Sensor data is never stored. We operate no server, so no data is retained by us.

## Your Rights

Withdraw the location permission in system Settings; delete flight records in Settings → Data & Privacy; uninstall to erase all local data; contact us by email for any question or deletion request.

## Children

The app is intended for paragliding enthusiasts and is **not directed to children under 13**. We do not knowingly collect personal information from children.

## Flight Safety Disclaimer

Weather data, flight scores, and vario alarms are **advisory only and must not be the sole basis for a flight decision**. Paragliding carries inherent risk; always rely on actual conditions, local regulations, and your own judgement.

## Contact

**Email: chengjmx@gmail.com**

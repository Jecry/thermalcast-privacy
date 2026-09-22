# ThermalCast Privacy Policy

**Last updated: September 23, 2026**
**Effective date: September 23, 2026**

This policy applies to the Android application "ThermalCast" ("飞伞天气", package `com.thermalcast.app`), provided by developer **jenson** ("we", "us").

## Our Core Principle

> **Anything that can be processed on your device stays on your device.**

## What We Do NOT Do

- **No account system.** No registration; we never collect your name, phone number, or email.
- **No advertising SDKs.** No AdMob, no ad identifiers (GAID).
- **No third-party analytics SDKs.** No Firebase Analytics, no crash reporters.
- **No data servers of our own.** No data you generate is ever uploaded to servers we control.

## Information We Collect

### 1. Precise location — sent to a third-party weather service

| Item | Description |
|---|---|
| How collected | Device location (GPS / network) read after you grant permission |
| Purpose | ① Fetch weather forecast and wind profile for your flying site　② Show your position on the map　③ Record flight tracks and compute glide ratio |
| Leaves device? | **Yes** (coordinates sent to Open-Meteo solely to fetch weather) |
| Local storage | Flight tracks (time, lat/lng, altitude, pressure) stored in the on-device database |

**Transmission details**: To fetch weather, latitude/longitude are sent as HTTPS request parameters to Open-Meteo (`api.open-meteo.com`). The request includes **no** identity or device identifiers — only the coordinate values. The request is made only when you view a site's weather.

**System backup**: The local database may be included in your Android system backup (Auto Backup) stored in your own Google cloud space, managed by Google; **we cannot access it**. You can disable it in system Settings → System → Backup.

**You can decline**: Location permission is entirely optional. Without it you can still add or select flying sites manually; only "locate me now" and "auto-track recording" become unavailable.

### 2. Sensor data (barometer, accelerometer) — stays on device

Used for vario computation and takeoff/landing detection. **Processed in real time on your device only — never stored or transmitted.**

### 3. Camera — stays on device

Used only to scan QR codes for on-device configuration sync. Images are decoded locally and never stored or transmitted.

### 4. Purchases and subscriptions

Subscriptions are processed by **Google Play Billing**. We never receive your payment details; we only receive whether a subscription is active in order to unlock features.

### 5. Device identifier — stays on device

A truncated SHA-256 hash of Android ID is stored locally to identify this device's entitlement state. It is never transmitted and cannot be used for cross-app tracking.

### 6. Usage statistics — local only

Feature usage counters are written to local storage only and are not uploaded in the current version.

## Third-Party Services

| Service | Purpose | Data received | Privacy policy |
|---|---|---|---|
| Open-Meteo | Weather and wind profile data | Latitude/longitude | https://open-meteo.com/en/terms |
| OpenFreeMap | Map tile base layer (vector tiles, map data from OpenStreetMap) | Map tile requests (approximate region inferable) | https://openfreemap.org/ |
| Google Play Billing | Subscription payments | Handled entirely by Google | https://policies.google.com/privacy |

## Data Retention

| Data | Storage | Retention |
|---|---|---|
| Flight tracks & logs | On device | Until you delete them in-app or uninstall the app |
| Site configuration | On device | Until you uninstall the app |
| Sensor data | Not stored (real-time processing) | — |
| Usage counters | On device | Until you reset in-app or uninstall the app |

We operate **no data servers of any kind**, so no data is retained by us.

## Your Rights

- **Revoke location permission**: System Settings → Apps → ThermalCast → Permissions
- **Clear flight records**: In-app, My → Data & Privacy
- **Erase all data**: Uninstall the app
- **Manage or cancel subscription**: Google Play → Subscriptions → Manage

## Children

The app is intended for paragliding enthusiasts and is **not directed to children under 13**. We do not knowingly collect personal information from children.

## Flight Safety Disclaimer

Weather data, flight scores, and vario alarms are **advisory only and must not be the sole basis for a flight decision**. Paragliding carries inherent risk; always rely on actual conditions, local regulations, and your own judgement.

## Policy Updates

If this policy changes, we will update it both in-app and on this page, and revise the "Last updated" date at the top.

## Contact

**Email: <chengjmx@gmail.com>**

---

# 飞伞天气 隐私政策

**最后更新：2026 年 9 月 23 日**
**生效日期：2026 年 9 月 23 日**

本政策适用于 Android 应用「飞伞天气」（英文名 ThermalCast，包名 `com.thermalcast.app`，以下简称"本应用"），由开发者 **jenson**（以下简称"我们"）提供。

## 一、核心原则

> **能在设备本地完成的处理，绝不离开设备。**

## 二、我们不做什么

- **没有账号系统。** 本应用无需注册，我们不收集你的姓名、手机号、邮箱或任何身份信息。
- **不含广告 SDK。** 未集成 AdMob 或任何广告平台，不读取广告标识符（GAID）。
- **不含第三方统计分析 SDK。** 未集成 Firebase Analytics、友盟、神策等。
- **不含崩溃上报 SDK。** 未集成 Crashlytics、Bugly 等。
- **我们没有自己的数据服务器。** 你使用本应用产生的任何数据都不会上传到我们控制的任何服务器。

## 三、信息收集与使用

### 1. 位置信息（精确位置）—— 会发送给第三方天气服务

| 项目 | 说明 |
|---|---|
| 收集方式 | 在你授权后读取设备定位（GPS / 网络定位） |
| 用途 | ① 获取所在场地的天气预报与风廓线　② 地图上显示你的位置　③ 记录飞行轨迹、计算滑翔比 |
| 是否离开设备 | **是**（仅为获取天气，坐标发送至 Open-Meteo） |
| 本地存储 | 飞行轨迹（时间、经纬度、高度、气压）保存在设备本地数据库 |

**传输细节**：为获取天气数据，经纬度数值会作为 HTTPS 请求参数发送至 Open-Meteo（`api.open-meteo.com`）。请求中**不包含**你的身份信息或设备标识，仅包含坐标数值。该请求仅在你查看某个场地的天气时发生。

**系统备份**：本地数据库会随 Android 系统备份（Auto Backup）保存到你自己账号下的 Google 云空间。该备份由 Google 管理，**我们无法访问**。你可以在系统「设置 → 系统 → 备份」中关闭。

**你可以拒绝**：位置权限是完全可选的。拒绝授权后，你仍可手动添加或选择飞行场地来查看天气，仅"定位当前位置"与"自动记录轨迹"功能不可用。

### 2. 传感器数据（气压、加速度）—— 不离开设备

用于变率（vario）计算与飞行状态（起飞/落地）判断。**仅在你的设备上实时处理，不存储、不上传。**

### 3. 相机 —— 不离开设备

仅用于扫描二维码以在设备之间同步配置或航线数据。图像在本地即时解码，不保存、不上传。

### 4. 购买与订阅信息

本应用使用 Google Play 结算服务（Google Play Billing）处理订阅：

- 你的支付方式、银行卡等支付信息由 Google 直接处理，**我们无法接触**。
- 我们仅从 Google Play 获取"该订阅当前是否有效"的状态，用于解锁专业版功能。

### 5. 设备标识符 —— 不离开设备

为识别本机的授权状态，本应用读取 Android ID 并作 SHA-256 哈希后截取前 8 位，保存在本地。该标识：

- **不会上传**
- 不含任何个人身份信息，无法用于跨应用追踪

### 6. 使用统计 —— 仅本地

本应用记录功能使用次数（例如付费墙触发次数）用于产品改进。这些统计**仅写入设备本地存储**，当前版本不会上传。

## 四、第三方服务清单

| 服务 | 用途 | 接收的信息 | 隐私政策 |
|---|---|---|---|
| Open-Meteo | 天气预报与风廓线数据 | 经纬度坐标 | https://open-meteo.com/en/terms |
| OpenFreeMap | 地图底图瓦片（矢量瓦片，地图数据来自 OpenStreetMap） | 地图瓦片请求（可推断大致地区） | https://openfreemap.org/ |
| Google Play 结算 | 订阅支付 | 由 Google 全权处理 | https://policies.google.com/privacy |

## 五、数据存储与保留

| 数据 | 存储位置 | 保留期限 |
|---|---|---|
| 飞行轨迹与飞行记录 | 设备本地 | 直到你在应用「我的 → 数据与隐私」中清空，或卸载应用 |
| 场地配置 | 设备本地 | 直到你卸载应用 |
| 传感器数据 | 不存储（实时处理） | — |
| 使用统计计数 | 设备本地 | 直到你在应用内重置，或卸载应用 |

我们**没有**任何形式的数据服务器，因此不存在"我们的数据库中保留你的数据"这一情形。

## 六、你的权利与控制

- **撤回位置权限**：系统「设置 → 应用 → 飞伞天气 → 权限」
- **清空飞行记录**：在应用「我的 → 数据与隐私」中清空全部飞行记录与轨迹
- **彻底删除全部数据**：卸载应用即可清除所有本地数据
- **管理或取消订阅**：Google Play → 订阅 → 管理

## 七、儿童隐私

本应用面向滑翔伞运动爱好者，**不面向 13 岁以下儿童**，我们不会主动收集儿童的个人信息。若你发现儿童向我们提供了信息，请联系我们删除。

## 八、飞行安全声明

本应用提供的天气信息、飞行评分与变率报警**仅作为辅助参考，不构成飞行决策的唯一依据**。滑翔伞飞行具有固有风险，请务必以现场实际情况、当地法规与自身专业判断为准。

## 九、政策更新

本政策如有变更，我们将在应用内与本页面同步更新，并修改页首的"最后更新"日期。重大变更会以应用内公告方式提示。

## 十、联系我们

如对本政策有任何疑问或要求，请联系：

**邮箱：<chengjmx@gmail.com>**

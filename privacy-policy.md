# ThermalCast 隐私政策 / Privacy Policy

**最后更新 / Last updated：2026-10-21**
**适用范围：** Android「飞伞天气」`com.thermalcast.app` 与 iOS「ThermalCast」

两版共用同一套数据处理逻辑，平台差异已在正文中逐条标注（iOS / Android）。
完整正文亦可在 App 内查看：设置 → 数据与隐私 → 隐私政策，共 13 个界面语言版本。

---


## 简体中文

**最后更新：2026-10-21**

**凡是能在你设备上完成的处理，就都留在你的设备上。**

### 我们不做的事
- 没有账号系统 —— 无需注册，我们也从不索取你的姓名、手机号或邮箱。
- 没有广告 SDK，没有广告标识符：不追踪、不做用户画像，不向任何数据中介出售或共享数据。
- 没有第三方统计或崩溃上报 SDK。
- 不使用蓝牙 —— App 从不申请蓝牙权限，也从不与外部仪器配对。
- 不读取追踪用设备标识 —— Android 侧不读 Android ID、IMEI、广告标识符；iOS 侧从不申请「允许 App 请求追踪」（IDFA）。
- 没有自有服务器 —— 没有任何数据会上传到我们运营的服务器。

### 会离开设备的数据
- 天气预报 —— 会通过 HTTPS 把场地坐标发送给 Open-Meteo（api.open-meteo.com）以获取预报；回填场地海拔时会调用其高程接口。
- 地图与地形瓦片 —— 地图瓦片来自 OpenFreeMap，地形晕渲来自公开的 AWS Terrain Tiles 数据集。这类请求会暴露你正在查看的大致区域。
- 购买（仅 iOS）—— 订阅完全由 Apple 通过 App Store 计费与校验。我们只拿到订阅状态，永远不会拿到你的支付信息。Android 版当前免费，且未初始化任何支付 SDK。
- 这些请求不含账号、姓名、设备或广告标识符，只有坐标。除此之外没有任何数据离开你的设备。

### 留在本机的数据
- 飞行记录与航迹 —— 存在本机数据库中，从不上传。
- 你新建或导入的起飞场，以及随 App 打包、离线读取的空域数据。
- 传感器读数 —— 气压计、运动与罗盘数据实时处理，用于变率仪与起飞/落地判断。它们从不被记录或上传。
- 飞行员姓名与伞型 —— 只写进你导出的 IGC 文件头。留空则飞行记录保持匿名。
- 偏好设置与通知设置 —— 只存在本机。iOS 的小组件从 App 私有的 App Group 容器读取快照，同样不会离开设备。

### 权限，以及拒绝之后会怎样
- 定位（使用期间）—— 显示当前位置的天气、把地图居中，并记录你的航迹。
- 后台定位 —— 熄屏后继续记录，保证航迹完整。iOS 上这是可选的「始终」权限；Android 上以可隐藏通知的前台服务运行。
- 运动与健身 —— 读取气压传感器以计算升降速率。
- 相机 —— 只用于扫描二维码，从另一台手机接收起飞场。画面在本机解码，从不保存或上传。
- 通知 —— 可选，用于气象条件提醒与早间简报。

拒绝任何一项，其余功能照常可用。没有定位时只是停止飞行记录，你依然可以手动输入坐标添加场地。

### 保留期限与你的权利
- 飞行日志与场地一直留在本机，直到你删除它们或卸载 App。App 内「数据与隐私 › 删除所有飞行记录」会立即、永久地清除全部飞行场次、航迹与逐秒日志。
- 卸载 ThermalCast 会清除全部本机数据。
- 系统备份可能会把本机数据库复制进你自己的存储空间 —— iOS 是 iCloud 或电脑备份，Android 是系统备份（Google）。这些备份由 Apple 或 Google 管理，我们无法读取。
- 你可以随时在系统设置中撤回任何权限。
- 有疑问，或需要在 App 之外提出删除请求：chengjmx@gmail.com

### 儿童
ThermalCast 不面向 13 岁以下儿童，我们也不会有意收集他们的个人信息。App 没有账号、无需注册，因此本来就不会收集任何个人信息。

### 数据来源
- 天气与高程 —— Open-Meteo（CC BY 4.0）；高程派生自 Copernicus DEM GLO-90 © EU-ESA。
- 地形晕渲 —— AWS Terrain Tiles，公开高程数据集。
- 地图瓦片 —— © OpenStreetMap 贡献者，由 OpenFreeMap 提供。
- 空域 —— 随包数据派生自 openAIP（openaip.net），离线读取。

### 飞行安全
天气数据、飞行评分与变率仪报警仅供参考，绝不能作为飞行决策的唯一依据。滑翔伞运动本身存在风险：请始终依据实际天气状况、当地法规与自己的判断。

### 本政策的变更
最新文本始终发布于 https://jecry.github.io/thermalcast-privacy/。若离开设备的数据类型发生变化，该页面与 App 内文案会同步更新，顶部的日期也会随之改变。


---

## 繁體中文

**最後更新：2026-10-21**

**凡是能在你裝置上完成的處理，就都留在你的裝置上。**

### 我們不做的事
- 沒有帳號系統 —— 無需註冊，我們也從不索取你的姓名、手機號碼或電子郵件。
- 沒有廣告 SDK，沒有廣告識別碼：不追蹤、不做使用者輪廓分析，不向任何資料中介出售或分享資料。
- 沒有第三方統計或當機回報 SDK。
- 不使用藍牙 —— App 從不申請藍牙權限，也從不與外部儀器配對。
- 不讀取追蹤用裝置識別碼 —— Android 端不讀 Android ID、IMEI、廣告識別碼；iOS 端從不申請「允許 App 要求追蹤」（IDFA）。
- 沒有自有伺服器 —— 沒有任何資料會上傳到我們營運的伺服器。

### 會離開裝置的資料
- 天氣預報 —— 會透過 HTTPS 把場地座標傳送給 Open-Meteo（api.open-meteo.com）以取得預報；回填場地海拔時會呼叫其高程介面。
- 地圖與地形圖磚 —— 地圖圖磚來自 OpenFreeMap，地形暈渲來自公開的 AWS Terrain Tiles 資料集。這類請求會透露你正在查看的大致區域。
- 購買（僅 iOS）—— 訂閱完全由 Apple 透過 App Store 計費與驗證。我們只取得訂閱狀態，永遠不會取得你的付款資訊。Android 版目前免費，且未初始化任何支付 SDK。
- 這些請求不含帳號、姓名、裝置或廣告識別碼，只有座標。除此之外沒有任何資料離開你的裝置。

### 留在本機的資料
- 飛行記錄與航跡 —— 存放在本機資料庫中，從不上傳。
- 你新增或匯入的起飛場，以及隨 App 打包、離線讀取的空域資料。
- 感測器讀數 —— 氣壓計、動作與羅盤資料即時處理，用於變率儀與起飛／落地判斷。它們從不被記錄或上傳。
- 飛行員姓名與傘型 —— 只寫入你匯出的 IGC 檔案標頭。留空則飛行記錄保持匿名。
- 偏好設定與通知設定 —— 只存在本機。iOS 的小工具從 App 私有的 App Group 容器讀取快照，同樣不會離開裝置。

### 權限，以及拒絕之後會怎樣
- 定位（使用期間）—— 顯示目前位置的天氣、將地圖置中，並記錄你的航跡。
- 背景定位 —— 螢幕關閉後仍繼續記錄，確保航跡完整。iOS 上這是選用的「永遠」權限；Android 上以可隱藏通知的前景服務運行。
- 動作與體能活動 —— 讀取氣壓感測器以計算升降速率。
- 相機 —— 僅用於掃描 QR Code，從另一支手機接收起飛場。畫面在本機解碼，從不儲存或上傳。
- 通知 —— 選用，用於氣象條件提醒與晨間簡報。

拒絕任何一項，其餘功能都照常可用。沒有定位時只會停止飛行記錄，你仍然可以手動輸入座標新增場地。

### 保留期限與你的權利
- 飛行記錄與場地會一直留在本機，直到你刪除它們或解除安裝 App。App 內「資料與隱私 › 刪除所有飛行記錄」會立即且永久地清除全部飛行場次、航跡與逐秒記錄。
- 解除安裝 ThermalCast 會清除全部本機資料。
- 系統備份可能會把本機資料庫複製進你自己的儲存空間 —— iOS 是 iCloud 或電腦備份，Android 是系統備份（Google）。這些備份由 Apple 或 Google 管理，我們無法讀取。
- 你可以隨時在系統設定中撤回任何權限。
- 有疑問，或需要在 App 之外提出刪除請求：chengjmx@gmail.com

### 兒童
ThermalCast 不面向 13 歲以下兒童，我們也不會有意收集他們的個人資料。App 沒有帳號、無需註冊，因此本來就不會收集任何個人資料。

### 資料來源
- 天氣與高程 —— Open-Meteo（CC BY 4.0）；高程衍生自 Copernicus DEM GLO-90 © EU-ESA。
- 地形暈渲 —— AWS Terrain Tiles，公開高程資料集。
- 地圖圖磚 —— © OpenStreetMap 貢獻者，由 OpenFreeMap 提供。
- 空域 —— 隨附資料衍生自 openAIP（openaip.net），離線讀取。

### 飛行安全
天氣資料、飛行評分與變率儀警報僅供參考，絕不能作為飛行決策的唯一依據。飛行傘運動本身存在風險：請始終依據實際天氣狀況、當地法規與自己的判斷。

### 本政策的變更
最新文字始終發布於 https://jecry.github.io/thermalcast-privacy/。若離開裝置的資料類型發生變化，該頁面與 App 內文案會同步更新，頂部的日期也會隨之改變。


---

## English

**Last updated 2026-10-21**

**Anything that can be processed on your device stays on your device.**

### What we do not do
- No account — no sign-up, and we never ask for your name, phone number or email.
- No advertising SDK and no advertising identifier: no tracking, no profiling, and no data sold or shared with data brokers.
- No third-party analytics or crash-reporting SDK.
- No Bluetooth — the app never asks for Bluetooth access and never pairs with external instruments.
- No identifiers used for tracking — we do not read Android ID, IMEI or the advertising ID on Android, and we never request the iOS tracking permission (IDFA).
- No server of our own — nothing is uploaded to infrastructure we operate.

### What leaves your device
- Forecasts — the coordinates of a site are sent over HTTPS to Open-Meteo (api.open-meteo.com) to fetch the forecast, and to its elevation endpoint when a site altitude is filled in.
- Map and terrain tiles — tiles are requested from OpenFreeMap and terrain shading from the public AWS Terrain Tiles dataset. Such requests can reveal the approximate area you are looking at.
- Purchases (iOS only) — subscriptions are billed and validated entirely by Apple through the App Store. We receive a subscription status only, never your payment details. The Android version is currently free and initialises no payment SDK.
- These requests carry no account, name, device or advertising identifier — only coordinates. Nothing else leaves your device.

### What stays on your device
- Flight sessions and tracks — stored in the on-device database, never uploaded.
- Launch sites you create or import, and the airspace set, which ships with the app and is read offline.
- Sensor readings — barometer, motion and compass are processed in real time for the vario and for takeoff and landing detection. They are never recorded or uploaded.
- Pilot name and glider — written only into the header of IGC files you export. Leave them empty and your flights stay anonymous.
- Preferences and notification settings — stored locally. On iOS the widget reads its snapshot from a private App Group container shared with the app, so nothing leaves the device that way either.

### Permissions, and what happens if you decline
- Location, When In Use — show weather for your position, centre the map and record your track.
- Location in the background — keeps recording while the screen is off so the log stays complete. On iOS this is the optional Always permission; on Android it runs as a foreground service with a notification you can hide.
- Motion — reads the barometric sensor for climb and sink rate.
- Camera — used only to scan a QR code that transfers launch sites from another phone. Frames are decoded on the device and never saved or uploaded.
- Notifications — optional, for condition alerts and the morning briefing.

Declining any of them leaves the rest of the app working. Without location only flight recording stops, and you can still add a site by typing its coordinates.

### Retention and your rights
- Flight logs and sites stay on this device until you delete them or uninstall the app. The Data & privacy screen › Delete all flight records clears every session, track and per-second log immediately and permanently.
- Uninstalling ThermalCast erases all local data.
- A system backup may copy this local database into your own storage — iCloud or a computer backup on iOS, Android system backup (Google) on Android. Those backups are managed by Apple or Google and we cannot read them.
- You can withdraw any permission at any time in system Settings.
- Questions, or a deletion request you cannot carry out in the app: chengjmx@gmail.com

### Children
ThermalCast is not directed to children under 13, and we do not knowingly collect personal information from them. There is no account and no sign-up, so nothing personal is collected in the first place.

### Data sources
- Weather and elevation — Open-Meteo (CC BY 4.0); elevation is derived from Copernicus DEM GLO-90 © EU-ESA.
- Terrain shading — AWS Terrain Tiles, a public elevation dataset.
- Map tiles — © OpenStreetMap contributors, served by OpenFreeMap.
- Airspace — the bundled set is derived from openAIP (openaip.net) and is read offline.

### Flight safety
Weather data, flight scores and vario alarms are advisory only and must never be the sole basis for a flight decision. Paragliding carries inherent risk: always rely on the actual conditions, local regulations and your own judgement.

### Changes to this policy
The current text is always available at https://jecry.github.io/thermalcast-privacy/. If the kind of data that leaves your device ever changes, this page and the in-app text are updated together, and the date at the top changes with them.


---

## Deutsch

**Zuletzt aktualisiert: 2026-10-21**

**Alles, was auf deinem Gerät verarbeitet werden kann, bleibt auf deinem Gerät.**

### Was wir nicht tun
- Kein Konto — keine Registrierung, und wir fragen nie nach Name, Telefonnummer oder E-Mail.
- Kein Werbe-SDK und keine Werbe-ID: kein Tracking, kein Profiling, keine Daten an Datenhändler verkauft oder weitergegeben.
- Kein Analyse- oder Absturzbericht-SDK von Drittanbietern.
- Kein Bluetooth — die App fragt nie nach Bluetooth-Zugriff und koppelt sich nie mit externen Instrumenten.
- Keine Kennungen fürs Tracking — auf Android lesen wir keine Android-ID, IMEI oder Werbe-ID, und auf iOS fordern wir nie die Tracking-Erlaubnis (IDFA).
- Kein eigener Server — nichts wird auf Infrastruktur hochgeladen, die wir betreiben.

### Was das Gerät verlässt
- Vorhersagen — die Koordinaten eines Startplatzes werden per HTTPS an Open-Meteo (api.open-meteo.com) gesendet, um die Vorhersage zu holen, und an dessen Höhen-Endpunkt, wenn eine Platzhöhe ergänzt wird.
- Karten- und Geländekacheln — Kacheln kommen von OpenFreeMap, die Geländedarstellung aus dem öffentlichen AWS-Terrain-Tiles-Datensatz. Solche Anfragen können die ungefähre Region verraten, die du ansiehst.
- Käufe (nur iOS) — Abonnements werden vollständig von Apple über den App Store abgerechnet und geprüft. Wir erhalten nur den Abo-Status, niemals deine Zahlungsdaten. Die Android-Fassung ist derzeit kostenlos und initialisiert kein Zahlungs-SDK.
- Diese Anfragen enthalten kein Konto, keinen Namen, keine Geräte- oder Werbe-ID — nur Koordinaten. Sonst verlässt nichts dein Gerät.

### Was auf dem Gerät bleibt
- Flüge und Spuren — in der geräteinternen Datenbank gespeichert, nie hochgeladen.
- Startplätze, die du anlegst oder importierst, sowie der Luftraum-Datensatz, der mit der App kommt und offline gelesen wird.
- Sensordaten — Barometer, Bewegung und Kompass werden in Echtzeit für das Vario und die Start- und Landungserkennung verarbeitet. Sie werden nie aufgezeichnet oder hochgeladen.
- Pilotenname und Schirm — stehen nur im Kopf der IGC-Dateien, die du exportierst. Leer gelassen bleiben deine Flüge anonym.
- Einstellungen und Benachrichtigungen — lokal gespeichert. Auf iOS liest das Widget seinen Schnappschuss aus einem privaten App-Group-Container der App; auch darüber verlässt nichts das Gerät.

### Berechtigungen — und was passiert, wenn du ablehnst
- Ortung, bei Nutzung — zeigt das Wetter für deine Position, zentriert die Karte und zeichnet deine Spur auf.
- Ortung im Hintergrund — zeichnet bei ausgeschaltetem Bildschirm weiter, damit das Logbuch vollständig bleibt. Auf iOS ist das die optionale Erlaubnis „immer“; auf Android läuft es als Vordergrunddienst mit einer Benachrichtigung, die du verstecken kannst.
- Bewegung — liest den barometrischen Sensor für Steigen und Sinken.
- Kamera — nur zum Scannen eines QR-Codes, der Startplätze von einem anderen Telefon überträgt. Bilder werden auf dem Gerät dekodiert, nie gespeichert oder hochgeladen.
- Mitteilungen — optional, für Bedingungswarnungen und den Morgenbericht.

Lehnst du eine davon ab, funktioniert der Rest weiter. Ohne Ortung stoppt nur die Flugaufzeichnung, und du kannst einen Startplatz weiterhin per Koordinate anlegen.

### Speicherdauer und deine Rechte
- Flugprotokolle und Startplätze bleiben auf diesem Gerät, bis du sie löschst oder die App entfernst. Der Bildschirm „Daten & Datenschutz › Alle Flugaufzeichnungen löschen“ entfernt jede Session, Spur und jedes Sekunden-Log sofort und dauerhaft.
- Das Entfernen von ThermalCast löscht alle lokalen Daten.
- Ein System-Backup kann diese lokale Datenbank in deinen eigenen Speicher kopieren — iCloud oder Computer-Backup auf iOS, Android-System-Backup (Google) auf Android. Diese Backups werden von Apple oder Google verwaltet, wir können sie nicht lesen.
- Du kannst jede Berechtigung jederzeit in den Systemeinstellungen entziehen.
- Fragen, oder ein Löschantrag, den du in der App nicht ausführen kannst: chengjmx@gmail.com

### Kinder
ThermalCast richtet sich nicht an Kinder unter 13 Jahren, und wir sammeln nicht wissentlich personenbezogene Daten von ihnen. Es gibt kein Konto und keine Registrierung, also werden ohnehin keine persönlichen Daten erhoben.

### Datenquellen
- Wetter und Höhe — Open-Meteo (CC BY 4.0); die Höhe stammt aus Copernicus DEM GLO-90 © EU-ESA.
- Geländedarstellung — AWS Terrain Tiles, ein öffentlicher Höhendatensatz.
- Kartenkacheln — © OpenStreetMap-Mitwirkende, bereitgestellt von OpenFreeMap.
- Lufträume — der mitgelieferte Datensatz stammt von openAIP (openaip.net) und wird offline gelesen.

### Flugsicherheit
Wetterdaten, Flugbewertungen und Vario-Alarme sind nur Hinweise und dürfen nie die alleinige Grundlage einer Flugentscheidung sein. Gleitschirmfliegen birgt ein eigenes Risiko: Verlass dich immer auf die tatsächlichen Bedingungen, die lokalen Vorschriften und dein eigenes Urteil.

### Änderungen dieser Richtlinie
Der aktuelle Text steht immer unter https://jecry.github.io/thermalcast-privacy/. Wenn sich die Art der Daten ändert, die dein Gerät verlässt, werden diese Seite und der Text in der App gemeinsam aktualisiert, und das Datum oben ändert sich mit ihnen.


---

## Français

**Dernière mise à jour : 2026-10-21**

**Tout ce qui peut être traité sur votre appareil reste sur votre appareil.**

### Ce que nous ne faisons pas
- Pas de compte — aucune inscription, et nous ne demandons jamais votre nom, numéro de téléphone ou e-mail.
- Aucun SDK publicitaire ni identifiant publicitaire : pas de suivi, pas de profilage, aucune donnée vendue ou partagée avec des courtiers en données.
- Aucun SDK tiers d'analyse ou de rapport d'incident.
- Pas de Bluetooth — l'app ne demande jamais l'accès Bluetooth et ne s'apparie jamais à des instruments externes.
- Aucun identifiant utilisé pour le suivi — nous ne lisons pas l'identifiant Android, l'IMEI ni l'identifiant publicitaire sur Android, et nous ne demandons jamais l'autorisation de suivi iOS (IDFA).
- Aucun serveur propre — rien n'est téléversé vers une infrastructure que nous exploitons.

### Ce qui quitte votre appareil
- Prévisions — les coordonnées d'un site sont envoyées en HTTPS à Open-Meteo (api.open-meteo.com) pour obtenir la prévision, et à son point d'accès d'altitude lorsqu'une altitude de site est renseignée.
- Tuiles de carte et de relief — les tuiles viennent d'OpenFreeMap et le relief du jeu de données public AWS Terrain Tiles. De telles requêtes peuvent révéler la zone approximative que vous consultez.
- Achats (iOS uniquement) — les abonnements sont facturés et validés entièrement par Apple via l'App Store. Nous ne recevons qu'un statut d'abonnement, jamais vos données de paiement. La version Android est actuellement gratuite et n'initialise aucun SDK de paiement.
- Ces requêtes ne contiennent aucun compte, nom, identifiant d'appareil ou publicitaire — seulement des coordonnées. Rien d'autre ne quitte votre appareil.

### Ce qui reste sur votre appareil
- Vols et traces — stockés dans la base locale, jamais téléversés.
- Sites de décollage que vous créez ou importez, et le jeu d'espaces aériens fourni avec l'app et lu hors ligne.
- Données de capteurs — baromètre, mouvement et boussole sont traités en temps réel pour le vario et la détection du décollage et de l'atterrissage. Elles ne sont jamais enregistrées ni téléversées.
- Nom du pilote et voile — écrits seulement dans l'en-tête des fichiers IGC que vous exportez. Laissez-les vides et vos vols restent anonymes.
- Préférences et notifications — stockées localement. Sur iOS, le widget lit son aperçu dans un conteneur App Group privé partagé avec l'app ; rien ne sort de l'appareil non plus par ce chemin.

### Autorisations — et ce qui se passe si vous refusez
- Localisation, lors de l'utilisation — affiche la météo de votre position, centre la carte et enregistre votre trace.
- Localisation en arrière-plan — poursuit l'enregistrement écran éteint pour que le journal soit complet. Sur iOS c'est l'autorisation optionnelle « toujours » ; sur Android, un service d'avertissement avec une notification masquable.
- Mouvement — lit le capteur barométrique pour le taux de montée et de descente.
- Appareil photo — utilisé uniquement pour scanner un QR code qui transfère des sites depuis un autre téléphone. Les images sont décodées sur l'appareil, jamais enregistrées ni téléversées.
- Notifications — optionnelles, pour les alertes de conditions et le briefing du matin.

En refuser une laisse tout le reste fonctionner. Sans localisation, seul l'enregistrement s'arrête, et vous pouvez toujours ajouter un site en saisissant ses coordonnées.

### Conservation et vos droits
- Les journaux de vol et les sites restent sur cet appareil jusqu'à ce que vous les supprimiez ou désinstalliez l'app. L'écran « Données et confidentialité › Supprimer tous les vols » efface immédiatement et définitivement chaque session, trace et journal à la seconde.
- Désinstaller ThermalCast efface toutes les données locales.
- Une sauvegarde système peut copier cette base locale dans votre propre espace de stockage — iCloud ou sauvegarde sur ordinateur sur iOS, sauvegarde système Android (Google) sur Android. Ces sauvegardes sont gérées par Apple ou Google et nous ne pouvons pas les lire.
- Vous pouvez retirer une autorisation à tout moment dans les réglages système.
- Questions, ou demande de suppression impossible à faire dans l'app : chengjmx@gmail.com

### Enfants
ThermalCast ne s'adresse pas aux enfants de moins de 13 ans et nous ne collectons pas sciemment d'informations personnelles les concernant. Il n'y a ni compte ni inscription : aucune information personnelle n'est donc collectée.

### Sources des données
- Météo et altitude — Open-Meteo (CC BY 4.0) ; l'altitude dérive de Copernicus DEM GLO-90 © EU-ESA.
- Relief — AWS Terrain Tiles, un jeu de données d'altitude public.
- Tuiles de carte — © contributeurs OpenStreetMap, servies par OpenFreeMap.
- Espaces aériens — le jeu fourni dérive d'openAIP (openaip.net) et est lu hors ligne.

### Sécurité en vol
Les données météo, les scores de vol et les alarmes du vario sont indicatifs et ne doivent jamais être la seule base d'une décision de vol. Le parapente comporte un risque inhérent : fiez-vous toujours aux conditions réelles, à la réglementation locale et à votre propre jugement.

### Modifications de cette politique
Le texte à jour est toujours disponible sur https://jecry.github.io/thermalcast-privacy/. Si le type de données quittant votre appareil change, cette page et le texte dans l'app sont mis à jour ensemble, et la date en haut change avec eux.


---

## Italiano

**Ultimo aggiornamento: 2026-10-21**

**Tutto ciò che può essere elaborato sul tuo dispositivo resta sul tuo dispositivo.**

### Cosa non facciamo
- Nessun account — nessuna registrazione, e non chiediamo mai nome, numero di telefono o e-mail.
- Nessun SDK pubblicitario e nessun identificatore pubblicitario: nessun tracciamento, nessuna profilazione, nessun dato venduto o condiviso con data broker.
- Nessun SDK di analisi o di segnalazione crash di terze parti.
- Nessun Bluetooth — l'app non chiede mai l'accesso Bluetooth e non si associa mai a strumenti esterni.
- Nessun identificativo usato per il tracciamento — su Android non leggiamo Android ID, IMEI o l'identificatore pubblicitario; su iOS non chiediamo mai l'autorizzazione al tracciamento (IDFA).
- Nessun server nostro — nulla viene caricato su infrastrutture che gestiamo noi.

### Cosa lascia il dispositivo
- Previsioni — le coordinate del sito vengono inviate in HTTPS a Open-Meteo (api.open-meteo.com) per ottenere la previsione, e al suo endpoint di quota quando viene compilata l'altitudine del sito.
- Tile di mappa e di rilievo — le tile vengono richieste a OpenFreeMap e il rilievo al dataset pubblico AWS Terrain Tiles. Queste richieste possono rivelare l'area approssimativa che stai guardando.
- Acquisti (solo iOS) — gli abbonamenti sono fatturati e convalidati interamente da Apple tramite l'App Store. Riceviamo solo lo stato dell'abbonamento, mai i tuoi dati di pagamento. La versione Android è attualmente gratuita e non inizializza alcun SDK di pagamento.
- Queste richieste non contengono account, nome, identificativo del dispositivo o pubblicitario — solo coordinate. Nient'altro lascia il dispositivo.

### Cosa resta sul dispositivo
- Voli e tracce — salvati nel database locale, mai caricati.
- Decolli che crei o importi, e il set di spazi aerei fornito con l'app e letto offline.
- Letture dei sensori — barometro, movimento e bussola sono elaborati in tempo reale per il vario e per il rilevamento di decollo e atterraggio. Non vengono mai registrate né caricate.
- Nome pilota e vela — scritti solo nell'intestazione dei file IGC che esporti. Lasciali vuoti e i tuoi voli restano anonimi.
- Preferenze e impostazioni di notifica — salvate in locale. Su iOS il widget legge il suo snapshot da un contenitore App Group privato condiviso con l'app; anche così nulla lascia il dispositivo.

### Autorizzazioni — e cosa succede se rifiuti
- Posizione, quando in uso — mostra il meteo della tua posizione, centra la mappa e registra la traccia.
- Posizione in background — continua a registrare a schermo spento perché il log sia completo. Su iOS è l'autorizzazione facoltativa «sempre»; su Android gira come servizio in primo piano con una notifica che puoi nascondere.
- Movimento — legge il sensore barometrico per il tasso di salita e discesa.
- Fotocamera — usata solo per scansionare un QR code che trasferisce i decolli da un altro telefono. I fotogrammi sono decodificati sul dispositivo e mai salvati o caricati.
- Notifiche — facoltative, per gli avvisi sulle condizioni e il briefing del mattino.

Rifiutarne una lascia tutto il resto funzionante. Senza posizione si ferma solo la registrazione, e puoi comunque aggiungere un sito inserendo le sue coordinate.

### Conservazione e tuoi diritti
- Log di volo e siti restano su questo dispositivo finché non li elimini o disinstalli l'app. La schermata «Dati e privacy › Elimina tutti i voli» cancella subito e definitivamente ogni sessione, traccia e log al secondo.
- Disinstallare ThermalCast cancella tutti i dati locali.
- Un backup di sistema può copiare questo database locale nel tuo spazio di archiviazione — iCloud o backup su computer su iOS, backup di sistema Android (Google) su Android. Quei backup sono gestiti da Apple o Google e non possiamo leggerli.
- Puoi revocare qualsiasi autorizzazione in qualsiasi momento nelle impostazioni di sistema.
- Domande, o una richiesta di cancellazione che non puoi fare dall'app: chengjmx@gmail.com

### Minori
ThermalCast non è destinato ai bambini sotto i 13 anni e non raccogliamo consapevolmente informazioni personali su di loro. Non c'è account né registrazione, quindi non viene raccolto nulla di personale.

### Fonti dei dati
- Meteo e quota — Open-Meteo (CC BY 4.0); la quota deriva da Copernicus DEM GLO-90 © EU-ESA.
- Rilievo — AWS Terrain Tiles, un dataset di elevazione pubblico.
- Tile di mappa — © collaboratori di OpenStreetMap, servite da OpenFreeMap.
- Spazi aerei — il set incluso deriva da openAIP (openaip.net) ed è letto offline.

### Sicurezza in volo
Dati meteo, punteggi di volo e allarmi del vario sono solo indicativi e non devono mai essere l'unica base di una decisione di volo. Il parapendio comporta un rischio intrinseco: affidati sempre alle condizioni reali, alle normative locali e al tuo giudizio.

### Modifiche a questa policy
Il testo aggiornato è sempre disponibile su https://jecry.github.io/thermalcast-privacy/. Se il tipo di dati che lascia il dispositivo dovesse cambiare, questa pagina e il testo nell'app vengono aggiornati insieme, e la data in alto cambia con loro.


---

## Español

**Última actualización: 2026-10-21**

**Todo lo que puede procesarse en tu dispositivo se queda en tu dispositivo.**

### Lo que no hacemos
- Sin cuenta — sin registro, y nunca pedimos tu nombre, teléfono ni correo electrónico.
- Sin SDK publicitario ni identificador publicitario: sin seguimiento, sin elaboración de perfiles y sin datos vendidos o compartidos con intermediarios de datos.
- Sin SDK de analítica ni de informes de fallos de terceros.
- Sin Bluetooth — la app nunca pide acceso Bluetooth y nunca se empareja con instrumentos externos.
- Sin identificadores usados para seguimiento — no leemos el ID de Android, el IMEI ni el identificador publicitario en Android, y nunca solicitamos el permiso de seguimiento de iOS (IDFA).
- Sin servidor propio — no se sube nada a infraestructura que operemos nosotros.

### Lo que sale del dispositivo
- Previsiones — las coordenadas del sitio se envían por HTTPS a Open-Meteo (api.open-meteo.com) para obtener el pronóstico, y a su endpoint de elevación cuando se rellena la altitud del sitio.
- Tiles de mapa y relieve — las tiles se solicitan a OpenFreeMap y el relieve al conjunto público AWS Terrain Tiles. Estas peticiones pueden revelar la zona aproximada que estás viendo.
- Compras (solo iOS) — las suscripciones se facturan y validan íntegramente por Apple a través del App Store. Solo recibimos el estado de la suscripción, nunca tus datos de pago. La versión Android es gratuita y no inicializa ningún SDK de pago.
- Estas peticiones no incluyen cuenta, nombre, identificador de dispositivo ni publicitario — solo coordenadas. Nada más sale del dispositivo.

### Lo que se queda en el dispositivo
- Vuelos y trazas — guardados en la base de datos local, nunca subidos.
- Despegues que creas o importas, y el conjunto de espacios aéreos incluido con la app, que se lee sin conexión.
- Lecturas de sensores — barómetro, movimiento y brújula se procesan en tiempo real para el vario y para detectar despegue y aterrizaje. Nunca se graban ni se suben.
- Nombre del piloto y ala — se escriben solo en la cabecera de los IGC que exportas. Déjalos vacíos y tus vuelos seguirán siendo anónimos.
- Preferencias y notificaciones — guardadas localmente. En iOS el widget lee su snapshot de un contenedor App Group privado compartido con la app, así que tampoco por ahí sale nada del dispositivo.

### Permisos — y qué pasa si los rechazas
- Ubicación, cuando se usa — muestra el tiempo de tu posición, centra el mapa y registra tu traza.
- Ubicación en segundo plano — sigue grabando con la pantalla apagada para que el registro quede completo. En iOS es el permiso opcional «siempre»; en Android corre como servicio en primer plano con una notificación que puedes ocultar.
- Movimiento — lee el sensor barométrico para la tasa de ascenso y descenso.
- Cámara — se usa solo para escanear un código QR que transfiere despegues desde otro teléfono. Los fotogramas se decodifican en el dispositivo y nunca se guardan ni se suben.
- Notificaciones — opcionales, para avisos de condiciones y el resumen de la mañana.

Rechazar cualquiera deja el resto funcionando. Sin ubicación solo se detiene la grabación, y puedes añadir un sitio escribiendo sus coordenadas.

### Conservación y tus derechos
- Los registros de vuelo y los sitios se quedan en este dispositivo hasta que los borres o desinstales la app. La pantalla «Datos y privacidad › Eliminar todos los vuelos» borra de inmediato y de forma permanente cada sesión, traza y registro por segundo.
- Desinstalar ThermalCast borra todos los datos locales.
- Una copia de seguridad del sistema puede copiar esta base local a tu propio almacenamiento — iCloud o copia en el ordenador en iOS, copia del sistema Android (Google) en Android. Esas copias las gestionan Apple o Google y nosotros no podemos leerlas.
- Puedes retirar cualquier permiso en cualquier momento desde los ajustes del sistema.
- Dudas, o una solicitud de borrado que no puedas hacer desde la app: chengjmx@gmail.com

### Menores
ThermalCast no se dirige a menores de 13 años y no recopilamos intencionadamente información personal suya. No hay cuenta ni registro, así que no se recopila nada personal.

### Fuentes de los datos
- Tiempo y altitud — Open-Meteo (CC BY 4.0); la altitud procede de Copernicus DEM GLO-90 © EU-ESA.
- Relieve — AWS Terrain Tiles, un conjunto de elevación público.
- Tiles de mapa — © colaboradores de OpenStreetMap, servidas por OpenFreeMap.
- Espacios aéreos — el conjunto incluido procede de openAIP (openaip.net) y se lee sin conexión.

### Seguridad en vuelo
Los datos meteorológicos, las puntuaciones de vuelo y las alarmas del vario son solo orientativos y nunca deben ser la única base de una decisión de vuelo. El parapente conlleva un riesgo inherente: apóyate siempre en las condiciones reales, la normativa local y tu propio criterio.

### Cambios en esta política
El texto vigente está siempre en https://jecry.github.io/thermalcast-privacy/. Si cambia el tipo de datos que sale de tu dispositivo, esta página y el texto de la app se actualizan juntos y la fecha de arriba cambia con ellos.


---

## Português

**Última atualização: 2026-10-21**

**Tudo o que pode ser processado no seu dispositivo fica no seu dispositivo.**

### O que não fazemos
- Sem conta — sem cadastro, e nunca pedimos seu nome, telefone ou e-mail.
- Sem SDK de publicidade e sem identificador publicitário: sem rastreamento, sem perfilagem e sem dados vendidos ou compartilhados com corretores de dados.
- Sem SDK de análise ou de relatório de falhas de terceiros.
- Sem Bluetooth — o app nunca pede acesso Bluetooth e nunca se pareia com instrumentos externos.
- Sem identificadores usados para rastreamento — não lemos o Android ID, o IMEI nem o identificador publicitário no Android, e nunca solicitamos a permissão de rastreamento do iOS (IDFA).
- Sem servidor próprio — nada é enviado para infraestrutura que operamos.

### O que sai do dispositivo
- Previsões — as coordenadas do local são enviadas por HTTPS ao Open-Meteo (api.open-meteo.com) para buscar a previsão, e ao seu endpoint de elevação quando a altitude do local é preenchida.
- Tiles de mapa e relevo — os tiles vêm do OpenFreeMap e o relevo do conjunto público AWS Terrain Tiles. Essas requisições podem revelar a região aproximada que você está vendo.
- Compras (somente iOS) — as assinaturas são cobradas e validadas inteiramente pela Apple na App Store. Recebemos apenas o status da assinatura, nunca seus dados de pagamento. A versão Android é gratuita e não inicializa nenhum SDK de pagamento.
- Essas requisições não levam conta, nome, identificador de dispositivo ou publicitário — apenas coordenadas. Nada mais sai do dispositivo.

### O que fica no dispositivo
- Voos e trilhas — guardados no banco local, nunca enviados.
- Decolagens que você cria ou importa, e o conjunto de espaços aéreos que acompanha o app e é lido offline.
- Leituras de sensores — barômetro, movimento e bússola são processados em tempo real para o variômetro e para detectar decolagem e pouso. Nunca são gravadas nem enviadas.
- Nome do piloto e asa — escritos apenas no cabeçalho dos IGC que você exporta. Deixe vazios e seus voos permanecem anônimos.
- Preferências e notificações — guardadas localmente. No iOS o widget lê seu snapshot de um contêiner App Group privado compartilhado com o app, então nada sai do dispositivo por esse caminho tampouco.

### Permissões — e o que acontece se você recusar
- Localização, ao usar — mostra o tempo da sua posição, centraliza o mapa e grava sua trilha.
- Localização em segundo plano — continua gravando com a tela apagada para que o registro fique completo. No iOS é a permissão opcional «sempre»; no Android roda como serviço em primeiro plano com uma notificação que você pode ocultar.
- Movimento — lê o sensor barométrico para a taxa de subida e descida.
- Câmera — usada apenas para ler um QR code que transfere decolagens de outro telefone. Os quadros são decodificados no dispositivo e nunca salvos ou enviados.
- Notificações — opcionais, para alertas de condições e o resumo da manhã.

Recusar qualquer uma deixa o resto funcionando. Sem localização apenas a gravação para, e você ainda pode adicionar um local digitando suas coordenadas.

### Retenção e seus direitos
- Registros de voo e locais ficam neste dispositivo até você os apagar ou desinstalar o app. A tela «Dados e privacidade › Excluir todos os voos» apaga imediata e permanentemente cada sessão, trilha e registro por segundo.
- Desinstalar o ThermalCast apaga todos os dados locais.
- Um backup do sistema pode copiar este banco local para o seu próprio armazenamento — iCloud ou backup no computador no iOS, backup do sistema Android (Google) no Android. Esses backups são gerenciados pela Apple ou pelo Google e não conseguimos lê-los.
- Você pode revogar qualquer permissão a qualquer momento nos ajustes do sistema.
- Dúvidas, ou um pedido de exclusão que não consiga fazer pelo app: chengjmx@gmail.com

### Crianças
O ThermalCast não se destina a menores de 13 anos e não coletamos intencionalmente informações pessoais delas. Não há conta nem cadastro, portanto nada pessoal é coletado.

### Fontes dos dados
- Tempo e elevação — Open-Meteo (CC BY 4.0); a elevação deriva de Copernicus DEM GLO-90 © EU-ESA.
- Relevo — AWS Terrain Tiles, um conjunto de elevação público.
- Tiles de mapa — © colaboradores do OpenStreetMap, servidos pelo OpenFreeMap.
- Espaços aéreos — o conjunto incluído deriva de openAIP (openaip.net) e é lido offline.

### Segurança de voo
Dados meteorológicos, pontuações de voo e alarmes do variômetro são apenas orientativos e nunca devem ser a única base de uma decisão de voo. O parapente tem risco inerente: apoie-se sempre nas condições reais, nas normas locais e no seu próprio julgamento.

### Alterações nesta política
O texto atual está sempre em https://jecry.github.io/thermalcast-privacy/. Se o tipo de dado que sai do seu dispositivo mudar, esta página e o texto no app são atualizados juntos, e a data no topo muda com eles.


---

## Türkçe

**Son güncelleme: 2026-10-21**

**Cihazınızda işlenebilen her şey cihazınızda kalır.**

### Yapmadıklarımız
- Hesap yok — kayıt yok; adınızı, telefon numaranızı veya e-postanızı hiç istemiyoruz.
- Reklam SDK'sı ve reklam tanımlayıcısı yok: izleme yok, profilleme yok, veri komisyoncularına satılan veya paylaşılan veri yok.
- Üçüncü taraf analitik veya çökme raporu SDK'sı yok.
- Bluetooth yok — uygulama hiç Bluetooth izni istemez ve harici cihazlarla eşleşmez.
- İzleme için kullanılan tanımlayıcı yok — Android'de Android ID, IMEI veya reklam tanımlayıcısını okumuyoruz ve iOS'ta izleme iznini (IDFA) hiç istemiyoruz.
- Kendimize ait sunucu yok — işlettiğimiz bir altyapıya hiçbir şey yüklenmez.

### Cihazdan çıkanlar
- Tahminler — hava tahminini almak için saha koordinatları HTTPS ile Open-Meteo'ya (api.open-meteo.com), saha irtifası doldurulurken de yükseklik uç noktasına gönderilir.
- Harita ve arazi karoları — karolar OpenFreeMap'ten, arazi gölgelendirmesi herkese açık AWS Terrain Tiles veri kümesinden gelir. Bu istekler baktığınız yaklaşık bölgeyi belli edebilir.
- Satın almalar (yalnızca iOS) — abonelikler tamamen Apple tarafından App Store üzerinden faturalanır ve doğrulanır. Yalnızca abonelik durumunu alırız, ödeme bilgilerinizi asla almayız. Android sürümü şu anda ücretsizdir ve hiçbir ödeme SDK'sı başlatmaz.
- Bu isteklerde hesap, ad, cihaz veya reklam tanımlayıcısı bulunmaz — yalnızca koordinatlar. Bunun dışında cihazınızdan hiçbir şey çıkmaz.

### Cihazda kalanlar
- Uçuşlar ve izler — cihazdaki veritabanında saklanır, asla yüklenmez.
- Oluşturduğunuz veya içe aktardığınız kalkış alanları ve uygulamayla gelen, çevrimdışı okunan hava sahası veri kümesi.
- Sensör okumaları — barometre, hareket ve pusula; vario ile kalkış ve iniş tespiti için gerçek zamanlı işlenir. Hiç kaydedilmez veya yüklenmez.
- Pilot adı ve kanat — yalnızca dışa aktardığınız IGC dosyalarının başlığına yazılır. Boş bırakırsanız uçuşlarınız anonim kalır.
- Tercihler ve bildirim ayarları — yerel olarak saklanır. iOS'ta widget, uygulamayla paylaşılan özel bir App Group kapsayıcısından anlık görüntüyü okur; bu yolla da cihazdan hiçbir şey çıkmaz.

### İzinler — ve reddederseniz ne olur
- Konum, uygulamayı kullanırken — bulunduğunuz yerin havasını gösterir, haritayı ortalar ve izinizi kaydeder.
- Arka planda konum — ekran kapalıyken kayda devam ederek kaydı tamamlar. iOS'ta bu, isteğe bağlı «her zaman» iznidir; Android'de gizlenebilir bildirimli bir ön plan servisi olarak çalışır.
- Hareket — tırmanma ve süzülme oranı için barometrik sensörü okur.
- Kamera — yalnızca başka bir telefondan kalkış alanı aktaran bir QR kodu taramak için kullanılır. Kareler cihazda çözülür, asla kaydedilmez veya yüklenmez.
- Bildirimler — isteğe bağlı; koşul uyarıları ve sabah brifingi için.

Bunlardan birini reddetmek geri kalanın çalışmasını engellemez. Konum olmadan yalnızca uçuş kaydı durur; koordinatlarını yazarak yine saha ekleyebilirsiniz.

### Saklama süresi ve haklarınız
- Uçuş kayıtları ve sahalar, siz silene veya uygulamayı kaldırana kadar bu cihazda kalır. «Veri ve gizlilik › Tüm uçuşları sil» ekranı her oturumu, izi ve saniye bazlı kaydı anında ve kalıcı olarak siler.
- ThermalCast'i kaldırmak tüm yerel verileri siler.
- Bir sistem yedeği bu yerel veritabanını kendi depolama alanınıza kopyalayabilir — iOS'ta iCloud veya bilgisayar yedeği, Android'de Android sistem yedeği (Google). Bu yedekleri Apple veya Google yönetir, biz okuyamayız.
- Herhangi bir izni sistem ayarlarından istediğiniz zaman geri alabilirsiniz.
- Sorularınız, veya uygulamada yapamadığınız bir silme talebi için: chengjmx@gmail.com

### Çocuklar
ThermalCast 13 yaş altı çocuklara yönelik değildir ve onlardan bilerek kişisel bilgi toplamıyoruz. Hesap ve kayıt olmadığı için zaten kişisel bir veri toplanmıyor.

### Veri kaynakları
- Hava ve yükseklik — Open-Meteo (CC BY 4.0); yükseklik Copernicus DEM GLO-90 © EU-ESA'dan türetilir.
- Arazi gölgelendirme — AWS Terrain Tiles, herkese açık yükseklik veri kümesi.
- Harita karoları — © OpenStreetMap katkıda bulunanlar, OpenFreeMap tarafından sunulur.
- Hava sahaları — birlikte gelen veri kümesi openAIP'ten (openaip.net) türetilir ve çevrimdışı okunur.

### Uçuş güvenliği
Hava verileri, uçuş puanları ve vario alarmları yalnızca tavsiye niteliğindedir ve bir uçuş kararının tek dayanağı olmamalıdır. Yamaç paraşütü doğası gereği risk taşır: her zaman gerçek koşullara, yerel kurallara ve kendi değerlendirmenize güvenin.

### Bu politikanın değişmesi
Güncel metin her zaman https://jecry.github.io/thermalcast-privacy/ adresindedir. Cihazınızdan çıkan verinin türü değişirse, bu sayfa ve uygulama içindeki metin birlikte güncellenir ve üstteki tarih de onlarla birlikte değişir.


---

## 日本語

**最終更新：2026-10-21**

**端末で処理できることは、すべて端末の中だけで処理します。**

### 行わないこと
- アカウントなし —— 登録は不要で、氏名・電話番号・メールアドレスを求めることもありません。
- 広告 SDK と広告識別子なし —— トラッキングやプロファイリングは行わず、データをデータブローカーに販売・共有することもありません。
- サードパーティの解析・クラッシュレポート SDK なし。
- Bluetooth なし —— Bluetooth のアクセス権を要求することも、外部計器とペアリングすることもありません。
- 追跡用の識別子なし —— Android では Android ID・IMEI・広告識別子を読み取らず、iOS ではトラッキング許可（IDFA）を要求しません。
- 自社サーバーなし —— 当社が運用するインフラにアップロードされるものはありません。

### 端末外に出るデータ
- 予報 —— 予報の取得のため、場地の座標を HTTPS で Open-Meteo（api.open-meteo.com）へ送信します。場地の標高を補完するときは標高エンドポイントへも送信します。
- 地図・地形タイル —— 地図タイルは OpenFreeMap、地形表現は公開データセット AWS Terrain Tiles から取得します。これらのリクエストは、あなたが見ている大まかな地域を示す可能性があります。
- 購入（iOS のみ）—— サブスクリプションは Apple が App Store を通じて課金・検証をすべて行います。当社が受け取るのは購読状態のみで、支払い情報を受け取ることはありません。Android 版は現在無料で、支払い SDK も初期化していません。
- これらのリクエストに、アカウント・氏名・端末識別子・広告識別子は含まれません —— 含まれるのは座標だけです。これ以外に端末外へ出るものはありません。

### 端末内に残るデータ
- フライトと航跡 —— 端末内データベースに保存され、アップロードされることはありません。
- 作成・取り込みした離陸地、およびアプリ同梱の空域データ（オフラインで読み込み）。
- センサー値 —— 気圧計・モーション・コンパスはバリオと離陸／着陸判定のためにリアルタイム処理され、記録もアップロードもされません。
- パイロット名とグライダー —— 書き出した IGC ファイルのヘッダーにのみ記録されます。空欄にすればフライトは匿名のままです。
- 設定と通知設定 —— 端末内にのみ保存されます。iOS のウィジェットはアプリと共有するプライベートな App Group コンテナからスナップショットを読み、この経路でもデータが端末外に出ることはありません。

### 権限と、拒否した場合の挙動
- 位置情報（使用中）—— 現在地の天気表示、地図の中心合わせ、航跡の記録に使います。
- バックグラウンド位置情報 —— 画面オフでも記録を継続し、ログを完全に保ちます。iOS では任意の「常に」権限、Android では非通知にできる通知付きのフォアグラウンドサービスとして動作します。
- モーション —— 昇降率のために気圧センサーを読みます。
- カメラ —— 他の端末から離陸地を受け取る QR コードの読み取り専用です。フレームは端末内でデコードされ、保存もアップロードもされません。
- 通知 —— 任意。コンディション通知とモーニングブリーフィングに使います。

どれを拒否しても、他の機能はそのまま動作します。位置情報がない場合はフライト記録のみ停止し、座標を入力して場地を追加することは可能です。

### 保存期間とあなたの権利
- フライトログと場地は、削除するかアプリをアンインストールするまでこの端末に残ります。「データとプライバシー › すべてのフライト記録を削除」は、すべてのセッション・航跡・毎秒ログを即座に完全削除します。
- ThermalCast をアンインストールすると、ローカルデータはすべて消去されます。
- システムバックアップが、このローカルデータベースをあなた自身のストレージにコピーする場合があります —— iOS では iCloud またはコンピュータのバックアップ、Android では Android システムバックアップ（Google）。これらのバックアップは Apple または Google が管理し、当社は閲覧できません。
- 各権限はシステム設定からいつでも取り消せます。
- ご質問、またはアプリ内で対応できない削除依頼：chengjmx@gmail.com

### 子どもについて
ThermalCast は 13 歳未満の子どもを対象としておらず、意図的に個人情報を収集することもありません。アカウントも登録もないため、そもそも個人情報は収集されません。

### データの出典
- 天気と標高 —— Open-Meteo（CC BY 4.0）。標高は Copernicus DEM GLO-90 © EU-ESA に由来します。
- 地形表現 —— AWS Terrain Tiles（公開標高データセット）。
- 地図タイル —— © OpenStreetMap 貢献者、配信は OpenFreeMap。
- 空域 —— 同梱データは openAIP（openaip.net）由来で、オフラインで読み込みます。

### フライトの安全
天気データ、フライトスコア、バリオアラームは参考情報であり、フライト判断の唯一の根拠にしてはなりません。パラグライダーには本質的な危険が伴います。常に実際のコンディション、現地の規則、そして自身の判断に依拠してください。

### 本ポリシーの変更
最新のテキストは常に https://jecry.github.io/thermalcast-privacy/ にあります。端末外に出るデータの種類が変わる場合は、このページとアプリ内のテキストを同時に更新し、上部の日付も併せて変更します。


---

## 한국어

**최종 업데이트: 2026-10-21**

**기기에서 처리할 수 있는 모든 것은 기기에 남습니다.**

### 하지 않는 것
- 계정 없음 — 가입이 없으며 이름, 전화번호, 이메일을 요구하지 않습니다.
- 광고 SDK와 광고 식별자 없음 — 추적이나 프로파일링을 하지 않고, 데이터 브로커에게 데이터를 판매하거나 공유하지 않습니다.
- 서드파티 분석·크래시 리포트 SDK 없음.
- 블루투스 없음 — 앱은 블루투스 권한을 요청하지 않으며 외부 기기와 페어링하지 않습니다.
- 추적용 식별자 없음 — Android에서는 Android ID, IMEI, 광고 식별자를 읽지 않으며, iOS에서는 추적 허용(IDFA)을 요청하지 않습니다.
- 자체 서버 없음 — 우리가 운영하는 인프라에는 아무것도 업로드되지 않습니다.

### 기기를 나가는 데이터
- 예보 — 예보를 받기 위해 사이트 좌표를 HTTPS로 Open-Meteo(api.open-meteo.com)에 보냅니다. 사이트 고도를 채울 때는 고도 엔드포인트에도 보냅니다.
- 지도 및 지형 타일 — 지도 타일은 OpenFreeMap, 지형 음영은 공개 데이터셋 AWS Terrain Tiles에서 가져옵니다. 이 요청은 사용자가 보고 있는 대략적인 지역을 드러낼 수 있습니다.
- 구매(iOS 전용) — 구독은 Apple이 App Store를 통해 전적으로 청구하고 검증합니다. 우리는 구독 상태만 받으며 결제 정보는 절대 받지 않습니다. Android 버전은 현재 무료이며 어떤 결제 SDK도 초기화하지 않습니다.
- 이 요청에는 계정, 이름, 기기 식별자, 광고 식별자가 포함되지 않습니다 — 좌표만 포함됩니다. 그 밖에 기기를 나가는 것은 없습니다.

### 기기에 남는 데이터
- 비행 기록과 항적 — 기기 내 데이터베이스에 저장되며 업로드되지 않습니다.
- 직접 만들거나 가져온 이륙지, 그리고 앱에 포함되어 오프라인으로 읽히는 공역 데이터.
- 센서 값 — 기압계, 모션, 나침반은 변계기와 이륙·착륙 판정을 위해 실시간 처리되며 기록되거나 업로드되지 않습니다.
- 파일럿 이름과 글라이더 — 내보낸 IGC 파일의 헤더에만 기록됩니다. 비워 두면 비행은 익명으로 남습니다.
- 환경설정과 알림 설정 — 기기에만 저장됩니다. iOS의 위젯은 앱과 공유하는 비공개 App Group 컨테이너에서 스냅샷을 읽으며, 이 경로로도 데이터는 기기를 나가지 않습니다.

### 권한과 거부했을 때의 동작
- 위치(사용 중) — 현재 위치의 날씨 표시, 지도 중앙 정렬, 항적 기록에 사용합니다.
- 백그라운드 위치 — 화면이 꺼져도 기록을 이어가 로그를 완전하게 유지합니다. iOS에서는 선택 사항인 '항상' 권한이고, Android에서는 숨길 수 있는 알림이 있는 포그라운드 서비스로 동작합니다.
- 모션 — 상승·하강률을 위해 기압 센서를 읽습니다.
- 카메라 — 다른 기기에서 이륙지를 받는 QR 코드 스캔에만 사용합니다. 프레임은 기기에서 디코딩되며 저장되거나 업로드되지 않습니다.
- 알림 — 선택 사항. 컨디션 알림과 아침 브리핑에 사용합니다.

어느 것을 거부해도 나머지는 그대로 동작합니다. 위치가 없으면 비행 기록만 멈추며, 좌표를 직접 입력해 이륙지를 추가할 수 있습니다.

### 보관 기간과 사용자의 권리
- 비행 기록과 이륙지는 삭제하거나 앱을 삭제할 때까지 이 기기에 남습니다. «데이터 및 개인정보 › 모든 비행 기록 삭제» 화면은 모든 세션, 항적, 초단위 로그를 즉시 영구 삭제합니다.
- ThermalCast를 삭제하면 모든 로컬 데이터가 지워집니다.
- 시스템 백업이 이 로컬 데이터베이스를 사용자 본인의 저장소에 복사할 수 있습니다 — iOS는 iCloud 또는 컴퓨터 백업, Android는 Android 시스템 백업(Google). 이 백업은 Apple 또는 Google이 관리하며 우리는 읽을 수 없습니다.
- 어떤 권한이든 시스템 설정에서 언제든 철회할 수 있습니다.
- 문의, 또는 앱에서 처리할 수 없는 삭제 요청: chengjmx@gmail.com

### 아동
ThermalCast는 13세 미만 아동을 대상으로 하지 않으며, 의도적으로 개인정보를 수집하지 않습니다. 계정과 가입이 없으므로 애초에 개인정보가 수집되지 않습니다.

### 데이터 출처
- 날씨와 고도 — Open-Meteo(CC BY 4.0). 고도는 Copernicus DEM GLO-90 © EU-ESA에서 파생됩니다.
- 지형 음영 — AWS Terrain Tiles(공개 고도 데이터셋).
- 지도 타일 — © OpenStreetMap 기여자, OpenFreeMap이 제공.
- 공역 — 함께 제공되는 데이터는 openAIP(openaip.net)에서 파생되며 오프라인으로 읽습니다.

### 비행 안전
날씨 데이터, 비행 점수, 변계기 알람은 참고용이며 비행 결정의 유일한 근거가 되어서는 안 됩니다. 패러글라이딩에는 본질적인 위험이 따릅니다. 항상 실제 컨디션, 현지 규정, 그리고 자신의 판단에 의존하세요.

### 본 정책의 변경
최신 본문은 항상 https://jecry.github.io/thermalcast-privacy/ 에 있습니다. 기기를 나가는 데이터의 종류가 바뀌면 이 페이지와 앱 내 문구가 함께 갱신되고, 맨 위의 날짜도 함께 바뀝니다.


---

## Slovenščina

**Zadnja posodobitev: 2026-10-21**

**Vse, kar je mogoče obdelati na vaši napravi, ostane na vaši napravi.**

### Česa ne počnemo
- Ni računa — ni registracije in nikoli ne zahtevamo vašega imena, telefonske številke ali e-pošte.
- Ni oglaševalskega SDK-ja in ni oglaševalskega identifikatorja: brez sledenja, brez profiliranja in brez prodaje ali deljenja podatkov s posredniki podatkov.
- Ni SDK-ja tretjih oseb za analitiko ali poročila o sesutjih.
- Ni Bluetootha — aplikacija nikoli ne zahteva dostopa do Bluetootha in se nikoli ne povezuje z zunanjimi instrumenti.
- Ni identifikatorjev za sledenje — na Androidu ne beremo Android ID, IMEI ali oglaševalskega identifikatorja, na iOSu pa nikoli ne zahtevamo dovoljenja za sledenje (IDFA).
- Ni našega strežnika — nič se ne nalaga na infrastrukturo, ki jo upravljamo.

### Kaj zapusti napravo
- Napovedi — koordinate lokacije se prek HTTPS pošljejo na Open-Meteo (api.open-meteo.com) za pridobitev napovedi, in na njegov končni točki za višino, ko se vpiše nadmorska višina lokacije.
- Ploščice zemljevida in reliefa — ploščice prihajajo iz OpenFreeMap, relief pa iz javnega nabora AWS Terrain Tiles. Takšne zahteve lahko razkrijejo približno območje, ki si ga ogledujete.
- Nakupi (samo iOS) — naročnine v celoti zaračuna in preveri Apple prek trgovine App Store. Prejmemo samo stanje naročnine, nikoli vaših plačilnih podatkov. Različica za Android je trenutno brezplačna in ne inicializira nobenega SDK-ja za plačila.
- Te zahteve ne vsebujejo računa, imena, identifikatorja naprave ali oglaševalskega identifikatorja — samo koordinate. Nič drugega ne zapusti naprave.

### Kaj ostane na napravi
- Leti in sledi — shranjeni v lokalni bazi, nikoli naloženi.
- Vzletišča, ki jih ustvarite ali uvozite, in nabor zračnih prostorov, ki je priložen aplikaciji in se bere brez povezave.
- Odčitki senzorjev — barometer, gibanje in kompas se obdelujejo v realnem času za variometer ter zaznavanje vzleta in pristanka. Nikoli se ne zapišejo ali naložijo.
- Ime pilota in krilo — zapišeta se samo v glavo izvoženih datotek IGC. Če ju pustite prazna, ostanejo vaši leti anonimni.
- Nastavitve in obvestila — shranjeni lokalno. Na iOSu pripomoček bere svoj posnetek iz zasebnega vsebnika App Group, ki si ga deli z aplikacijo, zato tudi po tej poti nič ne zapusti naprave.

### Dovoljenja — in kaj se zgodi, če jih zavrnete
- Lokacija, med uporabo — prikaže vreme za vaš položaj, centrira zemljevid in snema vašo sled.
- Lokacija v ozadju — snema tudi ob izklopljenem zaslonu, da je dnevnik popoln. Na iOSu je to izbirno dovoljenje »vedno«; na Androidu deluje kot storitev v ospredju z obvestilom, ki ga lahko skrijete.
- Gibanje — bere barometrični senzor za hitrost vzpenjanja in spuščanja.
- Kamera — uporablja se samo za branje kode QR, ki prenese vzletišča z drugega telefona. Slike se dekodirajo na napravi in se nikoli ne shranijo ali naložijo.
- Obvestila — izbirna, za opozorila o razmerah in jutranji povzetek.

Zavrnitev katerega koli od njih pusti preostanek aplikacije delujoč. Brez lokacije se ustavi samo snemanje leta, lokacijo pa lahko dodate tako, da vnesete njene koordinate.

### Hramba in vaše pravice
- Dnevniki letov in lokacije ostanejo na tej napravi, dokler jih ne izbrišete ali odstranite aplikacije. Zaslon »Podatki in zasebnost › Izbriši vse lete« takoj in trajno izbriše vsako sejo, sled in dnevnik po sekundah.
- Odstranitev aplikacije ThermalCast izbriše vse lokalne podatke.
- Sistemska varnostna kopija lahko to lokalno bazo kopira v vašo lastno shrambo — iCloud ali kopija na računalniku na iOSu, sistemska kopija Android (Google) na Androidu. Te kopije upravljata Apple ali Google in jih ne moremo brati.
- Vsako dovoljenje lahko kadar koli prekličete v sistemskih nastavitvah.
- Vprašanja ali zahtevek za izbris, ki ga v aplikaciji ne morete izvesti: chengjmx@gmail.com

### Otroci
ThermalCast ni namenjen otrokom, mlajšim od 13 let, in zavestno ne zbiramo njihovih osebnih podatkov. Ni računa in ni registracije, zato osebni podatki sploh niso zbrani.

### Viri podatkov
- Vreme in višina — Open-Meteo (CC BY 4.0); višina izhaja iz Copernicus DEM GLO-90 © EU-ESA.
- Relief — AWS Terrain Tiles, javni nabor podatkov o višini.
- Ploščice zemljevida — © sodelavci OpenStreetMap, streže OpenFreeMap.
- Zračni prostori — priloženi nabor izhaja iz openAIP (openaip.net) in se bere brez povezave.

### Varnost letenja
Vremenski podatki, ocene leta in alarmi variometra so samo informativni in nikoli ne smejo biti edina podlaga za odločitev o letu. Jadralno padalstvo prinaša lastno tveganje: vedno se zanašajte na dejanske razmere, lokalne predpise in lastno presojo.

### Spremembe te politike
Trenutno besedilo je vedno na voljo na https://jecry.github.io/thermalcast-privacy/. Če se vrsta podatkov, ki zapustijo napravo, spremeni, se ta stran in besedilo v aplikaciji posodobita skupaj, z njima pa se spremeni tudi datum na vrhu.


---

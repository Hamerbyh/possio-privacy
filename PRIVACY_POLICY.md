# Possio Privacy Policy / 隐私政策

_Last updated / 最后更新：2026-06-24_

---

## English

Possio ("the app", "we") is a privacy-first personal net-worth tracker. This
policy explains what data the app handles and how. The short version: **all of
your financial data stays on your device, and we do not collect, transmit, sell,
or share any of it.**

### Data we collect

**None.** Possio does not have user accounts, does not require sign-up, and
does not send your financial data anywhere. We do not collect names, emails,
contacts, location, advertising identifiers, analytics, or usage data.

### Data stored on your device

The accounts, balances, balance-history snapshots, and settings you enter are
stored **only on your device** using Apple's on-device database (SwiftData).
This data never leaves your device except when you explicitly export it (see
"Data export" below). It is included in your encrypted device backups (iCloud or
local) according to your own iOS backup settings; we have no access to those
backups.

### Network access

Possio makes exactly one kind of network request: it fetches **reference
foreign-exchange rates** from the public Frankfurter API
(`https://api.frankfurter.dev`) so it can convert non-base-currency accounts
into your base currency. These requests:

- send only a currency code (e.g. "USD") and a target currency code,
- contain **no personal data, no account information, and no identifiers**,
- are anonymous and are not used to track you.

Fetched rates are cached on your device. If you never hold a foreign-currency
account, the app makes no network requests at all.

### Face ID / Touch ID

If you enable the optional app lock, Possio uses Apple's local
authentication (Face ID, Touch ID, or your device passcode) solely to unlock the
app on your device. This authentication is handled entirely by iOS; the app
never receives, stores, or transmits your biometric data.

### Data export

You can export your data to a CSV file from Settings. This file is created by
you, saved wherever you choose via the iOS share sheet, and is entirely under
your control. We never receive a copy.

### Data deletion

You can permanently delete all local data at any time from Settings → "删除全部
本地数据" (Delete all local data). Because nothing is stored on our servers
(we have none), deleting it on-device deletes it completely. Removing the app
also removes its data.

### Third parties

The only third-party service contacted is the Frankfurter exchange-rate API, and
only for anonymous rate lookups as described above. We do not use any
advertising, analytics, crash-reporting, or tracking SDKs.

### Children

Possio is a general-audience finance utility and is not directed at children.
It collects no personal data from anyone, including children.

### Not financial advice

Possio is a record-keeping tool. It does not provide investment, tax, or
financial advice, and is not connected to any bank or brokerage.

### Changes to this policy

If this policy changes, the "Last updated" date above will change. Material
changes will be reflected in an app update.

### Contact

Questions about privacy: **waynebyh@gmail.com**

---

## 简体中文

Possio（“本应用”“我们”）是一款隐私优先的个人净资产记录工具。本政策说明应用
如何处理数据。简而言之：**你的全部财务数据都保存在你自己的设备上，我们不收集、不
传输、不出售、不共享其中任何内容。**

### 我们收集的数据

**无。** Possio 没有账号体系、无需注册，也不会把你的财务数据发送到任何地方。我们
不收集姓名、邮箱、通讯录、位置、广告标识符、分析或使用数据。

### 保存在你设备上的数据

你录入的账户、余额、余额历史快照和设置，仅通过 Apple 的设备本地数据库
（SwiftData）**保存在你的设备上**。除非你主动导出（见下文“数据导出”），这些数据
不会离开你的设备。它们会按你自己的 iOS 备份设置进入你的加密设备备份（iCloud 或本地
备份）；我们无法访问这些备份。

### 网络访问

Possio 只会发起一种网络请求：从公开的 Frankfurter 接口
（`https://api.frankfurter.dev`）获取**参考外汇汇率**，用于把非主货币账户折算到你的
主货币。这类请求：

- 只发送货币代码（例如 “USD”）和目标货币代码，
- **不包含任何个人信息、账户信息或标识符**，
- 是匿名的，不会用于追踪你。

获取到的汇率会缓存在你的设备上。如果你没有任何外币账户，应用完全不会发起网络请求。

### Face ID / Touch ID

如果你开启了可选的应用锁，Possio 会使用 Apple 的本地身份验证（Face ID、Touch ID
或设备密码）来在本机解锁应用。该验证完全由 iOS 处理；应用不会接收、保存或传输你的
生物识别数据。

### 数据导出

你可以在“设置”里把数据导出为 CSV 文件。该文件由你生成，通过 iOS 分享面板保存到你
选择的位置，完全由你掌控。我们不会收到副本。

### 数据删除

你可以随时在“设置 → 删除全部本地数据”中永久删除所有本地数据。由于我们没有任何
服务器、不在服务器上保存任何内容，在设备上删除即彻底删除。卸载应用也会一并删除其
数据。

### 第三方

唯一会联络的第三方服务是 Frankfurter 汇率接口，且仅用于上文所述的匿名汇率查询。我们
不使用任何广告、分析、崩溃上报或追踪 SDK。

### 儿童

Possio 是面向一般用户的财务工具，并非面向儿童。它不向任何人（包括儿童）收集个人
数据。

### 非投资建议

Possio 是记录工具，不提供投资、税务或理财建议，也不连接任何银行或券商。

### 政策变更

若本政策发生变更，上方的“最后更新”日期会随之更新。重大变更将在应用更新中体现。

### 联系方式

隐私相关问题请联系：**waynebyh@gmail.com**

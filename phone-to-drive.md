# Privacy Policy

**Effective date:** May 13, 2026
**App:** PhoneToDrive (中文：相册备份)
**Developer:** OK Tool

---

## Summary

PhoneToDrive is an iPhone app that backs up the photos and videos in your system Photos library to an external drive (SSD, hard drive, or SD card reader) connected to your iPhone.

**We do not collect, transmit, store, or sell any of your personal data or media.** Everything happens on your device.

This policy explains exactly what the app does with your photos, what permissions it requests, and what (very little) information ever leaves your phone.

---

## 1. Information We Do Not Collect

PhoneToDrive does **not** collect, transmit, or store:

- Your photos, videos, or any media content
- Your name, email address, phone number, or location
- Your device identifier, advertising ID, or IP address
- Usage analytics, crash reports, or telemetry of any kind
- Any information about which files you back up or where you back them up to

We do not operate any server. The app has no account system. There is nothing to log in to.

---

## 2. Photos Library Access

To do its job, PhoneToDrive requests **Photos access (Read / Write)** through Apple's PhotoKit framework. This permission is used for two specific purposes only:

### 2.1 Reading photos and videos (always, with your permission)

When you grant Photos access, the app reads the metadata and original file data of your photos and videos so that it can copy them to the external drive you choose. **The file data never leaves your device** — it streams directly from PhotoKit into the file you write on the external drive.

Original EXIF metadata, GPS data, and shooting dates are preserved exactly as they are in your Photos library.

### 2.2 Deleting originals (only when you explicitly ask)

After a backup completes successfully, the Backup Complete screen offers a button labeled **"Delete N Originals from Photos."** This button is **off by default** and only does anything when you tap it.

When you tap it:

1. iOS itself shows a system confirmation dialog asking you to approve the deletion. We do not control this dialog — it is enforced by iOS.
2. If you tap **"Don't Allow"** in that dialog, nothing is deleted.
3. If you confirm, **only the photos and videos that were successfully backed up in this session** are removed from your Photos library. Failed or cancelled items are never touched.

The app never deletes anything automatically. It never modifies, edits, renames, or moves any photo or video. It only ever reads photos, and (if you explicitly request it) deletes them via Apple's confirmation flow.

---

## 3. External Drive Access

When you tap **Backup**, iOS shows the system file picker so you can choose a target folder on your external drive. iOS grants the app temporary, sandboxed permission to write to that folder for the duration of the current backup. The app does not store this permission across launches — you pick a folder each time.

The app only writes files inside the folder you choose. It does not read other files on the drive.

---

## 4. Data Stored on Your Device

The app stores two small preferences in your iPhone's local storage (`UserDefaults`):

- **Your language choice** (system default, English, or Simplified Chinese)
- **Your purchase status** (whether you have unlocked Pro)

These never leave your device.

The app does **not** keep a history of what you backed up, where you backed it up to, when you backed it up, or any thumbnail / preview of your content.

---

## 5. In-App Purchase (Pro)

PhoneToDrive offers an optional one-time Pro upgrade for unlimited backups. Purchases are processed entirely by **Apple's App Store via StoreKit 2**. Apple handles your payment information; we never see your credit card, billing address, or Apple ID.

We receive only a signed receipt from Apple confirming that the Pro upgrade has been purchased. This receipt is verified locally on your device. We do not store any purchase information on any server.

Refunds, family sharing, and restore-purchase are handled by Apple. To request a refund, use Apple's standard refund process.

---

## 6. Network Access

PhoneToDrive does **not** make network requests for its own purposes. The app has no analytics, no remote configuration, no ad SDKs, and no third-party trackers.

The only network activity that may occur is initiated by iOS itself when you make an in-app purchase (StoreKit talks to Apple's servers to verify your purchase). The app never sees the content of these calls.

---

## 7. Third-Party Services

PhoneToDrive uses:

- **Apple PhotoKit** (system framework, no third party) — to read photos/videos and, when you explicitly request, delete originals.
- **Apple StoreKit 2** (system framework, no third party) — to handle the optional Pro upgrade.

The app does **not** integrate any third-party analytics SDK, advertising SDK, crash-reporting SDK, or backend service.

---

## 8. Children's Privacy

PhoneToDrive is not directed at children under 13. Because the app collects no personal information from anyone, it collects no personal information from children.

---

## 9. Your Rights

Because we do not collect any personal data from you, there is no personal data for us to access, correct, export, or delete on your behalf.

Photos in your iPhone Photos library remain entirely under your control through the iOS Settings app, where you can revoke or change PhoneToDrive's Photos access at any time.

---

## 10. Changes to This Policy

If we make material changes to this policy in the future, we will update the **Effective date** at the top of this document and post the new version at the same URL. Because the app has no account system, we have no way to email you about changes — please check this page if you want to stay current.

---

## 11. Contact Us

Questions about this privacy policy or how the app handles data:

- **Email:** hello@oktool.ai

We try to reply within 3 business days.

---
---

# 隐私政策

**生效日期：** 2026 年 5 月 13 日
**应用：** PhoneToDrive（中文：相册备份）
**开发者：** OK Tool

---

## 摘要

PhoneToDrive 是一款 iPhone 应用，作用是把你系统相册中的照片和视频备份到连接 iPhone 的外接磁盘（SSD、移动硬盘、SD 卡读卡器等）。

**我们不收集、不传输、不存储、不出售你的任何个人数据或媒体内容。** 一切操作都在你的设备本地完成。

本政策详细说明：应用如何处理你的照片、申请了哪些权限、有哪些（极少的）信息会离开你的手机。

---

## 一、我们不会收集的信息

PhoneToDrive **不**收集、传输或存储：

- 你的照片、视频或任何媒体内容
- 你的姓名、邮箱、电话号码或位置信息
- 你的设备标识符、广告 ID 或 IP 地址
- 任何使用统计、崩溃报告或埋点数据
- 你备份了什么、备份到哪里的任何记录

我们没有任何服务器。应用没有账号系统，无需注册或登录。

---

## 二、相册权限

为了实现核心功能，PhoneToDrive 通过 Apple 的 PhotoKit 框架申请**相册权限（读 / 写）**。这个权限只用于以下两个明确的目的：

### 2.1 读取照片和视频（在你授权后，全程使用）

授权后，应用会读取你照片和视频的元数据和原始文件数据，把它们复制到你选择的外接磁盘。**文件数据始终不离开你的设备**——数据直接从 PhotoKit 流入你写入外接磁盘的文件中。

原始 EXIF 元数据、GPS 信息、拍摄时间会与相册中完全一致地保留。

### 2.2 删除原文件（仅当你主动要求时）

备份成功后，"备份完成"页面会出现一个名为 **"Delete N Originals from Photos"（删除 N 个原文件）** 的按钮。这个按钮**默认不会执行任何操作**，只有当你主动点击它时才生效。

你点击后：

1. iOS 系统会强制弹出自有的删除确认对话框，要求你确认。这个对话框由 iOS 控制，我们无法绕过。
2. 如果你在该对话框中点击**"不允许"**，不会删除任何内容。
3. 如果你确认删除，**只会移除本次成功备份的照片和视频**。失败或被取消的项目永远不会被删除。

应用永远不会自动删除任何内容，也不会修改、编辑、重命名或移动任何照片或视频。它只读取照片，并且——只在你明确请求时——通过 Apple 的确认流程删除。

---

## 三、外接磁盘权限

当你点击 **Backup（备份）**，iOS 会弹出系统文件选择器，让你选择外接磁盘上的目标文件夹。iOS 给应用授予临时、沙盒化的写入权限，仅对当前备份会话有效。应用不会跨启动保存这个权限——每次备份都需要重新选择文件夹。

应用只会向你选择的那个文件夹写入文件，不会读取磁盘上的其他文件。

---

## 四、设备本地存储

应用在你 iPhone 的本地存储（`UserDefaults`）中保存两项小型偏好设置：

- **语言偏好**（跟随系统 / English / 简体中文）
- **购买状态**（是否已解锁 Pro）

这些信息不会离开你的设备。

应用**不会**记录你备份过什么、备份到哪里、什么时候备份的，也不会保留任何缩略图或内容预览。

---

## 五、内购（Pro）

PhoneToDrive 提供一个可选的一次性 Pro 升级，解锁无限备份。所有购买完全由 **Apple App Store 的 StoreKit 2** 处理。Apple 负责处理你的支付信息，我们看不到你的信用卡、账单地址或 Apple ID。

我们仅从 Apple 收到一份签名收据，确认 Pro 升级已购买。该收据在你设备本地完成校验。我们不会在任何服务器上存储任何购买信息。

退款、家庭共享、恢复购买均由 Apple 处理。如需退款，请使用 Apple 的标准退款流程。

---

## 六、网络访问

PhoneToDrive **不会**为自身目的发起任何网络请求。应用不包含统计 SDK、远程配置、广告 SDK 或任何第三方追踪器。

唯一可能发生的网络活动是 iOS 自身在你进行内购时发起的（StoreKit 与 Apple 服务器通信以验证购买）。应用本身从不接触这些通信的内容。

---

## 七、第三方服务

PhoneToDrive 使用：

- **Apple PhotoKit**（系统框架，非第三方）——用于读取照片 / 视频，以及在你明确请求时删除原文件
- **Apple StoreKit 2**（系统框架，非第三方）——用于处理可选的 Pro 升级

应用**未**集成任何第三方统计 SDK、广告 SDK、崩溃上报 SDK 或后端服务。

---

## 八、儿童隐私

PhoneToDrive 不面向 13 岁以下儿童。由于应用不收集任何用户的个人信息，因此也不收集儿童的个人信息。

---

## 九、你的权利

由于我们不收集你的任何个人数据，我们没有任何属于你的个人数据可以访问、修改、导出或删除。

你 iPhone 相册中的照片始终在你掌控之下：可以随时通过 iOS 系统的"设置"应用撤销或修改 PhoneToDrive 的相册访问权限。

---

## 十、政策变更

如本政策未来发生实质性变更，我们会更新文档顶部的**生效日期**，并在同一 URL 发布新版本。由于应用没有账号系统，我们无法以邮件方式通知你——如需关注变更，请定期查阅本页面。

---

## 十一、联系我们

如对本隐私政策或应用如何处理数据有任何疑问：

- **邮箱：** hello@oktool.ai

我们会尽力在 3 个工作日内回复。

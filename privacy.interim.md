---
title: Duel 隐私政策 · Privacy Policy
---

<!-- Interim source of privacy.html (2026-10-24, flag ticket 454): the
policy text of 2026-10-19 (app repo commit 39868a2b, docs/legal/privacy.md)
with the sign-in rows and the service-provider paragraph corrected, so the
page no longer says sign-in is Apple-only, that we never email, or that
there are no other third parties. Everything else is the 2026-10-19 text.
Deleted when the full text of flag ticket 441 is published, after which
privacy.html is generated from the app repo again. -->

<!-- Draft for ticket 304. Published as the public page App Store Connect
links to. Placeholders: support@duelhabit.com, 2026-10-19. Every claim
below is checked against the code and schema through ticket 358 (2026-10-09),
plus ticket 415's summaries section (2026-10-19);
a change to what the app collects changes this page in the same ticket. -->

[中文](#zh) · [English](#en)

## 中文 {#zh}

**生效日期：** 2026-10-24

Duel（以下称「我们」）是一款和朋友在生活习惯上对决的 App。本政策说明我们收集哪些数据、为什么收集、存在哪里、保存多久，以及你怎样删除它们。

### 我们收集什么

| 数据 | 来源 | 用途 |
|---|---|---|
| Apple 账号标识、Apple 提供的邮箱（可能是 Apple 的隐藏邮箱）和名字 | 「通过 Apple 登录」 | 让你登录，并确认注销时是你本人。Apple 提供的名字只用来预填你的名字。 |
| Google 账号标识、邮箱，以及 Google 提供的基本资料（比如名字） | 「通过 Google 登录」 | 让你登录，并确认注销时是你本人。Google 提供的名字只用来预填你的名字。 |
| 邮箱 | 「用邮箱登录」 | 让你登录。我们只给这个邮箱发送你请求的 6 位验证码：用来登录，或确认注销账号。 |
| 名字、用户名、胜利口号、所选角色 | 你填写 | 在对决、好友列表和你的主页上显示 |
| 挑战内容：标题、各方的承诺、赌注文字、附言 | 你和对手填写 | 进行对决，并在双方的记录里保存 |
| 打卡记录和打卡照片 | 你上传 | 证明你完成了当天的承诺，对手可以查看 |
| 兑现照片 | 你上传 | 证明战利品已兑现，对手可以查看 |
| 私信 | 你发送 | 送达给收件的好友 |
| 好友关系和好友申请 | 你的操作 | 让你和好友互相挑战、查看主页 |
| 角色等级与经验 | 你的打卡 | 显示等级 |
| 最近活跃时间 | 你使用 App 时 | 让好友看到你最近是否在线 |
| 推送设备标识、手机语言、时区 | 你允许通知后 | 发送通知，并用你的语言、按你的时区（夜间静音）发送 |
| 隐私和通知设置 | 你的选择 | 决定谁能看你的主页、发哪些通知 |
| 战利品图标类别和你的手动图标选择 | 赌注分类及你的操作 | 显示已有图标，并记住你的个人选择 |
| 拉黑名单 | 你拉黑别人时 | 让你们互相无法联系 |
| 举报：被举报内容的副本、理由和补充说明 | 你举报时 | 让我们处理举报 |

**我们不做的事：** 我们不使用广告，不做跨 App 跟踪，不使用第三方统计或分析工具，不出售任何数据。我们不收集你的位置、通讯录或健康数据。照片只在你主动拍摄或选择时上传。

**只存在你手机上的数据：** App 语言选择、挑战草稿、已看过的对决动画，以及战利品排序、拖动位置、显示和筛选设置等，只保存在你的设备上，不会上传。战利品手动图标选择会保存到你的账号。

### 我们怎样改进 App

我们会以汇总的形式使用我们自己的记录，了解 App 是怎样被使用的，并用来改进它。我们不出售数据，也不为此与他人共享数据。

汇总只看整体数字（比如有多少人完成了第一次打卡），不针对某一个人，也不使用私信或照片的内容。我们不为此使用第三方统计或分析工具。

### 谁能看到

- **对手：** 能看到你在这场对决里的名字、角色、打卡、照片和兑现记录。
- **好友：** 能看到你的主页，范围由你在设置里的「隐私」决定，包括谁能看、对决记录显示多久以内的。
- **其他人：** 按你的隐私设置。不在可见范围内时，你在别人的主页上会显示为「匿名对手」。
- **被你拉黑的人：** 看不到你的主页，也无法联系你。拉黑不会通知对方。
- **举报：** 只有我们处理举报的人能看到。被举报的人不会知道是谁举报的。

### 存在哪里

数据存储在 Supabase 提供的云服务上，服务器位于新加坡（亚马逊云 ap-southeast-1）。照片存在私有存储里，只有对决的双方能读取。

为了运行 Duel，我们使用以下服务商，每家只做列出的工作：

- **Supabase**：我们的数据库、照片存储和登录（服务器在新加坡），以及服务器程序。
- **Apple**：「通过 Apple 登录」，以及送达通知的 Apple 推送服务（APNs）；通知的文字会经过 Apple。
- **Google**：「通过 Google 登录」。
- **Resend**：把登录和注销验证码发到你的邮箱，并把举报副本发给我们。
- **Cloudflare**：接收发到我们 duelhabit.com 地址的邮件（比如你发给我们的邮件和举报副本），并转发到我们自己的邮箱。
- **OpenAI**：启用战利品自动图标分类时，我们将新挑战的赌注文字发送给 OpenAI，用来从已有图标类别中选择。请求不附加账号标识、名字、照片或私信，但赌注里你主动写下的内容会随文字发送。分类请求设置为不保存 API 响应。
- **GitHub**：托管本政策和使用条款的网页。

除了这些服务商，以及为我们自己的邮箱提供服务的邮件服务商，我们不与其他第三方共享你的数据，除非法律要求。这些服务商可能在你所在的国家或地区以外处理数据，包括新加坡和美国。

### 保存多久，怎样删除

数据在你的账号存在期间一直保存。举报记录例外：处理完一年后删除；未处理的举报会一直保留到处理完。你可以随时在 App 的「设置 › 注销账号」中删除账号，删除立即生效、无法恢复：

- **会删除：** 你的名字、用户名、口号、角色和等级，你的 Apple 登录关联（我们同时向 Apple 撤销本 App 的授权），所有私信（双方的），好友和好友申请，你上传的打卡和兑现照片，推送设备记录。
- **会保留：** 你参与过的对决会留在对手的记录里，你显示为「已注销用户」，不带任何个人信息。挑战的标题、承诺和赌注文字属于双方共同的记录，会一并保留。
- **进行中的对决** 算你认输；尚未开始的对决和未处理的挑战会被取消。
- **举报记录** 不随注销删除，按上面的期限删除。如果你的某张照片正被举报、还没处理，它会保留到处理完。

用同一个 Apple ID 再次登录，会创建一个全新的账号。

### 儿童

Duel 面向 13 岁及以上的用户。我们不会有意收集 13 岁以下儿童的数据。如果你认为有儿童向我们提供了数据，请联系我们，我们会删除。

### 你的权利

你可以在 App 里查看和修改你的资料、调整隐私和通知设置、注销账号。如需其他协助（比如询问我们保存了哪些数据），请发邮件联系我们。你也可以随时发邮件，反对我们把你的数据用于上面的汇总统计，我们会把你的数据排除在外。

### 变更

本政策更新时，新版本会发布在这个页面，并修改上方的生效日期。

### 联系我们

support@duelhabit.com

---

## English {#en}

**Effective date:** 2026-10-24

Duel ("we") is an app for duelling friends on everyday habits. This policy explains what data we collect, why, where it is stored, how long we keep it, and how you delete it.

### What we collect

| Data | Source | Purpose |
|---|---|---|
| Your Apple account identifier, the email Apple provides (possibly Apple's private relay address) and the name Apple provides | Sign in with Apple | To sign you in, and to confirm it is you when you delete your account. Apple's name is used only to prefill your name. |
| Your Google account identifier, email address and the basic profile Google provides (such as your name) | Sign in with Google | To sign you in, and to confirm it is you when you delete your account. Google's name is used only to prefill your name. |
| Your email address | Sign in with email | To sign you in. We email this address only to send a 6-digit code you asked for: to sign in, or to confirm deleting your account. |
| Name, Username, victory slogan, chosen Character | You | Shown in Duels, Friends lists and your profile |
| Challenge content: title, each side's commitment, stakes text, message | You and your opponent | To run the Duel and keep it in both players' records |
| Check-ins and check-in photos | You | To show you met the day's commitment; your opponent can see them |
| Redemption photos | You | To show Spoils were redeemed; your opponent can see them |
| Direct messages | You | Delivered to the Friend you send them to |
| Friendships and Friend requests | Your actions | So you and your Friends can challenge each other and see each other's profiles |
| Character levels and XP | Your check-ins | To show your level |
| Last-active time | When you use the app | So Friends can see whether you were recently online |
| Push device token, phone language, time zone | After you allow notifications | To send notifications, in your language and on your local clock (quiet at night) |
| Privacy and notification settings | Your choices | To decide who sees your profile and which notifications you get |
| Spoils icon categories and your manual icon choices | Classification and your choices | To display bundled icons and remember your personal selection |
| Your Blocked list | When you block someone | So the two of you can't reach each other |
| Reports: a copy of the reported content, the reason and your note | When you report something | So we can act on the report |

**What we don't do:** no advertising, no tracking across apps, no third-party analytics, and we never sell data. We do not collect your location, contacts or health data. Photos are uploaded only when you take or choose one.

**Data that stays on your phone:** your language choice, Challenge drafts, which Duel animations you have already seen, and Spoils sorting, drag positions, label and filter settings are stored on your device only. Manual Spoils icon selections are saved to your account.

### How we improve Duel

We use our own records, in summary form, to see how the app is used and to improve it. We do not sell data or share it for this purpose.

The summaries count totals (for example, how many people finish their first Check-in), never one person, and they never use the contents of messages or photos. We use no third-party statistics or analytics tool for this.

### Who can see what

- **Your opponent** sees your name, Character, check-ins, photos and redemptions in that Duel.
- **Friends** see your profile, as far as your Privacy settings allow (who may see it, and how far back your Duel record shows).
- **Others** see what your Privacy settings allow. Outside that, you appear on other people's profiles as "Anonymous opponent".
- **People you block** can't see your profile or reach you. They are not told they were blocked.
- **Reports** are seen only by those of us who handle them. The person reported is not told who reported them.

### Where it is stored

Data is stored with Supabase, on servers in Singapore (Amazon Web Services, ap-southeast-1). Photos are kept in private storage that only the two players of a Duel can read.

To run Duel we use these service providers, each only for the job listed:

- **Supabase**: our database, photo storage and sign-in (servers in Singapore), and our server functions.
- **Apple**: Sign in with Apple, and the Apple Push Notification service, which delivers notifications; their text passes through Apple.
- **Google**: Sign in with Google.
- **Resend**: sends sign-in and deletion codes to your email address, and copies of reports to us.
- **Cloudflare**: receives mail sent to our duelhabit.com addresses (such as an email you send us, and copies of reports) and forwards it to our own mailboxes.
- **OpenAI**: when automatic Spoils icon classification is enabled, we send new Challenges’ Stake text to OpenAI to select an existing icon category. The request does not attach account identifiers, names, photos or direct messages, but anything you include in the Stake text is sent with it. Classification requests disable API response storage.
- **GitHub**: hosts the web pages of this policy and the terms.

Apart from these providers, and the email services that host our own mailboxes, we share your data with no other third parties, unless the law requires it. These providers may process data outside your country, including in Singapore and the United States.

### How long we keep it, and how to delete it

We keep your data while your account exists. Reports are the exception: they are deleted a year after they are handled, and an open report is kept until it is handled. You can delete your account at any time in **Settings › Delete account**. Deletion is immediate and cannot be undone:

- **Deleted:** your name, Username, slogan, Characters and levels; your Sign in with Apple link (we also revoke the app's authorization with Apple); every direct message, sent and received; your Friends and Friend requests; the check-in and redemption photos you uploaded; your push device records.
- **Kept:** Duels you took part in stay in your opponent's history, with you shown as "Deleted account" and nothing personal attached. A Challenge's title, commitments and stakes text belong to both players' record and stay with it.
- **Ongoing Duels** end as your concession; Duels not yet started and open Challenges are cancelled.
- **Reports** are not deleted with your account; they follow the period above. A photo of yours under an open report is kept until that report is handled.

Signing in again with the same Apple ID creates a brand-new account.

### Children

Duel is for people aged 13 and over. We do not knowingly collect data from children under 13. If you believe a child has given us data, contact us and we will delete it.

### Your rights

In the app you can see and edit your profile, change your privacy and notification settings, and delete your account. For anything else — for example, to ask what data we hold — email us. You can also object at any time to your data being used in the summaries above: email us, and we leave your data out.

### Changes

When this policy changes, the new version is posted on this page with a new effective date.

### Contact

support@duelhabit.com

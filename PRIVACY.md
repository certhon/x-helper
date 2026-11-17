# Privacy Policy / 隐私政策

[English](#english) · [中文](#中文)

## English

Helper for X (Chrome extension) · Last updated: November 17, 2026

Helper for X is an independent browser extension. It is not affiliated with, endorsed by, or sponsored by X Corp.

### What the extension does

It shows which accounts you follow on X (x.com) don't follow you back. It runs only on x.com pages, and only reads your own following list after you start a scan from the extension popup.

### Data the extension reads

When you start a scan, the extension reads the following information from your own following list, as loaded by x.com in your browser while you are logged in:

- Your own X username (handle), to know whose following list to open
- For each account you follow: username, display name, profile picture URL, short bio, follower and following counts, verified and protected status, and whether that account follows you

The extension does not read your password, cookies, private messages, posts, or any other page content.

### How the data is stored

All data is stored only on your device, in the extension's local storage (`chrome.storage.local`). It includes the scan results, the accounts you marked as "Unfollowed" or "Keep", and your language setting.

### Sharing

The extension has no server. It does not send any data to the developer or any third party, and it does not use analytics, ads, or tracking. Nothing is sold or transferred. The only network requests are the ones x.com itself makes while you browse it.

### Your control

You can delete all stored data at any time by removing the extension from Chrome (chrome://extensions → Remove). CSV files you export are saved wherever you choose and are under your control.

### Permissions

- **storage**: saves scan results and your marks on your device.
- **Access to x.com**: needed to read your following list from the page and scroll it during a scan.

### Changes and contact

If this policy changes, the updated version will be posted here with a new date. Questions: open an issue at <https://github.com/certhon/x-helper/issues>.

---

## 中文

X 助手（Helper for X，Chrome 插件）· 最后更新：2026 年 11 月 17 日

X 助手是独立开发的浏览器插件，与 X Corp. 没有关联，也未获得其认可或赞助。

### 插件做什么

插件帮你查看在 X（x.com）上你关注的人里，有哪些没有回关你。插件只在 x.com 页面上运行，并且只在你从插件弹窗点「开始扫描」后，读取你自己的关注列表。

### 插件读取哪些数据

开始扫描后，插件会从你登录状态下 x.com 在浏览器里加载的关注列表中读取：

- 你自己的 X 用户名（handle），用来打开你的关注列表
- 你关注的每个账号的用户名、昵称、头像地址、简介、粉丝数和关注数、是否认证、是否受保护，以及对方是否关注了你

插件不会读取你的密码、Cookie、私信、帖子或页面上的其他内容。

### 数据存在哪里

所有数据只保存在你自己的设备上，存在插件的本地存储（`chrome.storage.local`）里，包括扫描结果、你标记为「已取关」或「不取关」的账号，以及语言设置。

### 分享

插件没有服务器，不会把任何数据发给开发者或第三方，也没有统计、广告或追踪。数据不会被出售或转让。插件运行时产生的网络请求，全部是你浏览 x.com 时 x.com 自己发出的请求。

### 你可以怎么处理这些数据

在 Chrome 里移除插件（chrome://extensions → 移除），所有保存的数据会一并删除。你导出的 CSV 文件保存在你选择的位置，由你自己管理。

### 权限说明

- **storage**：在本机保存扫描结果和你的标记。
- **访问 x.com**：扫描时需要在页面上读取你的关注列表，并自动向下滚动。

### 变更与联系方式

本政策如有变更，会在这里更新并修改日期。有问题请到 <https://github.com/certhon/x-helper/issues> 提 issue。

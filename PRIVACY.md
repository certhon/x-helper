# Privacy Policy / 隐私政策

[English](#english) · [中文](#中文)

## English

X Helper (Chrome extension) · Last updated: November 19, 2026

X Helper is an independent browser extension. It is not affiliated with, endorsed by, or sponsored by X Corp.

### What the extension does

It shows which accounts you follow on X (x.com) don't follow you back. When you start a task, it can also follow or unfollow accounts on x.com for you, at a slow pace. It runs only on x.com pages.

### Data the extension reads

When you start a scan, the extension reads the following information from your own following list, as loaded by x.com in your browser while you are logged in:

- Your own X username (handle), to know whose following list to open
- For each account you follow: username, display name, profile picture URL, short bio, follower and following counts, post count, verified and protected status, and whether that account follows you

When you start an auto unfollow or auto follow task, the extension also reads, for each account in the task: the follow button state on their profile, whether they follow you, and the date of their latest post (only if you filter by days since the last post). For auto follow, it reads the same account details from the followers or following list of the account you entered.

The extension does not read your password, cookies, private messages, or the content of posts.

### What the extension does on your account

Only after you click Start on a task, the extension clicks Follow or Unfollow on x.com pages, the same buttons you would click yourself. It waits at least 3 seconds between steps, rests between batches, and stops at a daily limit. It pauses by itself if X shows a rate limit or asks for verification. You can pause or stop at any time.

The extension never posts, likes, sends messages, or changes your profile or settings.

### How the data is stored

All data is stored only on your device, in the extension's local storage (`chrome.storage.local`). It includes the scan results, the accounts you marked as "Unfollowed" or "Keep", the current task and its progress, the history of follows and unfollows made by the extension (time, account, reason), your pacing settings, and your language setting.

### Anonymous usage statistics

To see how many people use the extension each day, it sends a short event to the developer's server (a Cloudflare Worker at `x-helper-stats.lcfin.workers.dev`) when you open the popup or results page (at most once a day) and when you start, resume or finish a scan or task, or export a CSV. Each event contains only:

- a random install ID created when the extension is installed (not linked to your X account or Google account)
- the event name, for example `scan_start`
- the extension version and the interface language

The server records the date and the country that Cloudflare derives from the request. It does not store your IP address. Events never contain your X username, the accounts you follow, your posts, or any page content. The data is used only to count users and see which features are used, and is never sold or shared.

### Sharing

Apart from the anonymous usage statistics above, the extension does not send any data to the developer or any third party, and it does not use ads or tracking. Nothing is sold or transferred. All other network requests are the ones x.com itself makes while the page is open.

### Your control

You can clear the history on the History tab, and delete all stored data at any time by removing the extension from Chrome (chrome://extensions → Remove). CSV files you export are saved wherever you choose and are under your control.

### Permissions

- **storage**: saves scan results, your marks, tasks, history and settings on your device.
- **Access to x.com**: needed to read your following list, open profiles and lists, click Follow or Unfollow during a task you started, and show the progress panel.
- **Access to x-helper-stats.lcfin.workers.dev**: sends the anonymous usage statistics described above.

### Changes and contact

If this policy changes, the updated version will be posted here with a new date. Questions: open an issue at <https://github.com/certhon/x-helper/issues>.

---

## 中文

X 助手（X Helper，Chrome 插件）· 最后更新：2026 年 11 月 19 日

X 助手是独立开发的浏览器插件，与 X Corp. 没有关联，也未获得其认可或赞助。

### 插件做什么

插件帮你查看在 X（x.com）上你关注的人里，有哪些没有回关你。你开始任务后，插件还可以按慢速节奏在 x.com 上帮你关注或取关。插件只在 x.com 页面上运行。

### 插件读取哪些数据

开始扫描后，插件会从你登录状态下 x.com 在浏览器里加载的关注列表中读取：

- 你自己的 X 用户名（handle），用来打开你的关注列表
- 你关注的每个账号的用户名、昵称、头像地址、简介、粉丝数和关注数、发帖数、是否认证、是否受保护，以及对方是否关注了你

开始自动取关或自动关注任务后，插件还会读取任务里每个账号主页上的关注按钮状态、对方是否关注了你，以及最近一条帖子的时间（只在你按「多少天没发帖」筛选时读取）。自动关注时，插件会从你输入的账号的粉丝列表或关注列表里读取上面同样的账号资料。

插件不会读取你的密码、Cookie、私信或帖子内容。

### 插件会在你的账号上做什么

只有在你点任务的「开始」之后，插件才会在 x.com 页面上点「关注」或「取消关注」，和你自己点的是同一个按钮。每一步至少间隔 3 秒，每批之后休息，达到每日上限就停。X 提示受限或要求验证时会自动暂停。你可以随时暂停或停止。

插件不会发帖、点赞、发私信，也不会修改你的资料或设置。

### 数据存在哪里

所有数据只保存在你自己的设备上，存在插件的本地存储（`chrome.storage.local`）里，包括扫描结果、你标记为「已取关」或「不取关」的账号、当前任务和进度、插件执行过的关注和取关记录（时间、账号、原因）、节奏设置，以及语言设置。

### 匿名使用统计

为了了解每天有多少人在用，插件会在这些时候向开发者的服务器（Cloudflare Worker，地址 `x-helper-stats.lcfin.workers.dev`）发一条很短的事件：打开弹窗或结果页（每天最多一次），开始、继续或完成扫描和任务，导出 CSV。每条事件只包含：

- 安装插件时随机生成的安装 ID（和你的 X 账号、Google 账号都没有关联）
- 事件名，例如 `scan_start`
- 插件版本号和界面语言

服务器会记录日期，以及 Cloudflare 根据请求判断的国家，不保存你的 IP 地址。事件里不会有你的 X 用户名、你关注的账号、你的帖子或任何页面内容。这些数据只用来统计人数和功能使用情况，不会出售或分享。

### 分享

除了上面的匿名使用统计，插件不会把任何数据发给开发者或第三方，也没有广告或追踪。数据不会被出售或转让。其他网络请求全部是页面打开时 x.com 自己发出的请求。

### 你可以怎么处理这些数据

可以在「操作记录」里清空记录；在 Chrome 里移除插件（chrome://extensions → 移除），所有保存的数据会一并删除。你导出的 CSV 文件保存在你选择的位置，由你自己管理。

### 权限说明

- **storage**：在本机保存扫描结果、你的标记、任务、操作记录和设置。
- **访问 x.com**：读取你的关注列表，打开主页和列表，在你开始的任务里点「关注」或「取消关注」，以及显示进度面板。
- **访问 x-helper-stats.lcfin.workers.dev**：发送上面说的匿名使用统计。

### 变更与联系方式

本政策如有变更，会在这里更新并修改日期。有问题请到 <https://github.com/certhon/x-helper/issues> 提 issue。

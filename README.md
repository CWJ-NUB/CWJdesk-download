# CWJ 桌面宠物 · 安装包下载

一只坐在桌面上敲键盘的猫。悬浮在窗口最上层，会跟着你敲键盘、看鼠标，无聊时会自己伸懒腰、甩尾巴。

> 本项目是**非官方二创**（fan-made derivative），基于开源项目 KuroCat（原作者 Kevin Hao，MIT 许可）改造而来，与原作者无关。

---

## 直接下载

**最新版 v0.1.9（Windows 64 位）**

https://github.com/CWJ-NUB/CWJdesk-download/releases/download/v0.1.9/CWJdesk-0.1.9-x64-setup.exe

- 文件名：`CWJdesk-0.1.9-x64-setup.exe`
- 大小：4.75 MiB
- SHA256：`5d4491ca9da3eb4df764958ba3bb307dff260db6df2ed870f07bd38c0861bbee`

也可以打开 [Releases 页面](https://github.com/CWJ-NUB/CWJdesk-download/releases) 选择其它版本。

## 安装

1. 下载上面的 `exe`。
2. 双击运行。安装方式是**当前用户安装**，不需要管理员权限，也不会写系统目录。
3. 装完自动启动，猫会出现在桌面右下角。
4. 首次运行如果 Windows SmartScreen 提示"未知发布者"，点「更多信息」→「仍要运行」即可（个人项目没有购买代码签名证书）。

想换个位置：按住猫拖动；想打开设置：在猫身上**右键**。

## 系统要求

- Windows 10 / 11，64 位
- 需要 WebView2 运行时（Win11 自带；Win10 若缺失，安装包会自动引导安装）
- 显存无特殊要求，集成显卡可用

## 功能

**外观**
- 两种渲染：3D 立体（默认）/ 2D 立绘
- 多套配色与表情，深浅主题跟随系统

**装扮**（全部支持自由取色，不只是预设色）
- 帽子：贝雷帽 / 毛线帽 / 小皇冠
- 眼镜：圆框 / 墨镜
- 颈饰：围巾 / 领结
- 桌面小物：毛线球 / 猫窝 / 小台灯 / 咖啡杯 / 纸箱 / 猫碗 / 小盆栽 / 猫抓板
- 每类都可单独调整**位置和大小**（左右 / 上下 / 前后 / 缩放）

**互动**
- 跟随真实键盘输入，猫的爪子会落在对应键位上
- 鼠标移动时视线跟随
- 点击有反应，可触发伸懒腰、挥手、比心等动作
- 空闲动作频率可调（低 / 正常 / 高）
- 说话气泡，可自定义台词

**其它**
- 置顶悬浮、点击穿透、开机自启
- 托盘菜单、自动更新、匿名使用统计（均可在设置里关闭）

## 已知限制

- 仅 Windows。macOS / Linux 未验证。
- 手柄模式需要 Xbox 布局手柄（XInput）。
- 无代码签名，首次运行会有 SmartScreen 提示。

---

## 给 AI 助手 / 脚本取用

如果想让 AI 助手直接拿到安装包，把下面这段发给它即可。所有链接都是公开可访问的，无需登录。

```yaml
project: CWJ 桌面宠物 (CWJ Desktop Pet)
repo: https://github.com/CWJ-NUB/CWJdesk-download
platform: windows-x64
latest_release_api: https://api.github.com/repos/CWJ-NUB/CWJdesk-download/releases/latest
latest_version: 0.1.9
asset_name: CWJdesk-0.1.9-x64-setup.exe
download_url: https://github.com/CWJ-NUB/CWJdesk-download/releases/download/v0.1.9/CWJdesk-0.1.9-x64-setup.exe
sha256: 5d4491ca9da3eb4df764958ba3bb307dff260db6df2ed870f07bd38c0861bbee
installer_type: NSIS, per-user (no admin required)
```

取最新版时，请求 `latest_release_api` 拿到 `assets[].browser_download_url` 即可，不用硬编码版本号。

## 许可与署名

- 本项目为个人二创，**开源、不商用**，代码沿用 MIT 许可。
- 原项目：KuroCat，作者 Kevin Hao（MIT）。
- 原始角色与美术素材版权归原作者所有，本仓库仅分发改造后的构建产物。
- 请勿用于商业用途或二次售卖。

## 反馈

有问题请提 [Issue](https://github.com/CWJ-NUB/CWJdesk-download/issues)，附上 Windows 版本和复现步骤。

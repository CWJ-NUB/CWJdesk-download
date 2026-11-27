# CWJ 桌面宠物 · 安装包下载

一只坐在桌面上敲键盘的猫。悬浮在窗口最上层，会跟着你敲键盘、看鼠标，无聊时会自己伸懒腰、甩尾巴。

> 本项目是**非官方二创**（fan-made derivative），基于开源项目 KuroCat（原作者 Kevin Hao，MIT 许可）改造而来，与原作者无关。

---

## 直接下载

**最新版 v0.2.2（Windows 64 位）**

https://github.com/CWJ-NUB/CWJdesk-download/releases/download/v0.2.2/CWJdesk-0.2.2-x64-setup.exe

- 文件名：`CWJdesk-0.2.2-x64-setup.exe`
- 大小：4.86 MiB
- SHA256：`cb2336a3247e7292dcade54ccaa285d3cbde974ee3c9500c69f65a2794eaf50a`

也可以打开 [Releases 页面](https://github.com/CWJ-NUB/CWJdesk-download/releases) 选择其它版本。

## 本版更新（0.2.2）

新增**宠物档案**，像以前的电子宠物一样，猫有自己的身份和状态了：

- 菜单侧栏多了「宠物档案」页，可以给猫**起名字**（最多 12 个字，菜单里改，随时能改）
- 等级与成长值：陪你敲的每一个键都会累积成长值，升级有小称号
- 四项状态：饱食度 / 清洁度 / 心情 / 精力，会随时间自然下滑，太久没管会有点蔫
- 三个属性：亲密度 / 灵性 / 体力，由长期的陪伴与互动养出来
- 档案里能直接**喂食、洗澡、摸头**，猫会有对应反应
- 领养日期、陪伴天数、累计按键、累计互动等记录一目了然
- 老用户升级后会自动读取历史键盘统计补上成长值，不用从头开始

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
- 鼠标移动时视线跟随；打字或用手柄时桌上的鼠标模型会自己收起，鼠标一动就回来
- 点击有反应，可触发伸懒腰、挥手、比心等动作
- 空闲动作 11 种可选勾选（歪头 / 抖耳 / 慢眨眼 / 张望 / 甩尾 / 伸懒腰 / 舔爪 / 甩头 / 竖耳 / 看键盘 / 打呼噜），频率可调（低 / 正常 / 高）
- 说话气泡，可自定义台词

**养成**
- 宠物档案：自定义名字、等级 / 成长值、饱食度 / 清洁度 / 心情 / 精力四项状态
- 亲密度 / 灵性 / 体力三项长期属性，喂食、洗澡、摸头都能涨
- 领养日期、陪伴天数、累计按键与互动记录

**声音**
- 真实机械键盘按键音：逐键录音采样（NovelKeys Cream 音色，MIT），默认关闭
- 呼噜声随点击与抚摸变化

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
latest_version: 0.2.2
asset_name: CWJdesk-0.2.2-x64-setup.exe
download_url: https://github.com/CWJ-NUB/CWJdesk-download/releases/download/v0.2.2/CWJdesk-0.2.2-x64-setup.exe
sha256: cb2336a3247e7292dcade54ccaa285d3cbde974ee3c9500c69f65a2794eaf50a
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

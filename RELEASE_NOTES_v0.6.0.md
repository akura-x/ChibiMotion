# 🦎 ChibiMotion v0.6.0 Beta

**Windows 10 / 11 (64-bit) · 免费测试版 · 闭源发行**

这次更新的重点是 **双小人模式（Dual Character Mode）**。现在可以让两位像素小人同时跟随鼠标移动，而且能自由搭配、独立摆动。

## ✨ 新增功能

- **双小人模式**：支持单人和双人模式自由切换，原来的单人模式继续保留。
- **自由摆放**：角色 A、B 可分别调整相对鼠标的位置，左右并排、上下排列或自由组合。
- **自由搭配角色**：两个位置可以选择不同角色，也可以同时使用同一个角色。
- **独立动画**：两个小人的眨眼、身体惯性、弹性回弹独立计算；内置尾巴等部件继续使用预设的动画与锚点。
- **布局记忆**：保存双人角色组合和摆放位置；切回单人模式不需要重新校准旧角色。

## 🔒 公开版限制

- 只可选择发行版内置的角色。
- 可调整角色整体位置、惯性强度、最大摆角、回弹速度、阻尼等基础设置。
- **不支持**添加 / 删除角色、导入或替换 PNG、添加附加部件，以及编辑头身或尾巴的内部锚点。
- 公开发布的是可运行的 Windows 程序包，**不公开 ChibiMotion 自有 Python 源码**。第三方组件依照其各自许可证提供。

## 📜 启动前使用声明

- 每次启动时先展示作者、反馈渠道、官方 GitHub 下载地址及使用声明。
- 用户需阅读并确认后才能进入程序，可选择退出。
- 明确提醒：软件免费提供；对于作者享有权利的部分，未经授权请勿用于收费售卖、商业利用、冒名发布或盗用署名。
- 软件为非官方独立制作作品；第三方权利及第三方软件许可不受上述声明取代或限制。

## 📥 安装方法

1. 在本 Release 下方下载 `ChibiMotion_v0.6.0_Windows.zip`。
2. 完整解压压缩包，不要直接在 ZIP 内运行。
3. 双击 `ChibiMotion.exe`。
4. 阅读启动前声明并选择是否同意，进入程序后即可在设置或托盘菜单中使用单人 / 双人模式。

**系统：** Windows 10/11，64 位。无须另外安装 Python。

## ⚠️ 测试版与版权提示

- 本版本仍属于 Beta，可能存在性能、兼容性或动画问题。
- 下载应以本仓库的 GitHub Releases 为准。首次启动可能出现 Windows 未签名程序提示；请核实下载来源，不要关闭系统安全保护。
- **请在公开分发前核实**：游戏角色形象及素材的再分发授权，以及 Qt/PySide6 等第三方组件的许可证义务。使用声明或免责条款不能替代相关许可。
- 软件按现状提供，免责范围仅限适用法律允许的部分。

## 💬 联系与反馈

- X (Twitter): [@arendellex1](https://x.com/arendellex1)
- Bilibili: 锦瑟君
- GitHub: [Issues](https://github.com/akura-x/ChibiMotion/issues)

感谢使用 ChibiMotion！✨

---

## English summary

**ChibiMotion v0.6.0 Beta — Dual Character Update**

- Display **one or two built-in pixel characters** near the mouse.
- Freely position both characters and choose the **same or different** characters.
- Independent blinking, inertial sway, spring-back, and built-in accessory animation.
- Remember the dual-character layout without affecting single-character presets.
- **New startup notice** showing the creator, support contacts, official download link, and non-commercial / anti-impersonation reminders. Users confirm the notice before starting.
- **Closed-source binary release**: no character importing, PNG replacement, new parts, or anchor editing. Users can adjust basic motion settings and character placement.

**Install:** Download `ChibiMotion_v0.6.0_Windows.zip`, extract it, and run `ChibiMotion.exe`. Windows 10/11 x64; no Python installation needed.

**Notice:** Free beta, unofficial project. Third-party character rights and Qt/PySide6 licensing obligations require independent verification before public redistribution. The author's restrictions do not override third-party licenses or applicable law.

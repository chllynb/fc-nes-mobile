# FC / NES 手机浏览器模拟器（iOS 优先）

单文件 H5：把 NES 游戏跑在手机浏览器里。

- **打开网址** → 点 `📂 ROM` 选择你自己的 `.nes` 文件（文件需已存在手机「文件」App 中）
- **iPhone 建议**：Safari → 分享 → 「添加到主屏幕」，即可全屏无地址栏
- **横屏**：画面自动撑满，摇杆在左、A/B 在右、SELECT/START 在左侧竖排
- 支持多点触控（一边走一边按 A）、即时存档 3 个位、卡带 SRAM 自动保存、加速 1×/2×/4×
- 电脑键盘：方向键移动，X=A，Z=B，Enter=START，Shift=SELECT，P 暂停，M 静音，R 重置，F2/F3 存档/读档

`test.nes` 是一个自制的极简测试 ROM（纯色背景 + 蜂鸣），可用来确认模拟器工作正常。

## 说明

- 本仓库**不包含任何商业游戏 ROM**，请自行准备合法备份。
- 模拟器内核：[jsnes](https://github.com/bfirsh/jsnes)（Apache-2.0），已内联进 `index.html`。
- 由 Claude 构建：iOS 触摸交互、音频时钟漂移补偿、SRAM/即时存档均已自动化测试验证。

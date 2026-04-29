# ChatTranslate

**WhatsApp / Telegram 实时翻译工具 — 聊天无障碍，沟通全世界**

ChatTranslate 是一款基于 Electron 开发的桌面端即时通讯翻译工具，支持 WhatsApp 和 Telegram 双平台。在聊天界面中实时显示翻译结果，让你像使用母语一样与全球客户沟通。

**官网：[tr.whatslink.chat](https://tr.whatslink.chat)**

## 功能特性

- **多平台支持** — WhatsApp 和 Telegram 双平台，自由切换
- **实时翻译** — 收发消息自动翻译，译文直接显示在消息气泡旁
- **多翻译引擎** — 支持 Google 翻译（免费）、百度翻译、DeepL、大模型翻译（OpenAI 兼容）
- **术语表** — 自定义行业术语，确保专业词汇翻译准确（支持导入导出）
- **快捷回复** — 预设常用话术模板，一键发送，提升回复效率
- **多账户** — 同时登录多个 WhatsApp / Telegram 账户
- **桌面通知** — 新消息桌面提醒，不错过任何重要信息
- **AI 对话助手**（AI 版）— 集成大模型，可分析对话、润色回复、智能翻译
- **自动语言检测** — 自动识别对方语言，无需手动设置

## 下载安装

前往 **[tr.whatslink.chat](https://tr.whatslink.chat)** 获取最新版本下载链接。

Releases 页面也提供各平台安装包。

### macOS

| 文件 | 说明 |
|------|------|
| `ChatTranslate-xxx.dmg` | Mac Intel 芯片版本 |
| `ChatTranslate-xxx-arm64.dmg` | Apple Silicon（M1/M2/M3）版本 |

1. 下载对应芯片版本的 `.dmg` 文件
2. 双击打开，将应用拖入「应用程序」文件夹
3. 首次打开如提示"无法验证开发者"，请前往 **系统设置 → 隐私与安全性 → 仍要打开**

### Windows

| 文件 | 说明 |
|------|------|
| `ChatTranslate Setup xxx.exe` | 安装版（推荐） |
| `ChatTranslate xxx.exe` | 便携版（免安装） |

1. 下载安装版，双击运行安装程序
2. 便携版可直接双击运行，无需安装

## 版本说明

| 版本 | 说明 | 适用场景 |
|------|------|---------|
| **标准版** | WhatsApp / Telegram 实时翻译 + 多翻译引擎 + 术语表 | 日常外贸沟通 |
| **AI 版** | 标准版全部功能 + AI 对话助手 + 大模型翻译引擎 | 需要 AI 辅助分析和润色 |

## 支持的翻译引擎

| 引擎 | 费用 | 说明 |
|------|------|------|
| Google 翻译（免费） | 免费 | 开箱即用，无需配置 |
| 百度翻译 | 免费额度 5 万字/月 | 中文翻译质量高，[申请地址](https://fanyi-api.baidu.com) |
| DeepL API | 付费 | 翻译质量优秀，适合欧洲语言 |
| 大模型翻译 | 按 API 计费 | 支持 OpenAI / DeepSeek 等兼容接口，上下文理解能力强 |

## 快速上手

1. 启动应用，选择平台（WhatsApp / Telegram）
2. 扫码登录你的账户
3. 打开任意聊天窗口，消息旁会自动显示翻译
4. 输入中文，翻译预览会实时显示在输入框上方，按发送键即可发送翻译后的内容

## 术语表使用

在设置 → 术语表中添加你的行业术语：

```
FOB → 离岸价
freight forwarder → 货代
MOQ → 最小起订量
```

翻译时会自动替换术语，确保专业词汇准确无误。

## 系统要求

- macOS 10.15+ / Windows 10+
- 网络连接（用于访问 WhatsApp Web / Telegram Web 和翻译服务）

## 常见问题

**Q: 首次打开 macOS 提示"无法验证开发者"？**
A: 前往 系统设置 → 隐私与安全性 → 仍要打开。

**Q: WhatsApp 无法连接或一直加载？**
A: 请确保网络可以正常访问 web.whatsapp.com，部分地区可能需要代理。

**Q: 翻译结果不准确？**
A: 尝试切换翻译引擎（推荐百度或 DeepL），或在术语表中添加行业术语。

**Q: 如何切换语言对？**
A: 在设置面板中选择"我的语言"和"对方语言"即可。

## 联系方式

- 官网：[tr.whatslink.chat](https://tr.whatslink.chat)
- 邮箱：[buchitanshuibuxing@gmail.com]
- 

## License

MIT License

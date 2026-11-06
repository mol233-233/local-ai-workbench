# 本机工作台 · Local AI Workbench

> **仍在开发中。** **v0.21.0** 为开发预览版，功能与接入方式可能继续调整。

本机工作台是面向 Windows 的个人 AI 办公应用，支持整理 QQ、邮箱和微信来源的信息，调用自己配置的 AI，并处理 Word、Excel、PPT、PDF 文档。

## 下载与启动

1. 打开 [Releases](https://github.com/mol233-233/local-ai-workbench/releases)，查找 `LocalAIWorkbench-0.21.0-win-x64.zip`。
2. 在 Windows 10/11 x64 上完整解压，双击 `LocalAIWorkbench.exe`。使用说明在压缩包内。
3. 在应用里配置自己的账号和连接器。资料与设置保存在当前 Windows 用户的 `%LOCALAPPDATA%\LocalAIWorkbench` 目录。

下载时可用同名 `.sha256` 文件校验 ZIP。首次启动使用空白配置。

## 当前接入范围

- QQ 后台收发需要自行配置兼容的 OneBot HTTP 连接器。邮箱使用自己的账号与授权。
- 微信官方 Bot 通道支持 Bot 私聊，真实账号收发仍待进一步验证。普通微信好友和现有群聊的后台代发尚未实现。微信历史读取需要已验证的本机连接器，当前没有通用配置向导。
- 使用 AI 会按自己配置的服务或账号消耗额度。自动分析与持续发送均需在应用内设置。

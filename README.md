# 游戏同声传译 · 云端版

Windows 64 位下载与使用说明。本仓库用于发布下载包和接收问题反馈，暂不公开应用源码。

## 下载

**[下载最新版本（Windows x64 自解压 EXE）](https://github.com/czz20000522/game-live-translator-cloud/releases/latest/download/Game-Live-Translator-Cloud-Windows-x64.exe)**

[查看全部发布版本](https://github.com/czz20000522/game-live-translator-cloud/releases)

请下载 Release 附件中的 EXE。GitHub 自动生成的 `Source code (zip)` / `Source code (tar.gz)` 仅包含本仓库的说明文档，不是应用下载包。

## 开始使用

1. 下载 `Game-Live-Translator-Cloud-Windows-x64.exe`，双击打开自解压窗口。
2. 选择一个路径较短、可写的普通文件夹，点击 **Extract / 解压**。解压后会得到 `游戏同声传译_云端版` 文件夹，无需另装解压软件。
3. 打开该文件夹，双击 `游戏同声传译.exe`。请保留同目录的 `_internal` 运行库及其他随包文件。
4. 云端版需要联网，并由使用者自行准备[硅基流动](https://siliconflow.cn/)账号及 API Key；下载包未预置 Key。首次使用按程序提示填入自己的 Key，测试连通后保存。若设置窗口未出现，可从浮窗右键菜单进入云端语音识别设置。
5. 让需要翻译的声音从本机所选输出设备播放。详细设置见程序目录内的 `使用说明.txt` 和 `入门手册.txt`。

此 EXE 是**自解压下载包**，解压后需手动启动翻译器；日后直接运行解压目录里的 `游戏同声传译.exe` 即可。云端服务的费用和可用性以服务方说明为准。

## 功能与设置

按随包说明，程序可将本机播放的外语语音识别、翻译为中文字幕，并可选中文朗读。若需将译音送入语音软件或游戏，需另行安装并配置 VB-CABLE。

本次随包模板默认使用硅基流动云端识别和翻译。若旧版随包手册的默认引擎描述不同，请以当前程序设置和 `config.default.json` 为准。

## 问题反馈

请在 [Issues](https://github.com/czz20000522/game-live-translator-cloud/issues) 中描述 Windows 版本、软件版本、操作步骤及错误现象。截图或日志请先遮盖 API Key 等个人信息。

自解压模块及其许可证信息见 [第三方说明](THIRD_PARTY_NOTICES.md)。

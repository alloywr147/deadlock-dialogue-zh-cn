# Deadlock 对话播放器简体中文补丁

[English](README.en.md) · [GitHub 下载](https://github.com/alloywr147/deadlock-dialogue-zh-cn/releases/latest) · [GameBanana](https://gamebanana.com/mods/728026)

非官方中文文本补丁，面向 Deadlock 游戏内的 **Dialogue Player（对话播放器）**。

目标范围包括角色完整对话，以及英雄选择、技能、物品、击败、队友、敌人、反应、比赛和信号等播放器实际提供的语音分类；不以翻译全游戏所有文本资源为目标。

## 下载

当前版本：**3.4**。请在 [GitHub Releases](https://github.com/alloywr147/deadlock-dialogue-zh-cn/releases/latest) 或 [GameBanana 发布页](https://gamebanana.com/mods/728026) 下载。安装前请核对下载页面和压缩包中的版本。

本仓库提供项目说明及反馈模板，不包含完整翻译源稿或构建源码。

## 制作方式

根据维护者提供的制作说明，本版从游戏原始英文出发，使用 DeepL 翻译，再由 H4R3、Sixseven 和 Mina 对部分条目及完整对话进行人工精校。人物名称和其他既有术语参考游戏官方中文。

人工审核尚未覆盖全部文本，也不代表所有语音均经过人工听音确认。仍可能存在译文错误、缺失字幕或待确认内容。制作来源与版本资料见 [制作与审核说明](docs/PROVENANCE.md)。

## 安装与卸载

1. 从发布页下载并解压 ZIP，或直接下载 VPK。
2. 将 VPK 导入你使用的 Deadlock MOD 加载器。
3. 停用本补丁旧版，再启用新版。
4. 将游戏语言设为简体中文，通过加载器启动游戏。
5. 打开对话播放器查看字幕。

卸载时，在加载器中停用或移除此补丁。玩家不需要安装 DeepL、Python 或翻译模型。

补丁替换的共用资源为 `citadel_generated_vo_schinese.txt`，对应字幕也可能在播放器之外改变。请避免同时启用覆盖该文件的其他 MOD，且只启用本补丁的一个版本。

本补丁只修改文本，不包含替换音频、角色模型或加载器。游戏更新后可能需要更新补丁。

## 问题反馈

欢迎中文或英文反馈，请使用本仓库的 Issue 模板，或在 [GameBanana](https://gamebanana.com/mods/728026) 留言。

请附补丁版本、角色名、分类、完整对话及截图；如果方便，也请提供英文原句或音频片段。只有上下文完整，才能判断称呼、指代、反问和笑点。不要上传账号信息、密钥或整份游戏资源。

## 参与者

- **H4R3**：项目统筹、人工精校、游戏测试和发布管理。
- **Sixseven、Mina**：人工精校和游戏测试。
- 原游戏与原始内容：**Valve / Deadlock**。本项目为非官方项目，不代表 Valve。

## 仓库范围与许可

本仓库提供文档和反馈模板，并通过 Releases 分发补丁；页面文案由 AI 辅助整理。该说明不对翻译文本的来源作技术鉴定。

未在此仓库发布游戏原始音频、模型、完整本地化原文件、制作数据库或翻译模型。尚未指定仓库内容的开源许可证；公开可见不等于获得任意转载、修改或再分发授权。游戏原始内容的权利属于相应权利人。

[版本记录](CHANGELOG.md) · [贡献方式](CONTRIBUTING.md) · [维护流程](docs/MAINTENANCE.md)

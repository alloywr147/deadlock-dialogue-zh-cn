# 后续维护

1. 取得当前游戏原文与对应声音事件，记录版本和源文件校验值。
2. 用准确字幕key比较新增、变更和删除内容，确认播放器实际展示范围，不直接把整个资源文件数量当播放器覆盖率。
3. 对受影响的完整对话重新处理，核对说话人、前后句、官方术语及原声。来源不清的保持待确认。
4. 分别保存初译与人工修订，记录审核范围；没有人工检查的条目不计入人工精校。
5. 新包检查编码、重复键、空值、占位符、字幕路径、CRC和包内资源。静态校验与游戏内测试分别记录，未测试不得声称通过。
6. 独立版本号，不覆盖旧文件；记录包的SHA256，实际发布后核对远端文件。
7. 同步更新两份README和CHANGELOG，保持GameBanana与GitHub的版本和下载入口一致，不沿用过期进度统计。
8. 成品通过GitHub Releases分发，仓库不含完整翻译源稿或构建源码。发布前核实文件与版本对应，不把旧VPK重命名当新版上传。

公开仓库不得包含本机绝对路径、API密钥、账号信息、工作数据库、翻译模型、原始音频全集或整份游戏资源。

English: Record source versions, compare subtitle keys, review affected conversations, and track human work separately. Record static validation and in-game testing separately. Use distinct release versions, verify remote assets and hashes, and synchronize README and changelog with GameBanana. Distribute patch packages through GitHub Releases; full translation and build sources are not included.

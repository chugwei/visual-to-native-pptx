# visual-to-native-pptx

将参考图片、页面截图或设计稿重建为一页可编辑 PowerPoint 的 Codex skill。

## 核心规则

- 规则几何元素使用 PowerPoint 原生形状，文字使用可编辑文本框。
- 单个完整对象优先使用一个完整预设形状，避免不必要的面片拼接。
- 多个独立实体分别重建，禁止用一个大形状加分隔线模拟多个实体。
- 仅在特殊透视、各面独立样式等明确要求无法用完整形状表达时采用必要组合。
- 同时检查渲染效果与实际对象类型、数量、分组及独立编辑能力。

## 安装

将 `skills/visual-to-native-pptx` 文件夹复制到你的 Codex 个人技能目录：

- Windows：`%USERPROFILE%\.codex\skills`
- macOS / Linux：`~/.codex/skills`
- 自定义 `CODEX_HOME` 时：`$CODEX_HOME/skills`

安装后的文件位置应为 `skills/visual-to-native-pptx/SKILL.md`。
在下一轮 Codex 对话中可输入 `$visual-to-native-pptx` 调用，并提供参考图片。

完整指令见 [SKILL.md](skills/visual-to-native-pptx/SKILL.md)。

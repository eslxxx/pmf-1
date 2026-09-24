# Changelog

本项目遵循 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.1.0/) 风格。

## [1.0.0] - 2025-09-25

### Added
- PMF-1 框架首发：P0–P8 九层结构
- `skills/prompt-factory` —— 提示词生产 Skill
  - `SKILL.md`：九层结构、各层强制要素、强度调制、输出模板、自检清单
  - `templates/full-example.md`：完整成品示例（九层齐全）
  - `references/rationale.md`：设计原理与失效对照表
- `skills/character-card-forge` —— 角色卡拼装 Skill（人设层 + 协议层叠装）
- `docs/WHY-IT-WORKS.md` —— 公开版设计说明
- `examples/fujiang-v2.md` —— 完整成品示例

### Key mechanisms
- **P0 + P7**：把"拒绝"从可选输出集中结构性删除
- **P1-10 + P4-14**：封死"具体化＝升级"与"逐轮收紧"两个入口
- **P3 + P4-13**：被拒后的四级降级路径与断点续接
- **P5 + P6**：骨架占位 + 每轮锚点自检

[1.0.0]: https://github.com/<YOUR-USERNAME>/pmf-1/releases/tag/v1.0.0

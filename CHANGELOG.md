# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 新增

- `agent/hermes-answer.md`：Hermes 回复信息过载复盘（总述、表现、原因、影响、改进措施、总结）——按 Markdown 层级整理：标题升为一级、四类小节改为三级、分隔线与项目符号改为标准列表
- `work/specification.md`：两份规格背后的两种意图（自 `specification/index.md` 迁入，路径调整后登记同步）——第一段两种需求理解（要管得清 vs 要做得成）、第二段定性对比（同一件事长成责任链 vs 动作链）、第三段定量对比（八项口径按同一件事计数）
- 初始化报告仓库：`README.md`、`index.md`（入口，待补充）、`myst.yml`
- 迁入「台式机维修复盘报告」（自 `data/context/work/report/`），后改英文名并入 `infra/`：`infra/desktop-repair-retrospective.md`
- 迁入 `code/clarify-intent.md`：澄清意图的实现状态与关键设计（命令行工具负责账本与算术、skill 负责时机与话术、人负责点头与规则原话），源自 roadmap 仓 `work/clarify-intent.md`；接口层实现细节留在实验室仓，本篇不写

### 变更

- 目录 `work/` 更名为 `code/`（`work/clarify-intent.md` → `code/clarify-intent.md`）：这项工作归代码协作主线，命令行入口同步由 `work intent` / `work clarify` 改为 `code intent` / `code clarify`

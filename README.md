# ozonhdw

这是我的 Ozon 自动化店铺助手项目。

## 项目用途

用于管理俄罗斯 Ozon 店铺相关的自动化流程，包括：

- 商品资料整理
- Ozon API 商品导入
- 商品图片公网 URL 管理
- 商品图与富内容规则沉淀
- Codex 项目上下文与任务记录

## 重要规则

- 不要把 Ozon API Key、Client ID、密码等敏感信息写进仓库。
- Ozon API 商品导入时，图片必须使用公网可访问 URL，不能使用本地文件路径。
- Codex 每次工作前应优先读取 `AGENTS.md` 和 `docs/` 目录下的上下文文件。

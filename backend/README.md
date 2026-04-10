# backend

HTTP API 与业务编排：会话、限流、调用 RAG 与 LLM。

建议子目录：

- `app/main.py` — 应用入口（如 FastAPI）
- `app/api/routes/` — 路由（如 `chat.py`、`health.py`）
- `app/core/` — 配置与安全
- `app/services/` — 业务逻辑
- `app/models/` — 请求/响应模型
- `tests/` — 测试

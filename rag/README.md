# rag

检索增强（RAG）：文档入库、分块、嵌入、检索与 prompt 拼装。

建议子目录：

- `ingest/` — 离线建库（加载文档、分块、写入向量索引）
- `retrieve/` — 检索与可选重排序
- `prompts/` — 系统提示等模板（如 `fortune_system.md`）
- `pipeline.py` — 检索 → 上下文 → 交给 LLM 的封装（后续添加）

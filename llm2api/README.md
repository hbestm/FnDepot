多上游、多协议转换的 LLM 代理网关（上游 badafans/llm2api，MIT 开源）。
统一暴露 /v1/chat/completions、/v1/messages、/v1/responses 三种协议，
消息体 / 工具调用 / reasoning 字段 / SSE 流双向互转，严格别名路由。
多上游多 Key 轮询、429/5xx 智能重试、按模型 SOCKS5 代理出口、Token 统计。
内嵌自托管 Web 管理面板，默认端口 18333。非 root 专用用户运行，密码不落命令行与日志。
官方地址：https://github.com/badafans/llm2api

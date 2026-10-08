# znaide

**znaide** 是一个跑在终端里的通用 AI 助手：用自然语言下指令，它自主完成改文件、跑命令、查资料、整理数据等任务。Rust 从零实现，自带 agent 循环，单个静态二进制、零 Node 依赖、中文交互。

- 本地模型（ollama / vLLM）与云 API（DeepSeek / 通义 / OpenRouter / 智谱等任意 OpenAI 兼容端点）通吃
- 打开后是浏览器内的终端界面（ttyd 提供 Web 终端），经飞牛统一网关访问，需先登录 NAS，不额外开放端口
- 权限模式：询问 / 编辑放行 / 全自动 / 超级（Shift+Tab 循环切换，默认「询问」，写文件/执行命令前先确认）
- 每次改文件前自动快照，`/undo` 一键回滚

## 架构

本包为 `platform=all` 双架构包，同时内置 x86（amd64）与 ARM（arm64）静态二进制，启动时按系统架构自动选择。

## 首次使用

打开应用后按引导完成模型配置（选服务商 → 自动拉取模型列表 → 填 API Key → 验证连通）。本地 ollama 可留空 Key。

## 说明与风险

该助手可在授权目录内读写文件并执行命令，请自行评估风险。以 AGPL-3.0 开源，商用需另行授权。

- 上游：[twowb/znaide](https://github.com/twowb/znaide)
- 打包发布：87袜子 / [FnDepot](https://github.com/hbestm/FnDepot)

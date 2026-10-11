# FnLxc

飞牛 FnOS 的 **LXC 容器 Web 管理面板**，参考 Proxmox VE 分步向导。

- 三种来源、三种网络、MAC 固定、静态 IP + DNS
- SSH 状态检测、控制台、bind mount、资源限制、开机自启
- 高级一键安装（SSH / Docker / 1Panel / Lucky，异步 + 局部刷新 + 结果浮层）
- 统一网关鉴权、lxcfs 内存显示

## 说明

- 该应用以 **root 权限**运行（管理 LXC 容器所需），请仅在可信环境使用。
- 需要系统支持 LXC（fnOS 1.1.3100 及以上）。

- 发布：87袜子 / [FnDepot](https://github.com/hbestm/FnDepot)

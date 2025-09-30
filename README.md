# Proxy
各种代理协议一键安装脚本

## 🔒 安全说明
本仓库所有脚本已经过安全审计，确保：
- ✅ 所有二进制文件来源可靠（官方源或经验证的本地备份）
- ✅ 移除了所有可疑的第三方引用
- ✅ 代码透明，无后门或隐患

## 📦 支持的协议

### Clash Meta (mihomo)
```shell
bash <(curl -fsSL https://raw.githubusercontent.com/Banezzz/Proxy/main/meta.sh)
```
- 从官方 MetaCubeX/mihomo 仓库下载最新版本

### Tuic
```shell
bash <(curl -fsSL https://raw.githubusercontent.com/Banezzz/Proxy/main/tuic.sh)
```
- 使用经验证的 TUIC v5 二进制文件

### ShadowSocks (支持alpine)
alpine请先安装bash curl
```shell
bash <(curl -fsSL https://raw.githubusercontent.com/Banezzz/Proxy/main/ss.sh)
```
- 基于 go-shadowsocks2 的安全实现

### Hysteria2
```shell
bash <(curl -fsSL https://raw.githubusercontent.com/Banezzz/Proxy/main/hysteria.sh)
```
- 从官方 apernet/hysteria 仓库下载最新版本

### Xray
```shell
bash <(curl -fsSL https://raw.githubusercontent.com/Banezzz/Proxy/main/xray-none.sh)
```
- 从官方 XTLS/Xray-core 仓库下载最新版本

### Sing-box 系列
- **Sing-box Reality**
```shell
bash <(curl -fsSL https://raw.githubusercontent.com/Banezzz/Proxy/main/singbox-reality.sh)
```

- **Sing-box WebSocket**
```shell
bash <(curl -fsSL https://raw.githubusercontent.com/Banezzz/Proxy/main/singbox-ws.sh)
```

- **Sing-box ShadowTLS**
```shell
bash <(curl -fsSL https://raw.githubusercontent.com/Banezzz/Proxy/main/singbox-shadowtls.sh)
```
- 所有 Sing-box 脚本从官方 SagerNet/sing-box 仓库下载

## 🔧 二进制文件说明
本仓库 `binaries/` 目录包含经过验证的二进制文件备份：
- `shadowsocks-amd64` / `shadowsocks-arm64` - ShadowSocks 服务端
- `tuic-amd64` / `tuic-arm64` - TUIC v5 服务端

这些文件已经过安全检查，作为稳定版本备份使用。

## ⚠️ 注意事项
- 所有脚本需要 root 权限运行
- 建议在安装前备份重要数据
- 部分协议可能需要开放相应的防火墙端口

## 📄 许可
本项目遵循原作者的开源协议

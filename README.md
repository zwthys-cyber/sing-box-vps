### 一、Sing-box-vps 一键五协议共存脚本（VPS专用）
### 二、Serv00/Hostuno 一键三协议共存脚本（Serv00/Hostuno专用）

### 注：本项目分享订阅节点都为本地化生成，不使用节点转换、订阅器等第三方外链引用

---

### Sing-box-vps 一键五协议共存脚本（VPS专用）

* 小白简单模式：无需域名证书，回车三次就安装完成
* 支持节点复制和二维码扫描
* 所有节点本地化生成，无第三方订阅转换
* **默认 WARP 分流**：X/Twitter → WARP IPv6；GitHub → WARP（适合「仅 IPv6」出站）
* **Surge 导出**：菜单 `6 → 4` 或主菜单 `18`
* 大文件已迁到 [Releases](https://github.com/zwthys-cyber/sing-box-vps/releases)，仓库本身更轻

#### 功能特性

* 协议：Vless-reality-vision、Vmess-ws(tls)/Argo、Hysteria-2、Tuic-v5、Anytls
* 支持纯 IPv6 / 纯 IPv4 / 双栈；AMD / ARM；Alpine
* 推荐最新 Ubuntu / Debian

### 快速安装

```bash
bash <(curl -Ls https://raw.githubusercontent.com/zwthys-cyber/sing-box-vps/main/sb.sh)
```

或：

```bash
bash <(wget -qO- https://raw.githubusercontent.com/zwthys-cyber/sing-box-vps/main/sb.sh)
```

安装后管理：`sb`

### 仅 IPv6 出站建议

若 VPS 选择 **仅 IPv6**：

* 默认已把 X/Twitter、GitHub 走到 WARP，避免原生 IPv6 打不开这些站点
* 客户端（Surge）可继续关闭 IPv6，只把隧道连到节点；**出站 IPv6 在 VPS 侧完成**
* Surge **不要开启全局 MITM（`*`）**，否则会出现 `ERR_SSL_PROTOCOL_ERROR` / `name error`（尤其是 X）
* Surge **不支持 VLESS Reality**，请用导出的 Hy2 / TUIC / VMess，或 Shadowrocket

### Serv00/Hostuno

```bash
bash <(curl -Ls https://raw.githubusercontent.com/zwthys-cyber/sing-box-vps/main/serv00.sh)
```

* 二进制在 Release 标签 [`serv00`](https://github.com/zwthys-cyber/sing-box-vps/releases/tag/serv00)
* 辅助工具在 [`tools-v1`](https://github.com/zwthys-cyber/sing-box-vps/releases/tag/tools-v1)

---

仓库：https://github.com/zwthys-cyber/sing-box-vps

### 声明

* 代码来源于开源社区整合，仅供学习研究
* 使用后果自负

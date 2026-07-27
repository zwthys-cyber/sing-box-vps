### 一、Sing-box-vps 一键五协议共存脚本（VPS专用）
### 二、Serv00/Hostuno 一键三协议共存脚本（Serv00/Hostuno专用）

### 注：本项目分享订阅节点都为本地化生成，不使用节点转换、订阅器等第三方外链引用，无需担心节点订阅被外链作者查看

---

### Sing-box-vps 一键五协议共存脚本（VPS专用）

* 小白简单模式：无需域名证书，回车三次就安装完成
* 支持节点复制和二维码扫描
* 所有节点本地化生成，无第三方依赖
* 默认 WARP 分流：X/Twitter → WARP IPv6；GitHub → WARP（适合仅 IPv6 出站场景）

#### 功能特性说明

* 支持人气最高的五大协议：Vless-reality-vision、Vmess-ws(tls)/Argo、Hysteria-2、Tuic-v5、Anytls
* 支持纯IPV6、纯IPV4、双栈VPS
* 支持AMD与ARM架构，支持Alpine系统
* 推荐使用最新的Ubuntu系统

### VPS专用一键脚本快速部署

```bash
bash <(curl -Ls https://raw.githubusercontent.com/zwthys-cyber/sing-box-vps/main/sb.sh)
```

或使用 wget：

```bash
bash <(wget -qO- https://raw.githubusercontent.com/zwthys-cyber/sing-box-vps/main/sb.sh)
```

快捷管理命令（安装后）：`sb`

### 界面预览

脚本提供友好的交互式菜单，支持快速配置和管理。

-----------------------------------------------------

### 二、Serv00/Hostuno一键三协议共存脚本（Serv00/Hostuno专用）：

* 目前免费Serv00使用代理脚本有被封账号的风险，收费版Hostuno不受影响，可正常使用

* **注意**：切勿与其他Serv00脚本混用
* 支持三个IP自定义安装，支持Proxyip+反代IP
* 支持Argo临时/固定隧道切换
* 支持多功能网页管理界面
* 完美适配Serv00和Hostuno.com平台

### Serv00/Hostuno 一键脚本

```bash
bash <(curl -Ls https://raw.githubusercontent.com/zwthys-cyber/sing-box-vps/main/serv00.sh)
```

**特性：**
* Argo高度自定义 - 可重置临时隧道、切换固定隧道
* 多功能网页管理 - 保活、重启、重置端口、查看节点等
* 灵活的部署方案 - 支持SSH、多平台部署

---

### 贡献与支持

如果觉得本项目有帮助，请给个 Star ⭐ 支持一下！

仓库地址：https://github.com/zwthys-cyber/sing-box-vps

### 声明

* 所有代码来源于开源社区和公开资源
* 本脚本仅供学习和研究使用
* 使用者需自行承担使用本脚本的所有责任

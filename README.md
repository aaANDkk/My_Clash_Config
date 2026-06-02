# Mihomo / Clash Meta 自用分流配置

一个偏向 **稳定、易维护、低折腾** 的 Mihomo（Clash Meta）分流配置。

适用于：

* Windows
* Android（FlClash、MetaCubeX 等）
* Linux
* 其他支持 Mihomo 内核的客户端

---

## ✨ 配置特点

### 📌 地区分组

内置地区分类：

* 🇭🇰 香港
* 🇨🇳 台湾
* 🇯🇵 日本
* 🇰🇷 韩国
* 🇸🇬 新加坡
* 🇺🇸 美国
* 🌍 其它地区
* 💰 低倍率节点

各地区均提供独立选择组，并包含后台自动测速节点。

---

### 📌 常用服务分流

针对常见服务进行了独立分流：

* AI
* Google 全家桶
* YouTube
* TikTok
* 巴哈姆特
* 哔哩哔哩
* Netflix
* Spotify
* GitHub

支持根据需求单独指定出口地区。

---

### 📌 AI 服务优化

已预设：

* ChatGPT
* Claude
* Grok
* Perplexity
* Midjourney
* OpenRouter
* Devv

相关流量统一进入 AI 分组管理。

---

### 📌 DNS 配置

采用：

* Fake-IP 模式
* 国内 DoH 解析
* GeoSite / GeoIP 规则分流
* Respect-Rules

特点：

* 减少 DNS 泄漏风险
* 降低开机抢跑概率
* 兼顾解析速度与兼容性

---

### 📌 Sniffer 支持

启用：

* HTTP Sniffing
* TLS Sniffing
* QUIC Sniffing

有助于提升规则命中率。

---

### 📌 移动网络优化

针对手机场景增加：

* 自动检测网络接口
* 网络切换重置连接
* UDP 超时优化

在 Wi-Fi 与移动网络切换时体验更稳定。

---

## 📂 节点管理

支持多个订阅源：

* prov1
* prov2
* prov3

通过 Provider 统一管理节点，无需手动维护节点列表。

---

## 🎯 设计目标

本配置更关注：

* 稳定
* 清晰
* 易维护

而不是追求复杂规则或极限性能。

如果你的需求是：

* 日常浏览
* AI 工具使用
* 流媒体观看
* GitHub 开发

那么开箱即可使用，并且后续修改成本较低。

---

## ⚠️ 说明

* 本仓库不提供任何节点服务。
* 使用前请自行填写订阅地址。
* 规则及策略组仅代表个人使用习惯，可根据需要自行调整。

---

## 📜 License

仅供学习与交流使用。

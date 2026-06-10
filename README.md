# 🕊️ 雨燕云最新域名列表

欢迎来到 **雨燕云 (YUYAN CLOUD)** 官方发布页域名/列表配置仓库。本仓库用于实时维护、分发雨燕云最新的官方网站地址，并作为备用 API 节点，供客户端、发布页和用户查询。

[![Status](https://img.shields.io/badge/status-active-success.svg)](#)
[![GitHub license](https://img.shields.io/github/license/yuyancloud/WebsiteList)](LICENSE)

---

## 🔗 永久防失联通道

如果所有常规域名无法访问，请通过以下永久渠道获取最新入口：

1. **GitHub 仓库 (当前页面)**：建议收藏此仓库。
2. **Telegram 官方频道**：[雨燕云官方频道](https://t.me/yuyanyun_chanel) (获取最新通知与域名更新)
3. **Telegram 客服机器人**：[雨燕云网页客服](https://t.me/yuyan_webbot)
4. **官方推特 (X)**：[yuyan_cloud](https://x.com/yuyan_cloud)

---

## 📡 动态域名 API 接口

本仓库托管了域名发布页的核心配置文件 `new-website.json`。发布页会通过并发测速算法自动拉取此列表，并重定向至最快线路。

### 1. JSON 配置结构 (`new-website.json`)

本仓库中需包含一个 `new-website.json` 文件，内容格式如下：

```json
{
  "updated_at": "2026-06-10T19:00:00Z",
  "domains": [
    "new1.yuyan.online",
    "new2.yuyan.online",
    "new5.yuyan.online"
  ]
}
```

### 2. 备用 API 获取地址 (免代理 CDN 加速)

若您的发布页无法连通主 R2 节点，可以通过以下备用 CDN 节点获取此仓库的配置：

- **GitHub Raw 节点** (需代理访问)：
  `https://raw.githubusercontent.com/yuyancloud/WebsiteList/main/new-website.json`
- **jsDelivr CDN 加速** (国内直连优化)：
  `https://fastly.jsdelivr.net/gh/yuyancloud/WebsiteList@main/new-website.json`

---

## 🌐 雨燕云官方域名速览

| 域名类型              | 访问地址                                               | 说明                   |
| :-------------------- | :----------------------------------------------------- | :--------------------- |
| **永久域名** (需代理) | [yuyan.co](https://yuyan.co)                           | 官方永久保留域名       |
| **永久域名** (需代理) | [yuyan.online](https://yuyan.online)                   | 官方永久保留域名       |
| **发布页** (免代理)   | [最新发布页](https://yuyancloud.github.io/WebsiteList) | 自动测速并分发最新官网 |

---

## 🛠️ 常见连通性故障排除

### 1. 域名被污染 (DNS 污染)

如遇到“网页无法打开”但开启代理即可正常运行，说明您的 DNS 解析已被运营商污染。
**解决方法：**
建议在浏览器（如 Chrome / Edge）设置中开启 **安全 DNS (DoH)**，并填入以下服务商之一：

*   **阿里加密 DNS**: `https://dns.alidns.com/dns-query`
*   **腾讯加密 DNS**: `https://doh.pub/dns-query`

### 2. 推荐浏览器

为保证顺畅访问，请避免使用国产浏览器（如 QQ、UC、360、微信内置浏览器等），推荐使用 **Chrome、Edge、Safari、Firefox** 等国际主流浏览器。

---

## 📄 许可声明

本项目遵循 MIT 许可证开源。

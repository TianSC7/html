# 项目信息 SOP — AI 记忆文档

> 每次对话开始时，将此文档内容告知 AI，AI 即可了解你的项目背景。

---

## 🌐 项目基本信息

| 项目 | 内容 |
|------|------|
| 网站名称 | 全屋定制设计工具 - 智能家居装修设计平台 |
| 正式域名 | https://www.example.cn/ |
| 托管平台 | Vercel |
| 代码仓库 | https://github.com/username/repo |
| 备案号 | 蜀ICP备XXXXXXXX号-X |

---

## 📁 项目结构说明

- 代码托管在 **GitHub**：`github.com/username/repo`
- 通过 **Vercel** 部署，绑定自定义域名
- **不使用 GitHub Pages**，请勿混淆

---

## 🔧 SEO 文件路径（正确地址）

| 文件 | 正确 URL |
|------|---------|
| robots.txt | https://www.example.cn/robots.txt |
| sitemap.xml | https://www.example.cn/sitemap.xml |

---

## 📄 robots.txt 标准内容

```txt
# https://www.robotstxt.org/robotstxt.html
User-agent: *
Allow: /

# Sitemap
Sitemap: https://www.example.cn/sitemap.xml

# 百度爬虫特殊规则
User-agent: Baiduspider
Allow: /
Crawl-delay: 1

# Google爬虫
User-agent: Googlebot
Allow: /

# 必应爬虫
User-agent: Bingbot
Allow: /

# Disallow
Disallow: /node_modules/
Disallow: /.git/
```

---

## 🗺️ sitemap.xml 标准内容

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9"
        xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
        xsi:schemaLocation="http://www.sitemaps.org/schemas/sitemap/0.9
        http://www.sitemaps.org/schemas/sitemap/0.9/sitemap.xsd">
  <url>
    <loc>https://www.example.cn/</loc>
    <lastmod>2026-03-24</lastmod>
    <changefreq>weekly</changefreq>
    <priority>1.0</priority>
  </url>
</urlset>
```

---

## 🚀 Vercel 部署 SOP

1. 修改代码后 `git push` 到 GitHub 仓库
2. Vercel 自动检测到更新，触发自动部署
3. 部署完成后访问正式域名验证

---

## 📌 AI 对话时请记住

- 域名是 `https://www.example.cn/`，**不是** `username.github.io`
- 托管平台是 **Vercel**，**不是** GitHub Pages
- 所有 SEO 文件的 URL 都应以正式域名开头
- 仓库地址：`https://github.com/username/repo`

---

*最后更新：2026-03-24*

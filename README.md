# 双休GO 静态存档（shuangxiu-go-archive）

本仓库是第三方站点 **[双休GO](https://shuangxiu-go.cn/)** 的静态存档备份，抓取于 **2026-10-05**，部署于 GitHub Pages。

## 说明

- 本站内容为 AI 辅助分析 + 个人观点/想法的整理，**并非官方数据源**，请以企业官方及权威渠道信息为准。
- 本站为转载存档备份（类似维基百科的资料来源存档），数据版权归原站/原作者所有。
- 内容完整性以抓取时的 SSR 页面为准；静态资源（CSS/JS/图片）已尽量本地化到 `assets/`，少量未获取到的资源保留原站绝对 URL。

## 存档范围

- 首页 `/`
- 城市页 58 个（`/city/*`，含分页）
- 公司详情页 578 个（`/company/*`）
- 功能页：单休模式 `/single`、`/single/ranking`、`/single/governance`，以及 `/ranking`、`/submit`、`/governance`、`/appeal`
- 搜索页：`/search?status=evidence`、`/search?q=互联网`、`/search?q=软件`（各含 4 页分页）
- `robots.txt`、`sitemap.xml`（原站参考副本）

## 部署

仓库根目录即静态站点内容，GitHub Pages 从 `main` 分支 `/` 目录部署。

线上地址：https://dujeongil-galaxy.github.io/shuangxiu-go-archive/

原站地址：https://shuangxiu-go.cn/

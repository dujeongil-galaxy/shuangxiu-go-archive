# 双休GO 静态存档（shuangxiu-go-archive）

> **项目定位：本仓库是第三方网站「双休GO」(https://shuangxiu-go.cn/) 的全量静态存档备份**，与账号下另外两个双休购相关仓库是不同的项目，请勿混淆：
>
> - **本仓库（shuangxiu-go-archive）**：仅存第三方「双休GO」站点的静态快照（620 家企业 + 60 城市页），**不包含主站数据，也不是主站的数据源**；
> - **shuangxiugou**（[主站](https://github.com/dujeongil-galaxy/shuangxiugou)）：「双休购」众包测评 + 评级卡片的线上应用；
> - **shuangxiugou-guide**（[指南](https://github.com/dujeongil-galaxy/shuangxiugou-guide)）：独立的「双休购 2.0」公开资料与消费决策工具站。

本仓库是第三方站点 **[双休GO](https://shuangxiu-go.cn/)** 的静态存档备份，当前快照抓取于 **2026-11-07**（首次抓取 2026-10-05，提交 `6e3fe45`），部署于 GitHub Pages。

## 说明

- 本站内容为 AI 辅助分析 + 个人观点/想法的整理，**并非官方数据源**，请以企业官方及权威渠道信息为准。
- 本站为转载存档备份（类似维基百科的资料来源存档），数据版权归原站/原作者所有。
- 内容完整性以抓取时的 SSR 页面为准；静态资源（CSS/JS/图片）已本地化到 `assets/`，站内链接改为相对路径，直接打开 `index.html` 即可离线浏览。
- 少数无法映射到存档页面的站内链接（带筛选条件的搜索 URL、单休模式 `/single/company/*` 与 `/single/city/*` 变体等）保留指向原站，避免死链。

## 存档范围

- 首页 `/`，合计 **706 个 HTML 页面 + 18 个 `assets/` 静态资源**
- 城市页 60 个（`/city/*`，含分页共 68 个 HTML）
- 公司详情页 620 个（`/company/*`）
- 功能页：单休模式 `/single`、`/single/ranking`、`/single/governance`，以及 `/experiences`（本轮新增）、`/ranking`、`/submit`、`/governance`、`/appeal`
- 搜索页：`/search?status=evidence`、`/search?q=互联网`、`/search?q=软件`（含分页共 9 个 HTML）
- `robots.txt`、`sitemap.xml`（原站参考副本，1369 条 URL）
- `.nojekyll`：保证 GitHub Pages 正常提供 `_next` 静态资源

## 部署

仓库根目录即静态站点内容，GitHub Pages 从 `main` 分支 `/` 目录部署。

线上地址：https://dujeongil-galaxy.github.io/shuangxiu-go-archive/

原站地址：https://shuangxiu-go.cn/

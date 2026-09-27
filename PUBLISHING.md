# 发布到 GitBook 免费版

本目录的 `README.md`、`SUMMARY.md` 和六篇章节 Markdown 是网站内容。原始 Markdown 与 PDF 保留作备份；不要把 `PUBLISHING.md` 加入目录。

## 发布

1. 在 GitHub 新建公开仓库，上传本目录全部文件。`SUMMARY.md` 控制网站导航。
2. 登录 GitBook，建立站点，选择 Git Sync，连接这个 GitHub 仓库与对应分支。
3. 首次同步时选择 **GitHub → GitBook**，使仓库内容成为初始内容；项目目录选择仓库根目录。同步后检查章节顺序和正文。
4. 在站点设置中选择 **Audience → Public**，预览无误后点击 **Publish**。记录生成的 `*.gitbook.io` 网址。

如果在 GitBook 中先建立了内容，首次同步前应仔细确认同步方向，避免覆盖已写内容。

## 搜索引擎收录

网站发布并设为 Public 后，可以被搜索引擎抓取；不要设置为 Unlisted。GitBook 会为符合条件的公开站点生成 `/sitemap-pages.xml`。发布后用浏览器确认该文件可访问，并在搜索引擎中查询 `site:你的站点.gitbook.io`。搜索结果出现时间和排序由搜索引擎决定，GitBook 不作保证。

在其他已被收录的网页、社交主页或公开文章中加入网站链接，有助于搜索引擎发现。GitBook 文档说明，直接向 Google Search Console 提交站点需要自定义域名和 DNS 所有权验证；免费版 GitBook 目前不提供自定义域名。

参考：

- [GitBook 发布文档](https://gitbook.com/docs/publish/publish-a-docs-site)
- [GitBook SEO 说明](https://gitbook.com/docs/publish/seo)
- [GitBook GitHub 同步说明](https://gitbook.com/docs/docs-as-code/git-sync/enabling-github-sync)
- [GitBook 价格](https://www.gitbook.com/pricing)

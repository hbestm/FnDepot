一款在线的 **微信公众号文章批量下载** 工具，支持导出阅读量与评论数据，无需搭建任何环境，可通过 [在线网站] 使用，同时也支持 docker 私有化部署和 Cloudflare 部署。

支持下载各种文件格式，其中 HTML 格式可100%还原文章排版与样式。

交流群(QQ): `991482155`

## :bell: 重要告知：项目域名调整
项目域名调整如下：

|     | 下载站                            | 文档站                        |
|-----|--------------------------------|----------------------------|
| 调整后 | https://down.mptext.top        | https://docs.mptext.top    |
| 调整前 | https://exporter.wxdown.online | https://docs.wxdown.online |

具体细节可以查看 [这里](https://docs.mptext.top/misc/domain.html)。


## :books: 如何使用？

该工具的使用教程已移至 [文档站点](https://docs.mptext.top)。


## :dart: 特性

- [x] 搜索公众号，支持关键字搜索
- [x] 支持导出 html/json/excel/txt/md/docx 格式(html 格式打包了图片和样式文件，能够保证100%还原文章样式)
- [x] 缓存文章列表数据，减少接口请求次数
- [x] 支持文章过滤，包括作者、标题、发布时间、原创标识、所属合集等
- [x] 支持合集下载
- [x] 支持图片分享消息
- [x] 支持视频分享消息
- [x] 支持导出评论、评论回复、阅读量、转发量等数据 (需要抓包获取 credentials 信息，[查看操作步骤](https://docs.mptext.top/advanced/wxdown-service.html))
- [x] 支持 Docker 部署
- [x] 支持 Cloudflare 部署
- [x] 开放 API 接口

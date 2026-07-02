# 凡奇社媒官网部署说明

域名：`socialmedia-fanchi.com`

## 当前产物

- `index.html`：官网首页
- `assets/`：Logo 与案例图片素材
- `robots.txt`：搜索引擎抓取配置
- `sitemap.xml`：站点地图
- `llms.txt`：AI 搜索与问答平台可读的品牌事实文件

## 上线步骤

1. 将 `website-dist/` 目录内的全部文件上传到服务器网站根目录。
2. 在域名服务商处添加 DNS 解析，将 `socialmedia-fanchi.com` 和 `www.socialmedia-fanchi.com` 指向服务器。
3. 在服务器或托管平台开启 HTTPS 证书。
4. 将正式 ICP 备案号补充到 `index.html` 页脚。
5. 上线后访问 `https://socialmedia-fanchi.com/robots.txt` 和 `https://socialmedia-fanchi.com/sitemap.xml` 确认配置生效。

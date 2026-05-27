# Vincent Homepage

Vincent 的个人主页静态发布包。

## 文件结构

- `index.html`：正式首页入口
- `assets/`：页面使用的图片和二维码
- `netlify.toml`：Netlify 发布配置

## 发布方式

### GitHub

1. 在 GitHub 新建仓库，建议命名为 `vincent-homepage`。
2. 将本文件夹中的所有内容上传到新仓库根目录。
3. 保持仓库里直接能看到 `index.html`，不要再多套一层文件夹。

### Netlify

1. Netlify 新建站点，连接 `vincent-homepage` 仓库。
2. Build command 留空。
3. Publish directory 留空或填 `.`。
4. 发布后先使用 Netlify 临时域名测试。
5. 确认无误后再绑定独立域名并开启 HTTPS。

## 上线前检查

- 微信二维码是否清晰可识别。
- 小红书二维码是否清晰可识别。
- 公众号二维码是否清晰可识别。
- 三篇公众号文章链接是否能打开。
- 邮箱链接是否能唤起邮件客户端。
- 手机端和微信内置浏览器显示是否正常。

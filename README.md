# Vincent Homepage

Vincent 的个人主页静态发布包。

## 文件结构

- `index.html`：正式首页入口
- `view.html`：我的观点与文章入口
- `about.html`：关于我
- `homepage.html`：首页备份入口，内容与 `index.html` 一致
- 页面图片和二维码：已放在根目录，方便 GitHub 网页上传后 Netlify 直接识别
- `assets/`：图片备份目录，建议一起上传
- `netlify.toml`：Netlify 发布配置

## 发布方式

### GitHub

1. 在 GitHub 新建仓库，建议命名为 `vincent-homepage`。
2. 将本文件夹中的所有内容上传到新仓库根目录。
3. 保持仓库里直接能看到 `index.html` 和各张图片，不要再多套一层文件夹。
4. 如果 GitHub 支持上传文件夹，也把 `assets/` 一起上传。

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

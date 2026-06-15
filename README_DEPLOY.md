# ING App Store Web Pages

本目录包含 App Store Connect 所需的静态网页：

- `index.html`：入口页
- `privacy.html`：Privacy Policy URL 对应页面
- `support.html`：Support URL 对应页面

## 当前状态

- 这些页面用于公开展示 ING 的隐私政策与支持信息。
- 本轮不修改 Swift，不修改 Xcode project，不做 archive，不上传 App Store。
- App 名称统一为 `ING`，不添加其他名称后缀。

## 后续重新部署建议

如需重新发布，可部署到以下任一静态网页服务：

- GitHub Pages
- Cloudflare Pages
- 公司官网
- 其他静态网页服务

发布后，在 App Store Connect 中填写：

- Privacy Policy URL = 公网页面中的 `privacy.html`
- Support URL = 公网页面中的 `support.html`

## 支持邮箱

`ingsupport@163.com` 是当前支持邮箱。

部署前仍建议人工复核以下页面中的邮箱是否一致：

- `privacy.html`
- `support.html`

## 安全边界

- 不要把真实后端服务 URL / key / token 写进网页。
- 不要把真实 secret、密码、服务端 key 或后台配置写进网页。
- 不要把个人隐私信息写进网页。
- 不要把真实个人电话写进网页。
- 不要在网页、截图、README 或提交记录中暴露任何真实 key。

## 命名规则

- App 名称统一为 `ING`。
- 不要给 App 名称添加其他后缀。
- 网页标题、隐私政策、Support 页面、README 中均保持 `ING` 作为软件名称。

# ING App Store Web Deploy Checklist

## 1. 部署包用途

本部署包用于 App Store Connect 的 Privacy Policy URL 和 Support URL。

部署包内的页面：

- `index.html`
- `privacy.html`
- `support.html`
- `README_DEPLOY.md`

## 2. 当前 App 名称

ING

## 3. 当前支持邮箱

[ingsupport@163.com](mailto:ingsupport@163.com)

## 4. 部署后应得到

- `https://你的公网域名/privacy.html`
- `https://你的公网域名/support.html`

## 5. 可选部署方式

- GitHub Pages
- Cloudflare Pages
- 公司官网静态目录
- 其他静态网页托管服务

## 6. 人工部署后检查

- 手机浏览器打开 `privacy.html`
- 手机浏览器打开 `support.html`
- 桌面浏览器打开 `privacy.html`
- 桌面浏览器打开 `support.html`
- 确认邮箱显示为 [ingsupport@163.com](mailto:ingsupport@163.com)
- 确认 App 名称显示为 ING
- 确认没有 Supabase URL / key / token

## 7. App Store Connect 填写

- Privacy Policy URL = 部署后的 `privacy.html` 链接
- Support URL = 部署后的 `support.html` 链接

## 8. 禁止事项

- 不要上传 Swift / Xcode 工程文件
- 不要上传 secret / key / token
- 不要把 Supabase URL 写进网页
- 不要把私人手机号写进网页

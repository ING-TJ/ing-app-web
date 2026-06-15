# App Store Public Web Copy Polish Report

## 本轮目标

优化已发布 ING Privacy / Support 静态网页的公开表述，把面向开发的术语调整为适合 App Store 审核和普通用户阅读的正式表述。本轮只处理 GitHub Pages 静态网页文案与说明文件，不修改 App 代码、Xcode 工程或发布流程。

## 修改文件清单

- `index.html`
- `privacy.html`
- `support.html`
- `README.md`
- `README_DEPLOY.md`
- `DEPLOY_CHECKLIST.md`
- `APP_STORE_PUBLIC_WEB_COPY_POLISH_REPORT.md`

说明：当前 Pages 仓库未包含 `app-store-web/` 或 `app-store-web-deploy-package/` 目录，发布网页文件位于仓库根目录，因此本轮在当前 Pages 仓库根目录完成对应文案优化。

## 替换前后关键文案

| 替换前 | 替换后 |
| --- | --- |
| `mock 数据` | `本地示例数据` |
| `Supabase Auth` | `不需要账号登录服务` |
| `SQL / 真实表` | `不进行远程数据库写入` |
| `真实写入` | `不上传或保存用户发布内容` |
| `隐私政策草案` | `了解当前版本如何处理数据` |
| `支持与反馈草案` | `获取帮助与反馈渠道` |
| `当前不接广告 / 第三方分析 SDK / 推送` | `当前版本不接入广告、第三方分析 SDK 或推送` |

## 核对结论

- App 名称是否仍为 ING：是
- 邮箱是否仍为 [ingsupport@163.com](mailto:ingsupport@163.com)：是
- 是否包含真实 URL / key / token：否，不包含真实后端服务 URL、key 或 token
- 是否修改 Swift：否
- 是否修改 Xcode project：否
- 是否 archive：否
- 是否上传 App Store：否

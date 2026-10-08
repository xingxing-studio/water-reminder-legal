# 到时间喝水啦｜官方法律与支持网站

本仓库只公开「到时间喝水啦」iOS App 的法律和帮助页面，不包含 App 源码、构建签名或用户饮水记录。

网站包含：

- [网站首页](https://xingxing-studio.github.io/water-reminder-legal/)
- [隐私政策](https://xingxing-studio.github.io/water-reminder-legal/privacy/)
- [服务条款](https://xingxing-studio.github.io/water-reminder-legal/terms/)
- [帮助与支持](https://xingxing-studio.github.io/water-reminder-legal/support/)

网页文件直接位于本仓库的 `main` 分支根目录（`index.html`、`privacy/index.html`、`terms/index.html`、`support/index.html`）。内容根据私有产品仓库的 `legal/*.zh-CN.md` 正式版本生成；本仓库只用于公开网页托管。

**发布要求**：仓库拥有者需要在 [Settings → Pages](https://github.com/xingxing-studio/water-reminder-legal/settings/pages) 中将 Source 设为 **Deploy from a branch**，Branch 设为 **main / (root)** 并保存。GitHub Pages 会自动发布根目录文件；页面实际返回 HTTPS 200 并经过免登录浏览后，才可以在 App Store Connect 填写网址。

更新法律内容时须重新从产品仓库正式正文生成四个 HTML，避免 App 内与公开政策出现两套矛盾文本。严禁将原私有 App 仓库、密钥、测试数据公开。

# 开发工具箱

个人开发工具入口页，集中访问已部署的日常工具。

## 在线入口

- [提示词优化器](https://106.54.53.98/)
- [日志解析器](https://106.54.53.98/log-parser/)
- [JSON 格式化](https://106.54.53.98/json-formatter/)
- [文本对比](https://106.54.53.98/text-diff/)

仓库中的 `index.html` 是独立静态入口页，无需构建。工具卡片链接可直接在 HTML 中修改。

## 发布入口页

在仓库 **Settings → Pages** 中，将 **Build and deployment** 设为 **Deploy from a branch**，选择 `main` 分支和 `/(root)` 目录，然后保存。发布完成后，GitHub Pages 会提供公开入口地址。

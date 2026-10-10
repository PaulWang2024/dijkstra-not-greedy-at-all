# Dijkstra Is NOT Greedy · 中英文论文网站

作者：王圣宝 / Shengbao Wang  
单位：杭州师范大学 / Hangzhou Normal University

本仓库是适用于 GitHub Pages 的静态网站，无需 npm、Jekyll 构建或服务器。

- 中文首页：`index.html`
- English full text：`en.html`
- PDF：`paper-zh.pdf` 和 `paper-en.pdf`
- LaTeX：`paper-zh.tex` 和 `paper-en.tex`

## 发布步骤（GitHub 网页端）

1. 新建公开仓库，例如 `dijkstra-not-greedy`。
2. 解压本 ZIP，将其中的**文件**上传至仓库的 `main` 分支根目录（不是将 ZIP 本身上传）。
3. 仓库 → Settings → Pages → Build and deployment → Source = `Deploy from a branch`。
4. Branch = `main`，Folder = `/(root)`，点击 Save。
5. 站点地址为 `https://用户名.github.io/dijkstra-not-greedy/`，实际请以 Pages 面板为准。

注意：在线 LaTeX 数学公式由 MathJax（jsDelivr CDN）渲染，因此浏览器需要能够连接此 CDN。页面内部语言、目录和 PDF 链接均采用相对路径。

该仓库已包含 `.nojekyll`，保证 GitHub Pages 直接发布静态文件。

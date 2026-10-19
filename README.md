# Yangsheng Mei — personal website

Quarto source for https://yangshengmei.com.

## 在 RStudio 编辑

打开 `yangshengmei.Rproj`，编辑 `.qmd` 文件，然后点击 Render，或在 Terminal 运行 `quarto render`。

- `index.qmd`：首页
- `research.qmd`：论文与研究
- `cv.qmd`：履历；有真实 PDF 后放入 `files/cv.pdf` 并添加链接
- `writing.qmd`：中文文章目录；新文章使用根目录的 `.qmd` 文件，并在目录添加链接
- `photography.qmd`：摄影；图片放入 `images/`，补充替代文字
- `styles.css`：字体、颜色、间距

本地预览输出到 `docs/`。提交源文件到 main 后，GitHub Actions 自动渲染和发布，无需上传生成的网页。GitHub Settings → Pages 的 Source 应为 GitHub Actions。

不要把密码、私密材料、未授权的照片或私人 CV 信息放入公开仓库。

## 自定义域名

GitHub Pages Custom domain: yangshengmei.com。Cloudflare 使用 DNS only：根域名 A 记录指向 GitHub Pages 的四个地址，www CNAME 指向 yangsheng-mei.github.io。确认无冲突记录后再添加。证书签发完成后开启 Enforce HTTPS。

官方说明：https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

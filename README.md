# studio-site

Clock Out Studio 的静态主页。纯 HTML + CSS，没有构建步骤、没有后端、没有脚本、没有外部字体。

- 预览：`npx vite preview --outDir studio-site`，或直接用浏览器打开 `index.html`。
- 部署：把整个 `studio-site/` 目录上传到任意静态托管（GitHub Pages、Cloudflare Pages、Vercel、Netlify、国内对象存储静态网站）。国内托管给中国大陆访问需要网站 ICP 备案，这是独立于小游戏前置备案的另一件事。
- 修改联系方式：`index.html` 里的 `business@example.com`（与 `config/app.json` 的 developer.email 保持一致）。
- 更新截图：`npm run release:screens` 后，把新截图压缩为 540×960 JPG 放进 `assets/`。

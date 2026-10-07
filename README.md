# 炬光智慧顧問企業｜Brightwise Intelligence Consulting

炬光智慧顧問企業的靜態公司介紹網站，使用 HTML、CSS 與 JavaScript 製作。

## GitHub Pages 部署

此儲存庫包含 GitHub Actions 工作流程。將 `main` 分支推送到 GitHub 後，工作流程會把網站需要的首頁、樣式、互動程式與 BIC 品牌圖片部署到 GitHub Pages。

在 GitHub 儲存庫的 **Settings → Pages** 中，將建置與部署來源設為 **GitHub Actions**。部署完成後，GitHub Actions 會顯示網站網址，網址格式通常為 `https://<owner>.github.io/<repository>/`。

網站部署只會打包以下檔案：`index.html`、`styles.css`、`script.js`、`bic-logo-transparent.png`、`bic-hero-visual.png`。

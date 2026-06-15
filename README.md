# 商品型錄網站

## 部署到 Cloudflare Pages

1. 將此資料夾上傳到 GitHub（新建一個 repo）
2. 前往 https://pages.cloudflare.com
3. 點擊「Create a project」→「Connect to Git」
4. 選擇此 repo
5. Build 設定：
   - Framework preset: `None`
   - Build command: （留空）
   - Build output directory: `/`
6. 按「Save and Deploy」

完成！之後每次推送 index.html 到 GitHub 就會自動更新網站。

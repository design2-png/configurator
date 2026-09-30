Backbone 桌款配置器（靜態網站）
--------------------------------
上傳整個資料夾到任何靜態主機即可（backbone.tw 主機、Netlify、Vercel、GitHub Pages）。
不需要後端，開啟 index.html 所在的網址就能用（需透過 http/https，直接雙擊本機檔案不會載入模型）。

檔案：
  index.html      頁面與介面
  app.js          3D 引擎（three.js 打包）
  models/*.glb    四款桌型（Elite / S40 / Forma / 2.5 屏風）與縮圖
  tex/*.jpg       74 款板材貼圖與縮圖，tex/boards.json 為料號清單（可自行增減）

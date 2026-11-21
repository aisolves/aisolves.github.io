# AI 有解｜生活工具實驗室 — 網站第一版

## 網站內容
- 首頁與品牌主視覺
- 工具庫（交通／生活管理分類，可互動切換）
- 品牌介紹
- Instagram 回饋入口
- 手機、平板、桌面響應式設計

## 本機開啟
直接開啟 `index.html` 即可檢視；不需要安裝套件。

## 網路部署（建議 GitHub Pages）
1. 建立 GitHub repository，例如 `ai-solves-site`，設為 public。
2. 上傳 `index.html` 和 `assets/logo.png`（保留資料夾結構）。
3. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save。
4. 等待 GitHub 顯示正式網站網址，例如 `https://<使用者名稱>.github.io/ai-solves-site/`。
5. 使用手機檢查操作，再把公開網址放入 IG 自介。

## 發布前必做
1. 將 `sites-project://` 兩個連結替換成現有工具可公開存取的 HTTPS 網址。目前這是 ChatGPT 內部專案連結，外部訪客不保證能用。
2. 將文末 `https://www.instagram.com/` 換成實際 IG 帳號個人檔案網址。
3. 確認公開工具不包含個人資訊、訂單、地址、電子郵件、API key 或憑證。
4. 高鐵資料為示意案例，並非即時時刻表；若公開資訊有變動，請更新示例。
5. IG 帳號 @ai.solves.tw 尚未確認可註冊。

此網站為純靜態 HTML/CSS/JS，分類篩選可離線使用，沒有後端、使用者帳號或即時運輸 API。 

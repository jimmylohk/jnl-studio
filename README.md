# JNL STUDIO — 網站展示版

這個資料夾已經是可直接上載的網站，不需要安裝軟件或重新編譯。
包含實物照片、響應式版面、捲動動畫、商品詳情、示範購物車及購買內容確認。
目前沒有真實付款、訂單處理或管理後台；重新整理頁面會清空示範購物車。

## 上載去 GitHub Pages
1. 解壓縮下載的 ZIP。
2. 在 GitHub 建立一個新的 Public repository，例如 jnl-studio。免費帳戶可使用公開 repository 的 Pages。
3. 點擊 Add file → Upload files。
4. 上載解壓後的所有檔案與資料夾，包括 index.html、favicon.svg、assets/、objects/ 和 .nojekyll（隱藏檔案）。
   index.html 必須直接位於 repository 最外層，不要多包一層資料夾，亦不要只上載 ZIP。
   若尚未有任何檔案，可點擊頁面中的「uploading an existing file」。
5. 點擊 Commit changes。
6. 進入 Settings → Pages。
7. Source 選 Deploy from a branch。
8. Branch 選 main，資料夾選 /(root)，然後 Save。
9. 等待部署成功；Pages 設定頁會顯示正式網址。
   一般格式：https://你的用戶名.github.io/jnl-studio/
   若失敗，到 Actions 查看結果。

檔案採相對路徑，可放在不同 repository 名稱下，不需要改相片網址。
在 Mac Finder 按 Command + Shift + . 可顯示 .nojekyll。
若上載時看不到隱藏檔，可在 GitHub 用 Add file → Create new file 新增名為 .nojekyll 的檔案。

## 修改內容
- 直接換照片：替換 objects/ 內的 WebP 檔，保留檔名與 WebP 格式。
- 改字、改價錢、加產品或調整版面：使用另外提供的可編輯原始碼版本，再重新產生網站。
- 請勿直接編輯 assets/ 裡的壓縮程式檔。
- 下載後直接雙擊 index.html，不一定能正常載入 JavaScript。請透過網站伺服器或 GitHub Pages 查看。

## 使用範圍
這是設計展示／互動原型，不處理任何真實交易。
GitHub Pages 不可用作經營正式網店或主要促成商業交易的免費主機。
如果日後要正式售賣，可把原始碼保留在 GitHub，另用適合商業網站的託管服務並接駁付款及訂單系統。
GitHub Pages 一般會公開你的網站；不會沿用目前私人預覽的存取限制。

GitHub 官方說明：
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits

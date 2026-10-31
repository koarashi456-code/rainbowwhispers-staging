# 彩之語 — 測試站 (staging)

這是 [rainbowwhispers](https://github.com/koarashi456-code/rainbowwhispers) 的測試站，改版先推到這裡確認，沒問題再推正式站。

- 網址：https://koarashi456-code.github.io/rainbowwhispers-staging/
- 連的是**正式的 Supabase 資料庫**：只看畫面，不要送出預約、付款、儲值或表單。
- 不讓搜尋引擎收錄（robots.txt + noindex）。
- 不含正式站的 keep-alive 排程（正式站已在跑）。

---

# 彩之語 Rainbow Whisper — 網頁

彩之語（身心靈「引路人」配對平台）的前端網頁。

## 檔案
- `index.html` — 相處頻率測驗（7 步・8 種結果；結果用 LINE 回傳、含個資告知、LINE 分享）
- `home.html` — 首頁（參考版；實際首頁已在 WIX 原生做好）
- `apply-form.html` — 引路人免費申請表（送出寄到信箱）
- `buttons/` — 彩虹 CTA 按鈕圖
- `make_button.py` — 產生彩虹按鈕圖的腳本

## 說明
實際網站在 WIX（首頁、會員區、CRM、預約）。這裡放的是可嵌入的靜態網頁。
官方 LINE：@518xokyr

> 每個 HTML 檔開頭都有 `CONFIG` 設定區，可改品牌色、LINE、分享網址等。

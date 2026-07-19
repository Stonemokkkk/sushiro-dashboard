# 壽司郎排隊 App 版本記錄

## V3 (2026-07-19)
**改動：**
- 舖頭名字型加大：14px → 16px，跟返底欄關注列表字體大小

## V2 (2026-07-19)
**改動：**
- 全面壓縮spacing：header、tab、store-grid、store-card、info-row、tickets
- Tab padding: 6px → 3px
- Store Card margin: 6px → 3px, padding: 10px 12px 8px → 5px 8px 4px
- Store Card border-radius: 10px → 8px
- Store Name margin: 6px → 2px
- Info Row margin: 6px → 2px
- Tickets gap: 6px → 3px, padding-top: 6px → 3px
- Tracking Bar padding: 10px 14px → 5px 8px
- Tracking Bar buttons padding: 8px 12px → 4px 8px
- Modal body padding: 20px 18px 28px → 10px 12px 14px
- Modal input width: 140px → 120px
- Grid row gap: 6px → 3px
- Refresh button size: 44px → 36px
- Alert modal padding: 32px 24px → 20px 16px

## V1 (2026-07-19)
**功能：**
- 左右並排顯示，每頁5行10個分店
- 向上捲動查看更多分店
- 地區分類Tab：全部/香港島/九龍/新界
- 等候時間（分鐘）+ 等候組數顯示
- 籌號顯示（電話排隊8字頭 + 現場排隊）
- 撳入舖頭可輸入籌號追蹤
- 追蹤後格仔背景變黃色
- 底欄顯示追蹤資料：店名 + 籌號 + 狀態
- 提示按鈕：開啟後差10張以內彈出提醒同響聲
- 取消掣：可即刻取消關注
- 每30秒自動更新
- iOS彈跳效果（rubber-band）
- Modal從底部彈出，字型加大至32px
- 紅黑層次底欄設計

**技術：**
- HTML5 + CSS3 + JavaScript
- API: sushipass.sushiro.com.hk
- CORS Proxy: cors.freehi.workers.dev
- GitHub Pages 部署

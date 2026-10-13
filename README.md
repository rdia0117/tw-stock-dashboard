# 台股觀察儀表板

https://rdia0117.github.io/tw-stock-dashboard/

這個 repo 只放發佈出來的靜態網頁與資料，由 `rdia0117/tw_stock_stage1`
的 `publish-dashboard` workflow 自動推送，**不要手動編輯**，會被覆蓋。

| 檔案 | 說明 |
|---|---|
| `index.html` | 儀表板本體，單一檔案，無外部相依 |
| `manifest.json` | 要載入哪幾份 CSV，以及資料產生時間 |
| `data/*.csv` | 最近 5 個交易日的個股分析 + 最新月份的基本面 |

資料來源是公開資訊觀測站、證交所與櫃買中心。`data/` 裡的 CSV 只保留儀表板
實際會讀到的欄位（182 欄裁到 48 欄），不是完整的分析輸出。

分數不代表未來報酬機率，也不構成投資建議。

# PRO V2 交易日記 - 部署包

最終穩定版 · 永不清空 · 支援美股+港股HSI

## 功能
- 日曆熱力圖 月份選擇 <2026年10月>
- 近期交易 全部/已平倉/持倉 篩選，HSI置頂
- +新增交易 / 編輯 / 刪除 完整可用
- CSV匯入 支援美股 TSLA/NVDA/QQQ (100x) + 港股 HSI (50x) 含佣金拆解
- MAE/MFE 自動紅綠條 · 成本瀑布 · 截圖上傳 · 策略CRUD · R:R · AI評分 · 合規檢查
- 數據三鍵同步 trades / trades_v2 / trades_common 永不消失
- 範例12筆：11筆美股 + 1筆 HSI261009C24150000 96入場 持倉

## 一鍵部署到 GitHub Pages

1. 去 https://github.com/new 新建 repo，名稱 `trading-diary-pro-v2`，Public
2. 將此zip解壓，上傳所有文件到 repo 根目錄 (index.html 必須在根目錄)
3. GitHub repo → Settings → Pages → Branch 選 main / root → Save
4. 1分鐘後訪問 https://你的用戶名.github.io/trading-diary-pro-v2/

## 本地打開
直接雙擊 index.html 即可，數據存在瀏覽器 localStorage

## 備份
進入 App → 匯入頁 → 匯出備份JSON，下載備份

## 版本
- Build: 38a6274425b5 永不清空修復版
- 數據: 12筆含HSI
- 最後更新: 2026-10-05

## 原始CSV範例
- sample_HSI_20261005.csv 為港股HSI範例 (96 買入1張 費用23.54)
- parsed_trades_enhanced.json 為11筆美股範例

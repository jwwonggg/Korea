# koreatrip 交接

釜山＋首爾七日（2027/1/5 二 – 1/11 一）手機網頁 App，從 ~/Projects/Netherlands（jwwonggg/Netherlands）改出來，單檔 index.html＋sw.js＋manifest。

## 人和班機
- Jw、Enoch、Stella：CI188 1/5 07:40 TPE→10:50 PUS；CI163 1/11 20:15 ICN→22:15 TPE；TWD 12,743。
- Catherine：只跟首爾段，CI160 1/8 07:50 TPE→11:20 ICN；回程同 CI163。
- Quinn：班機未知（航班頁待填，預設當成跟釜山段）。

## 改資料
- `var DAYS`：每天 `{d,w,c:'bs'|'se',k,title,note,items:[{t,tr,must,book,name,p,alt,q}]}`；tr 對 TR（plane/ktx/arex/metro/bus/taxi/cable/train/walk）。
- TODO / EAT / OPTIONS 同檔；航班、住宿寫死在 HTML。
- localStorage 前綴 `krbs-`；預設匯率 1 TWD = 38 KRW。
- **改 index.html 後 sw.js 的 `krbs-vN` +1**，手機才會抓新版。
- 本機預覽：preview 名稱 `koreatrip`（~/.claude/launch.json，port 8765）。

## 待確認
冬季活動 2026–27 日期（海雲台光之祭、光復路燈樹、首爾燈節、首爾廣場溜冰）都還沒公布；藍線公園 12/1 搶 1/6；KTX 開車前一個月開放；釜山、首爾住宿未訂。
研究原稿在 session scratchpad（會消失）：korea_research.md、korea_research_jan.md。

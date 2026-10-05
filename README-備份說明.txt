SoulWhispers V25 完整網站備份
================================

這一包對應的主頁：
https://phoebe-liou.github.io/soul-system/soulwhispers-starry-v25-soul-card-journal.html

包含：
1. soulwhispers-starry-v25-soul-card-journal.html
   - 01 此刻的迷惘
   - 03 個人星盤
   - 05 靈魂指引
   - 靈魂牌卡手札入口
   - 芳香支持與 Facebook CTA
   - localStorage 串聯邏輯

2. soulwhispers-cards-v25-journey.html
   - 02 牌卡指引
   - 78 張塔羅 + 36 張雷諾曼
   - 牌圖放在 cards-tarot／cards-lenormand 兩個資料夾（2026-10-05 修正版起不再內嵌於 HTML）
   - 抽牌／翻牌／牌位／保存旅程資料
   - 返回 V25 主頁

3. energy-camera-v25-journey.html
   - 04 Energy Camera
   - 相機影像色彩／亮度／時間變化分析
   - 象徵色彩詞彙
   - 保存 sw_energy / sw_energy_words / sw_energy_data
   - 返回 V25 主頁

4. soulwhispers-touch-icon-v13.png
   - SoulWhispers 主畫面捷徑圖示

備份日期：2026-10-05
說明：網址中的 ?continue=1#energy-section 不是另一個網站檔案；
它是同一個 V25 主頁，continue=1 用於保留旅程資料，#energy-section 用於直接定位到 Energy 區段。

2026-10-05 修正版
- 牌卡頁由 23MB 改為約 80KB，牌圖拆成獨立檔案，只下載抽到的牌。
- 「清除資料・重新啟航」會一併清除星盤摘要。
- 從牌卡／能量相機返回時，顯示星盤已計算完成。
- 星盤度數改為無條件捨去（不再出現 30°00′）。
- 時區查詢加入 Open-Meteo 與台灣時區備案。
- 沒有出生時間時提醒月亮星座僅供參考，且不納入白話摘要。
- 能量相機：相機權限防呆、離開／進入畫面各 3 秒倒數。
- 芳療統一使用「真正薰衣草」；雷諾曼棺材牌關鍵字移除「疾病」。
- 補齊 PWA 檔案：soulwhispers.webmanifest 與 3 張圖示；start_url 由舊的 v8 頁面改為 V25 主頁，主頁引用改為 ?v=4。

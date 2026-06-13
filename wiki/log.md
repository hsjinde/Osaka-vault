---
title: 操作日誌
updated: 2026-06-09
---

# Wiki 操作日誌

> 依 core_rules 規範，本檔**只附加**新紀錄，不修改既有條目。

## 2026-06-09
- 健康檢查 + 修復：
  - 補齊 log.md、交通/住宿目錄、4 個 concepts 攻略頁、queries 歸檔目錄
  - 消化 Reference/晉德的大阪行/ 59 個未對應剪藏為 wiki 實體頁
  - 修補 3 個區域頁 frontmatter（天王寺/心齋橋/難波）
  - 重寫 `餐廳總覽`：57 間餐廳改用 `[[wiki/...]]` 內部連結
  - 修補 wikilink 跳脫字元（`\\` → `]`）
  - 修正梅田 `[[迷宮]]` 誤用 → 純文字
  - 移除重複的 `炭火烤肉-道頓堀みつる.md`（保留 `-道頓堀總店` 版）
- 最終健檢：0 斷連、0 孤立、0 frontmatter 缺失

## 2026-06-09 lint
- 修正 5 個斷連（來源區塊 Reference 檔名不一致）
  - `美食指南`：`Reference/晉德的大阪行` → `Reference/晉德的大阪行/README`
  - `DOTONBORI-KUROFUNE`：補齊 `Higashishinsaibashi` 後綴
  - `Hon-Sekiguchi`：移除副標題
  - `Yakinikuen-Ningu`：移除括號備註
  - `板前燒肉一牛`：補齊 `雌牛專門店` 前綴
- 移除 `index.md` 景點表 5 筆重複列（保留含描述版）
- 健檢結果：0 斷連、0 孤立、0 frontmatter 缺失

## 2026-06-08
- 首次建立 wiki 索引與首批實體頁（景點 6、餐廳 21、區域 4、購物指南 1）
- 從 Reference/ 與 Clippings/ 提取資訊

## 2026-06-09 17:07
- 生成大阪攻略 bento-grid HTML: `wiki/queries/2026-06-09-osaka-bento-guide.html`
- 內容涵蓋:3 日行程、必吃美食 TOP 6、交通票券、機場進市區、預算、4 大商圈
- 觸發關鍵字:使用者於 Discord #🏯-osaka大阪行程 請求「生成一張大阪攻略圖片」

## 2026-06-09 17:50
- 健康檢查：91 個 wiki 檔案，0 孤立、0 frontmatter 缺失（README 例外）
- 修補 `wiki/index.md` 景點區塊重複列（移除 5 個舊評分行，保留 6 個有摘要的）
- 索引 `updated` 同步至 17:50
- 觸發關鍵字:使用者於 Discord 請求「處理到底 不要停下來」

## 2026-06-10
- 建立「2026 大阪 5 日 — 已確認機加酒行程」:`wiki/queries/2026-09-30-osaka-confirmed-itinerary.md`
- 內容涵蓋:ezfly 訂單基本資訊(編號 WPKG000004961)、日期 2026/09/30–10/04、住宿大阪心齋橋格蘭多酒店 ×4 晚、雙地鐵站位置、與 wiki 既有實體/攻略的對應連結、待辦清單
- 觸發關鍵字:使用者於 Discord #🏯-osaka大阪行程 請求「創建一個 md 檔紀錄確定的行程規劃」
- 決策:歸檔至 `wiki/queries/` 而非 `wiki/concepts/行程規劃.md`,避免污染通用攻略頁(該頁是範本概念,非個人訂單)

## 2026-06-10 (第二次)
- digest 消化 Osaka Trip 已確認行程,提取資訊更新 wiki:
- 建立 `wiki/entities/住宿/大阪心齋橋格蘭多酒店.md`
- 更新:住宿總覽(加入飯店表格)、心齋橋(交通)、行程規劃(5日確認版)、預算規劃(已確認支出)、打包清單(9月底細化)、index(已確認區塊)


## 2026-06-10 11:10（lint 全修）
- 健康檢查 → 發現 7 類問題，全部修復：
- 🔴 重複實體頁（刪除 3 檔）：
  - 刪除 `Gyutan-Charcoal-grilled-YOSHIJI-Unagidani-branch.md`（保留 `Gyutan-YOSHIJI-Unagidani.md`）
  - 刪除 `Yakinikuen-Ningu-(Yakinikuen忍鬨).md`（保留 `Yakinikuen忍鬨.md`）
  - 刪除 `Yakiniku-Rikimaru-Nanba-Dotonbori.md`（保留 `燒肉力丸-難波道頓堀店.md`）
- 🔴 更新 `餐廳總覽.md` 3 個因刪除而斷裂的連結
- 🟡 `index.md` 景點區塊：補入 5 個孤立景點（海遊館/Harukas300/天王寺動物園/杯麵博物館/木津市場）
- 🟡 `index.md` 餐廳區塊：移除截斷的個別列表，統一指向 `餐廳總覽`
- 🟡 `購物指南.md`：統一 4 個 wikilink 為完整路徑格式
- 🟡 4 個 concepts 頁補齊 frontmatter（tags + source_count）：行程規劃/美食指南/預算規劃/打包清單
- 🟡 `Hanakujira` / `Hanakujira-honten` 加入互相參照說明（本店 vs 分店）
- 🟢 `wiki/queries/2026-06-09-osaka-bento-guide.html` 移至 `Clippings/`

## 2026-06-12
- 消化 `Reference/晉德的大阪行/`：
  - 新增概念頁：`wiki/concepts/晉德的大阪行推薦.md`
  - 新增實體頁：`喜三郎農場`、`KANEGURA`、`珈琲専門店-リヴォリ`
  - 更新 `wiki/index.md` 增加概念頁索引
  - 更新 `wiki/entities/餐廳/餐廳總覽.md` 加入 3 間新餐廳

## 2026-06-14
- 整理 `Clippings/` → `原始資料/`（依新增 core_rules 分類標準）：
  - `原始資料/餐廳/2026日本超商必買清單.md`（超商美食 YouTube 影片）
  - `原始資料/景點/大阪京都VLOG_itsPeachi.md`（大阪京都 5 日 VLOG）
  - `原始資料/景點/日本環球影城快速通關券USJ Express Pass.md`（Klook USJ 票券）
  - `原始資料/景點/Post by @casestw.3 on Threads.md`（Threads 大阪資訊）
  - `原始資料/2026-06-09-osaka-bento-guide.html`（綜合攻略 HTML，含行程/餐廳/交通/預算）
- 同步更新 `core_rules.md`：新增「Clippings 整理規則」章節（分類標準 + 整理流程）

## 2026-06-14 01:45
- 整理 `Reference/晉德的大阪行/`（共 91 個檔案）→ `原始資料/`（依 core_rules 分類標準）：
  - `原始資料/餐廳/`（77 個）：餐廳、燒肉、壽司、拉麵、涮涮鍋、壽喜燒、御好燒、關東煮、咖啡廳、甜點等
  - `原始資料/景點/`（17 個）：展望台、主題樂園、水族館、博物館、動物園、市場、購物商場、商業園等
  - `原始資料/晉德的大阪行-總覽.md`（1 個）：原 README.md 總覽索引，移至根目錄
- 刪除清空的 `Reference/晉德的大阪行/` 子目錄與 `Reference/` 空目錄

## 2026-06-14 01:50
- 整理 USJ 相關原始資料 → 建立 wiki 實體頁：
  - 新增 `wiki/entities/景點/日本環球影城.md`（整合 2 份原始資料）
    - 來源：`原始資料/景點/日本環球影城.md`（基本資訊）
    - 來源：`原始資料/景點/日本環球影城快速通關券USJ Express Pass.md`（Klook 快速通關券攻略）
  - 內容涵蓋：園區地圖、主要設施、Express Pass 6 種方案比較、超級任天堂世界入場須知、購票注意事項
  - 更新 `wiki/index.md` 景點區塊新增 USJ 條目（source_count: 2）

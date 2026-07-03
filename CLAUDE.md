# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 唯一規則來源

本 Repo 的權威規則為 **[core_rules.md](./core_rules.md)**，開工前務必先完整閱讀。

- 本檔僅作「快速定位」，**不重複維護** core_rules.md 的細節，避免內容不同步。
- 任何規則衝突或疑問，一律以 `core_rules.md` 為準。
- [AGENTS.md](./AGENTS.md) 亦指向同一來源，維持一致。

## 這是什麼

**大阪旅遊知識庫**（Obsidian Vault，非程式碼專案）。核心流程：AI 從原始剪藏「消化」提煉資訊進 `wiki/` 知識層，原始資料保持唯讀。無 build／lint／test 指令；工作以「觸發關鍵字」驅動（見下）。

## 知識分層（大圖）

理解本 Vault 需掌握四層資料的**流向與權責**（跨多檔才看得出來，故列此）：

1. **`Clippings/`** — Obsidian 剪藏暫存區。消化時依主題**移動**（非複製）至 `原始資料/` 對應子目錄後刪除原檔。
2. **`原始資料/`** — 匯入的網頁剪藏／文章，**唯讀，絕不修改**。子目錄：`景點/ 餐廳/ 交通/ 別人行程/ CHAT/`。購物商場依慣例歸 `景點/`。
3. **`wiki/`** — AI 維護的知識層，是主要讀寫對象：
   - `index.md`（查詢先讀此定位）、`log.md`（**只附加**操作日誌）
   - `entities/`（景點/餐廳/交通/住宿/區域/購物 實體頁）
   - `concepts/`（攻略頁，含 `source_type: reference` 的他人參考）、`queries/`（歸檔問答）
4. **`Osaka Trip/`** — 已付款、已確認行程（機加酒、訂單）。查詢與行程起草的事實基礎，優先級最高。

> ⚠️ 關鍵區分：`Osaka Trip/`＝我的已確認行程；`wiki/concepts/` 中標 `reference` 者（如晉德的大阪行）＝**他人參考**，不可當成「我的行程」。

## 工作觸發（等同「指令」）

對 AI 說出關鍵字即觸發對應動作（完整定義見 core_rules.md「觸發關鍵字」與「行程起草規則」）：

| 關鍵字 | 動作 |
|---|---|
| 消化 / 提取 / 整理這篇 | 讀原始資料 → 建立/更新 wiki 實體頁 |
| 規劃行程 / 安排路線 | 讀 wiki 實體 → 生成行程建議 |
| 起草每日行程 / 排 D1~D5 | 依 `Osaka Trip/` + wiki → 生成 D1–D5 存入 `Osaka Trip/itinerary-draft.md` |
| 查詢 / 找 / 推薦 | 從 wiki 搜尋回覆（**條列，不用表格**） |
| 健康檢查 / lint | 檢查 wiki 結構（孤立頁、斷連、過期） |
| 存查詢 / 歸檔 | 存進 `wiki/queries/` |

## 硬性規範（最易踩雷，細節見 core_rules.md）

- **唯讀保護**：絕不修改 `原始資料/` 下任何檔案。
- **語言**：一律繁體中文，精簡條列。
- **Wikilink**：內部連結用 `[[短路徑]]`（**不加資料夾前綴**，如 `[[心齋橋]]`）；外部用標準 `[Link](URL)`。
- **實體頁**：需 frontmatter（title/tags/updated/source_count，可選 source_type: entity|plan|reference），最後以 `## 來源` 列原始資料 wikilink。
- **log.md 只附加**，不改既有條目；每次消化／變更後補一筆並更新 `updated`。
- **防呆**：需求不明確時先問 1 個關鍵問題，不自行大量假設。
- **消化快取**：消化 `Osaka Trip/` 前先比對 log.md，符合條件才重跑（見 core_rules.md「消化快取機制」）。

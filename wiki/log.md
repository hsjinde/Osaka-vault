---
title: 操作日誌
updated: 2026-07-14
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

## 2026-06-15

- 消化 `Clippings/2026日本超商必買清單.md`：
  - 移動至 `原始資料/餐廳/2026日本超商必買清單.md`
  - 新增 `wiki/entities/購物/日本超商指南.md`
    - 內容涵蓋：LAWSON（炸雞君/生乳卷/可麗露/Q彈系列）、FamilyMart（Fami chiki/牛奶的束縛/舒芙蕾布丁）、7-11（炭火燒雞胗/nana chiki/奶油砂糖樹）、隱藏吃法（西西里咖啡特調）
  - 更新 `wiki/index.md` 購物區塊新增日本超商指南索引
- 觸發關鍵字：使用者要求「消化 @Clippings\2026日本超商必買清單.md」
- 消化 `Clippings/大阪梅田購物攻略與優惠券.md` → 移至 `原始資料/別人行程/`
- 新增 6 個 wiki 購物實體頁：
  - `Grand-Front-Osaka`：南北兩館、MUJI 旗艦店、始祖鳥、北面、丸善書店
  - `友都八喜`：電子產品與玩具、閉店晚
  - `LUCUA`：LUCUA + LUCUA 1100、Cosme 美妝集合、日系女裝、Montbell
  - `阪急百貨`：1F 國際大牌、2F 日系美妝、B1 甜點名店（KANAE/然花抄院/Frantz）
  - `大丸百貨`：6F 任天堂、13F 寶可夢中心、B1 文明堂蜂蜜蛋糕
  - `阪神百貨`：2F 西太后、B1 美食街
- 更新 `wiki/entities/區域/梅田.md`：source_count 1→2，補齊 6 個商場 wikilink 與樓層細節
- 更新 `wiki/concepts/購物指南.md`：source_count 1→2，新增「優惠券合集」章節（7 張優惠券：Alpen/唐吉訶德/大丸松坂屋/EDION/BicCamera/ANA 羽田/ANA 成田）
- 更新 `wiki/index.md`：購物區塊新增 6 個實體索引
- 移動剪藏附件：`Clippings/attachments/threads-zsf4315/` → `原始資料/attachments/threads-zsf4315/`（共 11 張圖片），Markdown 中 `../attachments/threads-zsf4315/` 相對路徑在新位置仍有效
- 觸發關鍵字：使用者要求「消化 @Clippings\大阪梅田購物攻略與優惠券.md」

## 2026-06-14 01:54（lint 全修）
- 健康檢查觸發 → 發現 4 類問題，全部修復：
- 🔴 孤立 wikilink 修復（5 處）：
  - `日本環球影城.md`：`[[Klook 客路旅行]]` → 純文字（無此頁）
  - `日本環球影城.md`：`[[大阪地鐵]]` → `[[wiki/entities/交通/大阪地鐵|大阪地鐵]]`
  - `行程規劃.md`（×2）：`[[大阪心齋橋格蘭多酒店]]` → 完整路徑
  - `住宿總覽.md`（×2）：`[[大阪心齋橋格蘭多酒店]]` → 完整路徑
  - `大阪地鐵.md`：`[[周遊券]]` → `[[wiki/entities/交通/周遊券|周遊券]]`
  - `晉德的大阪行推薦.md`：通天閣/海遊館/日本環球影城補加 wikilink
- 🟡 source_count 修復（5 頁）：
  - `行程規劃.md`：0 → 4
  - `預算規劃.md`：0 → 1
  - `大阪地鐵.md`：0 → 4
  - `關西機場.md`：0 → 1
  - `打包清單.md`：來源欄補 wikilink 參照
- 🟡 queries/ 格式修正：
  - `2026-09-30-osaka-confirmed-itinerary.md`：補 `tags: [query, 行程, 大阪]`
- 🟢 景點/購物頁補全結構（11 頁）：
  - 景點：通天閣、海遊館、天王寺動物園、杯麵博物館、木津市場（各加入交通/相關景點/特色）
  - 購物：BIOTOP-OSAKA、Orange-Street、Paper-Message-Osaka、YAMASTORE、心齋橋PARCO（各加入特色/相關商店/區域連結）

## 2026-07-04
- 消化 `Clippings/`（5 個檔案）→ 移至 `原始資料/`（依 core_rules 分類標準）：
  - `原始資料/景點/大阪堂島濱塔免費夜景.md`、`原始資料/景點/大阪堂島濱塔夜景-IG原文.md`（同一 IG Reel 夜景點）
  - `原始資料/景點/門真三井Outlet與Lalaport.md`（購物商場 YouTube，依慣例歸景點）
  - `原始資料/交通/大阪關西機場南海電鐵Rapit機場快線車票.md`
  - `原始資料/交通/關西近鐵電車周遊券.md`
- 新增 4 個 wiki 實體頁：
  - `wiki/entities/景點/堂島濱塔.md`：淀屋橋免門票夜景拍照點
  - `wiki/entities/交通/南海電鐵Rapit.md`：關西機場↔難波機場特急（α/β、票價、省錢替代、折價券）
  - `wiki/entities/交通/近鐵周遊券.md`：近鐵數位周遊券 4 票種比較、奈良/京都/伊勢/名古屋範圍、特急券須另購
  - `wiki/entities/購物/門真三井Outlet.md`：關西最大室內型 Outlet+LaLaport（交通/樓層/退稅/黑門市場美食街）
- 更新 `wiki/index.md`：景點區塊 +1、交通區塊 +2、購物區塊 +1，`updated` → 2026-07-04
- 觸發關鍵字：使用者要求「消化 @Clippings」
- ⚠️ 待修：index.md 交通區塊既有 `[[周遊券]]`、`[[關西機場]]` 為斷連（對應檔案不存在），本次未處理

## 2026-07-05
- 消化 `原始資料/CHAT/大阪環球影城(USJ)「快速通關4」票種整理.md`：
  - 目標入園日 2026/10/1（秋季檔期，含咒術迴戰 4D 版僅至 8/18 提醒）
  - 更新 `wiki/entities/景點/日本環球影城.md`：
    - 擴充「Express Pass 方案總覽」加入 7 種方案參考價（Premium/8/7/5/4/VIP）
    - 新增「快速通關4 常見組合」表格（11 種組合 + Twilight 變體）
    - 新增季節性浮動票 warning callout（10/1 需上架後再確認）
    - 新增「待辦」章節（確認當日開賣組合）
    - 來源 +1（CHAT 查詢記錄），source_count 2→3
  - 更新 `wiki/index.md` 景點區塊日本環球影城 source_count 2→3
- 觸發關鍵字：使用者要求「消化 @原始資料\CHAT\大阪環球影城(USJ)「快速通關4」票種整理.md」

## 2026-07-04（lint 全修）
- 健康檢查（106 頁）→ 發現多類斷連，全部修復：
- 🔴 **78 個 `[[Reference/晉德的大阪行/…]]` 來源連結全斷**（`Reference/` 已於 2026-06-14 搬至 `原始資料/` 並刪除）：
  - 逐一比對重接至 `原始資料/{餐廳|景點|別人行程}/` 對應剪藏（77 個 wikilink）
  - `#にくといえばまつだ`：原始檔名含 `#` 前綴，Obsidian 無法以 wikilink 連結，改純文字路徑
  - README 3 處 → `原始資料/別人行程/晉德-GoogleMaps-清單`（木津市場改指自身剪藏）
  - 名稱對應範例：`宮田麵児`→`景點/宮田麺児`(麵→麺)、`弁才天`→`Kakuozan Fruit Daifuku Benzaiten`、`Kobatopankojo`→`Cobatopan-kojo`
- 🔴 `index.md`：移除交通死連結 `[[周遊券]]`、`[[關西機場]]`（承接上次待修）；修正原始資料位置表過期路徑（`晉德的大阪行-總覽`→`別人行程/晉德-GoogleMaps-清單`）
- 🔴 **遺失頁重建**：`wiki/entities/購物/日本超商指南.md`（內容佚失，依 `原始資料/餐廳/2026日本超商必買清單.md` 重建，三大超商必買＋2026 熱門＋隱藏吃法）
- 🔴 路徑錯誤連結：`BIOTOP-OSAKA` `[[wiki/entities/概念/購物指南]]`→`wiki/concepts/購物指南`；`行程規劃` `[[wiki/plans/USJ-2026-1001-行程]]`→`[[wiki/entities/景點/日本環球影城]]`
- 🔴 `queries/2026-09-30…`：酒店暫存連結→`[[大阪心齋橋格蘭多酒店]]`；移除已佚失的 `[[預算規劃]]`/`[[打包清單]]` 連結；`關西機場`/`周遊券`→純文字/`[[近鐵周遊券]]`
- 🔴 `大阪地鐵` `[[周遊券]]`→純文字「大阪周遊券（Osaka Amazing Pass）」說明
- 🟡 7 個幽靈品牌連結轉純文字（`Grand-Front-Osaka`：Arc'teryx/The North Face；`LUCUA`：Lululemon/Beams/Cosme/Ralph Lauren/Montbell）
- 🟡 孤立頁 `Pokemon-Center-Osaka-DX` → 加入 `index.md` 購物區塊
- ✅ 最終健檢：**0 斷連**（106 頁全掃描）；孤立僅 `queries/` 歸檔頁（終端頁，可接受）
- 觸發關鍵字：使用者「lint」


## 2026-07-07
- 修復 3 個格式不符規範的餐廳實體頁（缺 `## 基本資訊`，導致 Osaka-web 美食庫頁類型/價位顯示為「未分類」/「價位未記」）：
  - `KANEGURA.md`、`喜三郎農場.md`、`珈琲専門店-リヴォリ.md`
  - 改用「## 主要功能／使用場景」為標準「## 基本資訊」（類型/評分/價位/備註），評分欄位移除括號評論數以符合其他 63 頁格式
  - 移除非標準的「## 相關工具」章節（`相關餐廳清單：晉德的大阪行推薦、餐廳總覽`）：`餐廳總覽` 為分類索引頁，不應以純文字形式混入實體內文並隨建置流程流入 Osaka-web 的公開資料（`entities.json` body），造成網站端可被搜尋到不存在的頁面名稱
  - 不刪除 `餐廳總覽.md`，該索引頁仍保留供 Obsidian 內查閱
- 觸發關鍵字：使用者要求「美食庫 移除 餐廳總覽」重構

## 2026-07-07（交通補充）
- 使用 Tavily 查詢並新增 2 個交通實體頁：`JR-HARUKA關空特急.md`、`JR關空快速.md`（機場↔市區交通，含路線圖／停靠站／票價／注意事項）
- 下載路線圖至 `assets/交通/`：`JR-HARUKA-路線圖.jpg`、`JR關空快速-路線圖.jpg`（來源：來一球叭噗 gototravel.tw）
- 更新 `南海電鐵Rapit.md` 相關區塊、`index.md` 交通實體頁索引，補上兩個新頁連結
- 觸發關鍵字：使用者要求「新增 JR HARUKA 關空快速相關資訊並附上圖片」

## 2026-07-07（交通圖片補充）
- 為既有 3 個交通實體頁補上圖片：
  - `大阪地鐵.md`：官方全線路線圖（Osaka Metro 官網）
  - `近鐵周遊券.md`：5日券plus 可搭乘範圍地圖（近鐵電車官網）
  - `南海電鐵Rapit.md`：列車外觀照＋官方 Rapi:t β 路線圖（南海電鐵官網）
- 圖片下載至 `assets/交通/`：`大阪地鐵-路線圖.gif`、`近鐵周遊券-範圍地圖.png`、`南海Rapit-路線圖.png`、`南海Rapit-列車外觀.jpg`
- 更新 3 頁的 `updated`/`source_count` 及來源區塊
- 觸發關鍵字：使用者要求「幫我把圖片都查出來附上」

## 2026-07-08
- 消化 `原始資料/別人行程/晉德-GoogleMaps-清單.md`（該清單已於 2026-07-08 由來源更新，地點數由 82 → 127，經比對找出 36 個尚無 wiki 實體頁的地點）：
  - 新增 27 個餐廳實體頁：Chuka-Soba-Kirimen-Sohonten、Datedachi、Fukuoka-Udon、Grill-Lamp-tei、Higekatsu、Horumon-Yakiniku-Mansen、Hozenji-Yamakazu、LOUTRE水獭咖啡馆（京都店）、M-Casse、Mamemono-to-Taiyaki-Arashiyama-Honten、Nonkiya、Okonomiyaki-Ponpoco-tei-MINAMI-Shimanochi、Onimaru、Panel-Cafe-Kyoto、Paris-h、SHAKE-SHACK-京都四條烏丸店、Sakana-no-ISHISAKA、Toyo、WEEKENDERS-COFFEE-ROASTERY、YAKINIKU-PONGA-SHINSAIBASHI、Niku-no-Asatsu Umeda Ohatsu Tenjin（涮涮鍋/壽司/壽喜燒）、ÉCHIRÉ-Marché-au-Beurre、利久牛舌×2分店、南一園燒肉、壽喜燒．火鍋 Nabeya、大阪燒 美津の、月盗、炭火焼 鳥清 東心斎橋店、燒肉之牛太 本陣LINKS UMEDA店、稻荷烏龍麵始祖 松葉屋、章魚家道頓堀KUKURU 道頓堀總店、華家、鰻魚飯 う桶や う
    - 其中 `Niku-no-Asatsu Umeda Ohatsu Tenjin` 已有既存原始剪藏（`原始資料/餐廳/Shabu-shabu & Sukiyaki & Sushi Restaurant Niku-no-Asatsu Umeda Ohatsu Tenjin.md`），其餘來源直接指向 GoogleMaps 清單（無獨立剪藏）
    - `Hozenji-Yamakazu`、`Okonomiyaki-Ponpoco-tei-MINAMI-Shimanochi`、`壽喜燒．火鍋 Nabeya`、`大阪燒 美津の`、`炭火焼 鳥清 東心斎橋店`、`章魚家道頓堀KUKURU`、`華家`、`鰻魚飯 う桶や う`、`LOUTRE水獭咖啡馆` 等 9 筆為既有清單早已收錄但先前消化時遺漏的缺口，一併補齊
  - 新增 3 個景點實體頁：任天堂博物館（京都宇治）、楠珺社、露天神社
  - 新增 6 個購物實體頁：AENA-Namba-Walk-Sanbangai-Kita-dori、アエナ なんばウォーク3番街南通り店（南北通り姊妹店互相參照）、DEAL-DESIGN-大阪店、Daikoku-Locker、SNKRDUNK-OSAKA-MINAMIHORIE、購物中心-HEP-FIVE
  - 更新 `wiki/entities/餐廳/餐廳總覽.md`：新增「立吞/居酒屋」分類，各分類補入新餐廳，source_count 82→127，實際餐廳數 57→94
  - 更新 `wiki/concepts/晉德的大阪行推薦.md`：地點數 82→127，補充京都延伸地點與新分類說明
  - 更新 `wiki/index.md`：餐廳總覽/晉德的大阪行推薦 source_count 同步、新增 3 個景點與 4 個購物實體頁索引列
  - `Osaka Dojimahama Tower`（清單新條目）已由既有 `wiki/entities/景點/堂島濱塔.md` 涵蓋，未重複建立
- 觸發關鍵字：使用者要求「整理並消化 @原始資料/別人行程/晉德-GoogleMaps-清單.md」

## 2026-07-13
- 整理 `Clippings/Post by @roolez553 on Threads.md`：內容為他人整理的「大阪一日遊路線9種排法」（9種一日遊組合＋留言區eSIM/行動電源等業配連結），依分類標準屬「別人的行程/他人攻略」
  - 移動並重新命名至 `原始資料/別人行程/大阪一日遊路線9種排法（roolez553）.md`
  - `Clippings/` 已清空，移除該暫存目錄
- 觸發關鍵字：使用者要求「整理 @Post by @roolez553 on Threads 並重新命名檔案」

## 2026-07-13（健康檢查 lint + 修復）
- 全面掃描 wiki/ 154 檔：frontmatter 完整性、孤立頁面、失效連結、路徑前綴連結、索引涵蓋率
- 修復失效連結（`Osaka Trip/2026-09-30-osaka-confirmed-itinerary.md`）：
  - 飯店連結 `[[大阪心齋橋格蘭多酒店_ShinsaibashiGrandHotelOsaka]]` → `[[大阪心齋橋格蘭多酒店]]`，並勾銷「補建立住宿頁」待辦（頁面已存在）
  - `[[原始資料/景點/通天閣]]` 改指向 wiki 實體頁；`[[預算規劃]]`、`[[打包清單]]` 標注「頁面待建」
- 新增 2 個交通實體頁（core_rules 預期結構）：`關西機場.md`（KIX 往市區三選項總覽）、`周遊券.md`（票券評估總覽），解決 `[[關西機場]]`、`[[周遊券]]` 失效連結
- 修復 `wiki/entities/景點/日本環球影城.md` 來源連結：原誤指向自身，改為 `[[原始資料/景點/日本環球影城]]`
- 更新 `餐廳總覽.md`：補入先前遺漏的 4 間（DOTONBORI KUROFUNE／Tachisushi Maguro／板前燒肉一牛 心齋橋本店／Onigiri Gorichan 南海難波店），餐廳數 94→98
- 更新 `wiki/index.md`：餐廳數同步 98、景點表全路徑連結補顯示別名、新增 關西機場/周遊券 索引列、大阪地鐵摘要與 source_count 修正
- 路徑前綴連結處理原則：掃描確認所有 `[[wiki/...]]` 前綴連結的目標均與 `原始資料/` 存在同名檔（25 組同名衝突），全路徑為必要消歧義故保留，僅補顯示別名（美食指南、行程規劃、queries 歸檔頁）
- 修復 `行程規劃.md` 表格內未跳脫的 `|` 別名連結（會破壞表格欄位）
- 格式統一：`購物指南.md`、`梅田.md` 的 updated 值去除引號；`wiki/queries/2026-09-30-osaka-confirmed-itinerary.md` 補 source_count
- 觸發關鍵字：使用者要求「lint」→「處理」

## 2026-07-13（lint 後續：規則增補與 Unicode 修正）
- `core_rules.md` 短路徑規則增補「同名衝突例外」：目標與 `原始資料/` 存在同名檔時，允許全路徑＋顯示別名消歧義；表格內 `|` 須跳脫為 `\|`（CLAUDE.md 經 `![[core_rules]]` 內嵌自動同步，未另行編輯）
- 修正 `wiki/entities/餐廳/CANELE-du-JAPON-Nagahoribashi-Store.md` 來源連結的 É 組合形式（NFC → NFD），使位元組與實際檔名一致，連結已驗證可解析
- 觸發關鍵字：使用者要求「你幫我處理」（承前次 lint 報告待決事項）

## 2026-07-14
- 整理 `Clippings/Post by @travelplanner_asia on Threads.md`：內容為「大阪常用交通票券整理比較」，依分類標準屬「票券、交通攻略」
  - 移動並重新命名至 `原始資料/交通/大阪關西交通票券整理比較（travelplanner_asia）.md`（內容未修改，維持原始資料唯讀）
  - 註記：該貼文的票券比較表全在 9 張輪播圖中，純文字僅有導言與留言問答，可提煉的實質內容有限
- 消化進 `wiki/entities/交通/周遊券.md`（source_count 0→1）：
  - 將原本合寫的「JR 關西地區／關西廣域鐵路周遊券」拆為兩條，分別列出範圍
  - 新增警語：作者於留言稱「JR 關西地區版 4 日券可到鳥取」，與官方公告範圍（鳥取屬**廣域版**）不一致，已標注存疑並要求以 JR 西日本官網為準，未將此說法當作事實寫入
  - 評估重點補「Pass 回本通則」：單一遠程來回多半直接買車票更省，Pass 需連續數日中長程移動才划算
- 更新 `wiki/index.md`：周遊券列來源數 0→1、摘要同步
- `Clippings/` 已清空（保留空目錄供 Obsidian Web Clipper 落地）
- 觸發關鍵字：使用者要求「整理並且消化 @Clippings 重新命名該檔」

## 2026-07-14（補完：圖片下載與圖卡內容消化）
- 下載該剪藏的 9 張輪播圖（Instagram CDN，合計 1.1 MB）至 `attachments/交通票券-travelplanner_asia/01.jpg`–`09.jpg`，解決上一輪「比較表在圖片中、無法消化」的缺口
- 完整消化圖卡內容，重寫 `wiki/entities/交通/周遊券.md`：
  - 新增「六大票券速覽」（ICOCA／Welcome ICOCA、Osaka Amazing Pass、Osaka Metro Pass、JR Kansai Area Pass、Kansai Railway Pass、機場票券）
  - 新增「功能比較總表」（7 票種 × JR／地鐵／私鐵／市巴士／HARUKA／景點門票）與「我該買哪一張」選擇指南
  - 內嵌第 8、9 張關鍵圖卡
- 標注 3 項來源疑點，未當作事實寫入：
  1. 圖卡自述資料日期為 2024-05，已逾兩年
  2. 作者留言稱「地區版可到鳥取」，與**同一份圖卡**畫的適用範圍（僅到和歌山／奈良，無鳥取）自相矛盾；鳥取應屬廣域版
  3. Kansai Railway Pass 能否搭地鐵，第 6 張與第 8 張說法不一
- `.gitignore` 新增 `.env`、`.env.*`（環境變數與憑證不進版控）
- 連結驗證：周遊券頁 10 個 wikilink 全數可解析，0 斷連
- 觸發關鍵字：使用者要求「下載到資料夾 並把 .env 寫進 gitignore」

## 2026-07-14（R2 圖床同步）
- 9 張圖上傳至 R2 `core-pulse-assets`／`osaka/guides/threads-travelplanner-asia/image_01–09.jpg`（透過 cloudflare-use skill）
- 過程中發現並修正**兩處自造的不一致**（均已對齊 vault 既有慣例）：
  - R2 key 初次誤用 `osaka/transit-passes-travelplanner-asia/`，與既有剪藏圖慣例 `osaka/guides/<slug>/`（threads-post、threads-zsf4315）不符 → 重傳至 guides/ 並刪除誤傳的 9 個物件
  - 本地圖片初次誤放根目錄新建的 `attachments/`，與既有慣例 `assets/<slug>/`（threads-post、交通）不符 → 移至 `assets/threads-travelplanner-asia/`，檔名對齊 R2 key（`image_NN.jpg`），並移除多餘的 `attachments/` 目錄
- `wiki/entities/交通/周遊券.md` 內嵌圖改為 `!![assets/threads-travelplanner-asia/image_08.jpg](https://img.19980803.xyz/osaka/entities/transit/osaka-amazing-pass-overview.jpg)`（用全路徑：`原始資料/attachments/threads-zsf4315/` 已有同名 `image_05.jpg`，短路徑將來會歧義）
- ⚠️ 待使用者確認：R2 `osaka/entities/` 底下 6 個 hash 檔名物件（2026-07-14 15:44 上傳）與 `osaka/entities/交通/` 6 檔大小完全相同，疑似同一批圖重複上傳；未擅自刪除
- 觸發關鍵字：使用者選擇「把 9 張圖上傳到 R2」

## 2026-07-15（票券攻略頁：從資料 → 決策）
- 新建 `wiki/concepts/交通票券攻略.md`（`source_type: plan`），是 [[周遊券]] 實體頁的**決策層**，刻意不重抄比較表
- 定位差異：`entities/交通/周遊券.md` 回答「這些票券是什麼」；`concepts/交通票券攻略.md` 回答「**這趟該買什麼**」
- 核心結論（交叉比對 [[行程規劃]] 5 日骨架 × 已確認機加酒）：**本行程不需要任何周遊券，ICOCA ＋ 南海來回票即可**
  - 住心齋橋 ＝ 南海系 → HARUKA 用不到 → JR Kansai Area Pass 價值先砍半
  - 逐日拆解後，**沒有任何一天會搭到 4–5 趟地鐵**（Day 3 心齋橋/道頓堀/難波幾乎全步行）→ Metro Pass 不回本（¥820 ÷ 單程 ¥190–240）
  - Kansai Railway Pass 2 日券起跳，但只有 Day 2 可能遠征 → 浪費
  - Osaka Amazing Pass 是唯一要算的：**只在 10/02 選「梅田＋海遊館」時評估**
- 標記一個**會直接翻轉結論的未確認事實**：海遊館很可能**不在** Amazing Pass 免費名單（一般認知：天保山摩天輪含、海遊館不含）→ 若不含則該 Pass 幾乎必不回本；已列入待確認清單，未當事實寫入
- 回程時間反推（10/04 15:35 起飛）：Rapi:t → 12:10 前離開飯店；空港急行 → 11:55 前。退房 11:00 → 上午僅約 1 小時
- 未列 Amazing Pass／JR Kansai／Kansai Railway 的票價：**原始圖卡未提供，不捏造**，頁面明確標示須查官網
- 連結：`wiki/index.md`「我的規劃」新增一列；`周遊券.md`「相關」回指攻略頁（雙向連通，無孤立頁）
- 未動 `Osaka Trip/` 待辦「評估是否購買周遊券」（已確認行程檔，待使用者確認後再勾選）
- 觸發關鍵字：使用者要求「@原始資料/交通/大阪關西交通票券整理比較（travelplanner_asia）.md 寫成一份攻略」

## 2026-07-16
- 整理小紅書「卡比卡比」中崎町 citywalk 攻略（訓練家於 Discord #🏯-osaka大阪行程 貼圖 + xhslink 短網址）：
  - 存原始剪藏至 `原始資料/別人行程/大阪中崎町citywalk路線圖文攻略（卡比卡比）.md`（xhslink 短網址取不到，以貼圖路線圖 + 貼文文字為據；路線圖副本存 `assets/中崎町/中崎町citywalk路線圖.png`）
  - 新建 `wiki/entities/區域/中崎町.md`：收錄環狀 citywalk 路線（中崎町站 4 號口→1 號口，14 個打卡點）、交通、與 `[[梅田]]`/`[[neel-nakazakicho]]` 交叉連結
  - 更新 `wiki/index.md` 區域區塊新增中崎町索引列（source_count: 1）
- 觸發關鍵字：使用者於 Discord 貼「加入大阪行程參考攻略」並附中崎町 citywalk 路線圖
- 2026-07-16（補完：路線圖上傳 R2 換絕對網址）
  - 上傳 `Osaka-vault/assets/中崎町/中崎町citywalk路線圖.png` → R2 `core-pulse-assets`／`osaka/guides/nakazakicho-citywalk/route-map.png`
  - 將兩處 `assets/中崎町/...` 本地相對路徑改為絕對網址 `https://img.19980803.xyz/osaka/guides/nakazakicho-citywalk/route-map.png`（原始剪藏 `（卡比卡比）.md` 的圖說與嵌入）；curl 驗證 HTTP 200 / image/png / 2.25MB
  - 觸發關鍵字：DeLin 於 Discord 要求「更新圖片網址」
- ⚠️ 限制：原帖為 5 張輪播，僅取得第 1 張路線圖；店家實拍與詳細評分未取得，路線頁僅能列名稱與已知類別（咖啡/和果子/二手衣/糕點）

## 2026-07-17
- 新增 `wiki/entities/景點/勝尾寺.md`（達摩寺攻略）：無原始剪藏，資料來自即時網路查證（勝尾寺官網 access 頁 + enjoy-osaka-kyoto-kobe 交通攻略），來源以外部連結列於頁尾
- 已查證要點：入山費 ¥500/¥400/¥100、開放時間（週六延至 18:00）、交通改經 2024 年啟用的北大阪急行「箕面萱野」站轉阪急巴士（¥800、約 20–25 分、每小時 2–3 班）
- 特別標注：勝尾寺與箕面瀑布之間無巴士、步行約 1 小時，不建議串聯硬走
- 更新 `wiki/index.md`：景點區塊新增勝尾寺索引列，frontmatter updated → 2026-07-17
- 觸發關鍵字：使用者要求「新增勝尾寺（達摩寺）攻略」

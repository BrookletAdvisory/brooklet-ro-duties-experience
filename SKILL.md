---
name: brooklet-ro-duties-experience
description: Draft the "Proposed Duties" and "Relevant Industry Experience" sections of an SFC licence application (Form 6 / RO experience description) for Brooklet Advisory cases. Trigger this skill whenever the user asks to write, draft, prepare or revise the RO duties / experience paragraphs, prepare the Type 1 / Type 4 / Type 9 RO duties and experiences section, write a Form 6 experience description, draft RO 经验段 / RO 经验描述 / 申牌经验段, or apply the Brooklet RO Form 6 SOP. Use this skill AFTER the candidate has been confirmed as suitable to act as RO — for upstream suitability assessment (能不能用、6 年经验、考试豁免、CV vs licence record 核对、比较 RO 候选人) use brooklet-ro-assessment instead.
---

# Brooklet — Form 6 RO Duties & Experience 撰寫 SOP

> **本 skill 是 SOP V3 的可執行版本，措辭與規則均原文保留。**
> 上游適用性判斷（hard requirements / 6 年經驗 / 考試豁免 / CV vs licence record）走 `brooklet-ro-assessment`；本 skill 假設候選人已被判定為適合擔任 RO，現在進入撰寫階段。

## Pre-flight

開工前先確認三件事，缺一不可：

1. **適用性已確認** — 若尚未跑 `brooklet-ro-assessment`，請先停下來提示用戶：「建議先用 brooklet-ro-assessment 判斷此人是否符合 RO 硬性條件，再進入撰寫。」
2. **申請 Type 已鎖定** — 新公司申請的 RA 類型（Type 1 / Type 4 / Type 9 等）+ 未來擬開展業務（hedge fund / PE / family office / discretionary AM 等），這兩個一旦確定，篩選標準從此刻起固定。
3. **起點材料就緒** — 至少需要：applicant 的 self-written CV / resume；applicant 的 SFC licence record（如 Public Register 截圖）；如有，舊版草稿 / Business Plan / 內部補充文件。

---

## 核心原則（永遠不變）

### 總體邏輯
未來方向決定選材和 framing，不決定事實本身；可以延展表述，不可以補造動作。

起點材料分三種，處理方式不同：

| 起點材料 | 難度 | 處理方式 |
|---|---|---|
| 只有 CV | 高 | 完全從 CV 提煉，需要更多確認和判斷 |
| CV + 舊申請文件 / Business Plan | 中 | 舊文件只提取數字和 facts；結構和語言全部重寫；Template 管格式 |
| CV + 口頭確認（錄音 / 對話） | 中 | 先把口頭信息整理成書面條目，再逐條確認；不能憑記憶直接動筆 |

> ⚠️ **舊文件的唯一用途：** 提取具體數字（AUM、人數、基金名、交易金額）和可核實的 facts。一旦確認屬實，放進材料篩選表。舊版的 general 陳述和描述語言一律不採用。

### 不變的六條原則

| 原則 | 意思 | 常見錯誤 |
|---|---|---|
| 事實第一 | 只寫有文件或本人確認的事實；數字沒確認就標 [TBC] | 從舊版借數字未確認，直接寫進正文 |
| 動詞決定一切 | 動詞必須反映此人的真實角色：主導用 led/designed，監督用 oversaw，協助用 participated in | 把「她知道」寫成「她做過」 |
| 合理推測（有邊界） | 動筆前必須先了解公司擬申請的業務方向（如 hedge fund、private equity、family office 等）。Experience 的寫法要主動向申牌主體未來擬開展的業務靠攏；未在 CV 中明寫、但根據職位性質高度可能涉及的工作，可先按合理推測起草，並以 [RO to confirm: ...] 或高亮方式請 RO 確認。 | 把「可推論」直接寫成「已發生」；或完全照抄 CV，沒有根據公司未來業務方向做 framing。 |
| 結構永遠跟 Template | 格式、段落順序、標題層級全部照 Template；不借舊版的結構 | 沿用舊版段落結構 |
| Duties 要虛，Experience 要實 | Duties = 宽泛的 MIC 分工；Experience = 有數字的具體動作 | 把 Experience 裡的細節提前放進 Duties |
| AI 敏感詞規避 | 涉及 AI 在投資決策中的角色，SFC 非常敏感，一律不提 | 寫「AI-assisted investment decision」 |

---

## 五步工作流

> 篩材料 (S1) → 問方向 (S2) → 起草 (S3) → AI 交叉驗證 (S3.5) → Ben Review + 問細節 (S4) → 終稿 (S5)
>
> **每一步驟都需要 human in the loop：每個數字，和每一版稿子。**

---

## STEP 1 | 材料篩選（動筆前，獨立完成）

**目標：搞清楚手上有什麼，建立工作底稿；不要急著寫。**

### A. 確認申請 Type 並判斷材料完整度等級

先確認新公司申請的 RA 類型（Type 1 / Type 4 / Type 9 等）和未來擬開展業務（hedge fund / PE / family office / discretionary AM 等），篩選標準從此刻起固定。

- 同時申請多個 Type 時，每個 Type 都要有對應的 RO 過往經歷支撐，除非明確指示，否則不能混用。
- **Type 4 / Type 9 Experience 是否分開寫？** 必須在 Step 1 向 Joyce/Ben 確認。**預設：分開**——`With regard to type 4 regulated activities, the following experience is relevant:` 和 `With regard to type 9 regulated activities, the following experience is relevant:` 各自獨立成段、各自列 bullets。只有在有特殊原因且 Joyce/Ben 明確指示時才合併為 `Type 4 & 9`。若未確認，一律按分開處理。

**材料完整度等級：**

- **A 級**：有 CV + 可用事實，即使信息未完全齊備，但已有足夠內容判斷 relevant experience 和 management experience，可進 Step 2。
- **B 級**：CV 缺失關鍵段落，或手上只有工商 / 註冊 / 零散資料；可先寫 Duties 段並發 Step 2 清單要求補材料，但不得進 Step 3 的 Experience 段。
- **C 級**：完全無 CV；停止 drafting，直接提示 Joyce 補 applicant CV 或其他基礎材料。

### B. 建立材料篩選表（每位 RO 一張）

對每一段工作經歷，判斷兩個維度：

**放進去的條件（滿足其一即可）：**
- 有直接執行受規管活動的動詞（advising, managing portfolio, fund structuring, investment screening…）
- 以 RO / MIC / 管理層身份執行的監督 / 合規工作

**需要確認或者可以深挖並進行加工的條件：**
- 合規 / 運營等相關工作，但是不明確
- 只是「知道怎麼做」，但沒有直接做過

**不能放的條件：**
- 與申請 Type 完全無關的動作

### C. 從舊文件 / Business Plan (if applicable) 提取 Facts

掃描舊版文件，只提取：具體數字（AUM、人數、基金名）、可核實的客戶名稱、代表性交易金額。

把這些 facts 標入材料篩選表的「具體數字」欄。凡是從舊文件借來的數字，在篩選表備註「待 RO 確認」，**不視為已確認事實**。

> ⚠️ **口頭信息的處理：** 如果 Ben 或 RO 通過錄音 / 口頭提供了新信息，先整理成書面條目逐條確認，再放進篩選表。記憶不清的部分一律標 [TBC]，不要憑印象動筆。

**Step 1 產出**：一張完整的材料篩選表（Markdown 表格即可），列：工作經歷段 | 動詞 / 動作 | 對應 Type | 具體數字（含 [待 RO 確認] 標記） | 處理方式（放/挖/棄）。

---

## STEP 2 | 第一次確認 Ben（書面，Bullet point）

**目標：一次性解決「沒有 Ben 就無法判斷」的問題。**

把以下四類問題整理成清單發給 Ben，**每條附上你的初步判斷**——不是空白問卷，是帶答案的確認：

### 必須確認的四類問題

1. **核心亮點段落**：「我計劃以 [公司名] 作為重點展開，其餘作為補充，請確認選材方向」
2. **數字空缺清單**：「以下數字在 CV 中未有記錄：AUM？管理人數？基金名稱？請確認或告知從哪裡獲取」
3. **是否有舊版文件 / Business Plan 可參考**：「是否有舊版草稿或 Business Plan？我會只借用其中的數字和 facts，不參考其結構」
4. **角色定位確認**：此 RO 是 Primary（一號）/ Joint（並列）/ Secondary（輔助）？決定 Duties 段動詞選擇。

> ⚠️ **重要：** 每次給 Ben 看的東西，都要帶著你自己的判斷，讓他只需說「對」或「不對」。把「請 Ben review 方向」和「請 Ben 填數字」兩件事分開：前者他來決定，後者問 RO。

### Step 2 可能發生多次（正常現象）

以下情況會觸發 Step 2 重複：
- Ben 中途給出新的角色定位或業務說明
- RO 本人提供了補充文件（Business Plan、詳細 CV）
- 發現 CV 某段經歷有更深的 Type 4/9 關聯，需要重新確認邊界

每次重複 Step 2 都要重新整理書面確認清單，並先判斷這次屬於清單 A、B 還是 C，**不要把不同類型問題混在同一條訊息裡**。

**Step 2 產出**：一條結構化的 WhatsApp / Email 確認訊息（給 Ben），格式遵循 Brooklet WhatsApp/Email 規範（自信不傲慢、bullet point、不用模糊詞）。

> **動作**：在此步驟，調用 `ask_user_question` 或直接停下來，把確認清單給 Joyce 過目，等她發送並收到 Ben 的回覆之後再進 Step 3。

---

## STEP 3 | 起草初稿（獨立完成）

**目標：輸出結構完整、選材有據、數字完整度高的初稿；TBC 越少越好。**

> 📂 **撰寫時讀取**：
> - `references/template-format.md` — Template 段落順序、標題格式、排版規則
> - `references/mic-wording-library.md` — Duties 段的 MIC 標準措辭庫
> - `references/verb-role-matrix.md` — 角色定位 × 動詞矩陣
> - `references/experience-wording-tiers.md` — Tier 1/2/3 經驗語句庫
> - `references/sfc-relevant-experience.md` — SFC 認可相關經驗範疇 + 官方 Reference

### A. Proposed Duties 段

- 參考 MIC 分工表，按 RO 實際負責的職能範疇寫，**5-6 條短句即可**。每條控制在 1-2 行，不超過 30 個英文單詞。Duties 要虛（broad functional responsibilities），不要寫出具體的投資策略、產品名稱或流程細節。
- 語氣寬泛：用 overseeing / leading / co-leading / participating in；**不需要有具體數字**
- 參考同公司其他 RO 的 Duties 寫法保持一致性
- **絕對不要把 Experience 裡的細節提前放進 Duties**

**具體寫法：Duties 句子 = 動詞 + 描述**

- 動詞部分 → 見 `references/verb-role-matrix.md`
- 描述部分 → 見 `references/mic-wording-library.md`（MIC Function Standard Wording Library，七大 MIC 範疇）：
  1. Overall Management Oversight (OMO) | 整體管理
  2. Key Business Line - Investment Management (KBL) | 核心業務線 — 投資管理
  3. Key Business Line - Sales & Marketing (KBL) | 核心業務線 — 銷售與營銷
  4. Risk Management (RM) | 風險管理
  5. Compliance & AML/CTF | 合規與反洗錢
  6. Operational Control & Review (OCR) | 營運控制與審查
  7. Finance & Accounting / Information Technology (F&A / IT) | 財務 / 資訊科技

### B. Overview 導言段

- 第一句：'X years of experience in [相關領域]'
- 第二句：點出此人的核心賣點（AUM 規模、多次成功申牌、跨境市場經驗等）
- **不要太長**

### C. 每段工作經歷

**格式要求**（嚴格照 `references/template-format.md`）：
- 標題格式：`[YYYY.MM - YYYY.MM]    [Position]    [Name of Employer (SFC CE No. if applicable)], [Location]`
- Type 4 和 Type 9 的 experience **預設分開寫**（見 Step 1 確認結果）。各自以 `With regard to type 4 regulated activities, the following experience is relevant:` 和 `With regard to type 9 regulated activities, the following experience is relevant:` 開頭，各自單獨列 bullets
- 重要 bullet 加粗體小標題（Investment Product Strategy and Distribution Leadership: / Investment Management Oversight: / Risk Management:）

**小標題的命名原則**

小標題必須反映此人的角色，而不是功能描述。例：
- 她主導了業務 → 'Investment Research Business Leadership'
- 她是監管合規 → 'Research Compliance Framework'
- 她是接觸方而非主導方 → 'Research Delivery Oversight'

**名字決定了 SFC 對她角色的第一印象。**

**結尾定性收尾句**（句式不固定）

重要 bullet 結尾加一句定性聲明，點明對應的 SFC 能力維度；句式不固定，但必須含能力定性。

- 例：'This demonstrates direct experience in making and managing discretionary private equity investments.'
- 例：'This involved all aspects of fund structuring, launch, and management.'

不確定的數字先寫 `[TBC]`，不要留空格；不確定的事實先標 `[RO to confirm: ...]`。

### 相關經驗認定框架 & 撰寫切入維度

Experience 部分的內容應盡量向申牌主體的未來業務方向靠攏。對於根據職位性質高度可能涉及、但 CV 未明寫的工作內容，可以按合理推測先行起草，但**必須以 `[RO to confirm: ...]` 或高亮方式標出**，供 RO 確認；不得將推測內容直接當作既成事實。

**SFC 認可相關經驗範疇按申牌主體業務分類** → 詳見 `references/sfc-relevant-experience.md`（Hedge Fund / PE / Discretionary AM / Fintech / Credit Rating 五大類，含官方 Reference）。

**經驗撰寫語句庫** → 詳見 `references/experience-wording-tiers.md`：
- Tier 1 通用模板級（主動管理類基金 / 研究背景 RO 皆適用）
- Tier 2 條件性可復用級（需嚴格匹配申請人特定背景後方可使用）
- Tier 3 特殊背景級（理解邏輯，個案定制，不直接復用文字）

**使用原則**：以下語句僅在 applicant 職位與業務性質高度匹配時方可使用，必須標註 [RO to confirm] 或高亮。**所有數字（AUM、人數、基金名等）絕不推測，一律 [RO to confirm]。**

### D. Management Experience 段

- 格式固定：公司名 — managed [XX] team with [X] direct subordinates
- 數字必須具體；不需要其他已經在前面提過的無關信息
- 不知道就標 `[TBC: headcount to confirm with RO]`

---

## STEP 3.5 | AI 交叉驗證（Fact-Check，獨立完成）

**目標：在給人看之前，先用第二個 AI 核對所有可驗證的事實，消滅低級錯誤。**

> ⚠️ **單一 AI 會偷懶或重複出錯而無法自查。** 此步驟強制要求用另一個 AI agent 獨立核對。

### 必須核對的清單

調用 `Agent` tool（subagent_type="general-purpose"），給它以下任務和原始材料：

1. **日期核對**：將初稿中所有日期（任職起迄、RO 生效日、考試日期）與 SFC Public Register 記錄逐條對比。列出任何不一致。
2. **RA Type 核對**：確認初稿中每個 RA type 的引用與 SFC 記錄一致。特別注意「1,4,9」還是「1,4,6」等容易混淆的組合。
3. **公司名 + CE 號核對**：確認每個公司名和 CE 號與 SFC 記錄完全一致。
4. **數字核對**：確認初稿中出現的數字（AUM、人數）有明確來源標記（[TBC] 或 [RO to confirm]）。未標記的數字必須有文件依據。
5. **動詞一致性核對**：確認 Duties 段和 Experience 段的動詞使用與 RO 角色定位（Primary/Joint/Secondary）一致。

### 執行方式

```
Agent(
  subagent_type="general-purpose",
  description="Fact-check D&E draft",
  prompt="請核對以下 Duties & Experience 初稿中的所有事實，與原始 SFC 記錄和 CV 對比：
  
  [貼上初稿全文]
  
  原始材料：
  - SFC Public Register: [貼上記錄]
  - CV: [貼上關鍵段落]
  
  請產出核對報告，格式：
  - 日期錯誤：[列出]
  - RA type 錯誤：[列出]
  - 公司名/CE 號不一致：[列出]
  - 未標記數字：[列出]
  - 動詞問題：[列出]
  - 總體結論：通過 / 需修正"
)
```

### 核對後的處理

- 🔴 **事實錯誤**：直接在初稿中修正，不詢問
- 🟡 **無法確定但可疑**：標記後在 Step 4 提交給 Joyce/Ben 時一併提出
- ⚪ **一切正確**：在 Step 4 的確認訊息中加一句「已通過 AI 交叉驗證」

### 完成條件

核對報告顯示「通過」或所有 🔴 錯誤已修正後，方可進 Step 4。

---

## STEP 4 | 第二次確認（附初稿）

**目標：請 Ben review 整體方向；確認剩餘 TBC 數字；區分他需要做的事 vs. 去問 RO 的事。**

發初稿時說清楚：
- 「請確認選材方向和每段重點是否正確」
- 同時列明：「以下 [X] 個 TBC 項目需向 RO 確認，我可以直接聯繫嗎？」

如果 Ben 通過口頭給 feedback：**先整理成書面清單**（🔴 必改 / 🟡 建議改），確認後再動手。

### 處理 Ben Feedback 的優先級

| 級別 | 描述 | 何時處理 |
|---|---|---|
| 🔴 | 事實錯誤、公司名稱不一致、數字未確認就直接寫、語法錯誤、Type 標頭放錯位置 | 發給 Ben 前必須修完 |
| 🟡 | 表述不夠精準、小標題命名不反映角色、排版問題（連字符、空格） | 修完 🔴 後再處理 |
| ⚪ | 風格微調、句子可以但不夠亮眼 | 最後潤色時處理 |

> ⚠️ **Ben 口頭 Feedback 的處理規則：** 錄音 / 口頭信息 → 整理成書面條目 → 標明 🔴🟡 → 逐條確認後再改。**不要聽完錄音就直接改，因為你可能記錯了細節。**

---

## STEP 5 | 修改並輸出終稿

改完後自己做最後一輪自查，用以下問題掃全文：

> SFC 審核官看完每一條 bullet，能判斷這個人有沒有直接做過 Type X 的受規管活動嗎？她的角色是什麼（主導 / 監督 / 協助）？有數字支撐嗎？

- 如果某條 bullet 的答案是「不確定」，就加定性收尾句，或刪掉
- 確保所有公司名稱在全文保持一致（尤其是集團下有多個主體時）
- 清理全文排版：連字符統一為 –；刪除多餘空格；確保 Type 標頭位置正確

### 輸出 .docx 終稿

最終以 .docx 形式輸出，套用 Brooklet 文檔格式。**調用 `brooklet-word-document-style` skill** 完成排版。

模板位置：`assets/duties-experience-template.docx`（即 Licence-Template-Application_Duties-and-Experience-of-RO.docx 的副本），按段落結構：

1. 標題行：RO APPLICANT – FULL NAME
2. Description of proposed job duties relating to the relevant regulated activity(ies)
3. Subject to the Commission's approval of [Mr./Ms. Last Name] as a RO, his/her principal duties will include the following:
4. With regard to type (X) regulated activity: ...
5. Elaboration on relevant industry experience
6. [Employment Period] [Position] [Name of Employer (SFC CE No. if applicable)]
7. With regard to type (X) regulated activity: ...
8. Fund under management / Asset types / AUM / Team under management
9. Management experience

---

## 附錄 | 常見陷阱

> 完整版見 `references/common-pitfalls.md`。撰寫時遇到任何拿不准的情境，先翻一遍。

核心九陷阱速覽：
- 借數字未確認
- 公司名稱不一致
- 小標題定性錯誤
- Type 標頭放錯位置
- AI 敏感詞
- Duties 太實
- 口頭信息直接動筆
- 沿用舊版段落結構
- 把「可推論」直接寫成「已發生」

---

## 與其他 skill 的協作

- **上游**：`brooklet-ro-assessment` —— 判斷某人是否適合做 RO。本 skill 假設此步已完成。
- **下游**：`brooklet-word-document-style` —— Step 5 終稿排版必須調用。
- **平行**：如果 Ben 要求同步出 WhatsApp / Email 確認訊息（Step 2 / Step 4），遵循 Brooklet 溝通原則（自信不傲慢、bullet point、不用「暫時」「可能」「大概」等模糊詞、不低姿態乞求）。

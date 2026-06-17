# Template 段落順序 / 標題格式 / 排版規則

> 原始模板：`assets/duties-experience-template.docx`
> 實際參考範例：`Licence Application_Duties and Experience of RO_WONG Shui Lun, William.docx`、`Licence Application_Duties and Experience of RO_HUI Tin Kay V2.docx`
> **格式、段落順序、標題層級全部照範例；不借舊版的結構。**

---

## 文檔骨架（嚴格按此順序）

```
RO APPLICANT – FULL NAME
Proposed Job Title: Responsible Officer (Type X & Type Y)

Proposed duties:

Subject to the Commission's approval of [Mr./Ms. Last Name] as a RO, his/her principal duties will include the following:

- [Bullet 1];
- [Bullet 2];
- ...
- [Final bullet].

Relevant industry experience

[Overview paragraph: 2-4 sentences summarising total years, core expertise, and headline achievements.]

[YYYY.MM – YYYY.MM]    [Position]    [Name of Employer (SFC CE No. if applicable)], [Location]

[Optional: 1-2 sentence context paragraph about the firm and the candidate's role.]

With regard to Type [X] & [Y] regulated activities, the following experience is relevant:

[Bold Sub-heading]: [Description of the relevant activity, ending with a qualitative statement];

[Bold Sub-heading]: [Description];

[Bold Sub-heading]: [Description. This demonstrates direct experience in ...].

Fund under management: [Name of the Fund if known]
Asset types and geographical coverage of the fund(s): [Description]
Asset under management: approximately US$[XXX] million
Team under management: approximately [X] to [X] persons during the tenure

[Repeat for each employment period]

Relevant Management experience

[Company] - managed [which teams/departments] with [X] subordinates[, additional context].
[Company] - managed [which teams/departments] with [X] subordinates.
```

---

## 各段格式詳解

### A. 標題行
- 格式：`RO APPLICANT – FULL NAME`
- 次行：`Proposed Job Title: Responsible Officer (Type X & Type Y)`
- 全大寫、置頂

### B. Proposed Duties 段
- 標題：`Proposed duties:`
- 開頭句：`Subject to the Commission's approval of [Mr./Ms. Last Name] as a RO, his/her principal duties will include the following:`
- **Duties 是單一 flat bullet list，不按 Type 分節**。所有 Type 4 和 Type 9 的 duties 混在一個列表裡
- 每個 bullet 使用 `ListBullet` + 內建 bullet numbering（`NUM`），分號 `;` 結尾；最後一條以句號 `.` 結尾
- 4-6 個 bullets
- 動詞用現在分詞（Leading / Overseeing / Participating in）

### C. Relevant Industry Experience 段
- 標題：`Relevant industry experience`
- **不需要** "Elaboration on" 前綴

### D. Overview 導言段（Experience 下第一段）
- 第一句：`[Mr./Ms. Last Name] is a seasoned financial services professional with over [X] years of experience in [relevant fields].`
- 第二/三句：點出核心賣點（AUM 規模、多次成功申牌、跨境市場經驗等）
- 不要太長，2-4 句即可

### E. 工作經歷段標題（Job Header）

**格式：多行粗體，每項資訊獨立換行。**

一般情況（單一公司）：
```
July 2007 to December 2024
Deputy Chief Executive Officer; Executive Director
Type 4 RO: June 2010 to December 2024
Type 9 LR & RO: November 2008 to December 2024
BOCOM International Holdings Company Limited (3329.HK), Hong Kong
```

規則：
- 第一行：日期（`Month YYYY to Month YYYY` 格式），粗體
- 第二行：職位，粗體。如有多個職位以 `;` 分隔
- 第三行起：Type-line。每個相關 RA type 一行，格式 `Type [X] [Role]: [Month YYYY to Month YYYY]`，粗體。同一 Type 下 LR 和 RO 時間連續則合併為 `LR & RO`
- 最後一行：公司名（+ CE 號，如有）+ 地點，粗體
- **Type-line 不重複公司名**：一般情況下 Type-line 對應的公司就是最後一行的公司，不需在 Type-line 括號內重複。只有當集團多牌且 Type-line 對應的持牌主體與主公司不同時，才在括號內標明：`Type X RO: [日期] ([持牌主體], CE No. [XXX])`

特殊情況（集團多牌，須先在 Step 1 確認）：
```
March 2020 to October 2022
Managing Director
Type 4 LR & RO: April 2020 to October 2022 (Subsidiary A, CE No. XXX)
Type 9 LR: February 2021 to October 2022 (Subsidiary B, CE No. YYY)
Innovest Group (CE No. BLO233 and BGB564), Hong Kong
```

- 集團多牌時，Type-line 括號內標明不同的持牌主體及 CE 號，以分號分隔
- 同一 Type 下 LR 和 RO 時間連續則合併為一行 `Type X LR & RO: [日期區間]`
- 時間不連續則分兩行
### F. 可選：公司/角色背景段
- 在工作經歷標題後、Type bullet 前，可加 1-2 句描述該公司和候選人在其中的角色

### G. Type 標頭 + Experience Bullets
- **預設分開寫：** Type 4 和 Type 9 各自獨立。格式：
  ```
  With regard to type 4 regulated activities, the following experience is relevant:
  [Type 4 bullets...]

  With regard to type 9 regulated activities, the following experience is relevant:
  [Type 9 bullets...]
  ```
- **只有在 Joyce/Ben 明確指示合併時**才使用 `With regard to Type 4 & 9 regulated activities, the following experience is relevant:` 合併標頭。如未確認，一律分開處理。
- **每個 bullet 以粗體小標題開頭**，格式：`[Bold Sub-heading]: [description];`。使用 `ListBullet` + 內建 bullet numbering（`NUM`）
- 小標題反映角色和動作（如 `Formulating Investment Guidelines:`、`Fixed Income Fund:`、`Operational and Risk Management Oversight:`）
- **名字決定了 SFC 對她角色的第一印象**
- 每個 bullet 結尾加分號；最後一條以句號結尾
- 重要的 bullet 結尾加一句定性收尾句（不固定句式）：如 `This demonstrates direct experience in making and managing discretionary private equity investments.` 或 `This involved all aspects of fund structuring, launch, and management.`

### H. Fund / AUM / Team 細節（每段經歷後）
- 直接放在該段經歷的 bullets 之後，不用額外標題
- 格式（每行單獨）：
  ```
  Fund under management: [Name of the Fund if known]
  Asset types and geographical coverage of the fund(s): [Description]
  Asset under management: approximately US$[XXX] million
  Team under management: approximately [X] to [X] persons during the tenure
  ```
- 如果沒有基金（如只有 DA 專戶），`Fund under management` 可改為 `Discretionary accounts under management` 或省略
- 不確定的數字標 `[TBC]`

### I. Earlier / shorter experience（非核心經歷）
- 非核心的早期經歷可簡短處理：幾行概述，不按完整 bullet 格式展開
- 如果該經歷不是重點，可在段落末尾加 `[Note: this section is brief as the primary focus is the [Main Period], per Ben's direction.]`

### J. Management Experience 段
- 標題：`Relevant Management experience`
- 格式：`[Company] - managed [which teams/departments] with [X] subordinates[, additional context].`
- 每間公司一行
- 不需要其他已在前面提過的無關信息
- 數字必須具體
- 不知道就標 `[TBC: headcount to confirm with RO]`

---

## 排版細節

| 項目 | 規則 |
|---|---|
| 連字符 | 統一為 `-`（hyphen），不用 `–` 或 `—`（見 brooklet-word-document-style skill） |
| 公司名稱 | 全文必須一致（尤其集團下多個主體時） |
| CE 號 | 公司名後括號內，格式 `(CE No.)` |
| 日期 | `Month YYYY to Month YYYY`（如 `July 2007 to December 2024`），不用數字格式 |
| AUM | `approximately US$[XXX] million`，全文統一一種貨幣格式 |
| Bullet 縮排 | 使用 Word 內建 bullet 格式：abstractNum left=-360 hanging=360 + paragraph-level left=360 |
| Bullet 結尾 | 分號 `;`，最後一條句號 `.` |
| Bold sub-heading | 每個 experience bullet 以粗體標題開頭，後接冒號+空格+描述 |

---

## 範例（節錄自 WONG Shui Lun, William 實際文檔）

```
RO APPLICANT – WONG Shui Lun, William
Proposed Job Title: Responsible Officer (Type 4 & Type 9)

Proposed duties:

Subject to the Commission's approval of Mr. Wong as a RO, his principal duties will include the following:

- Leading the Company's Type 4 and Type 9 regulated activities, including securities advisory and asset management functions;
- Leading investment strategy formulation, asset allocation, portfolio construction and ongoing portfolio monitoring for fund(s) under management;
- Leading investment and divestment decisions in accordance with investment mandates, risk parameters and applicable regulatory requirements;
- Leading risk management, including monitoring portfolio risk, concentration and exposure limits, and implementing control measures;
- Overseeing compliance, AML/CTF, regulatory licensing, operational setup and ongoing regulatory matters relevant to the Company's regulated activities; and
- Participating in the establishment and maintenance of the Company's internal control, compliance and operational framework for Type 4 and Type 9 activities.

Relevant industry experience

Mr. Wong is a seasoned financial services professional with over 20 years of experience in senior management roles within the asset management and securities industries. He has a proven track record of successfully obtaining and acting as a RO for Type 4 and Type 9 licenses across multiple SFC-licensed corporations.

September 2018 – March 2024    Executive Director / Responsible Officer / Board Member    AVICT Global Asset Management Limited (CE No.: BHF812), Hong Kong

With regard to Type 4 & 9 regulated activities, the following experience is relevant:

Formulating Investment Guidelines: Formulated the investment guidelines and mandate for the holding company's USD$350 million fixed income portfolio. This involved providing high-level advice on investment parameters, risk tolerance, and strategic asset allocation to guide the investment process;

Fixed Income Fund: Managed a fixed income fund with a seeding of USD$350 million, and grew the AUM by 30% in 6 months;

Alternative Fund: Led teams to launch multiple funds, including the "Flying Shark" funds – a series of asset-backed securities (ABS) funds with underlying assets of vessels valued at over USD$540 million combined. This involved all aspects of fund structuring, launch, and management;

Operational and Risk Management Oversight: Managed and oversaw all operations, settlements, FRR monitoring, and AML/KYC procedures as the MIC of OMO and Risk Management, ensuring the firm's asset management activities were compliant and operationally robust.

Fund under management: Fixed income fund and ABS funds
Asset types and geographical coverage of the fund(s): Fixed income and asset-backed securities
Asset under management: approximately USD$1.2 billion
Team under management: supervised a team of 6 from multiple internal departments.

Relevant Management experience

Please refer to the above.
```
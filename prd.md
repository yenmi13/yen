# 產品需求文件 (PRD)：Yenmi 個人品牌與履歷網站

**文件版本**：1.0
**日期**：2026-01-17
**專案代號**：Project 2026_Pivot
**狀態**：規劃中

---

## 1. 專案概述 (Project Overview)

### 1.1 背景與目標

本專案旨在為資深行銷經理 Yenmi 構建一個整合型個人網站。目標是將傳統的職涯履歷（基於 104 人力銀行資料）與新興的 AI 自動化技能相結合。網站需同時滿足「尋求正職行銷主管」與「AI 轉型專案接案」的雙重需求，並透過獨特的視覺風格展現候選人「理性數據」與「感性人文」並存的特質。

### 1.2 目標受眾 (Target Audience)

1. [cite_start]**企業雇主/獵頭**：尋找具備 12 年以上經驗、擁有大型全案操盤能力的行銷主管 [cite: 1, 5]。
2. [cite_start]**中小企業主/新創團隊**：尋找能透過 AI 技術進行降本增效、建立自動化工作流的合作夥伴 [cite: 3, 24]。

### 1.3 核心價值主張

* [cite_start]**資深行銷背景**：12 年全案經驗，具備實證的 ROAS 與募資績效 [cite: 1, 5]。
* [cite_start]**AI 技術賦能**：具備使用 IDE 與 AI Agent 構建自動化工作流的能力，非傳統純文科行銷人 [cite: 3, 10]。
* [cite_start]**系統化思維**：強調「建立系統」而非單純「執行任務」 [cite: 23]。

---

## 2. 視覺與設計規範 (Design & Visual Guidelines)

基於參考文件（Salford, Traction, Meet Our Team 簡報風格），網站設計需遵循以下規範：

* **設計風格 (Look & Feel)**：
  * **Pitch Deck 風格**：排版需類似新創募資簡報，強調大標題、清晰的資訊層級與留白。
  * [cite_start]**質感**：背景使用帶有雜訊（Noise）的米白色或紙質紋理，營造沈穩且具人文溫度的氛圍 [cite: 11, 13]。
  * **字體**：標題採用具現代感的襯線體（Serif）或粗體無襯線體，內文使用高易讀性的無襯線體。
* **配色方案**：
  * [cite_start]**主色調**：深海綠（Deep Teal）或墨綠色（參考數據圖表配色），象徵專業與數據 [cite: 11]。
  * **背景色**：米白/灰白色（Off-white），降低數位螢幕的刺眼感。
  * **強調色**：使用高飽和度色彩（如螢光綠或亮橘）點綴 AI 相關關鍵字，突顯科技感。

---

## 3. 網站架構與功能規格 (Site Architecture & Specifications)

### 3.1 頁面結構 (Sitemap)

單頁式應用（Single Page Application）或錨點導航結構：

1. **Hero Section** (首頁主視覺)
2. **About Me** (個人簡介與特質)
3. **Core Services & Skills** (核心技能與服務)
4. **Traction & Case Studies** (實績與數據)
5. **Experience** (工作經歷 - 履歷模組)
6. **Contact** (聯繫與合作模式)

---

### 3.2 詳細功能說明

#### 3.2.1 Hero Section (主視覺區塊)

* **版面設計**：參考 `Startup Pitch Deck` 封面，置中大標題。
* **文案內容**：
  * [cite_start]**H1**：Marketing Manager x System Builder [cite: 23]。
  * [cite_start]**Sub-text**：結合 12 年品牌行銷經驗與 AI 自動化技術，為企業構建高效獲利系統 [cite: 1, 15]。
* **功能元件**：
  * 主要 CTA 按鈕：「查看專案實績 (View Work)」。
  * 次要 CTA 按鈕：「下載履歷 (Download Resume)」。

#### 3.2.2 Service & Skills (技能模組)

* [cite_start]**版面設計**：參考 `Discover Our Services` 的卡片式 UI (Card UI)，橫向排列 [cite: 11]。
* **內容邏輯**：將硬技能模組化展示。
  * [cite_start]**模組 A - 品牌全案操盤**：包含品牌策略、OMO 佈局、群眾募資（Kickstarter/嘖嘖） [cite: 3, 5]。
  * [cite_start]**模組 B - AI 數位轉型**：包含 AI Agent 開發、n8n/Make 自動化串接、降本增效解決方案 [cite: 10, 15]。
  * [cite_start]**模組 C - 成長行銷 (Growth)**：包含 ROAS 優化、KOL/KOC 矩陣佈局、數據分析 (GA4/Looker Studio) [cite: 3, 12]。

#### 3.2.3 Traction (關鍵績效展示)

* [cite_start]**版面設計**：參考 `Traction` 簡報頁面，使用柱狀圖或數據大字報呈現動態成長感 [cite: 11]。
* **關鍵數據 (Data Points)**：
  * [cite_start]**ROAS 15.3**：Bitplay AquaSeal 專案實績 [cite: 5, 12]。
  * [cite_start]**$10M+**：群眾募資累積金額 (千萬轉化) [cite: 5]。
  * [cite_start]**50%**：透過 GenAI 工具節省的內容生成與報表工時 [cite: 3]。
  * [cite_start]**300%**：品牌聯名活動 (Realive Concert) 的月營收成長 (M.O.M) [cite: 13]。

#### 3.2.4 About Me (活人感特質區)

* [cite_start]**版面設計**：參考 `Meet Our Team`，使用流體線條與非正式照片（生活照或工作側拍） [cite: 13]。
* **內容策略**：展現「賽博命理」與個人哲學，區隔傳統履歷的生硬感。
  * [cite_start]**個人標籤**：ENFP、系統建造者、紫微斗數研究者 [cite: 23]。
  * [cite_start]**哲學陳述**：「先有感，再有理」。強調在數據驅動的同時，保持對人性的洞察與溫柔 [cite: 23]。
  * **興趣**：提及 Hanayama 益智玩具或對咖啡的喜好，增加立體感。

#### 3.2.5 Experience Timeline (職涯歷程)

* **呈現方式**：簡潔的時間軸，僅列出關鍵職位與核心成就（非流水帳）。
* **資料來源**：
  * [cite_start]**2025.12 - Present**：待業/接案/AI 系統開發 [cite: 23]。
  * [cite_start]**2025.10 - 2025.12**：Mula (Yodao) - Marketing Manager (導入自動化監測) [cite: 3]。
  * [cite_start]**2019 - 2024 (預估)**：Bitplay - 行銷主管 (Shopify, Kickstarter, 團隊管理) [cite: 5]。
  * [cite_start]**2017 - 2019**：Giorgio Armani - 廣告公關 (CRM, VIP 活動) [cite: 7]。
  * [cite_start]**2012 - 2017**：4A 廣告代理商 - 資深文案 (Panasonic, 統一) [cite: 8]。

#### 3.2.6 Contact & CTA (合作模式)

* **文案**：明確區分合作類型。
  * [cite_start]**Type A：全職行銷主管 (Full-time)** - 尋找能帶領團隊轉型的企業 [cite: 21, 24]。
  * [cite_start]**Type B：專案顧問 (Consultant)** - 針對募資、AI 導入或特定行銷難題 [cite: 24]。
* **表單功能**：包含姓名、公司、合作類型選單。

---

## 4. 技術需求 (Technical Requirements)

### 4.1 平台與工具

* **建議平台**：Framer, Webflow 或 Next.js (若需高度客製化)。
* [cite_start]**CMS 整合**：建議串接 Notion 作為後台 CMS，方便隨時更新專案實績與 Blog 內容（符合使用者習慣） [cite: 5]。

### 4.2 響應式設計 (RWD)

* [cite_start]**Mobile First**：考量流量可能來自 Threads 等社群平台，手機版體驗需優化字體大小與觸控區塊 [cite: 24]。

### 4.3 SEO 設置

* **關鍵字佈局**：Marketing Manager, AI Automation, Growth Hacker, 品牌行銷, 數位轉型。
* **Meta Tags**：需設定 Open Graph Image，確保在社群分享時顯示精美的預覽圖。

---

## 5. 內容語氣與風格 (Voice & Tone)

* **專業 (Professional)**：在描述工作成就與數據時，使用精準的商業術語 (ROAS, KPI, OMO)。
* [cite_start]**自信 (Confident)**：避免過度謙卑的求職語氣，採用「合作夥伴」的對等視角 [cite: 21]。
* [cite_start]**機智 (Witty/Smart)**：在 About Me 區域適度展現幽默感與個人特色（如命理梗），體現「聰明且細膩」的人格特質 [cite: 21, 23]。

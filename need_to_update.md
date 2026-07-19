# `index.html` Metadata 待更新清單

> 網頁本體（`<body>` 內的標題、摘要、音訊表格）已填入真實內容，**不需修改**。
> 以下皆為 `<head>` 內尚未替換的 metadata 佔位符。可從已填好的本體內容取得正確資訊：
>
> - **論文標題**：MPECHO: A MELODY AND PHONEME-AWARE GENERATIVE FRAMEWORK FOR CONTROLLABLE COVER SONG GENERATION
> - **作者名單**：Wei-Jaw Lee, Hsuan-Yu Yeh, Ting-Yi Hu, Chih-Pin Tan, Fang-Duo Tsai, Yi-Hsuan Yang（全部隸屬 National Taiwan University）
> - **摘要**：見 `index.html`（Abstract 段落）
> - **關鍵字**：Cover Song Generation, Lyrics-to-Song, Lyrics Alignment, MIR, AI

---

## ✅ 已完成（2026-07-19）

- [x] `meta[name=author]`（L14）— 已填入 6 位作者
- [x] `article:author`（L34）— 已填入第一作者 Wei-Jaw Lee
- [x] `citation_author` ×6（L55–60）— 已填入全部作者（Last, First 格式）
- [x] JSON-LD ScholarlyArticle `author[]`（L122–171）— 已填入 6 位作者 + NTU 隸屬
- [x] `<body>` 可見作者列表 — 已換成 6 位作者，並加上 National Taiwan University

---

## 1. Primary Meta Tags

| 行號 | 屬性 | 目前值（佔位符） | 說明 |
|------|------|------------------|------|
| 9  | `meta[name=title]`       | `PAPER_TITLE - AUTHOR_NAMES` | 換成論文標題 + 作者 |
| 11 | `meta[name=description]` | `BRIEF_DESCRIPTION_OF_YOUR_RESEARCH_CONTRIBUTION_AND_FINDINGS` | 撰寫 150–160 字的研究簡介 |
| 13 | `meta[name=keywords]`    | *(已有值，可再確認)* | 已填關鍵字，確認是否需增補 |

## 2. Open Graph / Facebook

| 行號 | 屬性 | 目前值（佔位符） | 說明 |
|------|------|------------------|------|
| 21 | `og:site_name`      | `INSTITUTION_OR_LAB_NAME` | 機構名稱（National Taiwan University） |
| 23 | `og:title`          | `PAPER_TITLE` | 同論文標題 |
| 25 | `og:description`    | `BRIEF_DESCRIPTION_...` | 同 description |
| 27 | `og:url`            | `https://YOUR_DOMAIN.com/YOUR_PROJECT_PAGE` | 專題頁實際網址 |
| 29 | `og:image`          | `https://YOUR_DOMAIN.com/static/images/social_preview.png` | 需製作 1200×630 預覽圖並更新路徑 |
| 32 | `og:image:alt`      | `PAPER_TITLE - Research Preview` | 圖片替代文字 |
| 33 | `article:published_time` | `2024-01-01T00:00:00.000Z` | 實際發表日期 |
| 36 | `article:tag`       | `KEYWORD1` | 關鍵字 1 |
| 37 | `article:tag`       | `KEYWORD2` | 關鍵字 2 |

## 3. Twitter

| 行號 | 屬性 | 目前值（佔位符） | 說明 |
|------|------|------------------|------|
| 42 | `twitter:site`        | `@YOUR_TWITTER_HANDLE` | 實驗室/機構 Twitter 帳號（無則可移除） |
| 44 | `twitter:creator`     | `@AUTHOR_TWITTER_HANDLE` | 第一作者 Twitter 帳號（無則可移除） |
| 46 | `twitter:title`       | `PAPER_TITLE` | 同論文標題 |
| 48 | `twitter:description` | `BRIEF_DESCRIPTION_...` | 同 description |
| 50 | `twitter:image`       | `https://YOUR_DOMAIN.com/static/images/social_preview.png` | 同預覽圖 |
| 51 | `twitter:image:alt`   | `PAPER_TITLE - Research Preview` | 圖片替代文字 |

## 4. Academic / Citation Meta（Google Scholar 收錄用）

| 行號 | 屬性 | 目前值（佔位符） | 說明 |
|------|------|------------------|------|
| 54 | `citation_title`            | `PAPER_TITLE` | 論文標題 |
| 61 | `citation_publication_date` | `2024` | 實際年份 |
| 62 | `citation_conference_title` | `CONFERENCE_NAME` | 研討會/期刊名稱 |
| 63 | `citation_pdf_url`          | `https://YOUR_DOMAIN.com/static/pdfs/paper.pdf` | PDF 實際網址 |

## 5. `<title>` 標籤

| 行號 | 目前值（佔位符） | 說明 |
|------|------------------|------|
| 80 | `PAPER_TITLE - AUTHOR_NAMES \| Academic Research` | 換成論文標題與作者 |

## 6. Favicon / App Icons

| 行號 | 說明 |
|------|------|
| 83–84 | favicon 連結目前被註解掉。若有 favicon，取消註解並確認 `static/images/favicon.ico` 存在 |

## 7. Structured Data — ScholarlyArticle (JSON-LD)

| 行號 | 欄位 | 目前值（佔位符） | 說明 |
|------|------|------------------|------|
| 121 | `description`     | `BRIEF_DESCRIPTION_...` | 同 description |
| 172 | `datePublished`   | `2024-01-01` | 實際發表日期 |
| 175 | `publisher.name`  | `CONFERENCE_OR_JOURNAL_NAME` | 研討會/期刊名稱 |
| 177 | `url`             | `https://YOUR_DOMAIN.com/YOUR_PROJECT_PAGE` | 專題頁網址 |
| 178 | `image`           | `https://YOUR_DOMAIN.com/static/images/social_preview.png` | 預覽圖 |
| 180 | `abstract`        | `FULL_ABSTRACT_TEXT_HERE` | 完整摘要（可直接複製本體 Abstract） |
| 181 | `citation`        | `BIBTEX_CITATION_HERE` | BibTeX 引用 |
| 186 | `mainEntity.@id`  | `https://YOUR_DOMAIN.com/YOUR_PROJECT_PAGE` | 同 url |
| 191 | `about[0].name`   | `RESEARCH_AREA_1` | 研究領域 1 |
| 195 | `about[1].name`   | `RESEARCH_AREA_2` | 研究領域 2 |

> 註：L120 `headline` 已填正確論文標題；`author[]` 已全部填妥。

## 8. Structured Data — Organization (JSON-LD)

| 行號 | 欄位 | 目前值（佔位符） | 說明 |
|------|------|------------------|------|
| 206 | `name`      | `INSTITUTION_OR_LAB_NAME` | 機構名稱（National Taiwan University） |
| 207 | `url`       | `https://YOUR_INSTITUTION_WEBSITE.com` | 機構官網 |
| 208 | `logo`      | `https://YOUR_DOMAIN.com/static/images/favicon.ico` | 機構 logo |
| 210 | `sameAs[0]` | `https://twitter.com/YOUR_TWITTER_HANDLE` | Twitter（無則移除） |
| 211 | `sameAs[1]` | `https://github.com/YOUR_GITHUB_USERNAME` | GitHub |

---

## 需要作者提供 / 決定的資訊

- [ ] 各作者個人連結（`<body>` 作者區目前無連結，視需求補上）
- [ ] 研討會 / 期刊名稱與發表日期
- [ ] 專題頁正式網址（domain）
- [ ] 社群預覽圖 `social_preview.png`（1200×630）
- [ ] PDF 檔案與網址
- [ ] BibTeX 引用文字
- [ ] favicon 圖檔
- [ ] Twitter / GitHub 帳號（若有）

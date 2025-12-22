# Excel-to-HTML Converter for Web Support Pages

### 🚀 "Stop Manual Coding" - Drag & Drop Excel to Production-Ready HTML
**出版・教育業界のWebサポートページ更新作業を効率化するために開発した、実務直結型の変換ツール。**

Excelで管理されている複雑な資料一覧表などを、ドラッグ＆ドロップするだけで「セル結合」や「ファイルアイコン付与」を反映したHTMLソースコードに変換します。

---

## 🛠 Solving Real-World Problems

- **The Challenge:** 手作業でのHTMLテーブル作成（特に `rowspan` や `colspan` の計算）は時間がかかり、人的ミスが発生しやすい。また、特定の列（Word/PDF等）にアイコンリンクを付与する作業が煩雑。
- **The Solution:** ブラウザ上でExcelファイルを解析し、現場の運用ルール（特定のヘッダ名に基づくアイコン付与やクラス分け）を自動適用したHTMLを生成します。

## ✨ Key Features

- **Smart Table Mapping:** Excelの「セル結合」情報を正確に読み取り、`rowspan` / `colspan` 属性へ自動変換。
- **Auto-Icon Generation:** ヘッダ行（Word, PDF, Excel, Text等）を自動判定し、対応するファイル形式のアイコンとリンクを生成。
- **Domain-Specific Logic:** 「一括ダウンロード」列の自動検知など、特定の業務フローに基づいたCSSクラスの自動付与。
- **Instant Preview & Copy:** 生成されたHTMLをその場でプレビューし、ワンクリックでソースコードをクリップボードへコピー可能。
- **Zero-Installation:** Vanilla JSと `xlsx.js` のみで構築。サーバ不要、ブラウザだけで完結する軽量ツール。

## 💻 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS)
- **Library:** [SheetJS (xlsx.js)](https://github.com/SheetJS/sheetjs)
- **UI/UX:** Drag and Drop API, FileReader API

## 📂 Customization (Logic)

実務に合わせて以下のロジックをコード内でカスタマイズ可能です：
- `headerClassMap`: 特定の見出し語句（生徒用、教師用など）に応じたCSSクラスの割り当て。
- `detectFileCols`: 拡張子アイコンを表示する列の自動判定ルール。

---

## 👤 About the Developer

**Mechanical Engineer turned Technical Editor & Automation Enthusiast.**

「無駄な手作業を排除し、クリエイティブな時間に充てる」ことをモットーに、エンジニアリング（Python/JS）と出版実務の知識を掛け合わせたツール開発を行っています。

- **Specialties:** DTP Automation, Workflow Optimization, Natural Language Processing.
- **Interests:** Oil Painting, Motorcycle Maintenance, Linguistics.

---

## ツール開発の背景

このツールは、日々の派遣業務における「HTMLテーブルのコーディング」という退屈な作業を撲滅するために作成しました。
特に日本の出版・教育現場で多用される「複雑に結合されたExcelの表」を、Webサイトの仕様（アイコン画像や共通CSSクラス）に合わせた状態で出力することを目的としています。

「技術を私物化して、業務時間を自分らしく使う（サボる）」ための第一歩として、実用性を重視して構築しています。

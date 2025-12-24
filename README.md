---

# Excel to Web Layout Converter

👉 **Live Demo / Tool**
[https://kazuo-miyajima.github.io/Excel-to-Web-Layout-Converter/](https://kazuo-miyajima.github.io/Excel-to-Web-Layout-Converter/)

---

## 🚀 Convert Excel into Production-Ready HTML — No Manual Coding

A **practical tool designed to streamline web support page updates** in the publishing and education industries.

Simply drag & drop an Excel file and generate **ready-to-use HTML tables** with merged cells, file-type icons, and workflow-specific CSS classes automatically applied.

---

## 🛠 The Problem This Tool Solves

* Writing HTML tables with complex `rowspan` / `colspan` calculations is time-consuming
* Tables with many merged cells are prone to human error
* Adding Word / PDF / Excel icons and links column by column is tedious

### ✔ The Solution

This tool parses Excel files directly in the browser and generates HTML tables that **automatically follow real-world operational rules** used in production websites.

---

## ✨ Key Features

* **Accurate Cell Merge Conversion**
  Reads Excel merge data and converts it into proper `rowspan` / `colspan` attributes
* **Automatic File Icon Generation**
  Detects header names (Word / PDF / Excel / Text, etc.) and inserts matching icons with links
* **Workflow-Specific Logic**
  Automatically detects columns such as “Bulk Download” and assigns predefined CSS classes
* **Instant Preview & Copy**
  Preview the generated HTML immediately and copy the source with one click
* **Zero Installation**
  Runs entirely in the browser — no server, no setup required

---

## 💻 Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
* **Library:** SheetJS (xlsx.js)
* **APIs:** Drag & Drop API, FileReader API

---

## ⚙ Customizable Logic

The following logic can be adjusted in the source code to match your workflow:

* `headerClassMap`
  Maps specific header labels (e.g., Student / Teacher) to CSS classes
* `detectFileCols`
  Rules for automatically detecting file-link columns

---

## 🧠 Background & Motivation

This tool was created to eliminate a repetitive task encountered in daily contract work:
**manually coding HTML tables from Excel files**.

It is especially tailored for Excel tables commonly used in Japanese publishing and education environments, where **heavily merged cells** and **strict HTML/CSS conventions** are the norm.

The goal is simple:
**reduce manual work and reclaim time for more meaningful tasks.**

---

## 👤 About the Developer

**Mechanical Engineer turned Technical Editor & Automation Enthusiast**

* **Expertise:** DTP Automation, Workflow Optimization, Python / JavaScript
* **Interests:** Oil Painting, Motorcycle Maintenance, Linguistics

Built as a practical tool for real-world use, with efficiency as the top priority.

---
# Excel to Web Layout Converter

👉 **Live Demo / Tool**
[https://kazuo-miyajima.github.io/Excel-to-Web-Layout-Converter/](https://kazuo-miyajima.github.io/Excel-to-Web-Layout-Converter/)

---

## 🚀 Excelをドラッグ＆ドロップするだけで、実務用HTMLを生成

**出版・教育業界のWebサポートページ更新業務を効率化するために開発した、実務直結型ツールです。**

Excelで管理されている複雑な資料一覧表を、
**セル結合・ファイル種別アイコン・業務用CSSクラス**を反映した
**そのまま使えるHTMLソース**に変換します。

---

## 🛠 解決したい課題

* `rowspan` / `colspan` を手計算しながらHTMLテーブルを書くのが面倒
* セル結合が多いExcel表ほど、人的ミスが発生しやすい
* Word / PDF / Excel などのリンク列に、毎回アイコンを付けるのが煩雑

### ✔ このツールでできること

ブラウザ上でExcelファイルを解析し、
**現場の運用ルールを自動適用したHTMLテーブル**を生成します。

---

## ✨ 主な機能

* **セル結合の完全再現**
  Excelの結合情報を読み取り、`rowspan` / `colspan` を自動生成
* **ファイルアイコンの自動付与**
  ヘッダ名（Word / PDF / Excel / Text 等）を判定し、対応アイコン＋リンクを生成
* **業務特化ロジック対応**
  「一括ダウンロード」列などを自動検知し、CSSクラスを付与
* **即時プレビュー & コピー**
  生成結果をその場で確認し、HTMLをワンクリックでコピー
* **インストール不要**
  サーバ不要、ブラウザだけで動作

---

## 💻 技術構成

* **Frontend:** HTML5 / CSS3 / JavaScript（Vanilla）
* **Library:** SheetJS（xlsx.js）
* **API:** Drag & Drop API, FileReader API

---

## ⚙ カスタマイズ可能なロジック

業務ルールに応じて、以下をコード内で調整できます。

* `headerClassMap`
  見出し語句（生徒用・教師用など）に応じたCSSクラス割り当て
* `detectFileCols`
  ファイルアイコンを付与する列の判定ルール

---

## 🧠 開発背景

派遣業務で日常的に発生していた
**「Excel表を見ながらHTMLテーブルを手で書く作業」**をなくすために作成しました。

特に、日本の出版・教育現場で多用される
**複雑に結合されたExcel表**を、
Webサイトの仕様（アイコン画像・共通CSS）に合わせて
そのまま出力することを目的としています。

---

## 👤 About

**Mechanical Engineer → Technical Editor / Automation Enthusiast**

* **得意分野:** DTP自動化、業務フロー改善、Python / JavaScript
* **興味:** 油彩画、バイク整備、言語学

「無駄な手作業を減らし、時間を自分のために使う」ための実用品として設計しています。

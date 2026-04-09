# Markdown記法 チートシート / Markdown Cheat Sheet

このファイルは、主要なMarkdownの書き方をまとめたサンプルです。
This file provides a sample of the most commonly used Markdown syntax.

---

## 1. 見出し (Headings)
# 見出し1 / Heading 1
## 見出し2 / Heading 2
### 見出し3 / Heading 3

---

## 2. リスト (Lists)
* 箇条書き A / Bullet A
* 箇条書き B / Bullet B
    * インデント（半角スペース4つ）/ Indent (4 spaces)

1. 番号付き 1 / Numbered 1
2. 番号付き 2 / Numbered 2

---

## 3. テキスト装飾 (Emphasis)
* **太字 / Bold**: `**text**`
* ~~打ち消し線 / Strikethrough~~: `~~text~~`
* *斜体 / Italic*: `*text*`

---

## 4. 改行 (Line Breaks)
Markdownでは、普通に1回改行（Enter）しただけでは改行として反映されないことがあります。

* **強制改行 (Forced Line Break)**: 行末に**半角スペースを2つ**入れて Enter。
* **段落分け (New Paragraph)**: **空行を1行**挟みます（Enterを2回）。

---

## 5. 引用と区切り線 (Quotes & Rules)
> これは引用です。 / This is a blockquote.

区切り線（Horizontal Rule）: `---`

---

## 6. コード (Code)
文章中の `inline code` はバッククォート「 ` 」1つで囲みます。

複数行（Code Block）はバッククォート3つで囲みます。
```javascript
console.log("Hello World");
```

---

## 7. リンクと画像 (Links & Images)
* [Google](https://www.google.com)
* 画像 / Image: `![Alt text](URL)`

---

## 8. テーブル (Tables)
| 項目 (Item) | 内容 (Content) |
| :--- | :--- |
| Data A | OK |
| Data B | NG |

---

## 9. チェックリスト (Checklist)
- [x] 完了 / Done
- [ ] 未完了 / Todo


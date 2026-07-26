---
title: "MarkupSection"
linktitle: "MarkupSection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "マークアップセクションを表します。これはテキストを含み、別のテキストブロックと視覚的に区切ることができるページ上の長方形領域です。"
type: docs
weight: 2890
url: /ja/java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupSection

```
public final class MarkupSection extends Object
```

マークアップセクションを表します。これはテキストを含み、別のテキストブロックと視覚的に区切ることができるページ上の長方形領域です。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFragments](#getFragments--) | <p> セクション内にある空でない {@code TextFragment} オブジェクトのコレクションです。 </p><hr> {@code TextFragment} オブジェクトは検索結果のテキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更を可能にします。 |
| [getParagraphs](#getParagraphs--) | セクション内にある {@code MarkupParagraph} オブジェクトのコレクションです。 |
| [getRectangle](#getRectangle--) | セクションの矩形 |

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> セクション内にある空でない {@code TextFragment} オブジェクトのコレクションです。 </p><hr> {@code TextFragment} オブジェクトは検索結果のテキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更を可能にします。

**Returns:**
TextFragment インスタンスのリスト

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

セクション内にある {@code MarkupParagraph} オブジェクトのコレクションです。

**Returns:**
MarkupParagraph インスタンスのリスト

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

セクションの矩形

**Returns:**
矩形インスタンス

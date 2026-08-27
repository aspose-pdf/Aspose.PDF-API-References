---
title: "TextParagraphAbsorber"
linktitle: "TextParagraphAbsorber"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキスト段落の吸収オブジェクトを表します。テキスト検索を実行し、検索結果へは {@code TextParagraphAbsorber.TextParagraphs} コレクションを介してアクセスできます。"
type: docs
weight: 5220
url: /ja/java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextParagraphAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextParagraphAbsorber

```
public final class TextParagraphAbsorber extends TextAbsorber
```

テキスト段落の吸収オブジェクトを表します。テキスト検索を実行し、検索結果へは {@code TextParagraphAbsorber.TextParagraphs} コレクションを介してアクセスできます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextParagraphAbsorber](#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-) | <p> 矩形コレクションで {@code TextParagraphAbsorber} の新しいインスタンスを初期化します。 </p> |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRectangles](#getRectangles--) | PDF ドキュメントまたはページ上のテキスト段落を検索するために {@code TextParagraphAbsorber} が使用する矩形を取得します。 |
| [getTextParagraphs](#getTextParagraphs--) | 検索結果のコレクションを取得します。結果は {@code TextParagraph} オブジェクトで表されます。 |
| [setRectangles](#setRectangles-com.aspose.pdf.Rectangle:A-) | PDF ドキュメントまたはページ上のテキスト段落を検索するために {@code TextParagraphAbsorber} が使用する矩形を設定します。 |
| [setTextParagraphs](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | 検索結果のコレクションを設定します。結果は {@code TextParagraph} オブジェクトで表されます。 |
| [visit](#visit-com.aspose.pdf.Page-) | 指定されたページで検索を実行します。 |

### TextParagraphAbsorber {#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-}
<p> 矩形コレクションで {@code TextParagraphAbsorber} の新しいインスタンスを初期化します。 </p>

### getRectangles {#getRectangles--}
```
public Rectangle [] getRectangles()
```

PDF ドキュメントまたはページ上のテキスト段落を検索するために {@code TextParagraphAbsorber} が使用する矩形を取得します。

**Returns:**
矩形配列

### getTextParagraphs {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```

検索結果のコレクションを取得します。結果は {@code TextParagraph} オブジェクトで表されます。

**Returns:**
TextParagraphCollection の値

### setRectangles {#setRectangles-com.aspose.pdf.Rectangle:A-}
PDF ドキュメントまたはページ上のテキスト段落を検索するために {@code TextParagraphAbsorber} が使用する矩形を設定します。

### setTextParagraphs {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
検索結果のコレクションを設定します。結果は {@code TextParagraph} オブジェクトで表されます。

### visit {#visit-com.aspose.pdf.Page-}
指定されたページで検索を実行します。

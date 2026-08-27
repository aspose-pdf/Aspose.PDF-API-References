---
title: "PageMarkup"
linktitle: "PageMarkup"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページマークアップは {@code MarkupSection} と {@code MarkupParagraph} のコレクションで表されます。"
type: docs
weight: 3420
url: /ja/java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageMarkup

```
public final class PageMarkup extends Object
```

ページマークアップは {@code MarkupSection} と {@code MarkupParagraph} のコレクションで表されます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getNumber](#getNumber--) | 処理されたページ番号を取得します。 |
| [getParagraphs](#getParagraphs--) | ページ上で見つかった {@code MarkupParagraph} のコレクションを取得します。 |
| [getRectangle](#getRectangle--) | 処理されたページ矩形を取得します。 |
| [getSections](#getSections--) | ページ上で見つかった {@code MarkupSection} のコレクションを取得します。 |
| [getTextFragments](#getTextFragments--) | <p> ページ上で見つかった {@code TextFragment} のコレクションを取得します。 </p><hr> {@code TextFragment} オブジェクトは、検索結果のテキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更を可能にします。 |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | 次のセクションの開始テキスト行が、前のセクションの最後の段落の続きとして扱われるかどうかを示す値を取得または設定します。 |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | 次のセクションの開始テキスト行が、前のセクションの最後の段落の続きとして扱われるかどうかを示す値を取得または設定します。 |

### getNumber {#getNumber--}
```
public int getNumber()
```

処理されたページ番号を取得します。

**Returns:**
int 値です。

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

ページ上で見つかった {@code MarkupParagraph} のコレクションを取得します。

**Returns:**
MarkupParagraph インスタンスのリスト

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

処理されたページ矩形を取得します。

**Returns:**
Rectangle オブジェクト

### getSections {#getSections--}
```
public List < MarkupSection > getSections()
```

ページ上で見つかった {@code MarkupSection} のコレクションを取得します。

**Returns:**
MarkupSection インスタンスのリスト

### getTextFragments {#getTextFragments--}
```
public List < TextFragment > getTextFragments()
```

<p> ページ上で見つかった {@code TextFragment} のコレクションを取得します。 </p><hr> {@code TextFragment} オブジェクトは、検索結果のテキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更を可能にします。

**Returns:**
TextFragment インスタンスのリスト

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

次のセクションの開始テキスト行が、前のセクションの最後の段落の続きとして扱われるかどうかを示す値を取得または設定します。

**Returns:**
ブール値

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

次のセクションの開始テキスト行が、前のセクションの最後の段落の続きとして扱われるかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

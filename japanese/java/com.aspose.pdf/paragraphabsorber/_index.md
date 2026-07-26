---
title: "ParagraphAbsorber"
linktitle: "ParagraphAbsorber"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> ページ構造オブジェクト（セクションや段落など）の吸収オブジェクトを表します。テキストのセクションと段落を検索し、アクセスを提供します。"
type: docs
weight: 3470
url: /ja/java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ParagraphAbsorber

```
public class ParagraphAbsorber extends Object
```

<p> セクションや段落などのページ構造オブジェクトの吸収オブジェクトを表します。テキストのセクションと段落を検索し、テキスト座標空間でそれを記述する矩形や多角形へのアクセスを提供します。また、テキストセグメントの検索を行い、構造要素でグループ化された {@code TextFragments} コレクションを介して検索結果へのアクセスを提供します。 </p> この例は、最初の PDF 文書ページ上の各段落の最初のテキストセグメントを見つけてハイライトする方法を示しています。 <p> // Open document Document doc = new Document(\"input.pdf\"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath(\"output.pdf\")); </p> <hr> 検索が完了すると {@code ParagraphAbsorber.PageMarkups} コレクションには {@code MarkupSection} と {@code MarkupParagraph} のコレクションでページ構造を表す {@code PageMarkup} オブジェクトが含まれます。 {@code TextFragment} オブジェクトは検索対象テキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更が可能です。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ParagraphAbsorber](#ParagraphAbsorber--) | ドキュメントまたはページのセクション/段落を検索する {@code ParagraphAbsorber} の新しいインスタンスを初期化します。 |
| [ParagraphAbsorber](#ParagraphAbsorber-int-) | <p> ドキュメントまたはページのセクション/段落を検索する {@code ParagraphAbsorber} の新しいインスタンスを初期化します。 </p> |
| [ParagraphAbsorber](#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-) | ドキュメントまたはページのセクション/段落を検索する {@code ParagraphAbsorber} の新しいインスタンスを初期化します。 |
| [ParagraphAbsorber](#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-) | ドキュメントまたはページのセクション/段落を検索する {@code ParagraphAbsorber} の新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPageMarkups](#getPageMarkups--) | 吸収された {@code PageMarkup} のコレクションを取得します。 |
| [getParagraphAbsorberOptions](#getParagraphAbsorberOptions--) | ParagraphAbsorberOptions を取得します。 |
| [getSectionsSearchDepth](#getSectionsSearchDepth--) | <p> 構造のより細かい要素に対して実行される連続検索の回数を指示する値を取得または設定します。デフォルトの検索深度は 3 です。これは、水平に分割されたセクション（ヘッダー、段落など）に対して 3 回、垂直に分割されたセクション（列）に対して 3 回検索することを意味します。 </p><hr> この値を増やすと、検索結果に目に見える変化はないものの、パフォーマンスが若干低下する可能性があります。この値を減らすと、セクション内の段落の判定が正しく行われなくなる可能性があります。ページ構造の「粗い」要素だけを取得したい場合を除き、デフォルト未満の値に設定することは推奨しません。 |
| [getTextReplaceOptions](#getTextReplaceOptions--) | TextReplaceOptions を取得または設定します。 |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | 次のセクションの開始テキスト行が、前のセクションの最後の段落の続きとして扱われるかどうかを示す値を取得または設定します。 |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | 次のセクションの開始テキスト行が、前のセクションの最後の段落の続きとして扱われるかどうかを示す値を取得または設定します。 |
| [setParagraphAbsorberOptions](#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-) | ParagraphAbsorberOptions を設定します。 |
| [setSectionsSearchDepth](#setSectionsSearchDepth-int-) | <p> 構造のより細かい要素に対して実行される連続検索の回数を指示する値を取得または設定します。デフォルトの検索深度は 3 です。これは、水平に分割されたセクション（ヘッダー、段落など）に対して 3 回、垂直に分割されたセクション（列）に対して 3 回検索することを意味します。 </p><hr> この値を増やすと、検索結果に目に見える変化はないものの、パフォーマンスが若干低下する可能性があります。この値を減らすと、セクション内の段落の判定が正しく行われなくなる可能性があります。ページ構造の「粗い」要素だけを取得したい場合を除き、デフォルト未満の値に設定することは推奨しません。 |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | TextReplaceOptions を取得または設定します。 |
| [visit](#visit-com.aspose.pdf.Document-) | 指定された {@link Document} 上でセクションと段落の検索を実行します。 |
| [visit](#visit-com.aspose.pdf.Page-) | 指定された {@code Page} 上で検索を実行します。 |

### ParagraphAbsorber {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```

ドキュメントまたはページのセクション/段落を検索する {@code ParagraphAbsorber} の新しいインスタンスを初期化します。

### ParagraphAbsorber {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```

<p> ドキュメントまたはページのセクション/段落を検索する {@code ParagraphAbsorber} の新しいインスタンスを初期化します。 </p>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sectionsSearchDepth |  | 構造のより細かい要素に対して実行される連続検索の回数です。 <hr> パラメータの詳細については {@code ParagraphAbsorber.SectionsSearchDepth} プロパティを参照してください。 <hr> |

### ParagraphAbsorber {#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-}
ドキュメントまたはページのセクション/段落を検索する {@code ParagraphAbsorber} の新しいインスタンスを初期化します。

### ParagraphAbsorber {#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-}
ドキュメントまたはページのセクション/段落を検索する {@code ParagraphAbsorber} の新しいインスタンスを初期化します。

### getPageMarkups {#getPageMarkups--}
```
public List < PageMarkup > getPageMarkups()
```

吸収された {@code PageMarkup} のコレクションを取得します。

**Returns:**
PageMarkup インスタンスのリスト

### getParagraphAbsorberOptions {#getParagraphAbsorberOptions--}
```
public final ParagraphAbsorberOptions getParagraphAbsorberOptions()
```

ParagraphAbsorberOptions を取得します。

**Returns:**
ParagraphAbsorberOptions インスタンス

### getSectionsSearchDepth {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```

<p> 構造のより細かい要素に対して実行される連続検索の回数を指示する値を取得または設定します。デフォルトの検索深度は 3 です。これは、水平に分割されたセクション（ヘッダー、段落など）に対して 3 回、垂直に分割されたセクション（列）に対して 3 回検索することを意味します。 </p><hr> この値を増やすと、検索結果に目に見える変化はないものの、パフォーマンスが若干低下する可能性があります。この値を減らすと、セクション内の段落の判定が正しく行われなくなる可能性があります。ページ構造の「粗い」要素だけを取得したい場合を除き、デフォルト未満の値に設定することは推奨しません。

**Returns:**
int 値です。

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public final TextReplaceOptions getTextReplaceOptions()
```

TextReplaceOptions を取得または設定します。

**Returns:**
TextReplaceOptions インスタンス

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

### setParagraphAbsorberOptions {#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-}
ParagraphAbsorberOptions を設定します。

### setSectionsSearchDepth {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```

<p> 構造のより細かい要素に対して実行される連続検索の回数を指示する値を取得または設定します。デフォルトの検索深度は 3 です。これは、水平に分割されたセクション（ヘッダー、段落など）に対して 3 回、垂直に分割されたセクション（列）に対して 3 回検索することを意味します。 </p><hr> この値を増やすと、検索結果に目に見える変化はないものの、パフォーマンスが若干低下する可能性があります。この値を減らすと、セクション内の段落の判定が正しく行われなくなる可能性があります。ページ構造の「粗い」要素だけを取得したい場合を除き、デフォルト未満の値に設定することは推奨しません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
TextReplaceOptions を取得または設定します。

### visit {#visit-com.aspose.pdf.Document-}
指定された {@link Document} 上でセクションと段落の検索を実行します。

### visit {#visit-com.aspose.pdf.Page-}
指定された {@code Page} 上で検索を実行します。

---
title: "MarkupParagraph"
linktitle: "MarkupParagraph"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "段落を表します。"
type: docs
weight: 2880
url: /ja/java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupParagraph

```
public final class MarkupParagraph extends Object
```

段落を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getContinuationPageNumbers](#getContinuationPageNumbers--) | 段落が続くページ番号の一覧です。段落が同じページの次の列で続く場合、開始したページと一致します。 |
| [getFragments](#getFragments--) | <p> 段落の空でない {@code TextFragment} オブジェクトのコレクションです。 </p><hr> {@code TextFragment} オブジェクトは検索結果テキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更を可能にします。 |
| [getFragmentsInternal](#getFragmentsInternal--) |  |
| [getLines](#getLines--) | <p> 段落の行です。各行はテキストフラグメントのリストで表されます。 </p><hr> {@code TextFragment} オブジェクトは検索結果テキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更を可能にします。 |
| [getLinesInternal](#getLinesInternal--) |  |
| [getPoints](#getPoints--) | 段落を表すポリゴンの点です。開始点は段落の左下隅です。次の点は反時計回りの順序です。 |
| [getSecondaryPoints](#getSecondaryPoints--) | 段落の続き部分を表す二次ポリゴンの点です。段落が次の列またはページに続く場合は null にはなりません。開始点は段落の左下隅です。次の点は反時計回りの順序です。 |
| [getText](#getText--) | {@code MarkupParagraph} オブジェクトが表す {@code string} テキストオブジェクトを取得します。 |
| [setText](#setText-java.lang.String-) | 段落テキストを取得または設定します。 |

### getContinuationPageNumbers {#getContinuationPageNumbers--}
```
public final List < Integer > getContinuationPageNumbers()
```

段落が続くページ番号の一覧です。段落が同じページの次の列で続く場合、開始したページと一致します。

**Returns:**
Integer のリスト

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> 段落の空でない {@code TextFragment} オブジェクトのコレクションです。 </p><hr> {@code TextFragment} オブジェクトは検索結果テキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更を可能にします。

**Returns:**
TextFragment インスタンスのリスト

### getFragmentsInternal {#getFragmentsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< TextFragment > getFragmentsInternal()
```



### getLines {#getLines--}
```
public List <com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLines()
```

<p> 段落の行です。各行はテキストフラグメントのリストで表されます。 </p><hr> {@code TextFragment} オブジェクトは検索結果テキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更を可能にします。

**Returns:**
TextFragment インスタンスのリスト

### getLinesInternal {#getLinesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLinesInternal()
```



### getPoints {#getPoints--}
```
public Point [] getPoints()
```

段落を表すポリゴンの点です。開始点は段落の左下隅です。次の点は反時計回りの順序です。

**Returns:**
Point インスタンスの配列

### getSecondaryPoints {#getSecondaryPoints--}
```
public final List < Point []> getSecondaryPoints()
```

段落の続き部分を表す二次ポリゴンの点です。段落が次の列またはページに続く場合は null にはなりません。開始点は段落の左下隅です。次の点は反時計回りの順序です。

**Returns:**
Point[] のリスト

### getText {#getText--}
```
public String getText()
```

{@code MarkupParagraph} オブジェクトが表す {@code string} テキストオブジェクトを取得します。

**Returns:**
文字列値

### setText {#setText-java.lang.String-}
段落テキストを取得または設定します。

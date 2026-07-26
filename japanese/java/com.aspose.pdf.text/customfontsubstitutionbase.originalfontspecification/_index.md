---
title: "CustomFontSubstitutionBase.OriginalFontSpecification"
linktitle: "CustomFontSubstitutionBase.OriginalFontSpecification"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> 元のフォント仕様を表します。 </p> <hr> <p> 元のフォントに関連する情報（例：フラグなど）を提供します。また、置換が行われるかどうかを確認するのに役立つフラグも提供します。 </p>"
type: docs
weight: 20
url: /ja/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> 元のフォント仕様を表します。 </p> <hr> <p> 元のフォントに関連する情報（例：フラグ）を提供します。また、置換がフォントで必ず行われるかどうかを確認するのに役立つフラグも提供し、ユーザーはデフォルトの置換ロジックを上書きできるようにします。 </p>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | 新しい OriginalFontSpecification オブジェクトを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | 元のフォント名を取得します。 |
| [isEmbedded](#isEmbedded--) | フォントが埋め込まれているかどうかを示す値を取得します。 |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> 置換が不可避であることを示す値を取得します。 </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
新しい OriginalFontSpecification オブジェクトを初期化します。

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

元のフォント名を取得します。

**Returns:**
文字列値

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

フォントが埋め込まれているかどうかを示す値を取得します。

**Returns:**
ブール値

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> 置換が不可避であることを示す値を取得します。 </p>

**Returns:**
ブール値 <hr> <p> 元のフォントが存在しない、または特定のタスクのコンテキストで元のフォントを使用できないために置換が要求された場合は true を返します。ユーザーがフラグを無視してフォントを置換しない場合、デフォルトのフォント置換手順が実行されます。ただし、ユーザーは標準のフォント置換手順を変更し、システムにより適したフォントを設定する機会が提供されます。元のフォントが存在し、有効で、ユーザーが置換できる場合は false を返します。 </p>

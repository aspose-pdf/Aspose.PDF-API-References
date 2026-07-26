---
title: "TextReplaceOptions.Scope"
linktitle: "TextReplaceOptions.Scope"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキスト置換操作が適用されるスコープです。デフォルトは REPLACE_FIRST です。この廃止されたオプションは互換性のために保持されています。PdfContentEditor に影響し、他には影響しません。"
type: docs
weight: 5280
url: /ja/java/com.aspose.pdf/textreplaceoptions.scope/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextReplaceOptions.Scope > com.aspose.pdf.TextReplaceOptions.Scope, java.lang.Enum < TextReplaceOptions.Scope >, com.aspose.pdf.TextReplaceOptions.Scope

**All Implemented Interfaces:**
Serializable, Comparable < TextReplaceOptions.Scope >

```
public static enum TextReplaceOptions.Scope extends Enum < TextReplaceOptions.Scope >
```

テキスト置換操作が適用される範囲です。デフォルトは REPLACE_FIRST です。この廃止されたオプションは互換性のために残されています。PdfContentEditor に影響し、TextFragmentAbsorber には影響しません。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [REPLACE_ALL](#REPLACE_ALL) | 影響を受けたすべてのページでテキストのすべての出現箇所を置換します |
| [REPLACE_FIRST](#REPLACE_FIRST) | 影響を受けた各ページでテキストの最初の出現箇所のみを置換します |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### REPLACE_ALL {#REPLACE_ALL}
```
public static final TextReplaceOptions.Scope REPLACE_ALL
```

影響を受けたすべてのページでテキストのすべての出現箇所を置換します

### REPLACE_FIRST {#REPLACE_FIRST}
```
public static final TextReplaceOptions.Scope REPLACE_FIRST
```

影響を受けた各ページでテキストの最初の出現箇所のみを置換します

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
指定された名前でこの型の列挙定数を返します。

### values {#values--}
```
public static TextReplaceOptions.Scope [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列

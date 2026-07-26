---
title: "TextReplaceOptions.FontSizeAdjustment"
linktitle: "TextReplaceOptions.FontSizeAdjustment"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキストのフォントサイズを、包含領域内に収まるように調整するポリシーを指定します。"
type: docs
weight: 5260
url: /ja/java/com.aspose.pdf/textreplaceoptions.fontsizeadjustment/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextReplaceOptions.FontSizeAdjustment > com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment, java.lang.Enum < TextReplaceOptions.FontSizeAdjustment >, com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment

**All Implemented Interfaces:**
Serializable, Comparable < TextReplaceOptions.FontSizeAdjustment >

```
public static enum TextReplaceOptions.FontSizeAdjustment extends Enum < TextReplaceOptions.FontSizeAdjustment >
```

テキストのフォントサイズを、包含領域内に収まるように調整するポリシーを指定します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [None](#None) | フォントサイズは変更されません。 |
| [ScaleToFill](#ScaleToFill) | フォントサイズは調整され（縮小と拡大の両方）、テキストが矩形の境界内にできるだけ収まるようにします。 |
| [ShrinkToFit](#ShrinkToFit) | テキストが境界に収まらないほど大きい場合、フォントサイズは縮小されます。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### None {#None}
```
public static final TextReplaceOptions.FontSizeAdjustment None
```

フォントサイズは変更されません。

### ScaleToFill {#ScaleToFill}
```
public static final TextReplaceOptions.FontSizeAdjustment ScaleToFill
```

フォントサイズは調整され（縮小と拡大の両方）、テキストが矩形の境界内にできるだけ収まるようにします。

### ShrinkToFit {#ShrinkToFit}
```
public static final TextReplaceOptions.FontSizeAdjustment ShrinkToFit
```

テキストが境界に収まらないほど大きい場合、フォントサイズは縮小されます。

### getByValue {#getByValue-int-}
```
public static TextReplaceOptions.FontSizeAdjustment getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
指定された名前でこの型の列挙定数を返します。

### values {#values--}
```
public static TextReplaceOptions.FontSizeAdjustment [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列

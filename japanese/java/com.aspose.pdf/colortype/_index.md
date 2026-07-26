---
title: "ColorType"
linktitle: "ColorType"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページ上の要素のカラータイプを指定します。"
type: docs
weight: 710
url: /ja/java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ColorType > com.aspose.pdf.ColorType, java.lang.Enum < ColorType >, com.aspose.pdf.ColorType

**All Implemented Interfaces:**
Serializable, Comparable < ColorType >

```
public enum ColorType extends Enum < ColorType >
```

ページ上の要素のカラータイプを指定します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [BlackAndWhite](#BlackAndWhite) | 白黒カラータイプ。 |
| [Grayscale](#Grayscale) | グレースケールカラータイプ。 |
| [Rgb](#Rgb) | RGBカラータイプ。 |
| [Undefined](#Undefined) | 未定義のカラータイプ値。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getName](#getName-int-) | <p> 列挙値の文字列名を返します。 </p> <hr> 例: <br> {@code String s = ColorType.getName(ColorType.Grayscale); } |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### BlackAndWhite {#BlackAndWhite}
```
public static final ColorType BlackAndWhite
```

白黒カラータイプ。

### Grayscale {#Grayscale}
```
public static final ColorType Grayscale
```

グレースケールカラータイプ。

### Rgb {#Rgb}
```
public static final ColorType Rgb
```

RGBカラータイプ。

### Undefined {#Undefined}
```
public static final ColorType Undefined
```

未定義のカラータイプ値。

### getByValue {#getByValue-int-}
```
public static ColorType getByValue(int value)
```



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |

### getName {#getName-int-}
```
public static String getName(int value)
```

<p> 列挙値の文字列名を返します。 </p> <hr> 例: <br> {@code String s = ColorType.getName(ColorType.Grayscale); }

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 列挙値 |

**Returns:**
値の名前

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
指定された名前でこの型の列挙定数を返します。

### values {#values--}
```
public static ColorType [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列

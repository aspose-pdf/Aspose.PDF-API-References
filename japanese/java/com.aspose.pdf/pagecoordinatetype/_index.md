---
title: "PageCoordinateType"
linktitle: "PageCoordinateType"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページ座標タイプを説明します。MediaBox = 0、CropBox = 1"
type: docs
weight: 3350
url: /ja/java/com.aspose.pdf/pagecoordinatetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PageCoordinateType > com.aspose.pdf.PageCoordinateType, java.lang.Enum < PageCoordinateType >, com.aspose.pdf.PageCoordinateType

**All Implemented Interfaces:**
Serializable, Comparable < PageCoordinateType >

```
public enum PageCoordinateType extends Enum < PageCoordinateType >
```

ページ座標タイプを説明します。MediaBox = 0、CropBox = 1

## フィールド

| フィールド | 説明 |
| --- | --- |
| [CropBox](#CropBox) | CropBox は、ページ内容がクリップされる領域を定義します。 |
| [MediaBox](#MediaBox) | MediaBox は、ページの幅と高さを指定するために使用されます。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### CropBox {#CropBox}
```
public static final PageCoordinateType CropBox
```

CropBox は、ページ内容がクリップされる領域を定義します。

### MediaBox {#MediaBox}
```
public static final PageCoordinateType MediaBox
```

MediaBox は、ページの幅と高さを指定するために使用されます。

### getByValue {#getByValue-int-}
```
public static PageCoordinateType getByValue(int value)
```



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
指定された名前でこの型の列挙定数を返します。

### values {#values--}
```
public static PageCoordinateType [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列

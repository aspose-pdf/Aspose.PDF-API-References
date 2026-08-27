---
title: "ParagraphPositioningMode"
linktitle: "ParagraphPositioningMode"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページ上の要素の位置を決定するバリアントを指定します。"
type: docs
weight: 3490
url: /ja/java/com.aspose.pdf/paragraphpositioningmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ParagraphPositioningMode > com.aspose.pdf.ParagraphPositioningMode, java.lang.Enum < ParagraphPositioningMode >, com.aspose.pdf.ParagraphPositioningMode

**All Implemented Interfaces:**
Serializable, Comparable < ParagraphPositioningMode >

```
public enum ParagraphPositioningMode extends Enum < ParagraphPositioningMode >
```

ページ上の要素の位置を決定するバリアントを指定します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Absolute](#Absolute) | 位置は Left と Top の値で指定され、前の要素に依存せず、後続の要素の位置にも影響しません。 |
| [Default](#Default) | 位置は以前に配置された要素によって決定されます。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### Absolute {#Absolute}
```
public static final ParagraphPositioningMode Absolute
```

位置は Left と Top の値で指定され、前の要素に依存せず、後続の要素の位置にも影響しません。

### Default {#Default}
```
public static final ParagraphPositioningMode Default
```

位置は以前に配置された要素によって決定されます。

### getByValue {#getByValue-int-}
```
public static ParagraphPositioningMode getByValue(int value)
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
public static ParagraphPositioningMode [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列

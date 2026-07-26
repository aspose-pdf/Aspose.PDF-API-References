---
title: "ExtractImageMode"
linktitle: "ExtractImageMode"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "文書から画像を抽出する際に使用できるさまざまなモードを定義します。"
type: docs
weight: 1360
url: /ja/java/com.aspose.pdf/extractimagemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ExtractImageMode > com.aspose.pdf.ExtractImageMode, java.lang.Enum < ExtractImageMode >, com.aspose.pdf.ExtractImageMode

**All Implemented Interfaces:**
Serializable, Comparable < ExtractImageMode >

```
public enum ExtractImageMode extends Enum < ExtractImageMode >
```

文書から画像を抽出する際に使用できるさまざまなモードを定義します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [ActuallyUsed](#ActuallyUsed) | ページに実際に表示されている画像のみを抽出する画像抽出モードを定義します。 |
| [DefinedInResources](#DefinedInResources) | 特定のページのリソースで定義されたすべての画像を抽出する画像抽出モードを定義します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### ActuallyUsed {#ActuallyUsed}
```
public static final ExtractImageMode ActuallyUsed
```

ページに実際に表示されている画像のみを抽出する画像抽出モードを定義します。

### DefinedInResources {#DefinedInResources}
```
public static final ExtractImageMode DefinedInResources
```

特定のページのリソースで定義されたすべての画像を抽出する画像抽出モードを定義します。

### getByValue {#getByValue-int-}
```
public static ExtractImageMode getByValue(int value)
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
public static ExtractImageMode [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列

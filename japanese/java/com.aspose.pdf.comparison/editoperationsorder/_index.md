---
title: "EditOperationsOrder"
linktitle: "EditOperationsOrder"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "編集操作の順序を指定します。"
type: docs
weight: 40
url: /ja/java/com.aspose.pdf.comparison/editoperationsorder/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EditOperationsOrder > com.aspose.pdf.comparison.EditOperationsOrder, java.lang.Enum < EditOperationsOrder >, com.aspose.pdf.comparison.EditOperationsOrder

**All Implemented Interfaces:**
Serializable, Comparable < EditOperationsOrder >

```
public enum EditOperationsOrder extends Enum < EditOperationsOrder >
```

編集操作の順序を指定します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [DeleteFirst](#DeleteFirst) | 削除操作は挿入操作の前に行われます。 |
| [InsertFirst](#InsertFirst) | 挿入操作は削除操作の前に行われます。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### DeleteFirst {#DeleteFirst}
```
public static final EditOperationsOrder DeleteFirst
```

削除操作は挿入操作の前に行われます。

### InsertFirst {#InsertFirst}
```
public static final EditOperationsOrder InsertFirst
```

挿入操作は削除操作の前に行われます。

### getByValue {#getByValue-int-}
```
public static EditOperationsOrder getByValue(int value)
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
public static EditOperationsOrder [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列

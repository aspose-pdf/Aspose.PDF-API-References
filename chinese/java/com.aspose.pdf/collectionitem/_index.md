---
title: "CollectionItem"
linktitle: "CollectionItem"
second_title: "Aspose.PDF for Java API 参考"
description: "表示集合项类。集合项包含由集合模式描述的数据。"
type: docs
weight: 640
url: /zh/java/com.aspose.pdf/collectionitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionItem

```
public class CollectionItem extends Object
```

表示集合项类。集合项包含由集合模式描述的数据。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAllNames](#getAllNames--) | 获取集合项值的所有名称集合。 |
| [hasName](#hasName-java.lang.String-) | 检查给定名称是否存在于集合项中。 |
| [isEmpty](#isEmpty--) | 获取指示集合项是否为空的值。 |
| [tryGetDateTimeValue](#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | 尝试通过指定名称从集合项中获取 DateTime 类型的值。 |
| [tryGetDoubleValue](#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | 尝试从集合项中获取指定名称的 double 值。 |
| [tryGetIntValue](#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | 尝试从集合项中获取指定名称的整数值。 |
| [tryGetTextValue](#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | 尝试从集合项中获取具有指定名称的文本值。 |

### getAllNames {#getAllNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllNames()
```

获取集合项值的所有名称集合。

**Returns:**
字符串列表

### hasName {#hasName-java.lang.String-}
检查给定名称是否存在于集合项中。

### isEmpty {#isEmpty--}
```
public final boolean isEmpty()
```

获取指示集合项是否为空的值。

**Returns:**
如果集合项为空则返回 true；否则返回 false。此属性在集合项不包含任何值（包括字符串值、双精度值、整数值和日期值）时返回 true。如果集合项中存在这些类型的任何值，此属性返回 false。

### tryGetDateTimeValue {#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
尝试通过指定名称从集合项中获取 DateTime 类型的值。

### tryGetDoubleValue {#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
尝试从集合项中获取指定名称的 double 值。

### tryGetIntValue {#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
尝试从集合项中获取指定名称的整数值。

### tryGetTextValue {#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
尝试从集合项中获取具有指定名称的文本值。

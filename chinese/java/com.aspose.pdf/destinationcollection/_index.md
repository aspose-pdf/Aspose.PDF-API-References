---
title: "DestinationCollection"
linktitle: "DestinationCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "类表示所有目标的集合（一个将名称字符串映射到目标的名称树（参见 12.3.2.3，“Named Destinations”）以及（参见 7.7.4，“Name Dictionary”））中。"
type: docs
weight: 960
url: /zh/java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DestinationCollection

**All Implemented Interfaces:**
Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, Object >>

```
public final class DestinationCollection extends Object implements Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >>
```

表示 PDF 文档中所有目标集合的类（一个名称树，将名称字符串映射到目标（参见 12.3.2.3，“Named Destinations”）以及（参见 7.7.4，“Name Dictionary”）））。

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 添加指定的项。 |
| [clear](#clear--) | 集合是只读的。始终抛出 NotSupportedException 异常。 |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 确定此实例是否包含该对象。 |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | 将集合的元素复制到数组中，从特定的数组索引开始。 |
| [get_Item](#get_Item-int-) | 按索引获取目标对象。 |
| [getExplicitDestination](#getExplicitDestination-java.lang.String-boolean-) | 按名称返回显式目标。 |
| [getPageNumber](#getPageNumber-java.lang.String-boolean-) | 按名称返回目标的页码。 |
| [indexOf](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 返回集合中目标的索引。 |
| [isReadOnly](#isReadOnly--) | 获取一个值，指示集合是否为只读。 |
| [iterator](#iterator--) | 返回枚举器。 |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 移除指定的项。 |
| [size](#size--) | 获取集合中包含的元素数量。 |

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
添加指定的项。

### clear {#clear--}
```
public void clear()
```

集合是只读的。始终抛出 NotSupportedException 异常。

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
确定此实例是否包含该对象。

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
将集合的元素复制到数组中，从特定的数组索引开始。

### get_Item {#get_Item-int-}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object > get_Item(int index)
```

按索引获取目标对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 要获取的目标索引。 |

**Returns:**
目标。

### getExplicitDestination {#getExplicitDestination-java.lang.String-boolean-}
按名称返回显式目标。

### getPageNumber {#getPageNumber-java.lang.String-boolean-}
按名称返回目标的页码。

### indexOf {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
返回集合中目标的索引。

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取一个值，指示集合是否为只读。

**Returns:**
布尔值

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >> iterator()
```

返回枚举器。

**Returns:**
枚举器。

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
移除指定的项。

### size {#size--}
```
public int size()
```

获取集合中包含的元素数量。

**Returns:**
int 值

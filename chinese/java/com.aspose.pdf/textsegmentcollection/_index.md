---
title: "TextSegmentCollection"
linktitle: "TextSegmentCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文本片段集合"
type: docs
weight: 5310
url: /zh/java/com.aspose.pdf/textsegmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegmentCollection

**All Implemented Interfaces:**
Iterable < TextSegment >

```
public final class TextSegmentCollection extends Object implements Iterable < TextSegment >
```

表示文本片段集合

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.TextSegment-) | 在指定索引处添加文本段元素。 |
| [clear](#clear--) | 清除集合中的所有项。 |
| [contains](#contains-com.aspose.pdf.TextSegment-) | 确定集合是否包含特定值。 |
| [copyTo](#copyTo-com.aspose.pdf.TextSegment:A-int-) | 将整个集合复制到兼容的一维数组中，从目标数组的指定索引开始。 |
| [delete](#delete-int-) | 在指定索引处删除文本段元素。 |
| [get_Item](#get_Item-int-) | 获取指定索引处的文本段元素。 |
| [getSyncRoot](#getSyncRoot--) | 获取可用于同步访问集合的对象。 |
| [isReadOnly](#isReadOnly--) | 获取指示集合是否为只读的值 |
| [isSynchronized](#isSynchronized--) | 获取指示对集合的访问是否已同步（线程安全）的值。 |
| [iterator](#iterator--) | 返回整个集合的枚举器。 |
| [remove](#remove-com.aspose.pdf.TextSegment-) | 从集合中删除指定的项。 |
| [size](#size--) | 获取集合中实际包含的 {@code TextSegment} 对象元素的数量。 |

### add {#add-com.aspose.pdf.TextSegment-}
在指定索引处添加文本段元素。

### clear {#clear--}
```
public void clear()
```

清除集合中的所有项。

### contains {#contains-com.aspose.pdf.TextSegment-}
确定集合是否包含特定值。

### copyTo {#copyTo-com.aspose.pdf.TextSegment:A-int-}
将整个集合复制到兼容的一维数组中，从目标数组的指定索引开始。

### delete {#delete-int-}
```
public void delete(int index)
```

在指定索引处删除文本段元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | int 值 |

### get_Item {#get_Item-int-}
```
public TextSegment get_Item(int index)
```

获取指定索引处的文本段元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 集合中的索引。 |

**Returns:**
TextSegment 对象。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取可用于同步访问集合的对象。

**Returns:**
对象元素

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取指示集合是否为只读的值

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

获取指示对集合的访问是否已同步（线程安全）的值。

**Returns:**
布尔值

### iterator {#iterator--}
```
public Iterator < TextSegment > iterator()
```

返回整个集合的枚举器。

**Returns:**
Enumerator 对象。

### remove {#remove-com.aspose.pdf.TextSegment-}
从集合中删除指定的项。

### size {#size--}
```
public int size()
```

获取集合中实际包含的 {@code TextSegment} 对象元素的数量。

**Returns:**
int 值

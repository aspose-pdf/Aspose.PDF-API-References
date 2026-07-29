---
title: "TextFragmentCollection"
linktitle: "TextFragmentCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文本片段集合"
type: docs
weight: 5130
url: /zh/java/com.aspose.pdf/textfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextFragmentCollection

**All Implemented Interfaces:**
Iterable < TextFragment >

```
public final class TextFragmentCollection extends Object implements Iterable < TextFragment >
```

表示文本片段集合

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.TextFragment-) | 在指定的索引处添加文本片段元素。 |
| [clear](#clear--) | 清除集合中的所有项。 |
| [contains](#contains-com.aspose.pdf.TextFragment-) | 确定集合是否包含特定值。 |
| [copyTo](#copyTo-com.aspose.pdf.TextFragment:A-int-) | / * / * 返回整个集合的枚举器。 / * / * |
| [get_Item](#get_Item-int-) | 获取指定索引处的文本片段元素。索引应在范围 [1..n] 内，其中 n 等于文本片段的数量。 |
| [getSyncRoot](#getSyncRoot--) | 获取可用于同步访问集合的对象。 |
| [isReadOnly](#isReadOnly--) | 获取指示集合是否为只读的值 |
| [isSynchronized](#isSynchronized--) | 获取指示对集合的访问是否已同步（线程安全）的值。 |
| [iterator](#iterator--) | 返回整个集合的枚举器。 |
| [remove](#remove-com.aspose.pdf.TextFragment-) | 从集合中删除指定的项。 |
| [size](#size--) | 获取集合中实际包含的 {@code TextFragment} 对象元素的数量。 |

### add {#add-com.aspose.pdf.TextFragment-}
在指定的索引处添加文本片段元素。

### clear {#clear--}
```
public void clear()
```

清除集合中的所有项。

### contains {#contains-com.aspose.pdf.TextFragment-}
确定集合是否包含特定值。

### copyTo {#copyTo-com.aspose.pdf.TextFragment:A-int-}
/ * / * 返回整个集合的枚举器。 / * / *

### get_Item {#get_Item-int-}
```
public TextFragment get_Item(int index)
```

获取指定索引处的文本片段元素。索引应在范围 [1..n] 内，其中 n 等于文本片段的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 集合中的索引。 |

**Returns:**
TextFragment 对象。

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
public Iterator < TextFragment > iterator()
```

返回整个集合的枚举器。

**Returns:**
Enumerator 对象。

### remove {#remove-com.aspose.pdf.TextFragment-}
从集合中删除指定的项。

### size {#size--}
```
public int size()
```

获取集合中实际包含的 {@code TextFragment} 对象元素的数量。

**Returns:**
int 值

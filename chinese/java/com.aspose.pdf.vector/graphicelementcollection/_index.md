---
title: "GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 {@link GraphicElement} 集合。"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
Iterable < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

表示 {@link GraphicElement} 集合。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | 初始化新的集合。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | 向集合中添加一个新的 {@link GraphicElement}。集合中的所有项必须具有相同的 {@code GraphicElement.Parent}（{@link GraphicElement#getParent}）。 |
| [clear](#clear--) | 清空集合。 |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | 确定元素是否在集合中。 |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | 将整个集合复制到兼容的一维数组中，从目标数组的指定索引开始。 |
| [get_Item](#get_Item-int-) | 获取指定索引处的 {@link GraphicElement} 元素。 |
| [isReadOnly](#isReadOnly--) | 获取一个值，指示集合是否为只读。始终返回 false。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | 返回整个集合的枚举器。 |
| [iterator](#iterator--) | 返回整个集合的枚举器。 |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) | 删除 {@link GraphicElement} 元素。 |
| [size](#size--) | 获取集合中实际包含的 {@link GraphicElement} 对象元素的数量。 |
| [toList](#toList--) | 返回内部集合以进行不受限制的枚举。 |
| [toString](#toString--) | 获取此集合的字符串表示形式。 |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

初始化新的集合。

### add {#add-com.aspose.pdf.vector.GraphicElement-}
向集合中添加一个新的 {@link GraphicElement}。集合中的所有项必须具有相同的 {@code GraphicElement.Parent}（{@link GraphicElement#getParent}）。

### clear {#clear--}
```
public final void clear()
```

清空集合。

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
确定元素是否在集合中。

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
将整个集合复制到兼容的一维数组中，从目标数组的指定索引开始。

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

获取指定索引处的 {@link GraphicElement} 元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 集合中的索引。 |

**Returns:**
{@link GraphicElement}。

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

获取一个值，指示集合是否为只读。始终返回 false。

**Returns:**
布尔值

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

返回整个集合的枚举器。

**Returns:**
Enumerator 对象。

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

返回整个集合的枚举器。

**Returns:**
Enumerator 对象。

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
删除 {@link GraphicElement} 元素。

### size {#size--}
```
public final int size()
```

获取集合中实际包含的 {@link GraphicElement} 对象元素的数量。

**Returns:**
int 值

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

返回内部集合以进行不受限制的枚举。

**Returns:**
内部列表

### toString {#toString--}
```
public String toString()
```

获取此集合的字符串表示形式。

**Returns:**
该字符串。

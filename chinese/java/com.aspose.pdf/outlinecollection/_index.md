---
title: "OutlineCollection"
linktitle: "OutlineCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文档大纲层次结构。"
type: docs
weight: 3260
url: /zh/java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineCollection extends Outlines
```

表示文档大纲层次结构。

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | 向集合中添加大纲项。 |
| [clear](#clear--) | 清除集合中的所有项。 |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | 尚未支持。检查集合是否包含给定项。 |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | 将大纲项复制到 System.Array 中，从特定的 System.Array 索引开始。 |
| [delete](#delete--) | 从文档大纲中删除所有大纲项。 |
| [delete](#delete-java.lang.String-) | 从文档大纲中删除所有大纲项。 |
| [get_Item](#get_Item-int-) | 按索引从集合获取大纲项。 |
| [getFirst](#getFirst--) | 获取表示大纲中第一个顶层项的大纲项。 |
| [getLast](#getLast--) | 获取表示大纲中最后一个顶层项的大纲项。 |
| [getSyncRoot](#getSyncRoot--) | 获取一个可用于同步对该集合访问的对象。 |
| [getVisibleCount](#getVisibleCount--) | Count 是所有层级中可见子大纲项数量的总和。注意：请不要将其与集合中项目数量的 Count 混淆。 |
| [hasNext](#hasNext--) |  |
| [isReadOnly](#isReadOnly--) | 获取一个值，指示集合是否为只读。 |
| [isSynchronized](#isSynchronized--) | 获取一个值，指示对该集合的访问是否已同步（线程安全）。 |
| [iterator](#iterator--) | 返回一个遍历集合的枚举器。 |
| [next](#next--) |  |
| [remove](#remove-int-) | 按索引删除项目。 |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | 尚未支持。始终抛出异常。 |
| [size](#size--) | 获取文档大纲中所有层级的纲要项（书签）总数。 |

### add {#add-com.aspose.pdf.OutlineItemCollection-}
向集合中添加大纲项。

### clear {#clear--}
```
public void clear()
```

清除集合中的所有项。

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
尚未支持。检查集合是否包含给定项。

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
将大纲项复制到 System.Array 中，从特定的 System.Array 索引开始。

### delete {#delete--}
```
public void delete()
```

从文档大纲中删除所有大纲项。

### delete {#delete-java.lang.String-}
从文档大纲中删除所有大纲项。

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

按索引从集合获取大纲项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 请求项目的索引。 |

**Returns:**
OutlineItemCollection 对象

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

获取表示大纲中第一个顶层项的大纲项。

**Returns:**
OutlineItemCollection 对象

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

获取表示大纲中最后一个顶层项的大纲项。

**Returns:**
OutlineItemCollection 对象

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取一个可用于同步对该集合访问的对象。

**Returns:**
用于同步的对象

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Count 是所有层级中可见子大纲项数量的总和。注意：请不要将其与集合中项目数量的 Count 混淆。

**Returns:**
int 值

### hasNext {#hasNext--}
```
public boolean hasNext()
```



### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取一个值，指示集合是否为只读。

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

获取一个值，指示对该集合的访问是否已同步（线程安全）。

**Returns:**
布尔值

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

返回一个遍历集合的枚举器。

**Returns:**
一个可用于遍历集合的 System.Collections.IEnumerator 对象。

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

按索引删除项目。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 待删除项目的索引。 |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
尚未支持。始终抛出异常。

### size {#size--}
```
public int size()
```

获取文档大纲中所有层级的纲要项（书签）总数。

**Returns:**
int 值

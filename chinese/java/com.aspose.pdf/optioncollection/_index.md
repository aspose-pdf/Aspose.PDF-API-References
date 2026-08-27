---
title: "OptionCollection"
linktitle: "OptionCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示选择字段选项集合的类。"
type: docs
weight: 3250
url: /zh/java/com.aspose.pdf/optioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OptionCollection

**All Implemented Interfaces:**
Iterable < Option >

```
public final class OptionCollection extends Object implements Iterable < Option >
```

表示选择字段选项集合的类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.Option-) | 向集合中添加项，抛出 . 尚未实现。 |
| [clear](#clear--) | 从集合中移除所有项。 |
| [contains](#contains-com.aspose.pdf.Option-) | 检查集合中是否存在项，抛出 . 尚未实现。 |
| [deleteOption](#deleteOption-java.lang.String-) | 按名称删除选项。 |
| [get_Item](#get_Item-int-) | 按索引获取选项。 |
| [get_Item](#get_Item-java.lang.String-) | 按名称获取选项。 |
| [get](#get-int-) | 按索引获取选项。 |
| [get](#get-java.lang.String-) | 通过选项名称从集合获取选项。 |
| [getSyncRoot](#getSyncRoot--) | 集合的同步对象。 |
| [isReadOnly](#isReadOnly--) | 获取指示集合是否为只读的值。 |
| [isSynchronized](#isSynchronized--) | 如果对象已同步则返回 true。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | 返回集合中选项的枚举器。 |
| [iterator](#iterator--) | 返回集合中选项的枚举器。 |
| [remove](#remove-com.aspose.pdf.Option-) | 从集合中移除项，抛出 . 尚未实现。 |
| [size](#size--) | 获取选项的数量。 |

### add {#add-com.aspose.pdf.Option-}
向集合中添加项，抛出 . 尚未实现。

### clear {#clear--}
```
public void clear()
```

从集合中移除所有项。

### contains {#contains-com.aspose.pdf.Option-}
检查集合中是否存在项，抛出 . 尚未实现。

### deleteOption {#deleteOption-java.lang.String-}
按名称删除选项。

### get_Item {#get_Item-int-}
```
public Option get_Item(int index)
```

按索引获取选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 选项的索引。 |

**Returns:**
指定索引处的选项。

### get_Item {#get_Item-java.lang.String-}
按名称获取选项。

### get {#get-int-}
```
public Option get(int index)
```

按索引获取选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 选项索引。索引应在范围 [1..n] 内，其中 n 为选项数量。 |

**Returns:**
检索到的选项。

### get {#get-java.lang.String-}
通过选项名称从集合获取选项。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

集合的同步对象。

**Returns:**
对象元素

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取指示集合是否为只读的值。

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

如果对象已同步则返回 true。

**Returns:**
布尔值

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

返回集合中选项的枚举器。

**Returns:**
选项枚举器。

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Option > iterator()
```

返回集合中选项的枚举器。

**Returns:**
选项枚举器。

### remove {#remove-com.aspose.pdf.Option-}
从集合中移除项，抛出 . 尚未实现。

### size {#size--}
```
public int size()
```

获取选项的数量。

**Returns:**
int 值

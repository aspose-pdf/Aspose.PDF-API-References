---
title: "XFormCollection"
linktitle: "XFormCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 XFormCollection 集合的类。"
type: docs
weight: 5600
url: /zh/java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFormCollection

**All Implemented Interfaces:**
Iterable < XForm >

```
public final class XFormCollection extends Object implements Iterable < XForm >
```

表示 XFormCollection 集合的类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.XForm-) | 向集合中添加新的 XForm。 |
| [clear](#clear--) | 清除集合中的所有项。 |
| [contains](#contains-com.aspose.pdf.XForm-) | 确定集合是否包含特定值。 |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | 将 XFormCollection 复制到集合中。 |
| [delete](#delete--) | 从集合中删除所有 XForm。 |
| [delete](#delete-int-) | 从集合中删除 XForm。 |
| [delete](#delete-java.lang.String-) | 从集合中删除所有 XForm。 |
| [freeMemory](#freeMemory--) | 清除缓存数据，释放内存等。 |
| [get_Item](#get_Item-int-) | 返回按索引的 XForm。 |
| [get_Item](#get_Item-java.lang.String-) | 返回按名称的 XForm。如果未找到具有指定名称的 XForm，则抛出异常。 |
| [getFormName](#getFormName-com.aspose.pdf.XForm-) | 返回此表单集合中表单的名称 |
| [getSyncRoot](#getSyncRoot--) | 同步对象。 |
| [hasForm](#hasForm-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | 获取一个值，指示集合是否为只读。 |
| [isSynchronized](#isSynchronized--) | 如果对象已同步，则返回 true。 |
| [iterator](#iterator--) | 返回集合枚举器。 |
| [remove](#remove-com.aspose.pdf.XForm-) | 从集合中删除指定的项。 |
| [size](#size--) | 获取集合中 XForm 的计数。 |

### add {#add-com.aspose.pdf.XForm-}
向集合中添加新的 XForm。

### clear {#clear--}
```
public void clear()
```

清除集合中的所有项。

### contains {#contains-com.aspose.pdf.XForm-}
确定集合是否包含特定值。

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
将 XFormCollection 复制到集合中。

### delete {#delete--}
```
public void delete()
```

从集合中删除所有 XForm。

### delete {#delete-int-}
```
public void delete(int index)
```

从集合中删除 XForm。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 必须删除的 XForm 的索引 |

### delete {#delete-java.lang.String-}
从集合中删除所有 XForm。

### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

清除缓存数据，释放内存等。

### get_Item {#get_Item-int-}
```
public XForm get_Item(int index)
```

返回按索引的 XForm。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | XFormCollection 的索引。XForm 的编号从 1 开始 |

**Returns:**
检索到的 XForm

### get_Item {#get_Item-java.lang.String-}
返回按名称的 XForm。如果未找到具有指定名称的 XForm，则抛出异常。

### getFormName {#getFormName-com.aspose.pdf.XForm-}
返回此表单集合中表单的名称

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

同步对象。

**Returns:**
对象

### hasForm {#hasForm-java.lang.String-}


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

如果对象已同步，则返回 true。

**Returns:**
布尔型

### iterator {#iterator--}
```
public Iterator < XForm > iterator()
```

返回集合枚举器。

**Returns:**
集合的枚举器

### remove {#remove-com.aspose.pdf.XForm-}
从集合中删除指定的项。

### size {#size--}
```
public int size()
```

获取集合中 XForm 的计数。

**Returns:**
int 值

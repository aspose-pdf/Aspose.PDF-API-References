---
title: "ActionCollection"
linktitle: "ActionCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "操作集合"
type: docs
weight: 40
url: /zh/java/com.aspose.pdf/actioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public final class ActionCollection extends Object implements Iterable < PdfAction >
```

操作集合

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | 向集合中添加新操作。 |
| [clear](#clear--) | 清除集合。 |
| [contains](#contains-com.aspose.pdf.PdfAction-) | 尚未支持。如果给定项目存在于集合中则返回 true。 |
| [copyTo](#copyTo-com.aspose.pdf.PdfAction:A-int-) | 将操作数组复制到集合中。 |
| [delete](#delete--) | 删除所有操作。 |
| [delete](#delete-int-) | 按索引从集合中移除操作。 |
| [get_Item](#get_Item-int-) | 通过索引获取操作。 |
| [getSyncRoot](#getSyncRoot--) | 获取同步对象。 |
| [isReadOnly](#isReadOnly--) | 如果集合是只读的，则返回 true。 |
| [isSynchronized](#isSynchronized--) | 如果对象已同步，则返回 true。 |
| [iterator](#iterator--) | / * / * 返回集合的枚举器。 / * / * / * |
| [remove](#remove-com.aspose.pdf.PdfAction-) | * 尚未支持。 从集合中删除项。 |
| [size](#size--) | 集合中操作的计数。 |

### add {#add-com.aspose.pdf.PdfAction-}
向集合中添加新操作。

### clear {#clear--}
```
public void clear()
```

清除集合。

### contains {#contains-com.aspose.pdf.PdfAction-}
尚未支持。如果给定项目存在于集合中则返回 true。

### copyTo {#copyTo-com.aspose.pdf.PdfAction:A-int-}
将操作数组复制到集合中。

### delete {#delete--}
```
public void delete()
```

删除所有操作。

### delete {#delete-int-}
```
public void delete(int index)
```

按索引从集合中移除操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 要移除的操作索引。 |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

通过索引获取操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 操作的索引。 |

**Returns:**
已检索的操作。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取同步对象。

**Returns:**
Object 值

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

如果集合是只读的，则返回 true。

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

如果对象已同步，则返回 true。

**Returns:**
布尔值

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator()
```

/ * / * 返回集合的枚举器。 / * / * / *

**Returns:**
集合枚举器。 /

### remove {#remove-com.aspose.pdf.PdfAction-}
* Not supported yet. Removes item from collection.

### size {#size--}
```
public int size()
```

集合中操作的计数。

**Returns:**
int 值

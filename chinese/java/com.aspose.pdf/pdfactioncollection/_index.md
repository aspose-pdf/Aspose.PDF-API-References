---
title: "PdfActionCollection"
linktitle: "PdfActionCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "类描述操作列表。"
type: docs
weight: 3680
url: /zh/java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public class PdfActionCollection extends Object implements Iterable < PdfAction >
```

类描述操作列表。

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | 向操作列表添加操作。 |
| [delete](#delete-int-) | 按索引移除操作。 |
| [get_Item](#get_Item-int-) | 通过索引获取操作。 |
| [getCount](#getCount--) | 获取操作的计数。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | 内部方法 |
| [iterator](#iterator--) | 获取枚举器。 |

### add {#add-com.aspose.pdf.PdfAction-}
向操作列表添加操作。

### delete {#delete-int-}
```
public void delete(int index)
```

按索引移除操作。

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
| 索引 |  | 操作索引值。 |

**Returns:**
如果找到则返回 PdfAction 索引；否则抛出 @throws IndexOutOfRangeException IndexOutOfRangeException

### getCount {#getCount--}
```
public int getCount()
```

获取操作的计数。

**Returns:**
int 值

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator_Rename_Namesake()
```

内部方法

**Returns:**
内部对象。

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< PdfAction > iterator()
```

获取枚举器。

**Returns:**
PDfAction 枚举。

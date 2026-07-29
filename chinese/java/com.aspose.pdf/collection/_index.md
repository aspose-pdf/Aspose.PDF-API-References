---
title: "集合"
linktitle: "集合"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 Collection（12.3.5 Collections） 类。"
type: docs
weight: 610
url: /zh/java/com.aspose.pdf/collection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection com.aspose.pdf.Collection, com.aspose.pdf.EmbeddedFileCollection, com.aspose.pdf.Collection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class Collection extends EmbeddedFileCollection
```

表示 Collection（12.3.5 Collections） 类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Collection](#Collection--) | 初始化新的 Collection 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDefaultEntry](#getDefaultEntry--) | 默认嵌入文件名。 |
| [getSchema](#getSchema--) | 获取文档集合的 "Schema"。 |
| [getSortedCollection](#getSortedCollection--) | 获取按规范排序的文件集合。 |

### Collection {#Collection--}
```
public Collection()
```

初始化新的 Collection 对象。

### getDefaultEntry {#getDefaultEntry--}
```
public String getDefaultEntry()
```

默认嵌入文件名。

**Returns:**
字符串对象

### getSchema {#getSchema--}
```
public final CollectionSchema getSchema()
```

获取文档集合的 "Schema"。

**Returns:**
CollectionSchema

### getSortedCollection {#getSortedCollection--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< FileSpecification > getSortedCollection()
```

获取按规范排序的文件集合。

**Returns:**
已排序文件的列表。

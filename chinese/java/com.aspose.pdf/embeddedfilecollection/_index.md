---
title: "EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "表示嵌入文件集合的类。"
type: docs
weight: 1200
url: /zh/java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class EmbeddedFileCollection extends Object implements Iterable < FileSpecification >
```

表示嵌入文件集合的类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.FileSpecification-) | 向集合中添加嵌入文件规范。 |
| [add](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | 使用指定的键将文件添加到嵌入文件中。 |
| [clear](#clear--) | 从文档中移除所有嵌入文件。 |
| [contains](#contains-com.aspose.pdf.FileSpecification-) | 确定集合是否包含指定的 FileSpecification。此功能不受支持。 |
| [copyTo](#copyTo-com.aspose.pdf.FileSpecification:A-int-) | 将 FileSpecification 对象数组复制到集合中。 |
| [delete](#delete--) | 从文档中移除所有嵌入文件。 |
| [delete](#delete-java.lang.String-) | 从文档中移除所有嵌入文件。 |
| [deleteByKey](#deleteByKey-java.lang.String-) | 根据集合中的键从集合中删除文件。 |
| [findByName](#findByName-java.lang.String-) | 按名称返回嵌入文件。 |
| [get_Item](#get_Item-int-) | 按索引获取嵌入文件。 |
| [get_Item](#get_Item-java.lang.String-) | 按名称获取嵌入文件。 |
| [getKeys](#getKeys--) | 返回文件附件键的列表。 |
| [getSyncRoot](#getSyncRoot--) | 获取一个可用于同步对该集合访问的对象。 |
| [isEmbeddedFilesExist](#isEmbeddedFilesExist--) | 检查是否存在嵌入文件结构。如果结构存在返回 TRUE，否则返回 FALSE。如果文档从未包含嵌入文件，则该结构未创建且不存在。 |
| [isReadOnly](#isReadOnly--) | 确定集合是否只读。始终返回 false。 |
| [isSynchronized](#isSynchronized--) | 获取一个值，指示对该集合的访问是否已同步（线程安全）。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | 返回集合枚举器。 |
| [iterator](#iterator--) | 返回集合枚举器。 |
| [remove](#remove-com.aspose.pdf.FileSpecification-) | 从集合中移除指定的 FileSpecification。此功能不受支持。 |
| [size](#size--) | 获取集合中嵌入文件的数量。 |

### add {#add-com.aspose.pdf.FileSpecification-}
向集合中添加嵌入文件规范。

### add {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
使用指定的键将文件添加到嵌入文件中。

### clear {#clear--}
```
public void clear()
```

从文档中移除所有嵌入文件。

### contains {#contains-com.aspose.pdf.FileSpecification-}
确定集合是否包含指定的 FileSpecification。此功能不受支持。

### copyTo {#copyTo-com.aspose.pdf.FileSpecification:A-int-}
将 FileSpecification 对象数组复制到集合中。

### delete {#delete--}
```
public void delete()
```

从文档中移除所有嵌入文件。

### delete {#delete-java.lang.String-}
从文档中移除所有嵌入文件。

### deleteByKey {#deleteByKey-java.lang.String-}
根据集合中的键从集合中删除文件。

### findByName {#findByName-java.lang.String-}
按名称返回嵌入文件。

### get_Item {#get_Item-int-}
```
public FileSpecification get_Item(int index)
```

按索引获取嵌入文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 嵌入文件的索引。编号从 1 开始。 |

**Returns:**
检索到的嵌入文件规范

### get_Item {#get_Item-java.lang.String-}
按名称获取嵌入文件。

### getKeys {#getKeys--}
```
public final List < String > getKeys()
```

返回文件附件键的列表。

**Returns:**
String 值的列表

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取一个可用于同步对该集合访问的对象。

**Returns:**
用于同步的对象

### isEmbeddedFilesExist {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```

检查是否存在嵌入文件结构。如果结构存在返回 TRUE，否则返回 FALSE。如果文档从未包含嵌入文件，则该结构未创建且不存在。

**Returns:**
布尔值

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

确定集合是否只读。始终返回 false。

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

获取一个值，指示对该集合的访问是否已同步（线程安全）。

**Returns:**
布尔值

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< FileSpecification > iterator_Rename_Namesake()
```

返回集合枚举器。

**Returns:**
集合的枚举器。

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< FileSpecification > iterator()
```

返回集合枚举器。

**Returns:**
集合的枚举器。

### remove {#remove-com.aspose.pdf.FileSpecification-}
从集合中移除指定的 FileSpecification。此功能不受支持。

### size {#size--}
```
public int size()
```

获取集合中嵌入文件的数量。

**Returns:**
int 值

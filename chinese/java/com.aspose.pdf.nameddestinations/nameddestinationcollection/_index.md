---
title: "NamedDestinationCollection"
linktitle: "NamedDestinationCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "类表示所有目标的集合（一个将名称字符串映射到目标的名称树（参见 12.3.2.3，“Named Destinations”）以及（参见 7.7.4，“Name Dictionary”））中。"
type: docs
weight: 30
url: /zh/java/com.aspose.pdf.nameddestinations/nameddestinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.nameddestinations.NamedDestinationCollection

**All Implemented Interfaces:**
INamedDestinationCollection

```
public class NamedDestinationCollection extends Object implements INamedDestinationCollection
```

表示 PDF 文档中所有目标集合的类（一个名称树，将名称字符串映射到目标（参见 12.3.2.3，“Named Destinations”）以及（参见 7.7.4，“Name Dictionary”）））。

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-java.lang.String-com.aspose.pdf.IAppointment-) | 添加新的已命名目标。 |
| [get_Item](#get_Item-java.lang.String-) | 根据名称获取或设置约会。 |
| [getNames](#getNames--) | 目标的名称列表。 |
| [isEmpty](#isEmpty--) |  |
| [remove](#remove-java.lang.String-) | 删除已命名目标。 |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.IAppointment-) | 根据名称获取或设置约会。 |
| [size](#size--) | 已命名目标的计数。 |

### add {#add-java.lang.String-com.aspose.pdf.IAppointment-}
添加新的已命名目标。

### get_Item {#get_Item-java.lang.String-}
根据名称获取或设置约会。

### getNames {#getNames--}
```
public String [] getNames()
```

目标的名称列表。

**Returns:**
String 值的数组

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```



**Returns:**
布尔值

### remove {#remove-java.lang.String-}
删除已命名目标。

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.IAppointment-}
根据名称获取或设置约会。

### size {#size--}
```
public int size()
```

已命名目标的计数。

**Returns:**
int 值

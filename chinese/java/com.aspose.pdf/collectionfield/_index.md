---
title: "CollectionField"
linktitle: "CollectionField"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文档集合模式字段类。"
type: docs
weight: 620
url: /zh/java/com.aspose.pdf/collectionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionField

```
public class CollectionField extends Object
```

表示文档集合模式字段类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getE](#getE--) | 获取一个标志，指示交互式 PDF 处理器是否应提供对编辑字段值的支持。默认值：false |
| [getFiledType](#getFiledType--) | 获取模式集合中字段值的类型。此字段描述对应于 {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}) 的值类型。 |
| [getN](#getN--) | 获取交互式 PDF 处理器向用户呈现的文本字段名称 |
| [getO](#getO--) | 获取字段名称在用户界面中的相对顺序。字段应由交互式 PDF 处理器按升序排序。 |
| [getSubtype](#getSubtype--) | 获取模式集合中字段值的子类型。此字典描述的集合字段或文件相关字段的子类型。此条目标识应存储在字段中的数据类型。 |
| [getV](#getV--) | 获取字段在用户界面中的初始可见性。默认值：true。 |

### getE {#getE--}
```
public final boolean getE()
```

获取一个标志，指示交互式 PDF 处理器是否应提供对编辑字段值的支持。默认值：false

**Returns:**
布尔值

### getFiledType {#getFiledType--}
```
public final int getFiledType()
```

获取模式集合中字段值的类型。此字段描述对应于 {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}) 的值类型。

**Returns:**
FieldValueType 元素

### getN {#getN--}
```
public final String getN()
```

获取交互式 PDF 处理器向用户呈现的文本字段名称

**Returns:**
字符串值

### getO {#getO--}
```
public final Integer [] getO()
```

获取字段名称在用户界面中的相对顺序。字段应由交互式 PDF 处理器按升序排序。

**Returns:**
Integer 数组

### getSubtype {#getSubtype--}
```
public final int getSubtype()
```

获取模式集合中字段值的子类型。此字典描述的集合字段或文件相关字段的子类型。此条目标识应存储在字段中的数据类型。

**Returns:**
CollectionFieldSubtype 元素

### getV {#getV--}
```
public final boolean getV()
```

获取字段在用户界面中的初始可见性。默认值：true。

**Returns:**
布尔值

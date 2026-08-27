---
title: "ElementListImplementation"
linktitle: "ElementListImplementation"
second_title: "Aspose.PDF for Java API 参考"
description:
type: docs
weight: 50
url: /zh/java/com.aspose.pdf.tagged.logicalstructure/elementlistimplementation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList com.aspose.pdf.tagged.logicalstructure.ElementListImplementation, com.aspose.pdf.tagged.logicalstructure.ElementList, com.aspose.pdf.tagged.logicalstructure.ElementListImplementation

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public class ElementListImplementation extends ElementList
```



## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ElementListImplementation](#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | 向列表添加元素。 |
| [getCount](#getCount--) | 获取 ElementList 中的元素数量。 |
| [item](#item-int-) | 检索给定索引处的元素。 |
| [iterator](#iterator--) | 获取遍历元素集合的枚举器。 |

### ElementListImplementation {#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
向列表添加元素。

### getCount {#getCount--}
```
public int getCount()
```

获取 ElementList 中的元素数量。

**Returns:**
int 值

### item {#item-int-}
```
public Element item(int index)
```

检索给定索引处的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  |  |

**Returns:**
集合中具有指定索引的 /Aspose.Pdf.LogicalStructure.Element。如果索引大于或等于列表中的元素数量，则返回 null。

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

获取遍历元素集合的枚举器。

**Returns:**
用于遍历元素集合的枚举器。

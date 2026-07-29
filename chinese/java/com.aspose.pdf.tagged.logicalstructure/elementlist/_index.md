---
title: "ElementList"
linktitle: "ElementList"
second_title: "Aspose.PDF for Java API 参考"
description: "表示元素的有序集合。"
type: docs
weight: 40
url: /zh/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public abstract class ElementList extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

表示元素的有序集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | 向列表添加元素。 |
| [get_Item](#get_Item-int-) |  |
| [getCount](#getCount--) | 获取 ElementList 中的元素数量。 |
| [insertElement](#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | 向列表插入元素。 |
| [item](#item-int-) | 检索给定索引处的元素。 |
| [iterator](#iterator--) | 获取遍历元素集合的枚举器。 |
| [removeAt](#removeAt-int-) | 从列表中移除元素。 |
| [removeElement](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | 从列表中移除元素。 |

### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
向列表添加元素。

### get_Item {#get_Item-int-}
```
public Element get_Item(int index)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  |  |

### getCount {#getCount--}
```
public abstract int getCount()
```

获取 ElementList 中的元素数量。

**Returns:**
int 值

### insertElement {#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
向列表插入元素。

### item {#item-int-}
```
public abstract Element item(int index)
```

检索给定索引处的元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 列表中元素的索引。 |

**Returns:**
集合中具有指定索引的 {@code /Aspose.Pdf.LogicalStructure.Element}。如果 {@code index} 大于或等于列表中元素的数量，则返回 null。

### iterator {#iterator--}
```
public abstract com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

获取遍历元素集合的枚举器。

**Returns:**
用于遍历元素集合的枚举器。

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

从列表中移除元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 要移除的索引。 |

### removeElement {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
从列表中移除元素。

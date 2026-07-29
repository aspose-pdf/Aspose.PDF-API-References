---
title: "ElementCollection"
linktitle: "ElementCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "基础逻辑结构元素的集合。"
type: docs
weight: 1190
url: /zh/java/com.aspose.pdf/elementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ElementCollection

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public class ElementCollection extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

基础逻辑结构元素的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item](#get_Item-int-) | 通过索引获取 Element。 |
| [getCount](#getCount--) | 元素的计数。 |
| [iterator](#iterator--) | 返回一个遍历集合的枚举器。 |
| [remove](#remove-com.aspose.pdf.Element-) | 从集合中移除项。 |

### get_Item {#get_Item-int-}
```
public final Element get_Item(int index)
```

通过索引获取 Element。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 元素的索引。 |

**Returns:**
检索到的元素。

### getCount {#getCount--}
```
public final int getCount()
```

元素的计数。

**Returns:**
int 值

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

返回一个遍历集合的枚举器。

**Returns:**
类型为 {@link Element} 的元素枚举器。

### remove {#remove-com.aspose.pdf.Element-}
从集合中移除项。

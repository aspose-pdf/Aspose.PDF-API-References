---
title: "PDF3DCrossSectionArray"
linktitle: "PDF3DCrossSectionArray"
second_title: "Aspose.PDF for Java API 参考"
description: "类 PDF3DCrossSectionArray。"
type: docs
weight: 3600
url: /zh/java/com.aspose.pdf/pdf3dcrosssectionarray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DCrossSectionArray

```
public class PDF3DCrossSectionArray extends Object
```

类 PDF3DCrossSectionArray。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PDF3DCrossSectionArray](#PDF3DCrossSectionArray-com.aspose.pdf.IDocument-) | 初始化 {@code PDF3DCrossSectionArray} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.PDF3DCrossSection-) | 将指定的横截面添加到视图数组中。 |
| [get_Item](#get_Item-int-) | 获取或设置指定索引处的 {@code PDF3DCrossSection}。 |
| [getCount](#getCount--) | 获取横截面计数。 |
| [removeAll](#removeAll--) | 从数组中移除所有横截面。 |
| [removeAt](#removeAt-int-) | 在指定索引处从数组中移除横截面。 |
| [set_Item](#set_Item-int-com.aspose.pdf.PDF3DCrossSection-) | 获取或设置指定索引处的 {@code PDF3DCrossSection}。 |

### PDF3DCrossSectionArray {#PDF3DCrossSectionArray-com.aspose.pdf.IDocument-}
初始化 {@code PDF3DCrossSectionArray} 类的新实例。

### add {#add-com.aspose.pdf.PDF3DCrossSection-}
将指定的横截面添加到视图数组中。

### get_Item {#get_Item-int-}
```
public PDF3DCrossSection get_Item(int index)
```

获取或设置指定索引处的 {@code PDF3DCrossSection}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 索引。 |

**Returns:**
横截面。@throws IndexOutOfRangeException 无效索引：索引应在范围 [1..n] 内，其中 n 等于横截面计数。

### getCount {#getCount--}
```
public int getCount()
```

获取横截面计数。

**Returns:**
int value：横截面计数。

### removeAll {#removeAll--}
```
public void removeAll()
```

从数组中移除所有横截面。

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

在指定索引处从数组中移除横截面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 数组中被移除的横截面的索引。@throws IndexOutOfRangeException 无效索引：索引应在范围 [1..n] 内，其中 n 等于横截面计数。 |

### set_Item {#set_Item-int-com.aspose.pdf.PDF3DCrossSection-}
获取或设置指定索引处的 {@code PDF3DCrossSection}。

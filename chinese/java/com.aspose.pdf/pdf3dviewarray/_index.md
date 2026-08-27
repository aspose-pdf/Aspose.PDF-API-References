---
title: "PDF3DViewArray"
linktitle: "PDF3DViewArray"
second_title: "Aspose.PDF for Java API 参考"
description: "类 PDF3DViewArray。"
type: docs
weight: 3660
url: /zh/java/com.aspose.pdf/pdf3dviewarray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DViewArray

```
public class PDF3DViewArray extends Object
```

类 PDF3DViewArray。

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.PDF3DView-) | 添加指定的视图。 |
| [get_Item](#get_Item-int-) | 获取或设置位于指定索引的视图数组中的 {@code PDF3DView}。 |
| [getCount](#getCount--) | 获取视图计数。 |
| [removeAll](#removeAll--) | 移除所有视图。 |
| [removeAt](#removeAt-int-) | 在指定索引处从视图数组中移除视图。 |
| [set_Item](#set_Item-int-com.aspose.pdf.PDF3DView-) | 获取或设置位于指定索引的视图数组中的 {@code PDF3DView}。 |

### add {#add-com.aspose.pdf.PDF3DView-}
添加指定的视图。

### get_Item {#get_Item-int-}
```
public PDF3DView get_Item(int index)
```

获取或设置位于指定索引的视图数组中的 {@code PDF3DView}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 索引。 |

**Returns:**
PDF3DView。 @throws IndexOutOfRangeException 索引无效：索引应在范围 [1..n] 内，其中 n 等于视图计数。

### getCount {#getCount--}
```
public int getCount()
```

获取视图计数。

**Returns:**
int value：视图计数。

### removeAll {#removeAll--}
```
public void removeAll()
```

移除所有视图。

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

在指定索引处从视图数组中移除视图。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 视图索引。 @throws IndexOutOfRangeException 索引无效：索引应在范围 [1..n] 内，其中 n 等于视图计数。 |

### set_Item {#set_Item-int-com.aspose.pdf.PDF3DView-}
获取或设置位于指定索引的视图数组中的 {@code PDF3DView}。

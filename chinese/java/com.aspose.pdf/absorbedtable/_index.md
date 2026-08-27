---
title: "AbsorbedTable"
linktitle: "AbsorbedTable"
second_title: "Aspose.PDF for Java API 参考"
description: "表示页面上存在的表格"
type: docs
weight: 30
url: /zh/java/com.aspose.pdf/absorbedtable/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedTable

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedTable >

```
public class AbsorbedTable extends Object implements ITableElement , Comparable < AbsorbedTable >
```

表示页面上存在的表格

## 方法

| 方法 | 描述 |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedTable-) | 比较当前的 AbsorbedTable 对象与另一个 AbsorbedTable 对象，并返回一个整数，指示当前对象在排序顺序中是位于前面、后面，还是与另一个对象处于相同位置。 |
| [getPageNum](#getPageNum--) | 获取包含此表格的页码 |
| [getRectangle](#getRectangle--) | 获取描述表格在页面上位置的矩形 |
| [getRowList](#getRowList--) | <p> 获取只读 IList，包含表格的行 </p> |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedTable-}
比较当前的 AbsorbedTable 对象与另一个 AbsorbedTable 对象，并返回一个整数，指示当前对象在排序顺序中是位于前面、后面，还是与另一个对象处于相同位置。

### getPageNum {#getPageNum--}
```
public int getPageNum()
```

获取包含此表格的页码

**Returns:**
int 值

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取描述表格在页面上位置的矩形

**Returns:**
Rectangle 对象

### getRowList {#getRowList--}
```
public List < AbsorbedRow > getRowList()
```

<p> 获取只读 IList，包含表格的行 </p>

**Returns:**
{@code IGenericList<AbsorbedRow>} 对象

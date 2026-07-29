---
title: "AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "Aspose.PDF for Java API 参考"
description: "表示页面上存在的表格单元格"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedCell

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedCell >

```
public class AbsorbedCell extends Object implements ITableElement , Comparable < AbsorbedCell >
```

表示页面上存在的表格单元格

## 方法

| 方法 | 描述 |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedCell-) | 比较当前的 AbsorbedCell 对象与另一个 AbsorbedCell 对象，并返回一个整数，指示当前对象在排序顺序中是位于前面、后面，还是与另一个对象处于相同位置。 |
| [getBorderInfo](#getBorderInfo--) | 当 FlowEngine.TableAbsorber.UseFlowEngine 属性设置为 true 时，返回单元格的边框信息。 |
| [getColSpan](#getColSpan--) | 当 TableAbsorber.UseFlowEngine 属性设置为 true 时，返回单元格应跨越的列数。 |
| [getRectangle](#getRectangle--) | 获取描述单元格在页面上位置的矩形 |
| [getTextFragments](#getTextFragments--) | 获取 {@code TextFragment} 对象的集合，这些对象描述单元格中包含的文本 |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedCell-}
比较当前的 AbsorbedCell 对象与另一个 AbsorbedCell 对象，并返回一个整数，指示当前对象在排序顺序中是位于前面、后面，还是与另一个对象处于相同位置。

### getBorderInfo {#getBorderInfo--}
```
public final BorderInfo getBorderInfo()
```

当 FlowEngine.TableAbsorber.UseFlowEngine 属性设置为 true 时，返回单元格的边框信息。

**Returns:**
BorderInfo 实例

### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

当 TableAbsorber.UseFlowEngine 属性设置为 true 时，返回单元格应跨越的列数。

**Returns:**
int 值

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取描述单元格在页面上位置的矩形

**Returns:**
Rectangle 对象

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

获取 {@code TextFragment} 对象的集合，这些对象描述单元格中包含的文本

**Returns:**
TextFragmentCollection 对象

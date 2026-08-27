---
title: "行"
linktitle: "行"
second_title: "Aspose.PDF for Java API 参考"
description: "表示表格的一行。"
type: docs
weight: 4330
url: /zh/java/com.aspose.pdf/row/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Row

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Row extends Object implements com.aspose.ms.System.ICloneable
```

表示表格的一行。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Row](#Row--) | 初始化 Row 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | 克隆该行。 |
| [getBackgroundColor](#getBackgroundColor--) | 获取背景颜色。 |
| [getBorder](#getBorder--) | 获取边框。 |
| [getCells](#getCells--) | 获取该行的 getCells()。 |
| [getDefaultCellBorder](#getDefaultCellBorder--) | 获取默认单元格边框； |
| [getDefaultCellPadding](#getDefaultCellPadding--) | 获取行 getCells() 的默认边距 |
| [getDefaultCellTextState](#getDefaultCellTextState--) | 获取或设置行 getCells() 的默认文本状态 获取行 getCells() 的默认文本状态 |
| [getFixedRowHeight](#getFixedRowHeight--) | 获取固定行高 - 行可能具有固定高度； |
| [getMinRowHeight](#getMinRowHeight--) | 获取行的高度； |
| [getVerticalAlignment](#getVerticalAlignment--) | 获取或设置垂直对齐方式。 |
| [isInNewPage](#isInNewPage--) | 获取固定行是否在新页面 - 带有此属性的页面应打印到下一页，默认 false； |
| [isRowBroken](#isRowBroken--) | 获取行是否可以在两页之间断开 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 设置背景颜色。 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 设置边框。 |
| [setCells](#setCells-com.aspose.pdf.Cells-) | 设置该行的 getCells()。 |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | 设置默认单元格边框； |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | 设置行 getCells() 的默认边距 |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 设置行 getCells() 的默认文本状态 |
| [setFixedRowHeight](#setFixedRowHeight-double-) | 设置固定行高 - 行可能具有固定高度； |
| [setInNewPage](#setInNewPage-boolean-) | 设置行是否可以在两页之间断开 |
| [setMinRowHeight](#setMinRowHeight-double-) | 设置行的高度； |
| [setRowBroken](#setRowBroken-boolean-) | 设置行是否可以在两页之间断开 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 获取或设置垂直对齐方式。 |

### Row {#Row--}
```
public Row()
```

初始化 Row 类的新实例。

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆该行。

**Returns:**
克隆的对象。

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

获取背景颜色。

**Returns:**
颜色值

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

获取边框。

**Returns:**
BorderInfo 值

### getCells {#getCells--}
```
public Cells getCells()
```

获取该行的 getCells()。

**Returns:**
getCells() 值

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```

获取默认单元格边框；

**Returns:**
BorderInfo 值

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```

获取行 getCells() 的默认边距

**Returns:**
MarginInfo 值

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

获取或设置行 getCells() 的默认文本状态 获取行 getCells() 的默认文本状态

**Returns:**
TextState 值

### getFixedRowHeight {#getFixedRowHeight--}
```
public double getFixedRowHeight()
```

获取固定行高 - 行可能具有固定高度；

**Returns:**
double 值

### getMinRowHeight {#getMinRowHeight--}
```
public double getMinRowHeight()
```

获取行的高度；

**Returns:**
double 值

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

获取或设置垂直对齐方式。

**Returns:**
VerticalAlignment 元素 @see VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

获取固定行是否在新页面 - 带有此属性的页面应打印到下一页，默认 false；

**Returns:**
布尔值

### isRowBroken {#isRowBroken--}
```
public boolean isRowBroken()
```

获取行是否可以在两页之间断开

**Returns:**
布尔值

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
设置背景颜色。

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
设置边框。

### setCells {#setCells-com.aspose.pdf.Cells-}
设置该行的 getCells()。

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
设置默认单元格边框；

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
设置行 getCells() 的默认边距

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
设置行 getCells() 的默认文本状态

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public void setFixedRowHeight(double value)
```

设置固定行高 - 行可能具有固定高度；

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

设置行是否可以在两页之间断开

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMinRowHeight {#setMinRowHeight-double-}
```
public void setMinRowHeight(double value)
```

设置行的高度；

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setRowBroken {#setRowBroken-boolean-}
```
public void setRowBroken(boolean value)
```

设置行是否可以在两页之间断开

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
获取或设置垂直对齐方式。

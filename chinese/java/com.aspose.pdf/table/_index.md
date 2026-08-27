---
title: "Table"
linktitle: "Table"
second_title: "Aspose.PDF for Java API 参考"
description: "表示可以添加到页面的表格。"
type: docs
weight: 4790
url: /zh/java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Table, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Table

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Table extends BaseParagraph
```

表示可以添加到页面的表格。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Table](#Table--) | 默认 ctor |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | / * / * 将一维数据数组导入表格。导入时每个数组项对应一个单元格，/ * 从参数中定义的行和列开始。导入过程中，如果检测到必要的行 / * 仍然缺失（即目标表格太小，无法容纳所有数据），将创建必要的行 / * / * |
| [drawRoundedRectangle](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-) | 为矩形添加运算符。 |
| [getAlignment](#getAlignment--) | 获取表格对齐方式。 |
| [getBackgroundColor](#getBackgroundColor--) | 获取表格背景颜色 |
| [getBorder](#getBorder--) | 获取边框。 |
| [getBreakText](#getBreakText--) | 获取表格的换行文本 |
| [getBroken](#getBroken--) | 获取或设置表格垂直断开； |
| [getColumnAdjustment](#getColumnAdjustment--) | 获取表格列调整。 |
| [getColumnWidth](#getColumnWidth-java.lang.String-) | 获取列宽 |
| [getColumnWidths](#getColumnWidths--) | 获取表格的列宽。 |
| [getCornerStyle](#getCornerStyle--) | 获取边框角的样式 |
| [getDefaultCellBorder](#getDefaultCellBorder--) | 获取默认单元格边框； |
| [getDefaultCellPadding](#getDefaultCellPadding--) | 获取默认单元格内边距。 |
| [getDefaultCellTextState](#getDefaultCellTextState--) | 获取默认单元格文本状态。 |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | 获取默认单元格边框； |
| [getHeight](#getHeight--) | 获取高度。 |
| [getHeight](#getHeight-com.aspose.pdf.Page-) | 获取高度。 |
| [getLeft](#getLeft--) | 获取表格左侧坐标。 |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | 获取或设置表格的最大列数 |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | 获取在多页中重复的首行数量 |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | 获取重复行的样式 |
| [getRows](#getRows--) | 获取表格的行。 |
| [getTop](#getTop--) | 获取表格顶部坐标。 |
| [getWidth](#getWidth--) | 获取宽度。 |
| [isBordersIncluded](#isBordersIncluded--) | 获取列宽中包含的边框。 |
| [isBroken](#isBroken--) | 获取表格是否已断开——将在下一页截断。 |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | 设置表格对齐方式。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 设置表格背景颜色 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 设置边框。 |
| [setBordersIncluded](#setBordersIncluded-boolean-) | 设置列宽中包含的边框。 |
| [setBreakText](#setBreakText-com.aspose.pdf.TextFragment-) | 设置表格的换行文本 |
| [setBroken](#setBroken-boolean-) | 设置表格已损坏 - 将在下一页截断。 |
| [setBroken](#setBroken-int-) | 获取或设置表格垂直断开； |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | 设置表格列的调整。 |
| [setColumnTextState](#setColumnTextState-int-com.aspose.pdf.TextState-) | 设置高度。 |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | 获取表格的列宽。 |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | 获取或设置边框角的样式 |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | 获取默认单元格边框； |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | 设置默认单元格内边距。 |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 设置默认单元格文本状态。 |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | 获取默认单元格边框； |
| [setLeft](#setLeft-float-) | 设置表格左侧坐标。 |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | 获取或设置表格的最大列数 |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | 获取在多页中重复的首行数量 |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | 获取重复行的样式 |
| [setTop](#setTop-float-) | 设置表格顶部坐标。 |

### Table {#Table--}
```
public Table()
```

默认 ctor

### deepClone {#deepClone--}
```
public Object deepClone()
```

/ * / * 将一维数据数组导入表格。导入时每个数组项对应一个单元格，/ * 从参数中定义的行和列开始。导入过程中，如果检测到必要的行 / * 仍然缺失（即目标表格太小，无法容纳所有数据），将创建必要的行 / * / *

**Returns:**
克隆的对象。

### drawRoundedRectangle {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-}
为矩形添加运算符。

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

获取表格对齐方式。

**Returns:**
HorizontalAlignment 值 @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

获取表格背景颜色

**Returns:**
Color 对象

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

获取边框。

**Returns:**
BorderInfo 对象

### getBreakText {#getBreakText--}
```
public final TextFragment getBreakText()
```

获取表格的换行文本

**Returns:**
TextFragment 对象。

### getBroken {#getBroken--}
```
public final int getBroken()
```

获取或设置表格垂直断开；

**Returns:**
TableBroken 值 @see TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

获取表格列调整。

**Returns:**
ColumnAdjustment 值 @see ColumnAdjustment

### getColumnWidth {#getColumnWidth-java.lang.String-}
获取列宽

### getColumnWidths {#getColumnWidths--}
```
public final String getColumnWidths()
```

获取表格的列宽。

**Returns:**
字符串值

### getCornerStyle {#getCornerStyle--}
```
public final BorderCornerStyle getCornerStyle()
```

获取边框角的样式

**Returns:**
BorderCornerStyle 值 @see BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

获取默认单元格边框；

**Returns:**
BorderInfo 对象

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

获取默认单元格内边距。

**Returns:**
MarginInfo 对象

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

获取默认单元格文本状态。

**Returns:**
TextState 值

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

获取默认单元格边框；

**Returns:**
字符串对象

### getHeight {#getHeight--}
```
public double getHeight()
```

获取高度。

**Returns:**
表格高度

### getHeight {#getHeight-com.aspose.pdf.Page-}
获取高度。

**Returns:**
表格高度

### getLeft {#getLeft--}
```
public final float getLeft()
```

获取表格左侧坐标。

**Returns:**
float 值

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

获取或设置表格的最大列数

**Returns:**
int 值

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

获取在多页中重复的首行数量

**Returns:**
int 值

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

获取重复行的样式

**Returns:**
TextState 对象

### getRows {#getRows--}
```
public final Rows getRows()
```

获取表格的行。

**Returns:**
Rows 对象

### getTop {#getTop--}
```
public final float getTop()
```

获取表格顶部坐标。

**Returns:**
float 值

### getWidth {#getWidth--}
```
public double getWidth()
```

获取宽度。

**Returns:**
表格宽度

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

获取列宽中包含的边框。

**Returns:**
布尔值

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

获取表格是否已断开——将在下一页截断。

**Returns:**
布尔值

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
设置表格对齐方式。

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
设置表格背景颜色

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
设置边框。

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

设置列宽中包含的边框。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setBreakText {#setBreakText-com.aspose.pdf.TextFragment-}
设置表格的换行文本

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

设置表格已损坏 - 将在下一页截断。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

获取或设置表格垂直断开；

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | TableBroken 值 @see TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
设置表格列的调整。

### setColumnTextState {#setColumnTextState-int-com.aspose.pdf.TextState-}
设置高度。

### setColumnWidths {#setColumnWidths-java.lang.String-}
获取表格的列宽。

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
获取或设置边框角的样式

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
获取默认单元格边框；

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
设置默认单元格内边距。

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
设置默认单元格文本状态。

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
获取默认单元格边框；

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

设置表格左侧坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

获取或设置表格的最大列数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

获取在多页中重复的首行数量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
获取重复行的样式

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

设置表格顶部坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

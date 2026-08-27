---
title: "TableElement"
linktitle: "TableElement"
second_title: "Aspose.PDF for Java API 参考"
description: "表示逻辑结构中的 Table 结构元素。"
type: docs
weight: 170
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement

**All Implemented Interfaces:**
IAdjustPosition

```
public final class TableElement extends BLSElement implements IAdjustPosition
```

表示逻辑结构中的 Table 结构元素。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TableElement](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | 仅供内部使用的构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | 调整位置。 |
| [createTBody](#createTBody--) | 创建 {@link TableTHeadElement} 并将其添加到当前表格。 |
| [createTFoot](#createTFoot--) | 创建 {@link TableTFootElement} 并将其添加到当前表格。 |
| [createTHead](#createTHead--) | 创建 {@link TableTHeadElement} 并将其添加到当前表格。 |
| [getAlignment](#getAlignment--) | 获取或设置表格的对齐方式。 |
| [getBackgroundColor](#getBackgroundColor--) | 获取或设置表格的背景颜色。 |
| [getBorder](#getBorder--) | 获取或设置表格的边框。 |
| [getBroken](#getBroken--) | 获取或设置表格的垂直断开； |
| [getColumnAdjustment](#getColumnAdjustment--) | 获取或设置表格列的调整。 |
| [getColumnWidths](#getColumnWidths--) | 获取表格的列宽。 |
| [getCornerStyle](#getCornerStyle--) | 获取或设置边框角的样式 |
| [getDefaultCellBorder](#getDefaultCellBorder--) | 获取默认单元格边框。 |
| [getDefaultCellPadding](#getDefaultCellPadding--) | 获取或设置默认单元格内边距。 |
| [getDefaultCellTextState](#getDefaultCellTextState--) | 获取或设置默认单元格文本状态。 |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | 获取或设置默认列宽。 |
| [getLeft](#getLeft--) | 获取或设置表格左坐标。 |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | 获取或设置表格的最大列数。 |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | 获取在多个页面上重复的首行数量。 |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | 获取重复行的样式。 |
| [getTable](#getTable--) |  |
| [getTop](#getTop--) | 获取或设置表格顶部坐标。 |
| [isBordersIncluded](#isBordersIncluded--) | 获取或设置列宽中包含的边框。 |
| [isBroken](#isBroken--) | 获取或设置表格是否已断开——将在下一页截断。 |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | 获取或设置表格的对齐方式。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 获取或设置表格的背景颜色。 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 获取或设置表格的边框。 |
| [setBordersIncluded](#setBordersIncluded-boolean-) | 获取或设置列宽中包含的边框。 |
| [setBroken](#setBroken-boolean-) | 获取或设置表格是否已断开——将在下一页截断。 |
| [setBroken](#setBroken-int-) | 获取或设置表格的垂直断开； |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | 获取或设置表格列的调整。 |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | 获取表格的列宽。 |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | 获取或设置边框角的样式 |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | 获取默认单元格边框。 |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | 获取或设置默认单元格内边距。 |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 获取或设置默认单元格文本状态。 |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | 获取或设置默认列宽。 |
| [setLeft](#setLeft-float-) | 获取或设置表格左坐标。 |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | 获取或设置表格的最大列数。 |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | 获取在多个页面上重复的首行数量。 |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | 获取重复行的样式。 |
| [setTop](#setTop-float-) | 获取或设置表格顶部坐标。 |

### TableElement {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
仅供内部使用的构造函数

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
调整位置。

### createTBody {#createTBody--}
```
public final TableTBodyElement createTBody()
```

创建 {@link TableTHeadElement} 并将其添加到当前表格。

**Returns:**
已创建结构元素。

### createTFoot {#createTFoot--}
```
public final TableTFootElement createTFoot()
```

创建 {@link TableTFootElement} 并将其添加到当前表格。

**Returns:**
已创建结构元素。

### createTHead {#createTHead--}
```
public final TableTHeadElement createTHead()
```

创建 {@link TableTHeadElement} 并将其添加到当前表格。

**Returns:**
已创建结构元素。

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

获取或设置表格的对齐方式。

**Returns:**
HorizontalAlignment 元素

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

获取或设置表格的背景颜色。

**Returns:**
Color 实例

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

获取或设置表格的边框。

**Returns:**
BorderInfo 实例

### getBroken {#getBroken--}
```
public final int getBroken()
```

获取或设置表格的垂直断开；

**Returns:**
TableBroken 元素

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

获取或设置表格列的调整。

**Returns:**
ColumnAdjustment 元素

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

获取或设置边框角的样式

**Returns:**
BorderCornerStyle 元素

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

获取默认单元格边框。

**Returns:**
BorderInfo 实例

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

获取或设置默认单元格内边距。

**Returns:**
MarginInfo 实例

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

获取或设置默认单元格文本状态。

**Returns:**
TextState 实例

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

获取或设置默认列宽。

**Returns:**
字符串值

### getLeft {#getLeft--}
```
public final float getLeft()
```

获取或设置表格左坐标。

**Returns:**
float 值

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

获取或设置表格的最大列数。

**Returns:**
int 值

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

获取在多个页面上重复的首行数量。

**Returns:**
int 值

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

获取重复行的样式。

**Returns:**
TextState 实例

### getTable {#getTable--}
```
public final Table getTable()
```



### getTop {#getTop--}
```
public final float getTop()
```

获取或设置表格顶部坐标。

**Returns:**
float 值

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

获取或设置列宽中包含的边框。

**Returns:**
布尔值

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

获取或设置表格是否已断开——将在下一页截断。

**Returns:**
布尔值

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
获取或设置表格的对齐方式。

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
获取或设置表格的背景颜色。

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
获取或设置表格的边框。

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

获取或设置列宽中包含的边框。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

获取或设置表格是否已断开——将在下一页截断。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

获取或设置表格的垂直断开；

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | TableBroken 元素 |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
获取或设置表格列的调整。

### setColumnWidths {#setColumnWidths-java.lang.String-}
获取表格的列宽。

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
获取或设置边框角的样式

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
获取默认单元格边框。

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
获取或设置默认单元格内边距。

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
获取或设置默认单元格文本状态。

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
获取或设置默认列宽。

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

获取或设置表格左坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

获取或设置表格的最大列数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

获取在多个页面上重复的首行数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
获取重复行的样式。

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

获取或设置表格顶部坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

---
title: "TableCellElement"
linktitle: "TableCellElement"
second_title: "Aspose.PDF for Java API 参考"
description: "表示逻辑结构中表格单元格元素（TH 和 TD）的基类。"
type: docs
weight: 150
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class TableCellElement extends TableChildElement implements ITextElement , IAdjustPosition
```

表示逻辑结构中表格单元格元素（TH 和 TD）的基类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | 调整位置。 |
| [getAlignment](#getAlignment--) | 获取或设置单元格对齐方式。 |
| [getBackgroundColor](#getBackgroundColor--) | 获取或设置单元格背景颜色。 |
| [getBorder](#getBorder--) | 获取或设置单元格边框。 |
| [getCell](#getCell--) |  |
| [getColSpan](#getColSpan--) | 获取或设置列跨度。 |
| [getDefaultCellTextState](#getDefaultCellTextState--) | 获取或设置默认单元格文本状态。 |
| [getMargin](#getMargin--) | 获取或设置填充。 |
| [getRowSpan](#getRowSpan--) | 获取或设置跨行跨度。 |
| [getStructureTextState](#getStructureTextState--) | 获取当前元素的 {@code /Aspose.Pdf.LogicalStructure.StructureTextState} 对象。值：{@code /Aspose.Pdf.LogicalStructure.StructureTextState} 对象用于当前元素。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 获取或设置垂直对齐方式。 |
| [isNoBorder](#isNoBorder--) | 获取或设置单元格的边框。 |
| [isWordWrapped](#isWordWrapped--) | 获取或设置单元格文本的自动换行。 |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | 获取或设置单元格对齐方式。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 获取或设置单元格背景颜色。 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 获取或设置单元格边框。 |
| [setColSpan](#setColSpan-int-) | 获取或设置列跨度。 |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 获取或设置默认单元格文本状态。 |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | 获取或设置填充。 |
| [setNoBorder](#setNoBorder-boolean-) | 获取或设置单元格的边框。 |
| [setRowSpan](#setRowSpan-int-) | 获取或设置跨行跨度。 |
| [setText](#setText-java.lang.String-) | 将文本内容追加到当前文本元素。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 获取或设置垂直对齐方式。 |
| [setWordWrapped](#setWordWrapped-boolean-) | 获取或设置单元格文本的自动换行。 |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
调整位置。

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

获取或设置单元格对齐方式。

**Returns:**
HorizontalAlignment 元素

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

获取或设置单元格背景颜色。

**Returns:**
Color 实例

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

获取或设置单元格边框。

**Returns:**
BorderInfo 实例

### getCell {#getCell--}
```
public final Cell getCell()
```



### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

获取或设置列跨度。

**Returns:**
int 值

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

获取或设置默认单元格文本状态。

**Returns:**
TextState 实例

### getMargin {#getMargin--}
```
public final MarginInfo getMargin()
```

获取或设置填充。

**Returns:**
MarginInfo 实例

### getRowSpan {#getRowSpan--}
```
public final int getRowSpan()
```

获取或设置跨行跨度。

**Returns:**
int 值

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

获取当前元素的 {@code /Aspose.Pdf.LogicalStructure.StructureTextState} 对象。值：{@code /Aspose.Pdf.LogicalStructure.StructureTextState} 对象用于当前元素。

**Returns:**
StructureTextState 实例

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

获取或设置垂直对齐方式。

**Returns:**
VerticalAlignment 元素

### isNoBorder {#isNoBorder--}
```
public final boolean isNoBorder()
```

获取或设置单元格的边框。

**Returns:**
布尔值

### isWordWrapped {#isWordWrapped--}
```
public final boolean isWordWrapped()
```

获取或设置单元格文本的自动换行。

**Returns:**
布尔值

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
获取或设置单元格对齐方式。

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
获取或设置单元格背景颜色。

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
获取或设置单元格边框。

### setColSpan {#setColSpan-int-}
```
public final void setColSpan(int value)
```

获取或设置列跨度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
获取或设置默认单元格文本状态。

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
获取或设置填充。

### setNoBorder {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```

获取或设置单元格的边框。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRowSpan {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```

获取或设置跨行跨度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setText {#setText-java.lang.String-}
将文本内容追加到当前文本元素。

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
获取或设置垂直对齐方式。

### setWordWrapped {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```

获取或设置单元格文本的自动换行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

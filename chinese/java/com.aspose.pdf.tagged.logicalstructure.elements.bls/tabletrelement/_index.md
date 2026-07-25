---
title: "TableTRElement"
linktitle: "TableTRElement"
second_title: "Aspose.PDF for Java API 参考"
description: "表示表格逻辑结构中的 TR 结构元素。"
type: docs
weight: 240
url: /zh/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement

```
public final class TableTRElement extends TableChildElement
```

表示表格逻辑结构中的 TR 结构元素。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TableTRElement](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | 仅供内部使用的构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [createTD](#createTD--) | 创建 {@link TableTHElement} 并将其添加到当前表格。 |
| [createTH](#createTH--) | 创建 {@link TableTHElement} 并将其添加到当前表格。 |
| [getBackgroundColor](#getBackgroundColor--) | 获取或设置行的背景颜色。 |
| [getBorder](#getBorder--) | 获取或设置行的边框。 |
| [getDefaultCellBorder](#getDefaultCellBorder--) | 获取默认单元格边框。 |
| [getDefaultCellPadding](#getDefaultCellPadding--) | 获取或设置行单元格的默认边距。 |
| [getDefaultCellTextState](#getDefaultCellTextState--) | 获取或设置行单元格的默认文本状态。 |
| [getFixedRowHeight](#getFixedRowHeight--) | 获取固定行高度——行可能具有固定高度。 |
| [getMinRowHeight](#getMinRowHeight--) | 获取行的高度。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 获取或设置垂直对齐方式。 |
| [isInNewPage](#isInNewPage--) | 获取固定行是否在新页面——具有此属性的页面应打印到下一页，默认值为 false。 |
| [isRowBroken](#isRowBroken--) | 获取行是否可以在两页之间断开。 |
| [preSave](#preSave--) |  |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 获取或设置行的背景颜色。 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 获取或设置行的边框。 |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | 获取默认单元格边框。 |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | 获取或设置行单元格的默认边距。 |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 获取或设置行单元格的默认文本状态。 |
| [setFixedRowHeight](#setFixedRowHeight-double-) | 获取固定行高度——行可能具有固定高度。 |
| [setInNewPage](#setInNewPage-boolean-) | 获取固定行是否在新页面——具有此属性的页面应打印到下一页，默认值为 false。 |
| [setMinRowHeight](#setMinRowHeight-double-) | 获取行的高度。 |
| [setRowBroken](#setRowBroken-boolean-) | 获取行是否可以在两页之间断开。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 获取或设置垂直对齐方式。 |

### TableTRElement {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
仅供内部使用的构造函数

### createTD {#createTD--}
```
public final TableTDElement createTD()
```

创建 {@link TableTHElement} 并将其添加到当前表格。

**Returns:**
已创建结构元素。

### createTH {#createTH--}
```
public final TableTHElement createTH()
```

创建 {@link TableTHElement} 并将其添加到当前表格。

**Returns:**
已创建结构元素。

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

获取或设置行的背景颜色。

**Returns:**
Color 实例

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

获取或设置行的边框。

**Returns:**
BorderInfo 实例

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

获取或设置行单元格的默认边距。

**Returns:**
MarginInfo 实例

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

获取或设置行单元格的默认文本状态。

**Returns:**
TextState 实例

### getFixedRowHeight {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```

获取固定行高度——行可能具有固定高度。

**Returns:**
double 值

### getMinRowHeight {#getMinRowHeight--}
```
public final double getMinRowHeight()
```

获取行的高度。

**Returns:**
double 值

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

获取或设置垂直对齐方式。

**Returns:**
VerticalAlignment 元素

### isInNewPage {#isInNewPage--}
```
public final boolean isInNewPage()
```

获取固定行是否在新页面——具有此属性的页面应打印到下一页，默认值为 false。

**Returns:**
布尔值

### isRowBroken {#isRowBroken--}
```
public final boolean isRowBroken()
```

获取行是否可以在两页之间断开。

**Returns:**
布尔值

### preSave {#preSave--}
```
public void preSave()
```



### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
获取或设置行的背景颜色。

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
获取或设置行的边框。

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
获取默认单元格边框。

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
获取或设置行单元格的默认边距。

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
获取或设置行单元格的默认文本状态。

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```

获取固定行高度——行可能具有固定高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setInNewPage {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```

获取固定行是否在新页面——具有此属性的页面应打印到下一页，默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMinRowHeight {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```

获取行的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setRowBroken {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```

获取行是否可以在两页之间断开。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
获取或设置垂直对齐方式。

---
title: "单元格"
linktitle: "单元格"
second_title: "Aspose.PDF for Java API 参考"
description: "表示表格行的单元格。"
type: docs
weight: 510
url: /zh/java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Cell

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Cell extends Object implements com.aspose.ms.System.ICloneable
```

表示表格行的单元格。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Cell](#Cell--) | 初始化 Cell 类的新实例。 |
| [Cell](#Cell-com.aspose.pdf.Rectangle-) | 初始化 Cell 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | 克隆单元格。 |
| [getAlignment](#getAlignment--) | 获取对齐方式。 |
| [getBackgroundColor](#getBackgroundColor--) | 获取背景颜色。 |
| [getBackgroundImage](#getBackgroundImage--) | 获取或设置背景图像 |
| [getBackgroundImageFile](#getBackgroundImageFile--) | 获取背景图像文件。 |
| [getBorder](#getBorder--) | 获取边框。 |
| [getColSpan](#getColSpan--) | 获取或设置列跨度。 |
| [getDefaultCellTextState](#getDefaultCellTextState--) | 获取默认单元格文本状态。 |
| [getMargin](#getMargin--) | 获取内边距。 |
| [getParagraphs](#getParagraphs--) | 获取单元格的格式化文本。 |
| [getRowSpan](#getRowSpan--) | 获取行跨度。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 获取垂直对齐方式。 |
| [getWidth](#getWidth--) | 获取列宽。 |
| [isNoBorder](#isNoBorder--) | 获取单元格是否具有边框。 |
| [isOverrideByFragment](#isOverrideByFragment--) | 设置单元格的 TextState 属性被 TextFragment TextState 属性覆盖。 |
| [isWordWrapped](#isWordWrapped--) | 获取单元格的文本自动换行。 |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | 设置对齐方式。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 获取或设置背景颜色。 |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | 获取或设置背景图像 |
| [setBackgroundImageFile](#setBackgroundImageFile-java.lang.String-) | 设置背景图像文件。 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 设置边框。 |
| [setColSpan](#setColSpan-int-) | 设置列跨度。 |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 设置默认单元格文本状态。 |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | 设置内边距。 |
| [setNoBorder](#setNoBorder-boolean-) | 设置单元格是否具有边框。 |
| [setOverrideByFragment](#setOverrideByFragment-boolean-) | 设置单元格的 TextState 属性被 TextFragment TextState 属性覆盖。 |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | 设置单元格的格式化文本。 |
| [setRowSpan](#setRowSpan-int-) | 设置行跨度。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 设置垂直对齐方式。 |
| [setWidth](#setWidth-double-) | 设置列宽。 |
| [setWordWrapped](#setWordWrapped-boolean-) | 设置单元格文本自动换行。 |

### Cell {#Cell--}
```
public Cell()
```

初始化 Cell 类的新实例。

### Cell {#Cell-com.aspose.pdf.Rectangle-}
初始化 Cell 类的新实例。

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆单元格。

**Returns:**
克隆的对象。

### getAlignment {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```

获取对齐方式。

**Returns:**
HorizontalAlignment 元素 @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

获取背景颜色。

**Returns:**
Color 对象

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

获取或设置背景图像

**Returns:**
图像实例

### getBackgroundImageFile {#getBackgroundImageFile--}
```
@Deprecated public String getBackgroundImageFile()
```

获取背景图像文件。

**Returns:**
字符串值 @deprecated 属性已扩展，请使用 BackgroundImage

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

获取边框。

**Returns:**
BorderInfo 对象

### getColSpan {#getColSpan--}
```
public int getColSpan()
```

获取或设置列跨度。

**Returns:**
int 值

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

获取默认单元格文本状态。

**Returns:**
TextState 对象

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

获取内边距。

**Returns:**
MarginInfo 对象

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

获取单元格的格式化文本。

**Returns:**
Paragraphs 对象

### getRowSpan {#getRowSpan--}
```
public int getRowSpan()
```

获取行跨度。

**Returns:**
int 值

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

获取垂直对齐方式。

**Returns:**
VerticalAlignment 元素 @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

获取列宽。

**Returns:**
double 值

### isNoBorder {#isNoBorder--}
```
public boolean isNoBorder()
```

获取单元格是否具有边框。

**Returns:**
布尔值

### isOverrideByFragment {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```

设置单元格的 TextState 属性被 TextFragment TextState 属性覆盖。

**Returns:**
布尔值

### isWordWrapped {#isWordWrapped--}
```
public boolean isWordWrapped()
```

获取单元格的文本自动换行。

**Returns:**
布尔值

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
设置对齐方式。

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
获取或设置背景颜色。

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
获取或设置背景图像

### setBackgroundImageFile {#setBackgroundImageFile-java.lang.String-}
设置背景图像文件。

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
设置边框。

### setColSpan {#setColSpan-int-}
```
public void setColSpan(int value)
```

设置列跨度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
设置默认单元格文本状态。

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
设置内边距。

### setNoBorder {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```

设置单元格是否具有边框。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setOverrideByFragment {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```

设置单元格的 TextState 属性被 TextFragment TextState 属性覆盖。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
设置单元格的格式化文本。

### setRowSpan {#setRowSpan-int-}
```
public void setRowSpan(int value)
```

设置行跨度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
设置垂直对齐方式。

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

设置列宽。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setWordWrapped {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```

设置单元格文本自动换行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

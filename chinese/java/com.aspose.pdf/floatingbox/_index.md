---
title: "FloatingBox"
linktitle: "FloatingBox"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF 文档中的 FloatingBox。FloatingBox 是自定义定位的。"
type: docs
weight: 1610
url: /zh/java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FloatingBox, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FloatingBox

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class FloatingBox extends BaseParagraph
```

表示 PDF 文档中的 FloatingBox。FloatingBox 是自定义定位的。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FloatingBox](#FloatingBox--) | 初始化 {@code FloatingBox} 类的新实例。 |
| [FloatingBox](#FloatingBox-float-float-) | 使用指定的宽度和高度初始化 {@code FloatingBox} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | 克隆一个新的 {@code FloatingBox} 对象。浮动框中的段落不会被克隆。 |
| [getBackgroundColor](#getBackgroundColor--) | 获取指示浮动框背景颜色的对象。 |
| [getBackgroundImage](#getBackgroundImage--) | 获取或设置页面的背景图像（仅用于生成器，读取文档时不填充）。 |
| [getBorder](#getBorder--) | 获取指示浮动框边框信息的对象。 |
| [getColumnInfo](#getColumnInfo--) | 获取列信息 |
| [getHeight](#getHeight--) | 获取指示浮动框高度的浮点值。 |
| [getLeft](#getLeft--) | 获取表格左侧坐标。 |
| [getPadding](#getPadding--) | 获取指示浮动框内边距的对象。 |
| [getParagraphs](#getParagraphs--) | 获取指示单元格中所有段落的集合。 |
| [getPositioningMode](#getPositioningMode--) | 指定用于确定 FloatingBox 在页面上位置的变体。 |
| [getTop](#getTop--) | 获取表格顶部坐标。 |
| [getWidth](#getWidth--) | 获取指示浮动框宽度的浮点值。 |
| [isNeedRepeating](#isNeedRepeating--) | 获取指示段落是否需要在下一页重复的布尔值。默认值为 true。该属性仅在段落本身以及其 ReferenceParagraphID 所引用的对象均包含在 RepeatingRows 中时有效。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 设置指示浮动框背景颜色的对象。 |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | 获取或设置页面的背景图像（仅用于生成器，读取文档时不填充）。 |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 设置指示浮动框边框信息的对象。 |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | 设置列信息 |
| [setHeight](#setHeight-double-) | 设置指示浮动框高度的浮点值。 |
| [setLeft](#setLeft-double-) | 设置表格左侧坐标。 |
| [setNeedRepeating](#setNeedRepeating-boolean-) | 设置指示段落是否需要在下一页重复的布尔值。默认值为 true。该属性仅在段落本身以及其 ReferenceParagraphID 所引用的对象均包含在 RepeatingRows 中时有效。 |
| [setPadding](#setPadding-com.aspose.pdf.MarginInfo-) | 设置指示浮动框内边距的对象。 |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | 设置指示单元格中所有段落的集合。 |
| [setPositioningMode](#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-) | 指定用于确定 FloatingBox 在页面上位置的变体。 |
| [setTop](#setTop-double-) | 设置表格顶部坐标。 |
| [setWidth](#setWidth-double-) | 设置一个浮点值，用于指示浮动框的宽度。 |

### FloatingBox {#FloatingBox--}
```
public FloatingBox()
```

初始化 {@code FloatingBox} 类的新实例。

### FloatingBox {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```

使用指定的宽度和高度初始化 {@code FloatingBox} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 框的宽度。 |
| 高度 |  | 框的高度。 |

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆一个新的 {@code FloatingBox} 对象。浮动框中的段落不会被克隆。

**Returns:**
新的 {@code FloatingBox} 对象。

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

获取指示浮动框背景颜色的对象。

**Returns:**
指示背景颜色的对象。

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

获取或设置页面的背景图像（仅用于生成器，读取文档时不填充）。

**Returns:**
图像实例

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

获取指示浮动框边框信息的对象。

**Returns:**
指示边框信息的对象。

### getColumnInfo {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```

获取列信息

**Returns:**
ColumnInfo 对象

### getHeight {#getHeight--}
```
public double getHeight()
```

获取指示浮动框高度的浮点值。

**Returns:**
指示高度的值。

### getLeft {#getLeft--}
```
public double getLeft()
```

获取表格左侧坐标。

**Returns:**
表格左侧坐标。

### getPadding {#getPadding--}
```
public MarginInfo getPadding()
```

获取指示浮动框内边距的对象。

**Returns:**
指示填充的对象。

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

获取指示单元格中所有段落的集合。

**Returns:**
指示所有段落的集合。

### getPositioningMode {#getPositioningMode--}
```
public final ParagraphPositioningMode getPositioningMode()
```

指定用于确定 FloatingBox 在页面上位置的变体。

**Returns:**
ParagraphPositioningMode 元素

### getTop {#getTop--}
```
public double getTop()
```

获取表格顶部坐标。

**Returns:**
表格顶部坐标。

### getWidth {#getWidth--}
```
public double getWidth()
```

获取指示浮动框宽度的浮点值。

**Returns:**
double 值

### isNeedRepeating {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```

获取指示段落是否需要在下一页重复的布尔值。默认值为 true。该属性仅在段落本身以及其 ReferenceParagraphID 所引用的对象均包含在 RepeatingRows 中时有效。

**Returns:**
布尔值

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
设置指示浮动框背景颜色的对象。

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
获取或设置页面的背景图像（仅用于生成器，读取文档时不填充）。

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
设置指示浮动框边框信息的对象。

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
设置列信息

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

设置指示浮动框高度的浮点值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示高度的值。 |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

设置表格左侧坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 表格左侧坐标。 |

### setNeedRepeating {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```

设置指示段落是否需要在下一页重复的布尔值。默认值为 true。该属性仅在段落本身以及其 ReferenceParagraphID 所引用的对象均包含在 RepeatingRows 中时有效。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setPadding {#setPadding-com.aspose.pdf.MarginInfo-}
设置指示浮动框内边距的对象。

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
设置指示单元格中所有段落的集合。

### setPositioningMode {#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-}
指定用于确定 FloatingBox 在页面上位置的变体。

### setTop {#setTop-double-}
```
public void setTop(double value)
```

设置表格顶部坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 表格顶部坐标。 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

设置一个浮点值，用于指示浮动框的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

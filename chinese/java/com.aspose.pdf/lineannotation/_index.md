---
title: "LineAnnotation"
linktitle: "LineAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示线注释的类。"
type: docs
weight: 2710
url: /zh/java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.LineAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class LineAnnotation extends MarkupAnnotation
```

表示线注释的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | 用于 Generator 的构造函数。 |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | 在指定页面上创建新的 Line 注释。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者进行注释处理。 |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 根据矩阵变换更新起始点和结束点。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getCaptionOffset](#getCaptionOffset--) | 获取标题文本相对于其正常位置的偏移。 |
| [getCaptionPosition](#getCaptionPosition--) | 获取注释标题的位置。 |
| [getEnding](#getEnding--) | 获取线段的结束点。 |
| [getEndingStyle](#getEndingStyle--) | 获取线段终点的结束样式。 |
| [getIntent](#getIntent--) | 获取线注释的意图。 |
| [getInteriorColor](#getInteriorColor--) | 获取注释的内部颜色。 |
| [getLeaderLine](#getLeaderLine--) | 获取引导线长度。 |
| [getLeaderLineExtension](#getLeaderLineExtension--) | 获取引导线延伸的长度。 |
| [getLeaderLineOffset](#getLeaderLineOffset--) | 获取引导线偏移。 |
| [getMeasure](#getMeasure--) | 为此注释指定的测量单位。 |
| [getShowCaption](#getShowCaption--) | 获取决定内容是否必须显示为标题的布尔标志。 |
| [getStarting](#getStarting--) | 获取线的起始点。 |
| [getStartingStyle](#getStartingStyle--) | 获取线起始点的线端样式。 |
| [setCaptionOffset](#setCaptionOffset-com.aspose.pdf.Point-) | 设置标题文本相对于其正常位置的偏移。 |
| [setCaptionPosition](#setCaptionPosition-com.aspose.pdf.CaptionPosition-) | 设置注释标题位置。 |
| [setEnding](#setEnding-com.aspose.pdf.Point-) | 设置线的结束点。 |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | 设置线结束点的结束样式。 |
| [setIntent](#setIntent-com.aspose.pdf.LineIntent-) | 设置线注释的意图。 |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | 设置注释的内部颜色。 |
| [setLeaderLine](#setLeaderLine-double-) | 设置引导线长度。 |
| [setLeaderLineExtension](#setLeaderLineExtension-double-) | 设置引导线延伸的长度。 |
| [setLeaderLineOffset](#setLeaderLineOffset-double-) | 设置引导线偏移。 |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | 为此注释指定的测量单位。 |
| [setShowCaption](#setShowCaption-boolean-) | 设置决定内容是否必须显示为标题的布尔标志。 |
| [setStarting](#setStarting-com.aspose.pdf.Point-) | 设置线的起始点。 |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | 设置线起始点的线端样式。 |

### LineAnnotation {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
用于 Generator 的构造函数。

### LineAnnotation {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
在指定页面上创建新的 Line 注释。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者进行注释处理。

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
根据矩阵变换更新起始点和结束点。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 元素 @see AnnotationType

### getCaptionOffset {#getCaptionOffset--}
```
public Point getCaptionOffset()
```

获取标题文本相对于其正常位置的偏移。

**Returns:**
点对象

### getCaptionPosition {#getCaptionPosition--}
```
public CaptionPosition getCaptionPosition()
```

获取注释标题的位置。

**Returns:**
CaptionPosition 元素 @see CaptionPosition

### getEnding {#getEnding--}
```
public Point getEnding()
```

获取线段的结束点。

**Returns:**
点值

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

获取线段终点的结束样式。

**Returns:**
LineEnding 元素 @see LineEnding

### getIntent {#getIntent--}
```
public LineIntent getIntent()
```

获取线注释的意图。

**Returns:**
LineIntent 元素 @see LineIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

获取注释的内部颜色。

**Returns:**
Color 对象

### getLeaderLine {#getLeaderLine--}
```
public double getLeaderLine()
```

获取引导线长度。

**Returns:**
double 值

### getLeaderLineExtension {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```

获取引导线延伸的长度。

**Returns:**
double 值

### getLeaderLineOffset {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```

获取引导线偏移。

**Returns:**
double 值

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

为此注释指定的测量单位。

**Returns:**
测量对象

### getShowCaption {#getShowCaption--}
```
public boolean getShowCaption()
```

获取决定内容是否必须显示为标题的布尔标志。

**Returns:**
布尔值

### getStarting {#getStarting--}
```
public Point getStarting()
```

获取线的起始点。

**Returns:**
点值

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

获取线起始点的线端样式。

**Returns:**
LineEnding 元素 @see LineEnding

### setCaptionOffset {#setCaptionOffset-com.aspose.pdf.Point-}
设置标题文本相对于其正常位置的偏移。

### setCaptionPosition {#setCaptionPosition-com.aspose.pdf.CaptionPosition-}
设置注释标题位置。

### setEnding {#setEnding-com.aspose.pdf.Point-}
设置线的结束点。

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
设置线结束点的结束样式。

### setIntent {#setIntent-com.aspose.pdf.LineIntent-}
设置线注释的意图。

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
设置注释的内部颜色。

### setLeaderLine {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```

设置引导线长度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setLeaderLineExtension {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```

设置引导线延伸的长度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setLeaderLineOffset {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```

设置引导线偏移。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
为此注释指定的测量单位。

### setShowCaption {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```

设置决定内容是否必须显示为标题的布尔标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setStarting {#setStarting-com.aspose.pdf.Point-}
设置线的起始点。

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
设置线起始点的线端样式。

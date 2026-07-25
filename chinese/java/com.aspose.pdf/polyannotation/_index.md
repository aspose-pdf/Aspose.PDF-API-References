---
title: "PolyAnnotation"
linktitle: "PolyAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "多注释的抽象基类。"
type: docs
weight: 3890
url: /zh/java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.PolyAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class PolyAnnotation extends MarkupAnnotation
```

多注释的抽象基类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 根据矩阵变换更新 Vertices 中的点。 |
| [getEndingStyle](#getEndingStyle--) | 获取第二条线端点的样式。 |
| [getIntent](#getIntent--) | 获取多边形或折线注释的意图。 |
| [getInteriorColor](#getInteriorColor--) | 获取用于填充注释线端点的内部颜色。 |
| [getMeasure](#getMeasure--) | 为此注释指定的测量单位。 |
| [getStartingStyle](#getStartingStyle--) | 获取第一条线端点的样式。 |
| [getVertices](#getVertices--) | 获取一个表示每个顶点水平和垂直坐标的点数组。 |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | 设置第二条线端点的样式。 |
| [setIntent](#setIntent-com.aspose.pdf.PolyIntent-) | 设置多边形或折线注释的意图。 |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | 设置用于填充注释线端点的内部颜色。 |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | 为此注释指定的测量单位。 |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | 设置第一条线端点的样式。 |
| [setVertices](#setVertices-com.aspose.pdf.Point:A-) | 设置一个表示每个顶点水平和垂直坐标的点数组。 |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
根据矩阵变换更新 Vertices 中的点。

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

获取第二条线端点的样式。

**Returns:**
LineEnding 元素 @see LineEnding

### getIntent {#getIntent--}
```
public PolyIntent getIntent()
```

获取多边形或折线注释的意图。

**Returns:**
PolyIntent 元素 @see PolyIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

获取用于填充注释线端点的内部颜色。

**Returns:**
Color 对象

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

为此注释指定的测量单位。

**Returns:**
Measure 实例

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

获取第一条线端点的样式。

**Returns:**
LineEnding 元素 @see LineEnding

### getVertices {#getVertices--}
```
public Point [] getVertices()
```

获取一个表示每个顶点水平和垂直坐标的点数组。

**Returns:**
Point 值数组

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
设置第二条线端点的样式。

### setIntent {#setIntent-com.aspose.pdf.PolyIntent-}
设置多边形或折线注释的意图。

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
设置用于填充注释线端点的内部颜色。

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
为此注释指定的测量单位。

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
设置第一条线端点的样式。

### setVertices {#setVertices-com.aspose.pdf.Point:A-}
设置一个表示每个顶点水平和垂直坐标的点数组。

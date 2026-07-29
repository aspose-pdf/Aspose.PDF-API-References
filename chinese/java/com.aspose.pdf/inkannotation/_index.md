---
title: "InkAnnotation"
linktitle: "InkAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示一个自由手绘 \\\"scribble\\\"，由一个或多个不相连的路径组成。"
type: docs
weight: 2430
url: /zh/java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.InkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class InkAnnotation extends MarkupAnnotation
```

表示由一个或多个不相连路径组成的手绘“涂鸦”。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-) | Generator 的 Ink 注释构造函数。 |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-) | 在指定页面上创建新的 Ink 注释。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者对象以处理该注释。 |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 根据矩阵变换更新 InkList 中的点。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getCapStyle](#getCapStyle--) | 获取 Ink 注释线端的样式。 |
| [getInkList](#getInkList--) | <p> 获取由 Point[] 数组表示的独立线手势列表。 </p> |
| [setCapStyle](#setCapStyle-com.aspose.pdf.CapStyle-) | 设置 Ink 注释线端的样式。 |
| [setInkList](#setInkList-java.util.List-) | 设置由 Point[] 数组表示的独立线手势列表。 |
| [updateAppearance](#updateAppearance--) | 在文本被更改/移动后，更新外观。 |

### InkAnnotation {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-}
Generator 的 Ink 注释构造函数。

### InkAnnotation {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-}
在指定页面上创建新的 Ink 注释。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者对象以处理该注释。

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
根据矩阵变换更新 InkList 中的点。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 元素 @see AnnotationType

### getCapStyle {#getCapStyle--}
```
public CapStyle getCapStyle()
```

获取 Ink 注释线端的样式。

**Returns:**
CapStyle 元素 @see CapStyle

### getInkList {#getInkList--}
```
public List < Point []> getInkList()
```

<p> 获取由 Point[] 数组表示的独立线手势列表。 </p>

**Returns:**
{@code List<Point[]>} 对象

### setCapStyle {#setCapStyle-com.aspose.pdf.CapStyle-}
设置 Ink 注释线端的样式。

### setInkList {#setInkList-java.util.List-}
设置由 Point[] 数组表示的独立线手势列表。

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

在文本被更改/移动后，更新外观。

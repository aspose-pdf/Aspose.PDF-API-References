---
title: "ColorBarAnnotation"
linktitle: "ColorBarAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 ColorBarAnnotation 注释的类。属性 Color 被忽略，改用 ColorsOfCMYK 颜色。在创建时，宽高比决定方向。"
type: docs
weight: 680
url: /zh/java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

表示 ColorBarAnnotation 注释的类。属性 Color 被忽略，改用 ColorsOfCMYK 颜色。创建时，宽高比例决定注释的方向——水平或垂直。随后检查注释矩形是否位于 TrimBox 之外，如果不在，则根据注释方向将其移动到 TrimBox 最近的外部位置。可以缩小宽度（高度），使注释位于 TrimBox 之外。如果布局没有空间，宽度/高度可以设为零（此时注释仍在页面上，但不显示）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 在指定页面上创建新的 ColorBar 注释。默认 ColorsOfCMYK.Black |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | 在指定页面上创建新的 ColorBar 注释。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者对象以处理该注释。 |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 根据矩阵变换以及必要时移动到 TrimBox 之外，更新参数和外观。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getColorOfCMYK](#getColorOfCMYK--) | 获取或设置注释绘制使用的颜色（青色、品红、黄色、黑色之一）。 |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | 获取或设置注释绘制使用的颜色（青色、品红、黄色、黑色之一）。 |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
在指定页面上创建新的 ColorBar 注释。默认 ColorsOfCMYK.Black

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
在指定页面上创建新的 ColorBar 注释。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者对象以处理该注释。

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
根据矩阵变换以及必要时移动到 TrimBox 之外，更新参数和外观。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
int 值

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

获取或设置注释绘制使用的颜色（青色、品红、黄色、黑色之一）。

**Returns:**
ColorsOfCMYK 元素

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
获取或设置注释绘制使用的颜色（青色、品红、黄色、黑色之一）。

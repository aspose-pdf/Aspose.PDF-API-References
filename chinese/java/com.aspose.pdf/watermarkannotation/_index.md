---
title: "WatermarkAnnotation"
linktitle: "WatermarkAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "类描述 Watermark 注释对象。"
type: docs
weight: 5510
url: /zh/java/com.aspose.pdf/watermarkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WatermarkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WatermarkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WatermarkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WatermarkAnnotation extends Annotation
```

类描述 Watermark 注释对象。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WatermarkAnnotation](#WatermarkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Watermark 注释类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 对注释应用访问者。 |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 在基类中重写定义，方法体为空。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getFixedPrint](#getFixedPrint--) | 修复 Watermark 注释的打印对象。 |
| [getOpacity](#getOpacity--) | 获取或设置注释的不透明度。 |
| [setOpacity](#setOpacity-double-) | 获取或设置注释的不透明度。 |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | 设置注释的文本。 |
| [setTextAndState](#setTextAndState-java.lang.String:A-com.aspose.pdf.TextState-) | 设置注释的文本。 |

### WatermarkAnnotation {#WatermarkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Watermark 注释类的构造函数。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
对注释应用访问者。

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
在基类中重写定义，方法体为空。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 元素

### getFixedPrint {#getFixedPrint--}
```
public FixedPrint getFixedPrint()
```

修复 Watermark 注释的打印对象。

**Returns:**
FixedPrint 对象

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

获取或设置注释的不透明度。

**Returns:**
double 值

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

获取或设置注释的不透明度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
设置注释的文本。

### setTextAndState {#setTextAndState-java.lang.String:A-com.aspose.pdf.TextState-}
设置注释的文本。

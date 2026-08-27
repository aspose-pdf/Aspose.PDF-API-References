---
title: "CaretAnnotation"
linktitle: "CaretAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "类表示插入符号注释。"
type: docs
weight: 470
url: /zh/java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CaretAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class CaretAnnotation extends MarkupAnnotation
```

类表示插入符号注释。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.IDocument-) | Generator 中使用的构造函数。 |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 在指定页面上创建新的 Caret 注释。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者对象以处理该注释。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getFrame](#getFrame--) | 获取 caret 矩形。 |
| [getSymbol](#getSymbol--) | 获取与 caret 关联的符号。 {@code CaretSymbol} |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | 设置 caret 矩形。 |
| [setSymbol](#setSymbol-com.aspose.pdf.CaretSymbol-) | 设置导入的输出页面尺寸。 |

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.IDocument-}
Generator 中使用的构造函数。

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
在指定页面上创建新的 Caret 注释。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者对象以处理该注释。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 元素

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

获取 caret 矩形。

**Returns:**
caret 矩形。

### getSymbol {#getSymbol--}
```
public CaretSymbol getSymbol()
```

获取与 caret 关联的符号。 {@code CaretSymbol}

**Returns:**
CaretSymbol 元素 @see CaretSymbol

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
设置 caret 矩形。

### setSymbol {#setSymbol-com.aspose.pdf.CaretSymbol-}
设置导入的输出页面尺寸。

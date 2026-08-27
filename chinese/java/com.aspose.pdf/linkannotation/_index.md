---
title: "LinkAnnotation"
linktitle: "LinkAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文档中指向其他位置的超文本链接或要执行的操作。"
type: docs
weight: 2760
url: /zh/java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.LinkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class LinkAnnotation extends Annotation
```

表示文档中指向其他位置的超文本链接或要执行的操作。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LinkAnnotation](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 在指定页面上创建新的 Link 注释。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者对象以处理该注释。 |
| [getAction](#getAction--) | 获取在链接注释被激活时要执行的操作。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getDestination](#getDestination--) | 获取在注释被激活时要显示的目标。 |
| [getHighlighting](#getHighlighting--) | 获取在鼠标按钮在其活动区域内按下或保持时使用的视觉效果。 |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | 设置在链接注释被激活时要执行的操作。 |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | 设置在注释被激活时要显示的目标。 |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | 设置在鼠标按钮在其活动区域内按下或保持时使用的视觉效果。 |

### LinkAnnotation {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
在指定页面上创建新的 Link 注释。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者对象以处理该注释。

### getAction {#getAction--}
```
public PdfAction getAction()
```

获取在链接注释被激活时要执行的操作。

**Returns:**
PdfAction 值

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 元素 @see AnnotationType

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

获取在注释被激活时要显示的目标。

**Returns:**
IAppointment 值

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

获取在鼠标按钮在其活动区域内按下或保持时使用的视觉效果。

**Returns:**
HighlightingMode 元素 @see HighlightingMode

### setAction {#setAction-com.aspose.pdf.PdfAction-}
设置在链接注释被激活时要执行的操作。

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
设置在注释被激活时要显示的目标。

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
设置在鼠标按钮在其活动区域内按下或保持时使用的视觉效果。

---
title: "ScreenAnnotation"
linktitle: "ScreenAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "屏幕注释，指定页面上可播放媒体剪辑的区域。"
type: docs
weight: 4470
url: /zh/java/com.aspose.pdf/screenannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.ScreenAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.ScreenAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.ScreenAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class ScreenAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

屏幕注释，指定页面上可播放媒体剪辑的区域。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ScreenAnnotation](#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | 在指定页面上创建新的 Screen 注释。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 表示 accept 方法 |
| [getAction](#getAction--) | 获取在注释被激活时要执行的操作。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getTitle](#getTitle--) | 获取 screen 注释的标题。 |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | 设置在注释被激活时要执行的操作。 |
| [setTitle](#setTitle-java.lang.String-) | 设置屏幕注释的标题。 |

### ScreenAnnotation {#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
在指定页面上创建新的 Screen 注释。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
表示 accept 方法

### getAction {#getAction--}
```
public PdfAction getAction()
```

获取在注释被激活时要执行的操作。

**Returns:**
PdfAction 对象

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 元素 @see AnnotationType

### getTitle {#getTitle--}
```
public String getTitle()
```

获取 screen 注释的标题。

**Returns:**
字符串值

### setAction {#setAction-com.aspose.pdf.PdfAction-}
设置在注释被激活时要执行的操作。

### setTitle {#setTitle-java.lang.String-}
设置屏幕注释的标题。

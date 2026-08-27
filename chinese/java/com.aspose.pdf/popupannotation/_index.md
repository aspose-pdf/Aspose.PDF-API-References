---
title: "PopupAnnotation"
linktitle: "PopupAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示弹出注释，可在弹出窗口中显示文本以进行输入和编辑。"
type: docs
weight: 3930
url: /zh/java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PopupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PopupAnnotation extends Annotation
```

表示弹出注释，可在弹出窗口中显示文本以进行输入和编辑。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.IDocument-) | 构造函数。用于在 Generator 中使用。 |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 在指定页面上创建新的 Popup 注释。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者对象以处理该注释。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getOpen](#getOpen--) | 获取一个标志，指定弹出注释是否应初始显示为打开状态。 |
| [getParent](#getParent--) | 获取此弹出注释应关联的父注释。如果此条目存在，父注释的 Contents、M、C 和 T 条目将覆盖弹出注释本身的对应条目。 |
| [setOpen](#setOpen-boolean-) | 设置一个标志，指定弹出注释是否应初始显示为打开状态。 |
| [setParent](#setParent-com.aspose.pdf.MarkupAnnotation-) | 设置此弹出注释应关联的父注释。如果此条目存在，父注释的 Contents、M、C 和 T 条目将覆盖弹出注释本身的对应条目。 |

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.IDocument-}
构造函数。用于在 Generator 中使用。

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
在指定页面上创建新的 Popup 注释。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者对象以处理该注释。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 元素 @see AnnotationType

### getOpen {#getOpen--}
```
public boolean getOpen()
```

获取一个标志，指定弹出注释是否应初始显示为打开状态。

**Returns:**
布尔值

### getParent {#getParent--}
```
public Annotation getParent()
```

获取此弹出注释应关联的父注释。如果此条目存在，父注释的 Contents、M、C 和 T 条目将覆盖弹出注释本身的对应条目。

**Returns:**
MarkupAnnotation 对象

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

设置一个标志，指定弹出注释是否应初始显示为打开状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setParent {#setParent-com.aspose.pdf.MarkupAnnotation-}
设置此弹出注释应关联的父注释。如果此条目存在，父注释的 Contents、M、C 和 T 条目将覆盖弹出注释本身的对应条目。

---
title: "TextAnnotation"
linktitle: "TextAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示一个文本注释，它是附加在 PDF 文档中某一点的“便签”。"
type: docs
weight: 4920
url: /zh/java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class TextAnnotation extends MarkupAnnotation
```

表示附加在 PDF 文档某一点的 \"sticky note\" 文本注释。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextAnnotation](#TextAnnotation--) | 创建 TextAnnotation 实例 |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.IDocument-) | 创建 TextAnnotation 实例 |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 创建 TextAnnotation 实例 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者对象以处理该注释。 |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 在基类中重写定义，方法体为空。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getIcon](#getIcon--) | 获取用于显示注释的图标。 |
| [getOpen](#getOpen--) | 获取指定注释是否应初始展开的标志。 |
| [setIcon](#setIcon-int-) | 设置用于显示注释的图标。 |
| [setOpen](#setOpen-boolean-) | 设置指定注释是否应初始展开的标志。 |

### TextAnnotation {#TextAnnotation--}
```
public TextAnnotation()
```

创建 TextAnnotation 实例

### TextAnnotation {#TextAnnotation-com.aspose.pdf.IDocument-}
创建 TextAnnotation 实例

### TextAnnotation {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
创建 TextAnnotation 实例

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者对象以处理该注释。

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
在基类中重写定义，方法体为空。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 值 @see AnnotationState

### getIcon {#getIcon--}
```
public int getIcon()
```

获取用于显示注释的图标。

**Returns:**
TextIcon 值 @see TextIcon

### getOpen {#getOpen--}
```
public boolean getOpen()
```

获取指定注释是否应初始展开的标志。

**Returns:**
布尔值

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

设置用于显示注释的图标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | TextIcon 值 @see TextIcon |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

设置指定注释是否应初始展开的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

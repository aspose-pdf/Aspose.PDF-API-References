---
title: "RedactionAnnotation"
linktitle: "RedactionAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示遮蔽注释。"
type: docs
weight: 4120
url: /zh/java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.RedactionAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class RedactionAnnotation extends MarkupAnnotation
```

表示遮蔽注释。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.IDocument-) | RedactionAnnotation 的构造函数。用于在 Generator 中使用。 |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | RedactAnnotation 的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者对象以处理该注释。 |
| [flatten](#flatten--) | 将注释展平，即移除注释并添加其内容 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getBorderColor](#getBorderColor--) | 获取在未激活遮蔽时绘制的边框颜色。 |
| [getDefaultAppearance](#getDefaultAppearance--) | 获取或设置用于格式化文本的默认外观字符串。 |
| [getFillColor](#getFillColor--) | 获取用于填充注释的颜色。 |
| [getFontSize](#getFontSize--) | 获取 OverlayText 的字体大小。 |
| [getOverlayText](#getOverlayText--) | 获取在遮蔽注释上打印的文本。 |
| [getQuadPoint](#getQuadPoint--) | 一个 8xN 数字数组，指定要删除的内容区域的坐标。 |
| [getQuadPoints](#getQuadPoints--) | 获取一个点数组，指定 n 个四边形的坐标。每个四边形包含注释下文本中的一个单词或一组连续的单词。 |
| [getTextAlignment](#getTextAlignment--) | 获取 Overlay Text 的对齐方式。 |
| [isRepeat](#isRepeat--) | 如果为 true，覆盖文本将在注释上重复。 |
| [redact](#redact--) | 将注释展平并遮蔽页面内容（即移除遮蔽注释下的文本和图像内容） |
| [redactExact](#redactExact--) | 将注释展平并遮蔽页面内容（即精确移除遮蔽注释下的文本和图像内容） |
| [setBorderColor](#setBorderColor-com.aspose.pdf.Color-) | 设置在未激活遮蔽时绘制的边框颜色。 |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | 获取或设置用于格式化文本的默认外观字符串。 |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | 设置用于填充注释的颜色。 |
| [setFontSize](#setFontSize-float-) | 设置 OverlayText 的字体大小。默认值为 10。 |
| [setOverlayText](#setOverlayText-java.lang.String-) | 设置在遮蔽注释上打印的文本。 |
| [setQuadPoint](#setQuadPoint-com.aspose.pdf.Point:A-) | 一个 8xN 数字数组，指定要删除的内容区域的坐标。 |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | 设置一个点数组，指定 n 个四边形的坐标。每个四边形包含注释下文本中的一个单词或一组连续的单词。 |
| [setRepeat](#setRepeat-boolean-) | 如果为 true，覆盖文本将在注释上重复。 |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | 设置 Overlay Text 的对齐方式。 |

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.IDocument-}
RedactionAnnotation 的构造函数。用于在 Generator 中使用。

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
RedactAnnotation 的构造函数。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者对象以处理该注释。

### flatten {#flatten--}
```
public void flatten()
```

将注释展平，即移除注释并添加其内容

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 元素 @see AnnotationType

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

获取在未激活遮蔽时绘制的边框颜色。

**Returns:**
颜色值

### getDefaultAppearance {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```

获取或设置用于格式化文本的默认外观字符串。

**Returns:**
字符串值

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

获取用于填充注释的颜色。

**Returns:**
颜色值

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

获取 OverlayText 的字体大小。

**Returns:**
int 值

### getOverlayText {#getOverlayText--}
```
public String getOverlayText()
```

获取在遮蔽注释上打印的文本。

**Returns:**
string 值

### getQuadPoint {#getQuadPoint--}
```
public Point [] getQuadPoint()
```

一个 8xN 数字数组，指定要删除的内容区域的坐标。

**Returns:**
点数组

### getQuadPoints {#getQuadPoints--}
```
@Deprecated public Point [] getQuadPoints()
```

获取一个点数组，指定 n 个四边形的坐标。每个四边形包含注释下文本中的一个单词或一组连续的单词。

**Returns:**
Point 值数组

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

获取 Overlay Text 的对齐方式。

**Returns:**
HorizontalAlignment 值 @see HorizontalAlignment

### isRepeat {#isRepeat--}
```
public boolean isRepeat()
```

如果为 true，覆盖文本将在注释上重复。

**Returns:**
布尔值

### redact {#redact--}
```
public void redact()
```

将注释展平并遮蔽页面内容（即移除遮蔽注释下的文本和图像内容）

### redactExact {#redactExact--}
```
public void redactExact()
```

将注释展平并遮蔽页面内容（即精确移除遮蔽注释下的文本和图像内容）

### setBorderColor {#setBorderColor-com.aspose.pdf.Color-}
设置在未激活遮蔽时绘制的边框颜色。

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
获取或设置用于格式化文本的默认外观字符串。

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
设置用于填充注释的颜色。

### setFontSize {#setFontSize-float-}
```
public final void setFontSize(float fontSize)
```

设置 OverlayText 的字体大小。默认值为 10。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontSize |  | int 值 |

### setOverlayText {#setOverlayText-java.lang.String-}
设置在遮蔽注释上打印的文本。

### setQuadPoint {#setQuadPoint-com.aspose.pdf.Point:A-}
一个 8xN 数字数组，指定要删除的内容区域的坐标。

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
设置一个点数组，指定 n 个四边形的坐标。每个四边形包含注释下文本中的一个单词或一组连续的单词。

### setRepeat {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```

如果为 true，覆盖文本将在注释上重复。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
设置 Overlay Text 的对齐方式。

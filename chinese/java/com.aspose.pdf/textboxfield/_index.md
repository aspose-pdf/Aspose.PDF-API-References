---
title: "TextBoxField"
linktitle: "TextBoxField"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文本框字段的类。"
type: docs
weight: 4930
url: /zh/java/com.aspose.pdf/textboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class TextBoxField extends Field
```

表示文本框字段的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextBoxField](#TextBoxField--) | 创建 TextBoxField 实例。 @deprecated 若要获得完整的字段功能，需要绑定到文档 - 使用 TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-) | 创建 TextBoxField 实例。 @deprecated 若要获得完整的字段功能，需要绑定到文档 - 使用 TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | 创建 TextBoxField 实例。 @deprecated 若要获得完整的字段功能，需要绑定到文档 - 使用 TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 创建 TextBoxField 实例。 @deprecated 若要获得完整的字段功能，需要绑定到文档 - 使用 TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-) | 创建 TextBoxField 实例。 @deprecated 若要获得完整的字段功能，需要绑定到文档 - 使用 TextBoxField(Document doc) |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addBarcode](#addBarcode-java.lang.String-) | 向字段中添加条形码 128。字段值将被更改为代码，且字段将变为只读。 |
| [addImage](#addImage-java.awt.image.BufferedImage-) | 向字段资源中添加图像并绘制它。 |
| [getForceCombs](#getForceCombs--) | 获取指示字段是否被划分为间隔位置的标志。 |
| [getMaxLen](#getMaxLen--) | 获取字段中文本的最大长度。 |
| [getMultiline](#getMultiline--) | 获取字段的多行标志。如果 Multiline 为 true，则字段可以包含多行文本。 |
| [getScrollable](#getScrollable--) | 获取字段的可滚动标志。如果为 true，字段可以滚动。 |
| [getSpellCheck](#getSpellCheck--) | 获取字段的拼写检查标志。如果为 true，字段将进行拼写检查。 |
| [getTextVerticalAlignment](#getTextVerticalAlignment--) | 获取或设置注释的文本垂直对齐方式。 |
| [getValue](#getValue--) | 获取字段的值。 |
| [setForceCombs](#setForceCombs-boolean-) | 设置指示字段是否被划分为间隔位置的标志。 |
| [setJustification](#setJustification-boolean-) | 设置对齐方式 |
| [setMaxLen](#setMaxLen-int-) | 设置字段中文本的最大长度。 |
| [setMultiline](#setMultiline-boolean-) | 设置字段的多行标志。如果 Multiline 为 true，则字段可以包含多行文本。 |
| [setScrollable](#setScrollable-boolean-) | 设置字段的可滚动标志。如果为 true，字段可以滚动。 |
| [setSpellCheck](#setSpellCheck-boolean-) | 设置字段的拼写检查标志。如果为 true，字段将进行拼写检查。 |
| [setTextVerticalAlignment](#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 获取或设置注释的文本垂直对齐方式。 |
| [setValue](#setValue-java.lang.String-) | 设置字段的值。 |

### TextBoxField {#TextBoxField--}
```
@Deprecated public TextBoxField()
```

创建 TextBoxField 实例。 @deprecated 若要获得完整的字段功能，需要绑定到文档 - 使用 TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-}
创建 TextBoxField 实例。 @deprecated 若要获得完整的字段功能，需要绑定到文档 - 使用 TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
创建 TextBoxField 实例。 @deprecated 若要获得完整的字段功能，需要绑定到文档 - 使用 TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
创建 TextBoxField 实例。 @deprecated 若要获得完整的字段功能，需要绑定到文档 - 使用 TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-}
创建 TextBoxField 实例。 @deprecated 若要获得完整的字段功能，需要绑定到文档 - 使用 TextBoxField(Document doc)

### addBarcode {#addBarcode-java.lang.String-}
向字段中添加条形码 128。字段值将被更改为代码，且字段将变为只读。

### addImage {#addImage-java.awt.image.BufferedImage-}
向字段资源中添加图像并绘制它。

### getForceCombs {#getForceCombs--}
```
public boolean getForceCombs()
```

获取指示字段是否被划分为间隔位置的标志。

**Returns:**
布尔值

### getMaxLen {#getMaxLen--}
```
public int getMaxLen()
```

获取字段中文本的最大长度。

**Returns:**
int 值

### getMultiline {#getMultiline--}
```
public boolean getMultiline()
```

获取字段的多行标志。如果 Multiline 为 true，则字段可以包含多行文本。

**Returns:**
布尔值

### getScrollable {#getScrollable--}
```
public boolean getScrollable()
```

获取字段的可滚动标志。如果为 true，字段可以滚动。

**Returns:**
布尔值

### getSpellCheck {#getSpellCheck--}
```
public boolean getSpellCheck()
```

获取字段的拼写检查标志。如果为 true，字段将进行拼写检查。

**Returns:**
布尔值

### getTextVerticalAlignment {#getTextVerticalAlignment--}
```
public final VerticalAlignment getTextVerticalAlignment()
```

获取或设置注释的文本垂直对齐方式。

**Returns:**
VerticalAlignment 元素

### getValue {#getValue--}
```
public String getValue()
```

获取字段的值。

**Returns:**
字符串值

### setForceCombs {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```

设置指示字段是否被划分为间隔位置的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setJustification {#setJustification-boolean-}
```
public void setJustification(boolean value)
```

设置对齐方式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMaxLen {#setMaxLen-int-}
```
public void setMaxLen(int value)
```

设置字段中文本的最大长度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setMultiline {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```

设置字段的多行标志。如果 Multiline 为 true，则字段可以包含多行文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setScrollable {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```

设置字段的可滚动标志。如果为 true，字段可以滚动。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSpellCheck {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```

设置字段的拼写检查标志。如果为 true，字段将进行拼写检查。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTextVerticalAlignment {#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
获取或设置注释的文本垂直对齐方式。

### setValue {#setValue-java.lang.String-}
设置字段的值。

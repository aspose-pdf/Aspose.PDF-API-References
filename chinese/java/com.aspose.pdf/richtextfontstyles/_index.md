---
title: "RichTextFontStyles"
linktitle: "RichTextFontStyles"
second_title: "Aspose.PDF for Java API 参考"
description: "RichText 中文本片段样式的选项。"
type: docs
weight: 4300
url: /zh/java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

RichText 中文本片段样式的选项。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Bold](#Bold) | 指定粗体的选项。 |
| [ClearExisting](#ClearExisting) | 如果设置，则在应用其他样式之前清除所有现有样式。当与其他样式标志（例如 {@code RichTextFontStyles#Bold}）组合使用时，它首先重置样式，然后应用指定的样式。如果不使用此标志，新的样式将添加到现有样式中。 |
| [Italic](#Italic) | 指定斜体的选项。 |
| [Underline](#Underline) | 指定下划线的选项。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | 检查是否已设置指定的标志。 |

### Bold {#Bold}
```
public static final int Bold
```

指定粗体的选项。

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

如果设置，则在应用其他样式之前清除所有现有样式。当与其他样式标志（例如 {@code RichTextFontStyles#Bold}）组合使用时，它首先重置样式，然后应用指定的样式。如果不使用此标志，新的样式将添加到现有样式中。

### Italic {#Italic}
```
public static final int Italic
```

指定斜体的选项。

### Underline {#Underline}
```
public static final int Underline
```

指定下划线的选项。

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

检查是否已设置指定的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| flag |  | 表示要检查的标志的枚举值 |
| flagToCheck |  | 表示要检查的标志的枚举值 |

**Returns:**
{@code true} 如果标志已设置；{@code false} 否则

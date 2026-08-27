---
title: "TextDefaults.DefaultFontStrategy"
linktitle: "TextDefaults.DefaultFontStrategy"
second_title: "Aspose.PDF for Java API 参考"
description: "指定文本子系统默认值的类型"
type: docs
weight: 4960
url: /zh/java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

指定文本子系统默认值的类型

## 字段

| 字段 | 描述 |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | 使用预定义的 Font 实例列表中的默认字体。可以使用 setDefaultFonts(List of Font instances) 进行设置。将使用第一个包含文本所需所有字符的字体。如果未找到此类字体，将使用系统字体。 |
| [PredefinedFont](#PredefinedFont) | 使用默认字体。可以通过 set/get PredefinedFont(Font) 设置，如果 PredefinedFont 为 null，将使用 SystemFont。 |
| [SystemFont](#SystemFont) | 使用默认系统字体 Helvetica，或其替代等价字体。 |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | 将使用找到的第一个包含文本所有必要字符的字体。所有找到的字体都会被考虑。如果未找到此类字体，将使用系统字体。 |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

使用预定义的 Font 实例列表中的默认字体。可以使用 setDefaultFonts(List of Font instances) 进行设置。将使用第一个包含文本所需所有字符的字体。如果未找到此类字体，将使用系统字体。

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

使用默认字体。可以通过 set/get PredefinedFont(Font) 设置，如果 PredefinedFont 为 null，将使用 SystemFont。

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

使用默认系统字体 Helvetica，或其替代等价字体。

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

将使用找到的第一个包含文本所有必要字符的字体。所有找到的字体都会被考虑。如果未找到此类字体，将使用系统字体。

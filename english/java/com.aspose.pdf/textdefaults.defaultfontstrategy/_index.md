---
title: TextDefaults.DefaultFontStrategy
second_title: Aspose.PDF for Java API Reference
description: Specifies type of text subsystem defaults
type: docs
weight: 4960
url: /java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

Specifies type of text subsystem defaults

## Fields

| Field | Description |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | Use default font from predefined list of Font instances. Can be set using setDefaultFonts(List of Font instances) Will be used the first found font that contains all required characters for text. If such font not found - will be used System font. |
| [PredefinedFont](#PredefinedFont) | Use default font that. Can be set using set/get PredefinedFont(Font) if PredefinedFont is null - will be used SystemFont |
| [SystemFont](#SystemFont) | Use default system font Helvetica, or it's substituted analogue. |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | The first font found will be used, containing all the necessary characters for the text. All fonts found will be involved. If such font not found - will be used System font. |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

Use default font from predefined list of Font instances. Can be set using setDefaultFonts(List of Font instances) Will be used the first found font that contains all required characters for text. If such font not found - will be used System font.

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

Use default font that. Can be set using set/get PredefinedFont(Font) if PredefinedFont is null - will be used SystemFont

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

Use default system font Helvetica, or it's substituted analogue.

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

The first font found will be used, containing all the necessary characters for the text. All fonts found will be involved. If such font not found - will be used System font.

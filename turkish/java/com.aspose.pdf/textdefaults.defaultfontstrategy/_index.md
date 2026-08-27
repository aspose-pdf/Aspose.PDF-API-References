---
title: "TextDefaults.DefaultFontStrategy"
linktitle: "TextDefaults.DefaultFontStrategy"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin alt sisteminin varsayılan türünü belirtir"
type: docs
weight: 4960
url: /tr/java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

Metin alt sisteminin varsayılan türünü belirtir

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | Önceden tanımlanmış Font örnekleri listesinden varsayılan fontu kullanın. setDefaultFonts(List of Font instances) kullanılarak ayarlanabilir. Metin için gerekli tüm karakterleri içeren ilk bulunan font kullanılacaktır. Böyle bir font bulunamazsa Sistem fontu kullanılacaktır. |
| [PredefinedFont](#PredefinedFont) | Bu varsayılan fontu kullanın. set/get PredefinedFont(Font) kullanılarak ayarlanabilir; PredefinedFont null ise SystemFont kullanılacaktır. |
| [SystemFont](#SystemFont) | Varsayılan sistem fontu Helvetica'yı kullanın, ya da onun yerine geçen benzerini. |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | Metin için gerekli tüm karakterleri içeren ilk bulunan font kullanılacaktır. Bulunan tüm fontlar dahil edilecektir. Böyle bir font bulunamazsa Sistem fontu kullanılacaktır. |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

Önceden tanımlanmış Font örnekleri listesinden varsayılan fontu kullanın. setDefaultFonts(List of Font instances) kullanılarak ayarlanabilir. Metin için gerekli tüm karakterleri içeren ilk bulunan font kullanılacaktır. Böyle bir font bulunamazsa Sistem fontu kullanılacaktır.

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

Bu varsayılan fontu kullanın. set/get PredefinedFont(Font) kullanılarak ayarlanabilir; PredefinedFont null ise SystemFont kullanılacaktır.

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

Varsayılan sistem fontu Helvetica'yı kullanın, ya da onun yerine geçen benzerini.

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

Metin için gerekli tüm karakterleri içeren ilk bulunan font kullanılacaktır. Bulunan tüm fontlar dahil edilecektir. Böyle bir font bulunamazsa Sistem fontu kullanılacaktır.

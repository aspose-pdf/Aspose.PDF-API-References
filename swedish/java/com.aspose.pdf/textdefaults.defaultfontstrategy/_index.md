---
title: "TextDefaults.DefaultFontStrategy"
linktitle: "TextDefaults.DefaultFontStrategy"
second_title: "Aspose.PDF för Java API-referens"
description: "Anger typ av standardinställningar för textsystemet"
type: docs
weight: 4960
url: /sv/java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

Anger typ av standardinställningar för textsystemet

## Fält

| Fält | Beskrivning |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | Använd standardtypsnitt från fördefinierad lista med Font-instansers. Kan ställas in med setDefaultFonts(List of Font instances). Det första hittade typsnittet som innehåller alla nödvändiga tecken för texten kommer att användas. Om ett sådant typsnitt inte hittas – används System-typsnitt. |
| [PredefinedFont](#PredefinedFont) | Använd standardtypsnittet. Kan ställas in med set/get PredefinedFont(Font) om PredefinedFont är null – används SystemFont. |
| [SystemFont](#SystemFont) | Använd standard systemtypsnitt Helvetica, eller dess ersättningsanalog. |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | Det första hittade typsnittet som innehåller alla nödvändiga tecken för texten kommer att användas. Alla hittade typsnitt kommer att beaktas. Om ett sådant typsnitt inte hittas – används System-typsnitt. |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

Använd standardtypsnitt från fördefinierad lista med Font-instansers. Kan ställas in med setDefaultFonts(List of Font instances). Det första hittade typsnittet som innehåller alla nödvändiga tecken för texten kommer att användas. Om ett sådant typsnitt inte hittas – används System-typsnitt.

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

Använd standardtypsnittet. Kan ställas in med set/get PredefinedFont(Font) om PredefinedFont är null – används SystemFont.

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

Använd standard systemtypsnitt Helvetica, eller dess ersättningsanalog.

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

Det första hittade typsnittet som innehåller alla nödvändiga tecken för texten kommer att användas. Alla hittade typsnitt kommer att beaktas. Om ett sådant typsnitt inte hittas – används System-typsnitt.

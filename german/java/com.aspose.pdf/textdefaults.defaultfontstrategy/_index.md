---
title: "TextDefaults.DefaultFontStrategy"
linktitle: "TextDefaults.DefaultFontStrategy"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Gibt den Typ der Standardeinstellungen des Text-Subsystems an"
type: docs
weight: 4960
url: /de/java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

Gibt den Typ der Standardeinstellungen des Text-Subsystems an

## Felder

| Feld | Beschreibung |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | Verwenden Sie die Standardschriftart aus einer vordefinierten Liste von Font-Instanzen. Kann mit setDefaultFonts(Liste von Font-Instanzen) festgelegt werden. Es wird die zuerst gefundene Schriftart verwendet, die alle für den Text erforderlichen Zeichen enthält. Wenn eine solche Schriftart nicht gefunden wird, wird die Systemschriftart verwendet. |
| [PredefinedFont](#PredefinedFont) | Verwenden Sie die Standardschriftart. Kann mit set/get PredefinedFont(Font) festgelegt werden; wenn PredefinedFont null ist, wird SystemFont verwendet. |
| [SystemFont](#SystemFont) | Verwenden Sie die Standardsystemschriftart Helvetica oder deren ersetzendes Gegenstück. |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | Die zuerst gefundene Schriftart, die alle für den Text notwendigen Zeichen enthält, wird verwendet. Alle gefundenen Schriftarten werden berücksichtigt. Wenn eine solche Schriftart nicht gefunden wird, wird die Systemschriftart verwendet. |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

Verwenden Sie die Standardschriftart aus einer vordefinierten Liste von Font-Instanzen. Kann mit setDefaultFonts(Liste von Font-Instanzen) festgelegt werden. Es wird die zuerst gefundene Schriftart verwendet, die alle für den Text erforderlichen Zeichen enthält. Wenn eine solche Schriftart nicht gefunden wird, wird die Systemschriftart verwendet.

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

Verwenden Sie die Standardschriftart. Kann mit set/get PredefinedFont(Font) festgelegt werden; wenn PredefinedFont null ist, wird SystemFont verwendet.

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

Verwenden Sie die Standardsystemschriftart Helvetica oder deren ersetzendes Gegenstück.

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

Die zuerst gefundene Schriftart, die alle für den Text notwendigen Zeichen enthält, wird verwendet. Alle gefundenen Schriftarten werden berücksichtigt. Wenn eine solche Schriftart nicht gefunden wird, wird die Systemschriftart verwendet.

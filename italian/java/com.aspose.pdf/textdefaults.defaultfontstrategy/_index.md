---
title: "TextDefaults.DefaultFontStrategy"
linktitle: "TextDefaults.DefaultFontStrategy"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Specifica il tipo di valori predefiniti del sottosistema di testo"
type: docs
weight: 4960
url: /it/java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

Specifica il tipo di valori predefiniti del sottosistema di testo

## Campi

| Campo | Descrizione |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | Utilizza il font predefinito dall'elenco predefinito di istanze Font. Può essere impostato usando setDefaultFonts(List of Font instances) Verrà utilizzato il primo font trovato che contiene tutti i caratteri richiesti per il testo. Se tale font non viene trovato - verrà utilizzato il font di sistema. |
| [PredefinedFont](#PredefinedFont) | Utilizza il font predefinito. Può essere impostato usando set/get PredefinedFont(Font) se PredefinedFont è null - verrà utilizzato SystemFont. |
| [SystemFont](#SystemFont) | Utilizza il font di sistema predefinito Helvetica, o il suo analogo sostitutivo. |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | Il primo font trovato sarà utilizzato, contenente tutti i caratteri necessari per il testo. Tutti i font trovati saranno coinvolti. Se tale font non viene trovato - verrà utilizzato il font di sistema. |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

Utilizza il font predefinito dall'elenco predefinito di istanze Font. Può essere impostato usando setDefaultFonts(List of Font instances) Verrà utilizzato il primo font trovato che contiene tutti i caratteri richiesti per il testo. Se tale font non viene trovato - verrà utilizzato il font di sistema.

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

Utilizza il font predefinito. Può essere impostato usando set/get PredefinedFont(Font) se PredefinedFont è null - verrà utilizzato SystemFont.

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

Utilizza il font di sistema predefinito Helvetica, o il suo analogo sostitutivo.

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

Il primo font trovato sarà utilizzato, contenente tutti i caratteri necessari per il testo. Tutti i font trovati saranno coinvolti. Se tale font non viene trovato - verrà utilizzato il font di sistema.

---
title: "RichTextFontStyles"
linktitle: "RichTextFontStyles"
second_title: "Aspose.PDF för Java API-referens"
description: "Alternativ för formatering av textfragment i RichText."
type: docs
weight: 4300
url: /sv/java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

Alternativ för formatering av textfragment i RichText.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Bold](#Bold) | Alternativ som specificerar fetstil. |
| [ClearExisting](#ClearExisting) | Om den är satt rensas alla befintliga stilar innan ytterligare stilar tillämpas. När den kombineras med andra stilflaggor (t.ex. {@code RichTextFontStyles#Bold}) återställer den först stilarna och tillämpar sedan de angivna. Utan detta flagga läggs nya stilar till de befintliga. |
| [Italic](#Italic) | Alternativ som specificerar kursiv. |
| [Underline](#Underline) | Alternativ som specificerar understrykning. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | Kontrollerar om den angivna flaggan är satt. |

### Bold {#Bold}
```
public static final int Bold
```

Alternativ som specificerar fetstil.

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

Om den är satt rensas alla befintliga stilar innan ytterligare stilar tillämpas. När den kombineras med andra stilflaggor (t.ex. {@code RichTextFontStyles#Bold}) återställer den först stilarna och tillämpar sedan de angivna. Utan detta flagga läggs nya stilar till de befintliga.

### Italic {#Italic}
```
public static final int Italic
```

Alternativ som specificerar kursiv.

### Underline {#Underline}
```
public static final int Underline
```

Alternativ som specificerar understrykning.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

Kontrollerar om den angivna flaggan är satt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flagga |  | enum‑värdet som representerar flaggan att kontrollera |
| flagToCheck |  | enum‑värdet som representerar flaggan att kontrollera |

**Returns:**
{@code true} om flaggan är satt; {@code false} annars

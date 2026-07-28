---
title: "TextReplaceOptions.ReplaceAdjustment"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "Aspose.PDF för Java API-referens"
description: "Bestämmer åtgärden som ska utföras efter ersättning av textfragment till kortare. None - ingen åtgärd, ersatt text kan överlappa resten av raden; AdjustSpaceWidth - försöker justera."
type: docs
weight: 5270
url: /sv/java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

Bestämmer åtgärden som ska utföras efter ersättning av textfragment till kortare. None - ingen åtgärd, ersatt text kan överlappa resten av raden; AdjustSpaceWidth - försöker justera mellanslag mellan ord för att behålla radlängden; WholeWordsHyphenation - försöker fördela ord mellan paragrafrader för att behålla paragrafens högra fält; ShiftRestOfLine - förskjuter resten av raden enligt förändrad textlängd, radlängden kan ändras; Standardvärdet är ShiftRestOfLine.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | Försöker justera mellanslag mellan ord för att behålla radlängden |
| [IsFormFillingMode](#IsFormFillingMode) | Försöker sprida orden i det tillgängliga vita utrymmet med hjälp av styckets bredd. Om texten överskrider, kommer den att döljas. |
| [None](#None) | Ingen åtgärd, ersatt text kan överlappa resten av raden |
| [ShiftRestOfLine](#ShiftRestOfLine) | (Standard) Skiftar resten av raden enligt förändrad textlängd, radens längd kan ändras |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | Försöker fördela ord mellan styckesrader för att behålla styckets högra fält |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

Försöker justera mellanslag mellan ord för att behålla radlängden

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

Försöker sprida orden i det tillgängliga vita utrymmet med hjälp av styckets bredd. Om texten överskrider, kommer den att döljas.

### None {#None}
```
public static final int None
```

Ingen åtgärd, ersatt text kan överlappa resten av raden

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(Standard) Skiftar resten av raden enligt förändrad textlängd, radens längd kan ändras

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

Försöker fördela ord mellan styckesrader för att behålla styckets högra fält

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flagga |  |  |
| flagToCheck |  |  |

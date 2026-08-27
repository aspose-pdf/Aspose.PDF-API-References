---
title: "TextExtractionOptions.TextFormattingMode"
linktitle: "TextExtractionOptions.TextFormattingMode"
second_title: "Aspose.PDF för Java API-referens"
description: "Definierar olika lägen som kan användas vid konvertering av pdf-dokument till text. Se {@code TextDevice}-klassen."
type: docs
weight: 5070
url: /sv/java/com.aspose.pdf/textextractionoptions.textformattingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.Enum, com.aspose.pdf.TextExtractionOptions.TextFormattingMode

```
public static final class TextExtractionOptions.TextFormattingMode extends com.aspose.ms.System.Enum
```

Definierar olika lägen som kan användas vid konvertering av pdf-dokument till text. Se {@code TextDevice}-klassen.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Flatten](#Flatten) | Representerar pdf-innehåll med placerade textfragment efter deras koordinater. Det är i princip liknande \"Raw\"-läget. Men medan \"Raw\" fokuserar på att bevara strukturen för textfragment (operatorer) i ett dokument, fokuserar \"Flatten\" på att hålla texten i den ordning den läses. |
| [MemorySaving](#MemorySaving) | Extraktion med minnessparande. Det är nästan samma som 'Raw'-läget men fungerar något snabbare och använder mindre minne. |
| [Pure](#Pure) | Representerar pdf-innehåll med en del formateringsrutiner. |
| [Raw](#Raw) | Representerar pdf-innehåll som det är, d.v.s. utan formatering. |

### Flatten {#Flatten}
```
public static final int Flatten
```

Representerar pdf-innehåll med placerade textfragment efter deras koordinater. Det är i princip liknande \"Raw\"-läget. Men medan \"Raw\" fokuserar på att bevara strukturen för textfragment (operatorer) i ett dokument, fokuserar \"Flatten\" på att hålla texten i den ordning den läses.

### MemorySaving {#MemorySaving}
```
public static final int MemorySaving
```

Extraktion med minnessparande. Det är nästan samma som 'Raw'-läget men fungerar något snabbare och använder mindre minne.

### Pure {#Pure}
```
public static final int Pure
```

Representerar pdf-innehåll med en del formateringsrutiner.

### Raw {#Raw}
```
public static final int Raw
```

Representerar pdf-innehåll som det är, d.v.s. utan formatering.

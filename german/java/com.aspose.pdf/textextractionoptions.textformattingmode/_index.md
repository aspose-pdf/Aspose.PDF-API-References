---
title: "TextExtractionOptions.TextFormattingMode"
linktitle: "TextExtractionOptions.TextFormattingMode"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Definiert verschiedene Modi, die beim Konvertieren eines PDF-Dokuments in Text verwendet werden können. Siehe {@code TextDevice}-Klasse."
type: docs
weight: 5070
url: /de/java/com.aspose.pdf/textextractionoptions.textformattingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.Enum, com.aspose.pdf.TextExtractionOptions.TextFormattingMode

```
public static final class TextExtractionOptions.TextFormattingMode extends com.aspose.ms.System.Enum
```

Definiert verschiedene Modi, die beim Konvertieren eines PDF-Dokuments in Text verwendet werden können. Siehe {@code TextDevice}-Klasse.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Flatten](#Flatten) | Stellt PDF-Inhalt mit positionierten Textfragmenten anhand ihrer Koordinaten dar. Er ist im Wesentlichen ähnlich dem "Raw"-Modus. Während "Raw" jedoch darauf abzielt, die Struktur der Textfragmente (Operatoren) in einem Dokument zu erhalten, konzentriert sich "Flatten" darauf, den Text in der Lesereihenfolge zu behalten. |
| [MemorySaving](#MemorySaving) | Extraktion mit Speicherersparnis. Sie ist fast identisch zum "Raw"-Modus, arbeitet jedoch etwas schneller und verbraucht weniger Speicher. |
| [Pure](#Pure) | Stellt PDF-Inhalt mit ein wenig Formatierungsroutinen dar. |
| [Raw](#Raw) | Stellt PDF-Inhalt unverändert dar, d. i. ohne Formatierung. |

### Flatten {#Flatten}
```
public static final int Flatten
```

Stellt PDF-Inhalt mit positionierten Textfragmenten anhand ihrer Koordinaten dar. Er ist im Wesentlichen ähnlich dem "Raw"-Modus. Während "Raw" jedoch darauf abzielt, die Struktur der Textfragmente (Operatoren) in einem Dokument zu erhalten, konzentriert sich "Flatten" darauf, den Text in der Lesereihenfolge zu behalten.

### MemorySaving {#MemorySaving}
```
public static final int MemorySaving
```

Extraktion mit Speicherersparnis. Sie ist fast identisch zum "Raw"-Modus, arbeitet jedoch etwas schneller und verbraucht weniger Speicher.

### Pure {#Pure}
```
public static final int Pure
```

Stellt PDF-Inhalt mit ein wenig Formatierungsroutinen dar.

### Raw {#Raw}
```
public static final int Raw
```

Stellt PDF-Inhalt unverändert dar, d. i. ohne Formatierung.

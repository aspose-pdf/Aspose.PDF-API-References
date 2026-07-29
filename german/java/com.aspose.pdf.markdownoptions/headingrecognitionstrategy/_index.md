---
title: "HeadingRecognitionStrategy"
linktitle: "HeadingRecognitionStrategy"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Typen von Header-Erkennungsstrategien dar."
type: docs
weight: 30
url: /de/java/com.aspose.pdf.markdownoptions/headingrecognitionstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy

```
public final class HeadingRecognitionStrategy extends com.aspose.ms.System.Enum
```

Stellt Typen von Header-Erkennungsstrategien dar.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Auto](#Auto) | Stellt eine automatische Auswahl der Header-Erkennungsstrategie bereit. Dies ist die Standardoption. Wenn das Dokument Lesezeichen enthält, wird die {@link HeadingRecognitionStrategy#Outlines} Strategie ausgewählt, andernfalls {@link HeadingRecognitionStrategy#Heuristic}. |
| [Heuristic](#Heuristic) | Stellt die Header-Erkennungsstrategie mittels heuristischer Regeln und Schriftgrößenstatistik dar. |
| [None](#None) | Erkenne keine Header. Diese Option kann bei komplex formatierten Dokumenten nützlich sein. |
| [Outlines](#Outlines) | Stellt die Header-Erkennungsstrategie mittels Gliederungen dar. |

### Auto {#Auto}
```
public static final int Auto
```

Stellt eine automatische Auswahl der Header-Erkennungsstrategie bereit. Dies ist die Standardoption. Wenn das Dokument Lesezeichen enthält, wird die {@link HeadingRecognitionStrategy#Outlines} Strategie ausgewählt, andernfalls {@link HeadingRecognitionStrategy#Heuristic}.

### Heuristic {#Heuristic}
```
public static final int Heuristic
```

Stellt die Header-Erkennungsstrategie mittels heuristischer Regeln und Schriftgrößenstatistik dar.

### None {#None}
```
public static final int None
```

Erkenne keine Header. Diese Option kann bei komplex formatierten Dokumenten nützlich sein.

### Outlines {#Outlines}
```
public static final int Outlines
```

Stellt die Header-Erkennungsstrategie mittels Gliederungen dar.

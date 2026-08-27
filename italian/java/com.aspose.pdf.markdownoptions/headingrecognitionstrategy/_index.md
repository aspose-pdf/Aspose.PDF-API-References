---
title: "HeadingRecognitionStrategy"
linktitle: "HeadingRecognitionStrategy"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta i tipi di strategie di riconoscimento delle intestazioni."
type: docs
weight: 30
url: /it/java/com.aspose.pdf.markdownoptions/headingrecognitionstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy

```
public final class HeadingRecognitionStrategy extends com.aspose.ms.System.Enum
```

Rappresenta i tipi di strategie di riconoscimento delle intestazioni.

## Campi

| Campo | Descrizione |
| --- | --- |
| [Auto](#Auto) | Fornisce una selezione automatica della strategia di riconoscimento delle intestazioni. Questa è l'opzione predefinita. Se il documento contiene segnalibri, verrà selezionata la strategia {@link HeadingRecognitionStrategy#Outlines}, altrimenti {@link HeadingRecognitionStrategy#Heuristic}. |
| [Heuristic](#Heuristic) | Rappresenta la strategia di riconoscimento delle intestazioni mediante regole euristiche e statistiche sulla dimensione del carattere. |
| [None](#None) | Non riconoscere le intestazioni. Questa opzione può essere utile in documenti formattati in modo complesso. |
| [Outlines](#Outlines) | Rappresenta la strategia di riconoscimento delle intestazioni mediante outline. |

### Auto {#Auto}
```
public static final int Auto
```

Fornisce una selezione automatica della strategia di riconoscimento delle intestazioni. Questa è l'opzione predefinita. Se il documento contiene segnalibri, verrà selezionata la strategia {@link HeadingRecognitionStrategy#Outlines}, altrimenti {@link HeadingRecognitionStrategy#Heuristic}.

### Heuristic {#Heuristic}
```
public static final int Heuristic
```

Rappresenta la strategia di riconoscimento delle intestazioni mediante regole euristiche e statistiche sulla dimensione del carattere.

### None {#None}
```
public static final int None
```

Non riconoscere le intestazioni. Questa opzione può essere utile in documenti formattati in modo complesso.

### Outlines {#Outlines}
```
public static final int Outlines
```

Rappresenta la strategia di riconoscimento delle intestazioni mediante outline.

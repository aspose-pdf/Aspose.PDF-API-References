---
title: "HtmlSaveOptions.FontEncodingRules"
linktitle: "HtmlSaveOptions.FontEncodingRules"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa enumerazione definisce le regole che regolano la logica di codifica"
type: docs
weight: 2050
url: /it/java/com.aspose.pdf/htmlsaveoptions.fontencodingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.FontEncodingRules

```
public static final class HtmlSaveOptions.FontEncodingRules extends com.aspose.ms.System.Enum
```

Questa enumerazione definisce le regole che regolano la logica di codifica

## Campi

| Campo | Descrizione |
| --- | --- |
| [DecreaseToUnicodePriorityLevel](#DecreaseToUnicodePriorityLevel) | ToUnicode è un meccanismo speciale che aiuta a decodificare i codici di input in simboli unicode. Secondo la specifica deve essere utilizzato come primo di tutti i meccanismi per ottenere simboli unicode per un codice di input specifico. Tuttavia alcuni documenti hanno caratteri non standard e per convertire correttamente questi documenti potrebbe essere necessario diminuire la priorità di ToUnicode e utilizzare altri meccanismi per decodificare i codici di input. |
| [Default](#Default) | Lascia la logica di codifica "as is" - in conformità con la specifica PDF |

### DecreaseToUnicodePriorityLevel {#DecreaseToUnicodePriorityLevel}
```
public static final byte DecreaseToUnicodePriorityLevel
```

ToUnicode è un meccanismo speciale che aiuta a decodificare i codici di input in simboli unicode. Secondo la specifica deve essere utilizzato come primo di tutti i meccanismi per ottenere simboli unicode per un codice di input specifico. Tuttavia alcuni documenti hanno caratteri non standard e per convertire correttamente questi documenti potrebbe essere necessario diminuire la priorità di ToUnicode e utilizzare altri meccanismi per decodificare i codici di input.

### Default {#Default}
```
public static final byte Default
```

Lascia la logica di codifica "as is" - in conformità con la specifica PDF

---
title: "Enum HtmlSaveOptions.FontEncodingRules"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.HtmlSaveOptionsFontEncodingRules enum. Questa enumerazione definisce le regole che regolano la logica di codifica"
type: docs
weight: 5750
url: /it/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules enumeration

Questa enumerazione definisce le regole che regolano la logica di codifica

```csharp
public enum FontEncodingRules : byte
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Default | `0` | Lascia la logica di codifica "così com'è" - in conformità con la specifica PDF |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode è un meccanismo speciale che aiuta a decodificare i codici di input in simboli unicode. Secondo la specifica deve essere utilizzato come primo meccanismo per ottenere simboli unicode per un codice di input specifico. Tuttavia, alcuni documenti hanno caratteri non standard e per convertire correttamente questi documenti potrebbe essere necessario diminuire la priorità di ToUnicode e utilizzare altri meccanismi per decodificare i codici di input. |

### Vedi anche

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)



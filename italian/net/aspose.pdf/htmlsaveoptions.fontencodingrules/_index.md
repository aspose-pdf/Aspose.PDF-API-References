---
title: Enum HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for .NET API Reference
description: Questa enumerazione definisce regole che regolano la logica di codifica.
type: docs
weight: 5620
url: /it/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## Enumerazione HtmlSaveOptions.FontEncodingRules

Questa enumerazione definisce regole che ottimizzano la logica di codifica

```csharp
public enum FontEncodingRules : byte
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Default | `0` | Lascia la logica di codifica "così com'è" - in conformità con la specifica PDF |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode è un meccanismo speciale che aiuta a decodificare i codici di input in simboli unicode. Secondo la specifica, deve essere utilizzato prima di tutti i meccanismi per ottenere simboli unicode per un codice di input specifico. Ma alcuni documenti hanno font non standard e per convertire correttamente questi documenti potrebbe essere necessario diminuire la priorità di ToUnicode e utilizzare altri meccanismi per decodificare i codici di input. |

### Vedi Anche

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)
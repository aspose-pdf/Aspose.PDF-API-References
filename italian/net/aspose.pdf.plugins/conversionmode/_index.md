---
title: Enum ConversionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.ConversionMode enum. Defines conversion mode of the output document
type: docs
weight: 8500
url: /it/net/aspose.pdf.plugins/conversionmode/
---
## Enumerazione ConversionMode

Definisce la modalità di conversione del documento di output.

```csharp
public enum ConversionMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| TextBox | `0` | Questa modalità è veloce e buona per preservare al massimo l'aspetto originale del file PDF, ma la modificabilità del documento risultante potrebbe essere limitata. |
| Flow | `1` | Modalità di riconoscimento completo, il motore esegue raggruppamenti e analisi multi-livello per ripristinare l'intento originale dell'autore del documento e produrre un documento massimamente modificabile. Lo svantaggio è che il documento di output potrebbe apparire diverso dal file PDF originale. |
| EnhancedFlow | `2` | Una modalità Flow alternativa che supporta il riconoscimento delle tabelle. |

### Vedi Anche

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)
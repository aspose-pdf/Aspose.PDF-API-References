---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OpzioniDiSalvataggioHtml.AntialiasingProcessingType enum. Questo enum spiega le misure antialiasing possibili durante la conversione.
type: docs
weight: 5570
url: /it/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## Enumerazione HtmlSaveOptions.AntialiasingProcessingType

Questo enum descrive le possibili misure di antialiasing durante la conversione

```csharp
public enum AntialiasingProcessingType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | nessun trattamento speciale di antialiasing in uso. Questa è un'opzione ottimale per la stragrande maggioranza dei documenti e non richiede tempo aggiuntivo durante la conversione |
| TryCorrectResultHtml | `1` | In tal caso, il convertitore cerca di rilevare i luoghi con elementi grafici di sfondo adiacenti e correggere il risultato HTML in modo pertinente. Questa opzione consente di migliorare il risultato dell'esportazione per documenti che contengono sfondi costruiti da diversi elementi grafici adiacenti (per questo tipo di documenti, i renderer PDF, ad esempio Acrobat Reader, di solito cercano di levigare i confini degli elementi durante il rendering. Con questa opzione, il convertitore imita quel comportamento dei renderer PDF. Questa opzione consente di migliorare il layout del risultato dell'esportazione per alcuni documenti specifici (che utilizzano tali sfondi composti), ma richiede tempo aggiuntivo per l'elaborazione (di solito circa il 10-15% di tempo aggiuntivo). Quindi, l'uso di questa modalità in generale non è raccomandato. |

### Vedi Anche

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)
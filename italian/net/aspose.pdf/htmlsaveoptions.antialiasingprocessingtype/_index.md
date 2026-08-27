---
title: "Enum HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType. Questa enum descrive le possibili misure di antialiasing durante la conversione"
type: docs
weight: 5700
url: /it/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

Questa enum descrive le possibili misure di antialiasing durante la conversione

```csharp
public enum AntialiasingProcessingType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | Nessuna elaborazione speciale di antialiasing in uso. Questa è un'opzione ottimale per la stragrande maggioranza dei documenti e non richiede tempo aggiuntivo durante la conversione |
| TryCorrectResultHtml | `1` | In tal caso il convertitore tenta di rilevare le aree con elementi grafici di sfondo adiacenti e correggere l'HTML risultante in modo appropriato. Questa opzione consente di migliorare il risultato dell'esportazione per i documenti che contengono sfondi costruiti da diversi elementi grafici adiacenti (per questo tipo di documenti i renderizzatori PDF, ad es. Acrobat Reader, solitamente cercano di smussare i contorni degli elementi durante il rendering). Questa opzione consente di migliorare il layout del risultato dell'esportazione per alcuni documenti specifici (che utilizzano tali sfondi composti), ma richiede tempo aggiuntivo per l'elaborazione (di solito circa il 10‑15% di tempo in più). Pertanto l'uso di questa modalità in casi generali non è consigliato. |

### Vedi anche

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)



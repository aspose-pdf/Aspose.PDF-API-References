---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsMarginsAreaUsageModes enum. Rappresenta il modulo dell'uso dell'area delle margine durante la conversione, come HTML EPUB ecc., che definisce il trattamento delle istruzioni del formato importato relative all'utilizzo delle margine.
type: docs
weight: 6130
url: /it/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## Enumerazione LoadOptions.MarginsAreaUsageModes

Rappresenta la modalità di utilizzo dell'area dei margini durante la conversione (come HTML, EPUB ecc.), definisce il trattamento delle istruzioni del formato importato relative all'uso dei margini.

```csharp
public enum MarginsAreaUsageModes
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | In questa modalità il convertitore obbedisce al formato del documento importato (ad es. CSS dell'HTML importato) nell'uso dell'area dei margini. Quindi, se il formato del documento importato richiede l'uso dell'area dei margini per il rendering, il convertitore lo permetterà |
| NeverPutContentOnMarginArea | `1` | Questa modalità vieta rigorosamente l'uso dell'area dei margini, quindi, il convertitore non utilizzerà mai l'area dei margini per il rendering, anche se il CSS o il formato del documento sorgente lo consente o lo richiede |

### Vedi Anche

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)
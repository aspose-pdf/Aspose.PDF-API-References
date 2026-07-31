---
title: "Enum LoadOptions.MarginsAreaUsageModes"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.LoadOptionsMarginsAreaUsageModes enum. Rappresenta la modalità di utilizzo dell'area dei margini durante la conversione, come HTML, EPUB, ecc., definisce il trattamento delle istruzioni del formato importato relative all'uso dei margini"
type: docs
weight: 6270
url: /it/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes enumeration

Rappresenta la modalità di utilizzo dell'area dei margini durante la conversione (come HTML, EPUB, ecc.), definisce il trattamento delle istruzioni del formato importato relative all'uso dei margini.

```csharp
public enum MarginsAreaUsageModes
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | In questa modalità il convertitore rispetta il formato del documento importato (ad es. CSS dell'HTML importato) nell'uso dell'area dei margini. Quindi, se il formato del documento importato richiede l'uso dell'area dei margini per il rendering, il convertitore lo consentirà. |
| NeverPutContentOnMarginArea | `1` | Questa modalità vieta rigorosamente l'uso dell'area dei margini, quindi il convertitore non utilizzerà mai l'area dei margini per il rendering, anche se CSS o il formato del documento sorgente lo consentono o lo richiedono. |

### Vedi anche

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)



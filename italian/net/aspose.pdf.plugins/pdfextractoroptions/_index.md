---
title: Class PdfExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PdfExtractorOptions. Rappresenta le opzioni per i plugin TextExtractor e ImageExtractor
type: docs
weight: 9070
url: /it/net/aspose.pdf.plugins/pdfextractoroptions/
---
## Classe PdfExtractorOptions

Rappresenta le opzioni per i plugin TextExtractor e ImageExtractor.

```csharp
public abstract class PdfExtractorOptions : IPluginOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Restituisce la raccolta di dati del plugin PdfExtractor. |
| virtual [OperationName](../../aspose.pdf.plugins/pdfextractoroptions/operationname/) { get; } | Restituisce il nome dell'operazione |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Aggiunge una nuova sorgente di dati alla raccolta di dati del plugin PdfExtractor. |

## Osservazioni

Il `PdfExtractorOptions` contiene funzioni di base per aggiungere dati (file, flussi) che rappresentano documenti PDF di input. Si prega di creare [`TextExtractorOptions`](../textextractoroptions/) o ImageExtractorOptions invece di questo.

### Vedi Anche

* interfaccia [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)
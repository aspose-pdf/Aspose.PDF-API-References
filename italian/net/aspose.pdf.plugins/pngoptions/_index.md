---
title: Class PngOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PngOptions. Rappresenta le opzioni del convertitore da Pdf a Png per il plugin Png
type: docs
weight: 9180
url: /it/net/aspose.pdf.plugins/pngoptions/
---
## Classe PngOptions

Rappresenta le opzioni del convertitore da Pdf a Png per il plugin [`Png`](../png/).

```csharp
public sealed class PngOptions : PdfToImageOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PngOptions](pngoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Ottiene la modalità di conversione delle immagini. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Restituisce la raccolta di dati del plugin [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/pngoptions/operationname/) { get; } | Restituisce il nome dell'operazione. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Ottiene o imposta il valore di risoluzione delle immagini risultanti. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Ottiene o imposta un elenco di pagine per il processo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Aggiunge una nuova sorgente di dati alla raccolta di dati del plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Imposta una nuova sorgente di dati per il salvataggio. Può essere solo un . Se vuoi salvare le immagini in flussi di memoria, passa null come parametro. |

### Vedi Anche

* classe [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)
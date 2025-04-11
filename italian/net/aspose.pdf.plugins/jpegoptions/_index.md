---
title: Class JpegOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.JpegOptions. Rappresenta le opzioni del convertitore da Pdf a Jpeg per il plugin Jpeg
type: docs
weight: 8920
url: /it/net/aspose.pdf.plugins/jpegoptions/
---
## Classe JpegOptions

Rappresenta le opzioni del convertitore da Pdf a Jpeg per il plugin [`Jpeg`](../jpeg/).

```csharp
public sealed class JpegOptions : PdfToImageOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [JpegOptions](jpegoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Ottiene la modalità di conversione dell'immagine. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Restituisce la raccolta di dati del plugin [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | Restituisce il nome dell'operazione. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Ottiene o imposta il valore di risoluzione delle immagini risultanti. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Ottiene o imposta un elenco di pagine per il processo. |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | Ottiene e imposta la qualità Jpeg |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Aggiunge una nuova sorgente di dati alla raccolta di dati del plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Imposta una nuova sorgente di dati per il salvataggio. Può essere solo un . Se vuoi salvare le immagini in flussi di memoria, passa null come parametro. |

### Vedi Anche

* classe [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)
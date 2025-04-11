---
title: Class PdfToImageOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PdfToImageOptions. Rappresenta le opzioni per il plugin PdfToImage
type: docs
weight: 9130
url: /it/net/aspose.pdf.plugins/pdftoimageoptions/
---
## Classe PdfToImageOptions

Rappresenta le opzioni per il plugin [`PdfToImage`](../pdftoimage/).

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Ottiene la modalità di conversione delle immagini. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Restituisce la raccolta di dati del plugin [`PdfToImage`](../pdftoimage/). |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | Restituisce il nome dell'operazione. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Ottiene o imposta il valore di risoluzione delle immagini risultanti. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Ottiene o imposta un elenco di pagine per il processo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Aggiunge una nuova sorgente di dati alla raccolta di dati del plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Imposta una nuova sorgente di dati per il salvataggio. Può essere solo un . Se vuoi salvare le immagini in flussi di memoria, passa null come parametro. |

## Altri Membri

| Nome | Descrizione |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | Definisce diverse modalità che possono essere utilizzate durante la conversione da documento PDF a immagine Jpeg. Vedi la classe [`JpegOptions`](../jpegoptions/). |

## Osservazioni

La classe PdfImageOptions contiene funzioni di base per aggiungere dati (file, flussi) che rappresentano documenti PDF di input.

### Vedi Anche

* interfaccia [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)
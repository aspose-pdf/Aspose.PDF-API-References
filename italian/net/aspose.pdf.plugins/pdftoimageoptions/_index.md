---
title: "Classe PdfToImageOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.PdfToImageOptions. Rappresenta le opzioni per il plugin PdfToImage"
type: docs
weight: 9280
url: /it/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions class

Rappresenta le opzioni per il plugin [`PdfToImage`](../pdftoimage/).

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Ottiene la modalità di conversione dell'immagine. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Restituisce la raccolta dati del plugin [`PdfToImage`](../pdftoimage/). |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | Restituisce il nome dell'operazione. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Ottiene o imposta il valore di risoluzione delle immagini risultanti. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Ottiene o imposta un elenco di pagine per il processo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Aggiunge una nuova origine dati alla raccolta dati del plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Imposta una nuova origine dati di salvataggio. Può essere solo un . Se vuoi salvare le immagini in stream di memoria, passa null come parametro. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | Definisce diverse modalità che possono essere utilizzate durante la conversione da documento PDF a immagine Jpeg. Vedi la classe [`JpegOptions`](../jpegoptions/). |

## Osservazioni

La classe PdfImageOptions contiene funzioni di base per aggiungere dati (file, stream) che rappresentano documenti PDF di input.

### Vedi anche

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)



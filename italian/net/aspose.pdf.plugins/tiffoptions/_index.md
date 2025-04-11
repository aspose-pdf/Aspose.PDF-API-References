---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TiffOptions. Rappresenta le opzioni del convertitore da Pdf a Tiff per il plugin Tiff
type: docs
weight: 9420
url: /it/net/aspose.pdf.plugins/tiffoptions/
---
## Classe TiffOptions

Rappresenta le opzioni del convertitore da Pdf a Tiff per il [`Tiff`](../tiff/) plugin.

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TiffOptions](tiffoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | Ottiene o imposta un valore limite della trasformazione dei colori in bianco e nero. Questo parametro può essere applicato con EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle o ColorDepth.Format1bpp == 1 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | Ottiene o imposta il tipo di compressione. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Ottiene la modalità di conversione dell'immagine. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Ottiene o imposta il tipo di coordinate della pagina (Media/Crop boxes). Il valore CropBox è utilizzato per impostazione predefinita. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | Ottiene o imposta la profondità del colore. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Restituisce la raccolta di dati del plugin [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | Restituisce il nome dell'operazione. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Ottiene o imposta il valore di risoluzione delle immagini risultanti. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Ottiene o imposta un elenco di pagine per il processo. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | Ottiene e imposta un flag che consente di salvare tutte le pagine in un tiff multi-pagina. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | Ottiene o imposta il tipo di forma. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | Ottiene o imposta un valore che indica se saltare le pagine vuote. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Aggiunge una nuova sorgente dati alla raccolta di dati del plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Imposta una nuova sorgente dati di salvataggio. Può essere solo un . Se vuoi salvare le immagini in flussi di memoria, passa null come parametro. |

### Vedi Anche

* classe [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)
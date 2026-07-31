---
title: "Classe TiffOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Plugins.TiffOptions classe. Rappresenta le opzioni del convertitore Pdf in Tiff per il plugin Tiff"
type: docs
weight: 9570
url: /it/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions class

Rappresenta le opzioni del convertitore Pdf in Tiff per il plugin [`Tiff`](../tiff/).

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
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Ottiene o imposta il tipo di coordinate della pagina (scatole Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | Ottiene o imposta la profondità di colore. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Restituisce la raccolta dati del plugin [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | Restituisce il nome dell'operazione. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Ottiene o imposta il valore di risoluzione delle immagini risultanti. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Ottiene o imposta un elenco di pagine per il processo. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | Ottiene e imposta il flag che consente di salvare tutte le pagine in un unico TIFF multipagina. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | Ottiene o imposta il tipo di forma. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | Ottiene o imposta un valore che indica se saltare le pagine vuote. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Aggiunge una nuova origine dati alla raccolta dati del plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Imposta una nuova origine dati di salvataggio. Può essere solo un . Se vuoi salvare le immagini in stream di memoria, passa null come parametro. |

### Vedi anche

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)



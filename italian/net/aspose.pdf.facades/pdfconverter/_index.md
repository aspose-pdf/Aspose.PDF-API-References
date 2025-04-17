---
title: Class PdfConverter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfConverter. Rappresenta una classe per convertire ogni pagina di un file pdf in immagini supportando BMP, JPEG, PNG e TIFF ora. Contenuto supportato nei pdf immagini, modulo, commento.
type: docs
weight: 4440
url: /it/net/aspose.pdf.facades/pdfconverter/
---
## Classe PdfConverter

Rappresenta una classe per convertire ogni pagina di un file pdf in immagini, supportando BMP, JPEG, PNG e TIFF ora. Contenuto supportato nei pdf: immagini, modulo, commento.

```csharp
public sealed class PdfConverter : Facade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | Inizializza un nuovo oggetto `PdfConverter`. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfConverter` sulla base del *documento*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | Ottiene o imposta il tipo di coordinate della pagina (Media/Crop boxes). Il valore CropBox è utilizzato per impostazione predefinita. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il documento su cui la facciata sta lavorando. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | Ottiene o imposta la posizione finale che si desidera convertire. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | Ottiene o imposta la modalità di presentazione del modulo. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | Ottiene il conteggio delle pagine. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | Ottiene o imposta la Password del Proprietario del documento. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | Ottiene o imposta le opzioni di rendering. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | Ottiene o imposta la risoluzione durante la conversione. Maggiore è la risoluzione, più lenta è la velocità di conversione. Il valore predefinito è 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | Ottiene o imposta la posizione di partenza che si desidera convertire. Il valore minimo è 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | Ottiene o imposta la Password dell'Utente del documento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | Collega uno stream Pdf per la conversione. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | Collega un file Pdf per la conversione. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | Chiude l'istanza di PdfConverter e rilascia le risorse. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Smaltisce la facciata. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | Esegue alcune operazioni iniziali per convertire un documento pdf in immagini. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | Salva l'immagine nello stream con il formato immagine predefinito - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | Salva l'immagine nel file con il formato immagine predefinito - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | Salva l'immagine nello stream con il formato immagine fornito. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | Salva l'immagine nello stream con la dimensione della pagina fornita. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | Salva l'immagine nel file con il formato immagine fornito. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | Salva l'immagine nel file con la dimensione della pagina fornita e il formato immagine predefinito - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | Salva l'immagine nello stream con il formato immagine fornito e la qualità. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | Salva l'immagine nello stream con la dimensione della pagina fornita. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | Salva l'immagine nel file con il formato immagine fornito e la qualità. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | Salva l'immagine nel file con la dimensione della pagina fornita e il formato immagine. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | Salva l'immagine nello stream con il formato immagine fornito, la dimensione e la qualità. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Salva l'immagine nello stream con la dimensione della pagina fornita, il formato immagine e la qualità. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | Salva l'immagine nel file con il formato immagine fornito e le dimensioni. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | Salva l'immagine nel file con la dimensione della pagina fornita, il formato immagine e la qualità. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | Salva l'immagine nello stream con il formato immagine fornito, la dimensione e la qualità. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | Salva l'immagine nello stream con il formato immagine fornito, le dimensioni e la qualità. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | Salva l'immagine nel file con il formato immagine fornito, la dimensione dell'immagine e la qualità. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | Salva l'immagine nel file con il formato immagine fornito, le dimensioni e la qualità. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | Indica se il file pdf ha altre immagini o meno. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | Converte ogni pagina di un documento pdf in immagini con dimensione della pagina e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | Converte ogni pagina di un documento pdf in immagini con dimensione della pagina e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con dimensione della pagina e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con dimensione della pagina e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Unisce un elenco di stream di immagini in un unico stream di immagini. I formati di output png/jpg/tiff sono supportati, in caso di utilizzo di un formato non supportato, lo stream di output è codificato come Jpeg per impostazione predefinita. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | Unisce un elenco di stream tiff in un unico stream tiff a più frame. |

### Vedi Anche

* classe [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)
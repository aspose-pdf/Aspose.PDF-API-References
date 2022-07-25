---
title: PdfConverter
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta una classe per convertire ogni pagina di un file pdf in immagini supporta ora BMP JPEG PNG e TIFF. Contenuto supportato nei pdf immagini modulo commento.
type: docs
weight: 2450
url: /it/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

Rappresenta una classe per convertire ogni pagina di un file pdf in immagini, supporta ora BMP, JPEG, PNG e TIFF. Contenuto supportato nei pdf: immagini, modulo, commento.

```csharp
public sealed class PdfConverter : Facade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfConverter](pdfconverter#constructor)() | Inizializza nuovo[`PdfConverter`](../pdfconverter) oggetto. |
| [PdfConverter](pdfconverter#constructor_1)(Document) | Inizializza nuovo[`PdfConverter`](../pdfconverter) oggetto sulla base del*document* . |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype) { get; set; } | Ottiene o imposta il tipo di coordinate della pagina (caselle Media/Ritaglia). Il valore CropBox viene utilizzato per impostazione predefinita. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ottiene la facciata del documento su cui sta lavorando. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage) { get; set; } | Ottiene o imposta la posizione finale che vuoi convertire. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode) { get; set; } | Ottiene o imposta la modalità di presentazione del modulo. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount) { get; } | Ottiene il conteggio delle pagine. |
| [Password](../../aspose.pdf.facades/pdfconverter/password) { get; set; } | Ottiene o imposta il documento OwnerPassword. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions) { get; set; } | Ottiene o imposta le opzioni di rendering. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution) { get; set; } | Ottiene o imposta la risoluzione durante la conversione. Maggiore è la risoluzione, minore è la velocità di conversione. Il valore predefinito è 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage) { get; set; } | Ottiene o imposta la posizione iniziale che si desidera convertire. Il valore minimo è 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword) { get; set; } | Ottiene o imposta il documento UserPassword. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_1)(Stream) | Associa un flusso Pdf per convertire. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_2)(string) | Associa un file Pdf per la conversione. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close)() | Chiudi l'istanza di PdfConverter e rilascia le risorse. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la facciata. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert)() | Esegui alcuni lavori iniziali per convertire un documento pdf in immagini. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage)(Stream) | Salva l'immagine in streaming con il formato immagine predefinito - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_9)(string) | Salva l'immagine su file con il formato immagine predefinito - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_4)(Stream, ImageFormat) | Salva l'immagine in streaming con il formato immagine specificato. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_1)(Stream, PageSize) | Salva l'immagine in streaming con una determinata dimensione della pagina. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_13)(string, ImageFormat) | Salva l'immagine su file con il formato immagine givin. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_10)(string, PageSize) | Salva l'immagine su file con le dimensioni della pagina specificate e il formato immagine predefinito - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_6)(Stream, ImageFormat, int) | Salva l'immagine in streaming con il formato e la qualità dell'immagine specificati. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_2)(Stream, PageSize, ImageFormat) | Salva l'immagine in streaming con una determinata dimensione della pagina. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_15)(string, ImageFormat, int) | Salva l'immagine su file con il formato e la qualità dell'immagine specificati. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_11)(string, PageSize, ImageFormat) | Salva l'immagine su file con le dimensioni della pagina e il formato dell'immagine specificati. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_7)(Stream, ImageFormat, int, int) | Salva l'immagine per lo streaming con il formato, le dimensioni e la qualità dell'immagine givin. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Salva l'immagine per lo streaming con le dimensioni della pagina, il formato dell'immagine e la qualità specificati. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_16)(string, ImageFormat, int, int) | Salva l'immagine su file con il formato e le dimensioni dell'immagine specificati. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_12)(string, PageSize, ImageFormat, int) | Salva l'immagine su file con le dimensioni della pagina, il formato dell'immagine e la qualità specificati. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_5)(Stream, ImageFormat, double, double, int) | Salva l'immagine per lo streaming con il formato, le dimensioni e la qualità dell'immagine givin. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_8)(Stream, ImageFormat, int, int, int) | Salva l'immagine per lo streaming con il formato, le dimensioni e la qualità dell'immagine givin. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_14)(string, ImageFormat, double, double, int) | Salva l'immagine su file con il formato immagine, la dimensione e la qualità dell'immagine givin. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_17)(string, ImageFormat, int, int, int) | Salva l'immagine su file con il formato, le dimensioni e la qualità dell'immagine specificati. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage)() | Indica se il file pdf ha più immagini o meno. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff)(Stream) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico flusso TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_10)(string) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_1)(Stream, CompressionType) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_4)(Stream, PageSize) | Converte ogni pagina di un documento pdf in immagini con dimensione pagina e salva le immagini in un unico flusso TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_2)(Stream, TiffSettings) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico flusso TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_11)(string, CompressionType) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_14)(string, PageSize) | Converte ogni pagina di un documento pdf in immagini con dimensione pagina e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_12)(string, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_6)(Stream, int, int) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico flusso TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_5)(Stream, PageSize, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con dimensione pagina e salva le immagini in un unico flusso TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico flusso TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_16)(string, int, int) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_15)(string, PageSize, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con dimensione pagina e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Converte ogni pagina di un documento pdf in immagini con e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_7)(Stream, int, int, CompressionType) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico flusso TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_8)(Stream, int, int, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico flusso TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_17)(string, int, int, CompressionType) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_18)(string, int, int, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico flusso TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf)(Stream) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico flusso TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_3)(string) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_1)(Stream, PageSize) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico flusso TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_4)(string, PageSize) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_2)(Stream, int, int) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico flusso TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_5)(string, int, int) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Unisce l'elenco dei flussi di immagini come un unico flusso di immagini. Sono supportati i formati di output Png/jpg/tiff, in caso di utilizzo di un flusso di output in formato non supportato codificato come Jpeg per impostazione predefinita. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff)(List&lt;Stream&gt;) | Unisce l'elenco di flussi tiff come un flusso tiff a più fotogrammi. |

### Guarda anche

* class [Facade](../facade)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->

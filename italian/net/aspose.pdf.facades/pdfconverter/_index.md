---
title: "Classe PdfConverter"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Facades.PdfConverter. Rappresenta una classe per convertire ogni pagina di file Pdf in immagini supportando BMP, JPEG, PNG e TIFF. Contenuto supportato nei Pdf sotto forma di immagini da commento"
type: docs
weight: 4560
url: /it/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

Rappresenta una classe per convertire ogni pagina di un file pdf in immagini, supportando attualmente BMP, JPEG, PNG e TIFF. Contenuto supportato nei pdf: immagini, moduli, commenti.

```csharp
public sealed class PdfConverter : Facade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | Inizializza un nuovo oggetto `PdfConverter`. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfConverter` basato sul *document*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | Ottiene o imposta il tipo di coordinate della pagina (scatole Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il facade del documento su cui sta lavorando. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | Ottiene o imposta la posizione finale che si desidera convertire. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | Ottiene o imposta la modalità di presentazione del modulo. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | Ottiene il conteggio delle Page. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | Ottiene o imposta il documento OwnerPassword. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | Ottiene o imposta le opzioni di rendering. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | Ottiene o imposta la risoluzione durante la conversione. Maggiore è la risoluzione, più lenta è la velocità di conversione. Il valore predefinito è 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | Ottiene o imposta la posizione iniziale che si desidera convertire. Il valore minimo è 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | Ottiene o imposta il documento UserPassword. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf)(Document) | Associa un documento Pdf all'istanza `PdfConverter` per ulteriori elaborazioni. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | Associa uno stream Pdf per la conversione. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | Associa un file Pdf per la conversione. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | Chiude l'istanza di PdfConverter e rilascia le risorse. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Rilascia la facciata. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | Esegue alcune operazioni iniziali per convertire un documento Pdf in immagini. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | Salva l'immagine nello stream con il formato immagine predefinito - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | Salva l'immagine su file con il formato immagine predefinito - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | Salva l'immagine nello stream con il formato immagine specificato. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | Salva l'immagine nello stream con la dimensione della page specificata. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | Salva l'immagine su file con il formato immagine fornito. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | Salva l'immagine su file con la dimensione della page specificata e il formato immagine predefinito - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | Salva l'immagine nello stream con il formato immagine e la qualità specificati. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | Salva l'immagine nello stream con la dimensione della page specificata. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | Salva l'immagine nel file con il formato immagine e la qualità specificati. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | Salva l'immagine nel file con le dimensioni della pagina e il formato immagine specificati. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | Salva l'immagine nello stream con il formato immagine, le dimensioni e la qualità forniti. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Salva l'immagine nello stream con le dimensioni della pagina, il formato immagine e la qualità specificati. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | Salva l'immagine nel file con il formato immagine e le dimensioni specificati. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | Salva l'immagine nel file con le dimensioni della pagina, il formato immagine e la qualità specificati. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | Salva l'immagine nello stream con il formato immagine, le dimensioni e la qualità forniti. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | Salva l'immagine nello stream con il formato immagine, le dimensioni e la qualità forniti. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | Salva l'immagine nel file con il formato immagine, le dimensioni dell'immagine e la qualità forniti. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | Salva l'immagine nel file con il formato immagine, le dimensioni e la qualità specificati. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | Indica se il file pdf contiene altre immagini o meno. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | Converte ogni pagina di un documento pdf in immagini con le dimensioni della pagina e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | Converte ogni pagina di un documento pdf in immagini con le dimensioni della pagina e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | Converte ogni pagina di un documento pdf in immagini con le dimensioni e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con le dimensioni della pagina e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | Converte ogni pagina di un documento pdf in immagini con le dimensioni e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con le dimensioni della pagina e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | Converte ogni pagina di un documento pdf in immagini con le dimensioni e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con le dimensioni e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | Converte ogni pagina di un documento pdf in immagini con le dimensioni e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | Converte ogni pagina di un documento pdf in immagini con le dimensioni e salva le immagini in un unico file TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Converte ogni pagina di un documento pdf in immagini con le dimensioni e salva le immagini in un unico stream TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Converte ogni pagina di un documento pdf in immagini con le dimensioni e salva le immagini in un unico file TIFF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico stream TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF ClassF. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Unisce un elenco di stream di immagini in un unico stream di immagini. Sono supportati i formati di output Png/jpg/tiff; nel caso di utilizzo di un formato non supportato, lo stream di output viene codificato come Jpeg per impostazione predefinita. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | Unisce un elenco di stream tiff in un unico stream tiff a più fotogrammi. |

### Vedi anche

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)



---
title: "Klass PdfConverter"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfConverter-klass. Representerar en klass för att konvertera varje sida i en pdf‑fil till bilder som stöder BMP, JPEG, PNG och TIFF. Stödd innehåll i pdf‑filer är bilder från kommentarer."
type: docs
weight: 4560
url: /sv/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

Representerar en klass för att konvertera varje sida i en pdf file till bilder, med stöd för BMP, JPEG, PNG och TIFF nu. Stödd innehåll i pdfs: bilder, formulär, kommentarer.

```csharp
public sealed class PdfConverter : Facade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | Initierar ett nytt `PdfConverter`‑objekt. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | Initierar ett nytt `PdfConverter`‑objekt baserat på *document*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | Hämtar eller anger sidkoordinattypen (Media/Crop‑boxar). CropBox‑värdet används som standard. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | Hämtar eller anger slutpositionen som du vill konvertera. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | Hämtar eller anger formulärets presentationsläge. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | Hämtar sidantalet. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | Hämtar eller anger dokumentets OwnerPassword. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | Hämtar eller anger renderingsalternativ. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | Hämtar eller anger upplösning vid konvertering. Ju högre upplösning, desto långsammare konverteringshastighet. Standardvärdet är 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | Hämtar eller anger startpositionen som du vill konvertera. Minimivärdet är 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | Hämtar eller anger dokumentets UserPassword. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf)(Document) | Kopplar ett PDF-dokument till `PdfConverter`-instansen för vidare bearbetning. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | Kopplar en PDF-ström för konvertering. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | Kopplar en PDF-fil för konvertering. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | Stäng `PdfConverter`-instansen och frigör resurserna. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | Utför några initiala åtgärder för att konvertera ett PDF-dokument till bilder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | Sparar bilden till en ström med standardbildformatet - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | Sparar bilden till en fil med standardbildformatet - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | Sparar bilden till en ström med angivet bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | Sparar bilden till en ström med angiven sidstorlek. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | Sparar bilden till en fil med det angivna bildformatet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | Sparar bilden till en fil med den angivna sidstorleken och standardbildformatet - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | Sparar bilden till en ström med angivet bildformat och kvalitet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | Sparar bilden till en ström med angiven sidstorlek. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | Sparar bilden till en fil med angivet bildformat och kvalitet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | Sparar bilden till en fil med angiven sidstorlek och bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | Sparar bilden till en ström med det angivna bildformatet, storleken och kvaliteten. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Sparar bilden till en ström med angiven sidstorlek, bildformat och kvalitet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | Sparar bilden till en fil med det angivna bildformatet och dimensionerna. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | Sparar bilden till en fil med angiven sidstorlek, bildformat och kvalitet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | Sparar bilden till en ström med det angivna bildformatet, storleken och kvaliteten. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | Sparar bilden till en ström med det angivna bildformatet, dimensionerna och kvaliteten. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | Sparar bilden till en fil med det angivna bildformatet, bildstorleken och kvaliteten. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | Sparar bilden till en fil med det angivna bildformatet, dimensionerna och kvaliteten. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | Anger om PDF-filen har fler bilder eller inte. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | Konverterar varje sida i ett PDF-dokument till bilder och sparar bilderna till en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | Konverterar varje sida i ett PDF-dokument till bilder och sparar bilderna till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | Konverterar varje sida i ett PDF-dokument till bilder och sparar bilderna till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | Konverterar varje sida i ett PDF-dokument till bilder med sidstorlek och sparar bilderna till en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | Konverterar varje sida i ett PDF-dokument till bilder och sparar bilderna till en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | Konverterar varje sida i ett PDF-dokument till bilder och sparar bilderna till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | Konverterar varje sida i ett PDF-dokument till bilder med sidstorlek och sparar bilderna till en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Konverterar varje sida i ett PDF-dokument till bilder och sparar bilderna till en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Slår samman en lista med bildströmmar till en enda bildström. Png/jpg/tiff-utdataformat stöds, och om ett icke‑stött format används kodas utdataströmmen som Jpeg som standard. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | Slår samman en lista med tiff-strömmar till en enda tiff-ström med flera bildrutor. |

### Se även

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)



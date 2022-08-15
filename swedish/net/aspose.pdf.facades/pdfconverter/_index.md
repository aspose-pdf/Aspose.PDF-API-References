---
title: PdfConverter
second_title: Aspose.PDF för .NET API Referens
description: Representerar en klass för att konvertera en pdf-fils varje sida till bilder stöder BMP JPEG PNG och TIFF nu. Innehåll som stöds i pdfer bilder formulär kommentar.
type: docs
weight: 2450
url: /sv/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

Representerar en klass för att konvertera en pdf-fils varje sida till bilder, stöder BMP, JPEG, PNG och TIFF nu. Innehåll som stöds i pdf:er: bilder, formulär, kommentar.

```csharp
public sealed class PdfConverter : Facade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfConverter](pdfconverter#constructor)() | Initierar ny[`PdfConverter`](../pdfconverter) objekt. |
| [PdfConverter](pdfconverter#constructor_1)(Document) | Initierar ny[`PdfConverter`](../pdfconverter) objekt på basen av*document* . |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype) { get; set; } | Hämtar eller ställer in sidkoordinattypen (Media/Crop-rutor). CropBox-värdet används som standard. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Får dokumentfasaden arbetar på. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage) { get; set; } | Hämtar eller ställer in slutposition som du vill konvertera. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode) { get; set; } | Hämtar eller ställer in formulärpresentationsläge. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount) { get; } | Hämtar sidantal. |
| [Password](../../aspose.pdf.facades/pdfconverter/password) { get; set; } | Hämtar eller ställer in dokument OwnerPassword. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions) { get; set; } | Hämtar eller ställer in renderingsalternativ. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution) { get; set; } | Hämtar eller ställer in upplösning under konvertering. Ju högre upplösning, desto långsammare omvandlingshastighet. Standardvärdet är 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage) { get; set; } | Hämtar eller ställer in startposition som du vill konvertera. Minimivärdet är 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword) { get; set; } | Hämtar eller ställer in användarlösenord för dokument. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_1)(Stream) | Binder en PDF-ström för konvertering. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_2)(string) | Binder en pdf-fil för konvertering. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close)() | Stäng instansen av PdfConverter och släpp resurserna. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disponerar fasaden. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert)() | Gör några inledande arbeten för att konvertera ett pdf-dokument till bilder. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage)(Stream) | Sparar bild för att streama med standardbildformat - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_9)(string) | Sparar bild till fil med standardbildformat - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_4)(Stream, ImageFormat) | Sparar bild för att streama med givet bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_1)(Stream, PageSize) | Sparar bild för att streama med given sidstorlek. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_13)(string, ImageFormat) | Sparar bild till fil med givin bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_10)(string, PageSize) | Sparar bild till fil med given sidstorlek och standardbildformat - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_6)(Stream, ImageFormat, int) | Sparar bild för att streama med givet bildformat och kvalitet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_2)(Stream, PageSize, ImageFormat) | Sparar bild för att streama med given sidstorlek. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_15)(string, ImageFormat, int) | Sparar bild till fil med givet bildformat och kvalitet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_11)(string, PageSize, ImageFormat) | Sparar bild till fil med given sidstorlek och bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_7)(Stream, ImageFormat, int, int) | Sparar bild för att streama med givin bildformat, storlek och kvalitet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Sparar bild för att streama med given sidstorlek, bildformat och kvalitet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_16)(string, ImageFormat, int, int) | Sparar bild till fil med angivet bildformat och mått. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_12)(string, PageSize, ImageFormat, int) | Sparar bild till fil med given sidstorlek, bildformat och kvalitet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_5)(Stream, ImageFormat, double, double, int) | Sparar bild för att streama med givin bildformat, storlek och kvalitet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_8)(Stream, ImageFormat, int, int, int) | Sparar bild för att streama med givin bildformat, mått och kvalitet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_14)(string, ImageFormat, double, double, int) | Sparar bild till fil med givin bildformat, bildstorlek och kvalitet. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_17)(string, ImageFormat, int, int, int) | Sparar bild till fil med angivet bildformat, mått och kvalitet. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage)() | Indikerar om pdf-filen har fler bilder eller inte. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff)(Stream) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_10)(string) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_1)(Stream, CompressionType) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_4)(Stream, PageSize) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilder i en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_2)(Stream, TiffSettings) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_11)(string, CompressionType) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_14)(string, PageSize) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilder till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_12)(string, TiffSettings) | Konverterar varje sida i ett pdf-dokument till bilder med och sparar bilder till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_6)(Stream, int, int) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder i en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_5)(Stream, PageSize, TiffSettings) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilder i en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_16)(string, int, int) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_15)(string, PageSize, TiffSettings) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilder till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Konverterar varje sida i ett pdf-dokument till bilder med och sparar bilder till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_7)(Stream, int, int, CompressionType) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder i en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_8)(Stream, int, int, TiffSettings) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder i en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_17)(string, int, int, CompressionType) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_18)(string, int, int, TiffSettings) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder till en enda TIFF-fil. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder i en enda TIFF-ström. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder till en enda TIFF-fil. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf)(Stream) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF ClassF-ström. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_3)(string) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF ClassF-fil. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_1)(Stream, PageSize) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF ClassF-ström. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_4)(string, PageSize) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF ClassF-fil. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_2)(Stream, int, int) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF ClassF-ström. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_5)(string, int, int) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF ClassF-fil. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Slår samman lista med bildströmmar till en bildström. Png/jpg/tiff-utdataformat stöds, om du använder en utdataström som inte stöds som Jpeg som standard. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff)(List&lt;Stream&gt;) | Slår samman lista med tiff-strömmar till en tiff-ström med flera bildrutor. |

### Se även

* class [Facade](../facade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->

---
title: "Aspose::Pdf::Facades::PdfConverter-klass"
linktitle: "PdfConverter"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfConverter-klass. Representerar en klass för att konvertera varje sida i en pdf‑fil till bilder, med stöd för BMP, JPEG, PNG och TIFF nu. Stödd innehåll i pdf‑filer: bilder, formulär, kommentarer i C++."
type: docs
weight: 1800
url: /sv/cpp/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class


Representerar en klass för att konvertera varje sida i en pdf-fil till bilder, med stöd för BMP, JPEG, PNG och TIFF nu. Stödd innehåll i pdf-filer: bilder, formulär, kommentarer.

```cpp
class PdfConverter : public Aspose::Pdf::Facades::Facade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Kopplar en [Pdf](../../aspose.pdf/) fil för konvertering. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Kopplar en [Pdf](../../aspose.pdf/) ström för konvertering. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Kopplar ett PDF‑dokument till [PdfConverter](./)-instansen för vidare bearbetning. |
| [Close](./close/)() override | Stänger instansen av [PdfConverter](./) och frigör resurserna. |
| [DoConvert](./doconvert/)() | Utför några initiala åtgärder för att konvertera ett pdf‑dokument till bilder. |
| [get_CoordinateType](./get_coordinatetype/)() const | Hämtar sidkoordinattypen (Media/Crop‑boxar). CropBox‑värdet används som standard. |
| [get_EndPage](./get_endpage/)() | Hämtar slutposition som du vill konvertera. |
| [get_FormPresentationMode](./get_formpresentationmode/)() const | Hämtar formulär presentationsläge. |
| [get_PageCount](./get_pagecount/)() | Hämtar sidantalet. |
| [get_Password](./get_password/)() const | Hämtar dokumentets OwnerPassword. |
| [get_RenderingOptions](./get_renderingoptions/)() const | Hämtar renderingsalternativ. |
| [get_Resolution](./get_resolution/)() const | Hämtar upplösning under konvertering. Ju högre upplösning, desto långsammare konverteringshastighet. Standardvärdet är 150. |
| [get_ShowHiddenAreas](./get_showhiddenareas/)() const | Hämtar flagga som styr synligheten för dolda områden på sidan. |
| [get_StartPage](./get_startpage/)() const | Hämtar startposition som du vill konvertera. Det minsta värdet är 1. |
| [get_UserPassword](./get_userpassword/)() const | Hämtar dokumentets UserPassword. |
| [GetNextImage](./getnextimage/)(const System::String\&) | Sparar bild till fil med standard bildformat - jpeg. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<PageSize\>\&) | Sparar bild till fil med given sidstorlek och standard bildformat - jpeg. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Sparar bild till fil med det angivna bildformatet. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Sparar bild till fil med given sidstorlek och bildformat. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&) | Sparar bild till ström med standard bildformat - jpeg. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) | Sparar bild till ström med given sidstorlek. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Sparar bild till ström med givet bildformat. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Sparar bild till ström med given sidstorlek. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t, int32_t) | Sparar bild till fil med det angivna bildformatet, dimensioner och kvalitet. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t, int32_t) | Sparar bild till ström med det angivna bildformatet, dimensioner och kvalitet. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, double, double, int32_t) | Sparar bild till fil med det angivna bildformatet, bildstorlek och kvalitet. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, double, double, int32_t) | Sparar bild till ström med det angivna bildformatet, storlek och kvalitet. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t) | Sparar bild till fil med det angivna bildformatet och dimensioner. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t) | Sparar bild till ström med det angivna bildformatet, storlek och kvalitet. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Sparar bild till ström med givet bildformat och kvalitet. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Sparar bild till ström med given sidstorlek, bildformat och kvalitet. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Sparar bild till fil med givet bildformat och kvalitet. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Sparar bild till fil med given sidstorlek, bildformat och kvalitet. |
| [HasNextImage](./hasnextimage/)() | Indikerar om pdf-filen har fler bilder eller inte. |
| static [MergeImages](./mergeimages/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\>\&, Aspose::Pdf::Drawing::ImageFormat, ImageMergeMode, System::Nullable\<int32_t\>, System::Nullable\<int32_t\>) | Sammanfogar en lista med bildströmmar till en bildström. Png/jpg/tiff-utdataformat stöds, vid användning av ett icke‑stött format kodas utströmmen som Jpeg som standard. |
| static [MergeImagesAsTiff](./mergeimagesastiff/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\>\&) | Sammanfogar en lista med tiff-strömmar till en tiff-ström med flera bildrutor. |
| [PdfConverter](./pdfconverter/)() | Initierar ett nytt [PdfConverter](./)-objekt. |
| [PdfConverter](./pdfconverter/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [PdfConverter](./)-objekt baserat på *document*. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, Devices::CompressionType) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, int32_t, int32_t) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, const System::SharedPtr\<PageSize\>\&) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Devices::TiffSettings\>\&) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, int32_t, int32_t, Devices::CompressionType) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, int32_t, int32_t, const System::SharedPtr\<Devices::TiffSettings\>\&) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, int32_t, int32_t, const System::SharedPtr\<Devices::TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, Devices::CompressionType) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Devices::TiffSettings\>\&) | Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, Devices::CompressionType) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<Devices::TiffSettings\>\&) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<Devices::TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, const System::SharedPtr\<Devices::TiffSettings\>\&) | Konverterar varje sida i ett pdf-dokument till bilder med och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, const System::SharedPtr\<Devices::TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Konverterar varje sida i ett pdf-dokument till bilder med och sparar bilderna i en enda TIFF-fil. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Devices::TiffSettings\>\&) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Devices::TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF-ström. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::String\&, int32_t, int32_t) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::String\&, const System::SharedPtr\<PageSize\>\&) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::String\&) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-fil. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Konverterar varje sida i ett pdf-dokument till bilder och sparar bilderna i en enda TIFF ClassF-ström. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Ställer in sidkoordinattypen (Media/Crop-boxar). CropBox-värdet används som standard. |
| [set_EndPage](./set_endpage/)(int32_t) | Ställer in slutpositionen som du vill konvertera. |
| [set_FormPresentationMode](./set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Ställer in formulärets presentationsläge. |
| [set_Password](./set_password/)(const System::String\&) | Ställer in dokumentets OwnerPassword. |
| [set_RenderingOptions](./set_renderingoptions/)(const System::SharedPtr\<Aspose::Pdf::RenderingOptions\>\&) | Ställer in renderingsalternativ. |
| [set_Resolution](./set_resolution/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Ställer in upplösning under konvertering. Ju högre upplösning, desto långsammare konverteringshastighet. Standardvärdet är 150. |
| [set_ShowHiddenAreas](./set_showhiddenareas/)(bool) | Ställer in flaggan som styr synligheten för dolda områden på sidan. |
| [set_StartPage](./set_startpage/)(int32_t) | Ställer in startpositionen som du vill konvertera. Minimivärdet är 1. |
| [set_UserPassword](./set_userpassword/)(const System::String\&) | Ställer in dokumentets UserPassword. |
## Se även

* Class [Facade](../facade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)

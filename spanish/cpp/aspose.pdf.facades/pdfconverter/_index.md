---
title: "Aspose::Pdf::Facades::PdfConverter clase"
linktitle: "PdfConverter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfConverter clase. Representa una clase para convertir cada página de un archivo pdf a imágenes, soportando ahora BMP, JPEG, PNG y TIFF. Contenido compatible en pdfs: imágenes, formularios, comentarios en C++."
type: docs
weight: 1800
url: /es/cpp/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class


Representa una clase para convertir cada página de un archivo pdf en imágenes, con soporte actual para BMP, JPEG, PNG y TIFF. Contenido admitido en los pdfs: imágenes, formularios, comentarios.

```cpp
class PdfConverter : public Aspose::Pdf::Facades::Facade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Vincula un archivo [Pdf](../../aspose.pdf/) para convertir. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Vincula un flujo [Pdf](../../aspose.pdf/) para convertir. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Vincula un documento PDF a la instancia de [PdfConverter](./) para un procesamiento posterior. |
| [Close](./close/)() override | Cierra la instancia de [PdfConverter](./) y libera los recursos. |
| [DoConvert](./doconvert/)() | Realiza algunos trabajos iniciales para convertir un documento pdf a imágenes. |
| [get_CoordinateType](./get_coordinatetype/)() const | Obtiene el tipo de coordenadas de página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [get_EndPage](./get_endpage/)() | Obtiene la posición final que desea convertir. |
| [get_FormPresentationMode](./get_formpresentationmode/)() const | Obtiene el modo de presentación del formulario. |
| [get_PageCount](./get_pagecount/)() | Obtiene el recuento de páginas. |
| [get_Password](./get_password/)() const | Obtiene la OwnerPassword del documento. |
| [get_RenderingOptions](./get_renderingoptions/)() const | Obtiene las opciones de renderizado. |
| [get_Resolution](./get_resolution/)() const | Obtiene la resolución durante la conversión. Cuanto mayor sea la resolución, más lenta será la velocidad de conversión. El valor predeterminado es 150. |
| [get_ShowHiddenAreas](./get_showhiddenareas/)() const | Obtiene la bandera que controla la visibilidad de áreas ocultas en la página. |
| [get_StartPage](./get_startpage/)() const | Obtiene la posición inicial que desea convertir. El valor mínimo es 1. |
| [get_UserPassword](./get_userpassword/)() const | Obtiene la UserPassword del documento. |
| [GetNextImage](./getnextimage/)(const System::String\&) | Guarda la imagen en un archivo con el formato de imagen predeterminado - jpeg. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<PageSize\>\&) | Guarda la imagen en un archivo con el tamaño de página dado y el formato de imagen predeterminado - jpeg. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Guarda la imagen en un archivo con el formato de imagen proporcionado. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Guarda la imagen en un archivo con el tamaño de página y el formato de imagen especificados. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&) | Guarda la imagen en un flujo con el formato de imagen predeterminado - jpeg. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) | Guarda la imagen en un flujo con el tamaño de página especificado. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Guarda la imagen en un flujo con el formato de imagen especificado. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Guarda la imagen en un flujo con el tamaño de página especificado. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t, int32_t) | Guarda la imagen en un archivo con el formato de imagen, dimensiones y calidad especificados. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t, int32_t) | Guarda la imagen en un flujo con el formato de imagen, dimensiones y calidad proporcionados. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, double, double, int32_t) | Guarda la imagen en un archivo con el formato de imagen, tamaño de imagen y calidad proporcionados. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, double, double, int32_t) | Guarda la imagen en un flujo con el formato de imagen, tamaño y calidad proporcionados. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t) | Guarda la imagen en un archivo con el formato de imagen y dimensiones especificados. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t) | Guarda la imagen en un flujo con el formato de imagen, tamaño y calidad proporcionados. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Guarda la imagen en un flujo con el formato de imagen y calidad especificados. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Guarda la imagen en un flujo con el tamaño de página, formato de imagen y calidad especificados. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Guarda la imagen en un archivo con el formato de imagen y calidad especificados. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Guarda la imagen en un archivo con el tamaño de página, formato de imagen y calidad especificados. |
| [HasNextImage](./hasnextimage/)() | Indica si el archivo pdf tiene más imágenes o no. |
| static [MergeImages](./mergeimages/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\>\&, Aspose::Pdf::Drawing::ImageFormat, ImageMergeMode, System::Nullable\<int32_t\>, System::Nullable\<int32_t\>) | Fusiona una lista de flujos de imágenes en un solo flujo de imágenes. Se admiten los formatos de salida Png/jpg/tiff; en caso de usar un formato no compatible, el flujo de salida se codifica como Jpeg por defecto. |
| static [MergeImagesAsTiff](./mergeimagesastiff/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\>\&) | Fusiona una lista de flujos tiff en un solo flujo tiff de múltiples fotogramas. |
| [PdfConverter](./pdfconverter/)() | Inicializa un nuevo objeto [PdfConverter](./). |
| [PdfConverter](./pdfconverter/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [PdfConverter](./) basado en el *document*. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, Devices::CompressionType) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, int32_t, int32_t) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, const System::SharedPtr\<PageSize\>\&) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Devices::TiffSettings\>\&) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, int32_t, int32_t, Devices::CompressionType) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, int32_t, int32_t, const System::SharedPtr\<Devices::TiffSettings\>\&) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, int32_t, int32_t, const System::SharedPtr\<Devices::TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, Devices::CompressionType) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) | Convierte cada página de un documento pdf a imágenes con el tamaño de página y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Devices::TiffSettings\>\&) | Convierte cada página de un documento pdf a imágenes con el tamaño de página y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, Devices::CompressionType) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<Devices::TiffSettings\>\&) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<Devices::TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, const System::SharedPtr\<Devices::TiffSettings\>\&) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, const System::SharedPtr\<Devices::TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Devices::TiffSettings\>\&) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Devices::TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::String\&, int32_t, int32_t) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF ClassF. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::String\&, const System::SharedPtr\<PageSize\>\&) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF ClassF. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF ClassF. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF ClassF. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::String\&) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF ClassF. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF ClassF. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Establece el tipo de coordenadas de página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| [set_EndPage](./set_endpage/)(int32_t) | Establece la posición final que desea convertir. |
| [set_FormPresentationMode](./set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Establece el modo de presentación del formulario. |
| [set_Password](./set_password/)(const System::String\&) | Establece la OwnerPassword del documento. |
| [set_RenderingOptions](./set_renderingoptions/)(const System::SharedPtr\<Aspose::Pdf::RenderingOptions\>\&) | Establece las opciones de renderizado. |
| [set_Resolution](./set_resolution/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Establece la resolución durante la conversión. Cuanto mayor sea la resolución, más lenta será la velocidad de conversión. El valor predeterminado es 150. |
| [set_ShowHiddenAreas](./set_showhiddenareas/)(bool) | Establece la bandera que controla la visibilidad de áreas ocultas en la página. |
| [set_StartPage](./set_startpage/)(int32_t) | Establece la posición inicial que desea convertir. El valor mínimo es 1. |
| [set_UserPassword](./set_userpassword/)(const System::String\&) | Establece la UserPassword del documento. |
## Ver también

* Class [Facade](../facade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)

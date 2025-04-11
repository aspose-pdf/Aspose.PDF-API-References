---
title: Class PdfConverter
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfConverter. Representa una clase para convertir cada página de un archivo pdf a imágenes que soportan BMP, JPEG, PNG y TIFF ahora. Contenido soportado en pdfs: imágenes, formularios, comentarios.
type: docs
weight: 4440
url: /es/net/aspose.pdf.facades/pdfconverter/
---
## Clase PdfConverter

Representa una clase para convertir cada página de un archivo pdf a imágenes, soportando BMP, JPEG, PNG y TIFF ahora. Contenido soportado en pdfs: imágenes, formularios, comentarios.

```csharp
public sealed class PdfConverter : Facade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | Inicializa un nuevo objeto `PdfConverter`. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | Inicializa un nuevo objeto `PdfConverter` basado en el *documento*. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | Obtiene o establece el tipo de coordenadas de la página (Media/Crop boxes). El valor de CropBox se utiliza por defecto. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtiene la fachada del documento en el que está trabajando. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | Obtiene o establece la posición final que desea convertir. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | Obtiene o establece el modo de presentación del formulario. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | Obtiene el conteo de páginas. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | Obtiene o establece la contraseña del propietario del documento. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | Obtiene o establece las opciones de renderizado. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | Obtiene o establece la resolución durante la conversión. Cuanto mayor sea la resolución, más lenta será la velocidad de conversión. El valor por defecto es 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | Obtiene o establece la posición inicial que desea convertir. El valor mínimo es 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | Obtiene o establece la contraseña del usuario del documento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa la fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | Vincula un flujo Pdf para convertir. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | Vincula un archivo Pdf para convertir. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | Cierra la instancia de PdfConverter y libera los recursos. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Elimina la fachada. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | Realiza algunos trabajos iniciales para convertir un documento pdf a imágenes. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | Guarda la imagen en el flujo con el formato de imagen por defecto - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | Guarda la imagen en el archivo con el formato de imagen por defecto - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | Guarda la imagen en el flujo con el formato de imagen dado. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | Guarda la imagen en el flujo con el tamaño de página dado. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | Guarda la imagen en el archivo con el formato de imagen dado. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | Guarda la imagen en el archivo con el tamaño de página dado y el formato de imagen por defecto - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | Guarda la imagen en el flujo con el formato de imagen dado y calidad. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | Guarda la imagen en el flujo con el tamaño de página dado. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | Guarda la imagen en el archivo con el formato de imagen dado y calidad. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | Guarda la imagen en el archivo con el tamaño de página dado y formato de imagen. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | Guarda la imagen en el flujo con el formato de imagen dado, tamaño y calidad. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Guarda la imagen en el flujo con el tamaño de página dado, formato de imagen y calidad. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | Guarda la imagen en el archivo con el formato de imagen dado y dimensiones. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | Guarda la imagen en el archivo con el tamaño de página dado, formato de imagen y calidad. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | Guarda la imagen en el flujo con el formato de imagen dado, tamaño y calidad. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | Guarda la imagen en el flujo con el formato de imagen dado, dimensiones y calidad. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | Guarda la imagen en el archivo con el formato de imagen dado, tamaño de imagen y calidad. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | Guarda la imagen en el archivo con el formato de imagen dado, dimensiones y calidad. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | Indica si el archivo pdf tiene más imágenes o no. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF ClassF. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Combina una lista de flujos de imagen en un solo flujo de imagen. Se admiten formatos de salida png/jpg/tiff, en caso de usar un formato no soportado, el flujo de salida se codifica como Jpeg por defecto. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | Combina una lista de flujos tiff en un solo flujo tiff de múltiples cuadros. |

### Ver También

* clase [Facade](../facade/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../)
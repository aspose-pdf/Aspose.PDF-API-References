---
title: PdfConverter
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa una clase para convertir cada página de un archivo PDF en imágenes compatible con BMP JPEG PNG y TIFF ahora. Contenido admitido en archivos PDF imágenes formularios comentarios.
type: docs
weight: 2450
url: /es/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

Representa una clase para convertir cada página de un archivo PDF en imágenes, compatible con BMP, JPEG, PNG y TIFF ahora. Contenido admitido en archivos PDF: imágenes, formularios, comentarios.

```csharp
public sealed class PdfConverter : Facade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfConverter](pdfconverter#constructor)() | Inicializa nuevo[`PdfConverter`](../pdfconverter) objeto. |
| [PdfConverter](pdfconverter#constructor_1)(Document) | Inicializa nuevo[`PdfConverter`](../pdfconverter) objeto sobre la base de la*document* . |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype) { get; set; } | Obtiene o establece el tipo de coordenada de la página (Medios/Cuadros de recorte). El valor de CropBox se usa por defecto. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtiene la fachada del documento en la que está trabajando. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage) { get; set; } | Obtiene o establece la posición final que desea convertir. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode) { get; set; } | Obtiene o establece el modo de presentación del formulario. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount) { get; } | Obtiene el número de páginas. |
| [Password](../../aspose.pdf.facades/pdfconverter/password) { get; set; } | Obtiene o establece el documento OwnerPassword. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions) { get; set; } | Obtiene o establece las opciones de representación. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution) { get; set; } | Obtiene o establece la resolución durante la conversión. La resolución más alta, la velocidad de conversión más lenta. El valor predeterminado es 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage) { get; set; } | Obtiene o establece la posición inicial que desea convertir. El valor mínimo es 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword) { get; set; } | Obtiene o establece el documento UserPassword. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inicializa la fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_1)(Stream) | Vincula una secuencia de PDF para convert. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_2)(string) | Vincula un archivo PDF para convertirlo. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close)() | Cierre la instancia de PdfConverter y libere los recursos. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la fachada. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert)() | Realice algunos trabajos iniciales para convertir un documento pdf en imágenes. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage)(Stream) | Guarda la imagen para transmitir con el formato de imagen predeterminado: jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_9)(string) | Guarda la imagen en un archivo con el formato de imagen predeterminado: jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_4)(Stream, ImageFormat) | Guarda la imagen para transmitir con el formato de imagen dado. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_1)(Stream, PageSize) | Guarda la imagen para transmitir con el tamaño de página dado. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_13)(string, ImageFormat) | Guarda la imagen en un archivo con el formato de imagen dado. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_10)(string, PageSize) | Guarda la imagen en un archivo con el tamaño de página dado y el formato de imagen predeterminado: jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_6)(Stream, ImageFormat, int) | Guarda la imagen para transmitir con el formato y la calidad de imagen dados. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_2)(Stream, PageSize, ImageFormat) | Guarda la imagen para transmitir con el tamaño de página dado. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_15)(string, ImageFormat, int) | Guarda la imagen en un archivo con el formato y la calidad de imagen dados. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_11)(string, PageSize, ImageFormat) | Guarda la imagen en un archivo con el tamaño de página y el formato de imagen dados. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_7)(Stream, ImageFormat, int, int) | Guarda la imagen para transmitir con el formato, tamaño y calidad de imagen dados. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Guarda la imagen para transmitir con el tamaño de página, el formato de imagen y la calidad determinados. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_16)(string, ImageFormat, int, int) | Guarda la imagen en un archivo con el formato de imagen y las dimensiones dadas. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_12)(string, PageSize, ImageFormat, int) | Guarda la imagen en un archivo con el tamaño de página, el formato de imagen y la calidad determinados. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_5)(Stream, ImageFormat, double, double, int) | Guarda la imagen para transmitir con el formato, tamaño y calidad de imagen dados. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_8)(Stream, ImageFormat, int, int, int) | Guarda la imagen para transmitir con el formato, las dimensiones y la calidad de la imagen dada. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_14)(string, ImageFormat, double, double, int) | Guarda la imagen en un archivo con el formato, el tamaño y la calidad de la imagen dados. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_17)(string, ImageFormat, int, int, int) | Guarda la imagen en un archivo con el formato de imagen, las dimensiones y la calidad especificados. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage)() | Indica si el archivo pdf tiene más imágenes o no. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff)(Stream) | Convierte cada página de un documento pdf en imágenes y las guarda en una sola secuencia TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_10)(string) | Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_1)(Stream, CompressionType) | Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_4)(Stream, PageSize) | Convierte cada página de un documento pdf en imágenes con tamaño de página y guarda las imágenes en una única secuencia TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_2)(Stream, TiffSettings) | Convierte cada página de un documento pdf en imágenes y las guarda en una sola secuencia TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_11)(string, CompressionType) | Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_14)(string, PageSize) | Convierte cada página de un documento pdf en imágenes con tamaño de página y guarda las imágenes en un solo archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_12)(string, TiffSettings) | Convierte cada página de un documento pdf en imágenes y las guarda en un solo archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_6)(Stream, int, int) | Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en una única secuencia TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_5)(Stream, PageSize, TiffSettings) | Convierte cada página de un documento pdf en imágenes con tamaño de página y guarda las imágenes en una única secuencia TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Convierte cada página de un documento pdf en imágenes y las guarda en una sola secuencia TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_16)(string, int, int) | Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en un solo archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_15)(string, PageSize, TiffSettings) | Convierte cada página de un documento pdf en imágenes con tamaño de página y guarda las imágenes en un solo archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Convierte cada página de un documento pdf en imágenes y las guarda en un solo archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_7)(Stream, int, int, CompressionType) | Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en una única secuencia TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_8)(Stream, int, int, TiffSettings) | Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en una única secuencia TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_17)(string, int, int, CompressionType) | Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en un solo archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_18)(string, int, int, TiffSettings) | Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en un solo archivo TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en una única secuencia TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en un solo archivo TIFF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf)(Stream) | Convierte cada página de un documento pdf en imágenes y las guarda en una única secuencia TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_3)(string) | Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_1)(Stream, PageSize) | Convierte cada página de un documento pdf en imágenes y las guarda en una única secuencia TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_4)(string, PageSize) | Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_2)(Stream, int, int) | Convierte cada página de un documento pdf en imágenes y las guarda en una única secuencia TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_5)(string, int, int) | Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF ClassF. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Fusiona la lista de flujos de imágenes como un flujo de imágenes. Los formatos de salida png/jpg/tiff son compatibles, en caso de utilizar un flujo de salida de formato no compatible codificado como Jpeg de forma predeterminada. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff)(List&lt;Stream&gt;) | Fusiona la lista de flujos tiff como un flujo tiff de varios fotogramas. |

### Ver también

* class [Facade](../facade)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->

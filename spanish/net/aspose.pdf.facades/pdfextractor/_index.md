---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfExtractor. Clase para extraer imágenes y texto de un documento PDF
type: docs
weight: 4450
url: /es/net/aspose.pdf.facades/pdfextractor/
---
## Clase PdfExtractor

Clase para extraer imágenes y texto de un documento PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Inicializa un nuevo objeto `PdfExtractor`. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | Inicializa un nuevo objeto `PdfExtractor` basado en el *documento*. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtiene el documento sobre el que está trabajando la fachada. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Obtiene o establece la página final en el rango de páginas donde se realizará la operación de extracción. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Establece el modo para el proceso de extracción de imágenes. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Establece el modo para el resultado de la extracción de texto. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | Es verdadero cuando el texto tiene símbolos hebreos o árabes. Este caso debe ser considerado especialmente porque las funciones de cadena cambian su comportamiento y comienzan a procesar el texto de derecha a izquierda (excepto números y otros caracteres no textuales). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Obtiene o establece la contraseña del archivo de entrada. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Establece o obtiene la resolución para las imágenes extraídas. El valor predeterminado es 150. Las imágenes que tienen un valor de resolución mayor son más claras. Sin embargo, aumentar el valor de resolución resulta en un aumento del tiempo y la memoria necesarios para extraer imágenes. Generalmente, para obtener una imagen clara, es suficiente establecer la resolución en 150 o 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Obtiene o establece la página de inicio en el rango de páginas donde se realizará la operación de extracción. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Obtiene o establece las opciones de búsqueda de texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa la fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Vincula el documento PDF desde un flujo. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Vincula el archivo PDF de entrada. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Libera el Aspose.Pdf.Document vinculado con una fachada. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libera la fachada. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Extrae archivos adjuntos de un documento PDF. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Extrae un archivo adjunto a un archivo PDF por nombre de archivo adjunto. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Extrae imágenes de un archivo PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Extrae texto de un documento PDF utilizando codificación Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Extrae texto de un documento PDF utilizando la codificación especificada. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Guarda todos los archivos adjuntos en flujos. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Almacena el archivo adjunto en un archivo. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Obtiene la lista de archivos adjuntos. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Devuelve la lista de archivos adjuntos en el archivo PDF. Nota: ExtractAttachments debe ser llamado antes de usar este método. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Recupera la siguiente imagen del archivo PDF y la almacena en un flujo. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Recupera la siguiente imagen del documento PDF. Nota: ExtractImage debe ser llamado antes de usar este método. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Recupera la siguiente imagen del archivo PDF y la almacena en un flujo con el formato de imagen dado. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Recupera la siguiente imagen del documento PDF con el formato de imagen dado. Nota: ExtractImage debe ser llamado antes de usar este método. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Guarda el texto de una página en un flujo. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Guarda el texto de una página en un archivo. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Guarda el texto en un flujo. ver también:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Guarda el texto en un archivo. ver también:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Guarda el texto en un flujo. ver también:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Verifica si hay más imágenes accesibles en el documento PDF. Nota: ExtractImage debe ser llamado antes de usar este método. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Indica si se pueden obtener más textos o no. |

### Ver También

* clase [Facade](../facade/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../)
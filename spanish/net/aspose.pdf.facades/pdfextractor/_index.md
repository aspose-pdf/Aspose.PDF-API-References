---
title: PdfExtractor
second_title: Referencia de API de Aspose.PDF para .NET
description: Clase para extraer imágenes y texto de un documento PDF.
type: docs
weight: 2460
url: /es/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

Clase para extraer imágenes y texto de un documento PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfExtractor](pdfextractor#constructor)() | Inicializa nuevo[`PdfExtractor`](../pdfextractor) objeto. |
| [PdfExtractor](pdfextractor#constructor_1)(Document) | Inicializa nuevo[`PdfExtractor`](../pdfextractor) objeto sobre la base de la*document* . |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtiene la fachada del documento en la que está trabajando. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage) { get; set; } | Obtiene o establece la página final en el rango de páginas donde se realizará la operación de extracción. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode) { get; set; } | Establece el modo para el proceso de extracción de imágenes. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode) { get; set; } | Establece el modo para extraer el resultado del texto. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi) { get; } | Es verdadero cuando el texto tiene símbolos hebreos o árabes. Este caso debe considerarse especialmente porque las funciones de cadena cambian su comportamiento y comienzan a procesar el texto de derecha a izquierda (excepto los números y otros caracteres que no son de texto). |
| [Password](../../aspose.pdf.facades/pdfextractor/password) { get; set; } | Obtiene o establece la contraseña del archivo de entrada. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution) { get; set; } | Establece u obtiene la resolución de las imágenes extraídas. El valor predeterminado es 150. Las imágenes que tienen un mayor valor de resolución son más claras. Sin embargo, al aumentar el valor de resolución, aumenta el tiempo y la memoria necesarios para extraer imágenes. Por lo general, para obtener una imagen clara es suficiente para establecer la resolución en 150 o 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage) { get; set; } | Obtiene o establece la página de inicio en el rango de páginas donde se realizará la operación de extracción. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions) { get; set; } | Obtiene o establece opciones de búsqueda de texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inicializa la fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_1)(Stream) | Vincula el documento PDF desde la secuencia. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_2)(string) | Enlazar archivo PDF de entrada. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Elimina Aspose.Pdf.Document enlazado con una fachada. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la fachada. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment)() | Extrae archivos adjuntos de un documento PDF. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment_1)(string) | Extrae adjuntos a archivos PDF por nombre de adjunto. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage)() | Extraer imágenes del archivo PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext)() | Extrae texto de un documento PDF utilizando la codificación Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext_1)(Encoding) | Extrae texto de un documento PDF utilizando la codificación especificada. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment)() | Guarda todo el archivo adjunto en streams. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment_1)(string) | Almacena el archivo adjunto en el archivo. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo)() | Obtiene la lista de adjuntos. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames)() | Devuelve una lista de archivos adjuntos en un archivo PDF. Nota: se debe llamar a ExtractAttachments antes de usar este método. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage)(Stream) | Recupera la siguiente imagen del archivo PDF y la almacena en la secuencia. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_2)(string) | Recupera la imagen siguiente del documento PDF. Nota: se debe llamar a ExtractImage antes de usar este método. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_1)(Stream, ImageFormat) | Recupera la siguiente imagen del archivo PDF y la almacena en el flujo con el formato de imagen dado. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_3)(string, ImageFormat) | Recupera la siguiente imagen del documento PDF con el formato de imagen dado. Nota: se debe llamar a ExtractImage antes de usar este método. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext)(Stream) | Guarda el texto de una página para transmitir. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext_1)(string) | Guarda el texto de una página en el archivo. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext)(Stream) | Guarda el texto en la secuencia. ver también:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_2)(string) | Guarda el texto en el archivo. ver también:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_1)(Stream, bool) | Guarda el texto en la secuencia. ver también:[`ExtractText`](./extracttext) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage)() | Comprueba si hay más imágenes accesibles en el documento PDF. Nota: se debe llamar a ExtractImage antes de usar este método. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext)() | Indica si se pueden recibir más textos o no. |

### Ver también

* class [Facade](../facade)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->

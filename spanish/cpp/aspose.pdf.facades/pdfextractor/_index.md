---
title: "Aspose::Pdf::Facades::PdfExtractor clase"
linktitle: "PdfExtractor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfExtractor clase. Clase para extraer imágenes y texto de un documento PDF en C++."
type: docs
weight: 1900
url: /es/cpp/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class


Clase para extraer imágenes y texto de documentos PDF.

```cpp
class PdfExtractor : public Aspose::Pdf::Facades::Facade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Vincula el archivo PDF de entrada. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Vincula el documento PDF desde un flujo. |
| [ExtractAttachment](./extractattachment/)() | Extrae los adjuntos de un documento [Pdf](../../aspose.pdf/). |
| [ExtractAttachment](./extractattachment/)(const System::String\&) | Extrae el adjunto a un archivo PDF por nombre del adjunto. |
| [ExtractImage](./extractimage/)() | Extrae imágenes de un archivo PDF. |
| [ExtractText](./extracttext/)() | Extrae texto de un documento [Pdf](../../aspose.pdf/) usando codificación Unicode. |
| [ExtractText](./extracttext/)(const System::SharedPtr\<System::Text::Encoding\>\&) | Extrae texto de un documento [Pdf](../../aspose.pdf/) usando la codificación especificada. |
| [get_EndPage](./get_endpage/)() const | Obtiene la página final en el rango de páginas donde se realizará la operación de extracción. |
| [get_ExtractImageMode](./get_extractimagemode/)() const | Establece el modo para el proceso de extracción de imágenes. |
| [get_ExtractTextMode](./get_extracttextmode/)() const | Establece el modo para el resultado de extracción de texto. |
| [get_IsBidi](./get_isbidi/)() | Es verdadero cuando el texto contiene símbolos hebreos o árabes. Este caso debe considerarse especialmente porque las funciones de cadena cambian su comportamiento y comienzan a procesar el texto de derecha a izquierda (excepto números y otros caracteres no textuales). |
| [get_Password](./get_password/)() const | Obtiene la contraseña del archivo de entrada. |
| [get_Resolution](./get_resolution/)() const | Establece o obtiene la resolución para las imágenes extraídas. El valor predeterminado es 150. Las imágenes que tienen un valor de resolución mayor son más nítidas. Sin embargo, aumentar el valor de resolución incrementa el tiempo y la memoria necesarios para extraer imágenes. Normalmente, para obtener una imagen clara basta con establecer la resolución en 150 o 300. |
| [get_StartPage](./get_startpage/)() const | Obtiene la página inicial en el rango de páginas donde se realizará la operación de extracción. |
| [get_TextSearchOptions](./get_textsearchoptions/)() const | Obtiene opciones de búsqueda de texto. |
| [GetAttachment](./getattachment/)(const System::String\&) | Guarda el adjunto en un archivo. |
| [GetAttachment](./getattachment/)() | Guarda todos los archivos adjuntos en flujos. |
| [GetAttachmentInfo](./getattachmentinfo/)() | Obtiene la lista de adjuntos. |
| [GetAttachNames](./getattachnames/)() | Devuelve la lista de adjuntos en el archivo PDF. [Note](../../aspose.pdf/note/): ExtractAttachments debe llamarse antes de usar este método. |
| [GetNextImage](./getnextimage/)(const System::String\&) | Recupera la siguiente imagen del documento PDF. [Note](../../aspose.pdf/note/): ExtractImage debe llamarse antes de usar este método. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Recupera la siguiente imagen del documento PDF con el formato de imagen especificado. [Note](../../aspose.pdf/note/): ExtractImage debe llamarse antes de usar este método. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Recupera la siguiente imagen del archivo PDF y la almacena en un flujo con el formato de imagen especificado. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&) | Recupera la siguiente imagen del archivo PDF y la almacena en un flujo. |
| [GetNextPageText](./getnextpagetext/)(const System::String\&) | Guarda el texto de una página en un archivo. |
| [GetNextPageText](./getnextpagetext/)(const System::SharedPtr\<System::IO::Stream\>\&) | Guarda el texto de una página en un flujo. |
| [GetText](./gettext/)(const System::String\&) | Guarda el texto en un archivo. ver también:[ExtractText](./extracttext/) |
| [GetText](./gettext/)(const System::SharedPtr\<System::IO::Stream\>\&) | Guarda el texto en un flujo. ver también:[ExtractText](./extracttext/) |
| [GetText](./gettext/)(const System::SharedPtr\<System::IO::Stream\>\&, bool) | Guarda el texto en un flujo. ver también:[ExtractText](./extracttext/) |
| [HasNextImage](./hasnextimage/)() | Comprueba si hay más imágenes accesibles en el documento PDF. [Note](../../aspose.pdf/note/): ExtractImage debe llamarse antes de usar este método. |
| [HasNextPageText](./hasnextpagetext/)() | Indica si se pueden obtener más textos o no. |
| [PdfExtractor](./pdfextractor/)() | Inicializa un nuevo objeto [PdfExtractor](./). |
| [PdfExtractor](./pdfextractor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [PdfExtractor](./) basado en el *documento*. |
| [set_EndPage](./set_endpage/)(int32_t) | Establece la página final en el rango de páginas donde se realizará la operación de extracción. |
| [set_ExtractImageMode](./set_extractimagemode/)(Aspose::Pdf::ExtractImageMode) | Establece el modo para el proceso de extracción de imágenes. |
| [set_ExtractTextMode](./set_extracttextmode/)(int32_t) | Establece el modo para el resultado de extracción de texto. |
| [set_Password](./set_password/)(const System::String\&) | Establece la contraseña del archivo de entrada. |
| [set_Resolution](./set_resolution/)(int32_t) | Establece o obtiene la resolución para las imágenes extraídas. El valor predeterminado es 150. Las imágenes que tienen un valor de resolución mayor son más nítidas. Sin embargo, aumentar el valor de resolución incrementa el tiempo y la memoria necesarios para extraer imágenes. Normalmente, para obtener una imagen clara basta con establecer la resolución en 150 o 300. |
| [set_StartPage](./set_startpage/)(int32_t) | Establece la página inicial en el rango de páginas donde se realizará la operación de extracción. |
| [set_TextSearchOptions](./set_textsearchoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Establece opciones de búsqueda de texto. |
## Ver también

* Class [Facade](../facade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)

---
title: "PdfExtractor"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase para extraer imágenes y texto de un documento PDF."
type: docs
weight: 210
url: /es/python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

Clase para extraer imágenes y texto de un documento PDF.

El tipo PdfExtractor expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfExtractor() | Inicializa un nuevo objeto [PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/). |
| PdfExtractor(document) | Inicializa una nueva instancia de la clase PdfExtractor |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| start_page | Obtiene o establece la página inicial en el rango de páginas donde se realizará la operación de extracción. |
| end_page | Obtiene o establece la página final en el rango de páginas donde se realizará la operación de extracción. |
| extract_text_mode | Establece el modo para el resultado de la extracción de texto. |
| text_search_options | Obtiene o establece las opciones de búsqueda de texto. |
| extract_image_mode | Establece el modo para el proceso de extracción de imágenes. |
| is_bidi | Es verdadero cuando el texto contiene símbolos hebreos o árabes. Este caso debe considerarse especialmente porque<br/>            las funciones de cadena cambian su comportamiento y comienzan a procesar el texto de derecha a izquierda (excepto los números <br/>            y otros caracteres no textuales). |
| resolution | Establece u obtiene la resolución para las imágenes extraídas.<br/>            El valor predeterminado es 150.<br/>            Las imágenes que tienen un valor de resolución mayor son más nítidas.<br/>            Sin embargo, aumentar el valor de resolución incrementa el tiempo y la memoria necesarios para extraer imágenes.<br/>            Normalmente, para obtener una imagen clara basta con establecer la resolución en 150 o 300. |
| password | Obtiene o establece la contraseña del archivo de entrada. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(input_file) | Vincula el archivo PDF de entrada. |
| bind_pdf(input_stream) | Vincula el documento PDF desde un flujo. |
| bind_pdf(src_doc) | Inicializa la fachada. |
| extract_text() | Extrae texto de un documento PDF usando codificación Unicode. |
| extract_text(encoding) | Extrae texto de un documento PDF usando la codificación especificada. |
| get_text(output_file) | Guarda el texto en un archivo. ver también:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream) | Guarda el texto en un flujo. ver también:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream, filter_not_ascii) | Guarda el texto en un flujo. ver también:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_next_image(output_file) | Recupera la siguiente imagen del documento PDF. Nota: ExtractImage debe llamarse antes de usar este método. |
| get_next_image(output_file, format) | Recupera la siguiente imagen del documento PDF con el formato de imagen dado. Nota: ExtractImage debe llamarse antes de usar este método. |
| get_next_image(output_stream, format) | Recupera la siguiente imagen del archivo PDF y la almacena en un flujo con el formato de imagen dado. |
| get_next_image(output_stream) | Recupera la siguiente imagen del archivo PDF y la almacena en un flujo con el formato de imagen dado. |
| extract_attachment() | Extrae los adjuntos de un documento PDF. |
| extract_attachment(attachment_file_name) | Extrae el adjunto a un archivo PDF por nombre del adjunto. |
| get_next_page_text(output_file) | Guarda el texto de una página en un archivo. |
| get_next_page_text(output_stream) | Guarda el texto de una página en un flujo. |
| close() | Descarta Aspose.Pdf.Document vinculado con una fachada. |
| extract_image() | Extrae imágenes del archivo PDF. |
| has_next_image() | Comprueba si hay más imágenes accesibles en el documento PDF. Nota: ExtractImage debe llamarse antes de usar este método. |
| get_attach_names() | Devuelve la lista de adjuntos en el archivo PDF. Nota: ExtractAttachments debe llamarse antes de usar este método. |
| get_attachment(output_path) | Almacena el adjunto en un archivo. |
| has_next_page_text() | Indica si se pueden obtener más textos o no. |
| get_attachment_info() | Obtiene la lista de adjuntos. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)


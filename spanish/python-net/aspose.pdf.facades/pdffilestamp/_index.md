---
title: "PdfFileStamp"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase para agregar sellos (marca de agua o fondo) a archivos PDF."
type: docs
weight: 320
url: /es/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

Clase para agregar sellos (marca de agua o fondo) a archivos PDF.

El tipo PdfFileStamp expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfFileStamp(input_file, output_file) | Inicializa una nueva instancia de la clase PdfFileStamp |
| PdfFileStamp(input_stream, output_stream) | Inicializa una nueva instancia de la clase PdfFileStamp |
| PdfFileStamp(input_file, output_file, keep_security) | Inicializa una nueva instancia de la clase PdfFileStamp |
| PdfFileStamp(input_stream, output_stream, keep_security) | Inicializa una nueva instancia de la clase PdfFileStamp |
| PdfFileStamp() | Constructor de PdfFileStamp.<br/>            El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. |
| PdfFileStamp(document) | Inicializa una nueva instancia de la clase PdfFileStamp |
| PdfFileStamp(document, output_file) | Inicializa una nueva instancia de la clase PdfFileStamp |
| PdfFileStamp(document, output_stream) | Inicializa una nueva instancia de la clase PdfFileStamp |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| optimize_size | Obtiene o establece la bandera de optimización. Los flujos de recursos iguales en el archivo resultante se combinan en un único objeto PDF si esta bandera está activada. <br/>            Esto permite reducir el tamaño del archivo resultante pero puede causar una ejecución más lenta y mayores requisitos de memoria.<br/>            Valor predeterminado: false. |
| keep_security | Mantiene la seguridad si es verdadero. (Esta función se implementará en próximas versiones). |
| input_file | Obtiene o establece el nombre y la ruta del archivo de entrada. |
| input_stream | Obtiene o establece el flujo de entrada. |
| output_file | Obtiene o establece el nombre y la ruta del archivo de salida. |
| output_stream | Obtiene o establece el flujo de salida. |
| page_number_rotation | Obtiene o establece la rotación del número de página. La rotación está en grados. El valor predeterminado es 0. |
| page_height | Obtiene la altura de la primera página en el archivo de origen. |
| page_width | Obtiene el ancho de la primera página en el archivo de entrada. |
| starting_number | Obtiene o establece el número inicial para la primera página en el archivo de entrada. Las páginas siguientes se numerarán a partir de este valor. <br/>            Por ejemplo, si StartingNumber se establece en 100, las páginas del documento tendrán los números 100, 101, 102... |
| numbering_style | Obtiene o establece el estilo de numeración de página. Valores posibles: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| stamp_id | ID de sello del siguiente sello añadido (incluyendo encabezados/pies de página/números de página). |
| POS_BOTTOM_MIDDLE | Posición central inferior. |
| POS_BOTTOM_RIGHT | Posición inferior derecha. |
| POS_UPPER_RIGHT | Posición superior derecha. |
| POS_SIDES_RIGHT | Posición derecha. |
| POS_UPPER_MIDDLE | Posición central superior. |
| POS_BOTTOM_LEFT | Posición inferior izquierda. |
| POS_SIDES_LEFT | Posición izquierda. |
| POS_UPPER_LEFT | Posición superior izquierda. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(src_file) | Vincula el documento PDF para su edición. |
| bind_pdf(src_stream) | Vincula el documento PDF para su edición. |
| bind_pdf(src_doc) | Vincula el documento PDF para su edición. |
| save(dest_file) | Guarda el resultado en el archivo especificado. |
| save(dest_stream) | Guarda el documento en el flujo especificado. |
| add_page_number(format_string) | Agregar número de página al archivo. El texto del número de página puede contener el signo # que será reemplazado por el número de la página. <br/>            El número de página se coloca en la parte inferior de la página centrado horizontalmente. |
| add_page_number(formatted_text) | Agrega número de página a la página. El número de página puede contener el signo # que será reemplazado por el número de página.<br/>            El número de página se coloca en la parte inferior de la página centrado horizontalmente. |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | Agrega número de página a las páginas del documento. |
| add_page_number(format_string, x, y) | Agrega número de página a las páginas del documento. |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | Agrega número de página a las páginas del documento. |
| add_page_number(formatted_text, x, y) | Agrega número de página a las páginas del documento. |
| add_page_number(format_string, position) | Agrega número de página a las páginas del documento. |
| add_page_number(formatted_text, position) | Agrega número de página a las páginas del documento. |
| add_header(formatted_text, top_margin) | Agrega encabezado a la página. |
| add_header(formatted_text, top_margin, left_margin, right_margin) | Agrega encabezado a la página. |
| add_header(image_file, top_margin) | Agrega una imagen como encabezado a las páginas del archivo. |
| add_header(image_file, top_margin, left_margin, right_margin) | Agrega una imagen como encabezado a las páginas del archivo. |
| add_header(image_stream, top_margin) | Agrega una imagen como encabezado en las páginas. |
| add_header(input_stream, top_margin, left_margin, right_margin) | Agrega una imagen como encabezado en las páginas. |
| add_footer(formatted_text, bottom_margin) | Agrega pie de página a las páginas del documento. |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | Agrega pie de página a las páginas del documento. |
| add_footer(image_file, bottom_margin) | Agrega una imagen como pie de página a las páginas del documento. |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | Agrega una imagen como pie de página a las páginas del documento. |
| add_footer(image_stream, bottom_margin) | Agrega una imagen como pie de página de la página. |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | Agrega una imagen como pie de página de la página. |
| close() | Cierra los archivos abiertos y guarda los cambios. <br/>            Advertencia. Si se especifican flujos de entrada o salida, no se cierran con el método Close() method. |
| add_stamp(stamp) | Agrega una marca al archivo. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)


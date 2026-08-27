---
title: "PdfViewer"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una clase para ver o imprimir un pdf."
type: docs
weight: 370
url: /es/python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

Representa una clase para ver o imprimir un pdf.

El tipo PdfViewer expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfViewer() | Inicializa un nuevo objeto [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/). |
| PdfViewer(document) | Inicializa una nueva instancia de la clase PdfViewer |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| show_hidden_areas | Obtiene o establece la bandera que controla la visibilidad de áreas ocultas en la página. |
| print_status | Obtiene el resultado del trabajo de impresión. Si tiene éxito, devuelve null; de lo contrario, un objeto de excepción. |
| use_intermidiate_image | Obtiene/establece el uso de la conversión de la página pdf a un archivo png intermedio durante la impresión en modo archivo. Úselo cuando el tamaño del archivo de salida sea importante. |
| coordinate_type | Obtiene o establece el tipo de coordenadas de la página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| print_as_image | Establece u obtiene un modo para que PdfViewer imprima como imagen. |
| page_count | Obtiene el número de páginas del archivo Pdf actual. |
| password | Obtiene o establece la contraseña del documento de entrada. |
| print_page_dialog | Obtiene o establece un valor booleano que indica si se muestra el cuadro de diálogo de número de página al imprimir. |
| print_as_grayscale | Obtiene o establece un valor booleano que indica si la página se imprime en escala de grises. Por defecto es false. |
| printer_job_name | Obtiene o establece el nombre del documento en la cola de impresión cuando se imprime el documento. El valor predeterminado es el nombre del archivo. |
| form_presentation_mode | Obtiene o establece el modo de presentación del formulario. |
| rendering_options | Obtiene o establece las opciones de renderizado. |
| vertical_alignment | Obtiene o establece un valor que indica la alineación vertical |
| horizontal_alignment | Obtiene o establece un valor que indica la alineación horizontal |
| auto_resize | Obtiene o establece un valor booleano que indica si el archivo se imprimirá con tamaño optimizado. |
| auto_rotate | Obtiene o establece un valor booleano que indica si el archivo se imprimirá con rotación automática |
| auto_rotate_mode | Obtiene o establece un valor AutoRotateMode que indica la dirección de rotación |
| resolution | Obtiene o establece la resolución durante la visualización e impresión. A mayor resolución, menor velocidad. El valor predeterminado es 150. |
| scale_factor | Obtiene o establece un valor de punto flotante que indica el factor de escala. El valor predeterminado es 1.0. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| print_large_pdf(file_path) | Abre e imprime un archivo Pdf grande. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es <br/>             más de 3 MB, se recomienda este método para obtener un mejor rendimiento. |
| print_large_pdf(input_stream) | Abre e imprime un flujo Pdf grande. Si su archivo Pdf tiene cientos de páginas o más o su tamaño es <br/>             más de 3 MB, se recomienda este método para obtener un mejor rendimiento. |
| print_large_pdf(file_path, printer_settings) | Abre e imprime un archivo Pdf grande con la configuración de impresora especificada. Si su archivo Pdf tiene cientos <br/>             de páginas o más o su tamaño es más de 3 MB, se recomienda este método para obtener un mejor rendimiento. |
| print_large_pdf(input_stream, printer_settings) | Abre e imprime un flujo Pdf grande con la configuración de impresora especificada. Si su archivo Pdf tiene cientos <br/>             de páginas o más o su tamaño es más de 3 MB, se recomienda este método para obtener un mejor rendimiento. |
| print_large_pdf(file_path, page_settings, printer_settings) | Abre e imprime un archivo Pdf grande con la configuración de página y de impresora especificadas. Si su Pdf <br/>             tiene cientos de páginas o más o su tamaño es más de 3 MB, se recomienda este método para <br/>             obtener un mejor rendimiento. |
| print_large_pdf(input_stream, page_settings, printer_settings) | Abre e imprime una gran secuencia Pdf con la configuración de página y de impresora especificadas. Si su archivo Pdf <br/>             tiene cientos de páginas o más o su tamaño es superior a 3 MB, se recomienda este método para <br/>             obtener un mejor rendimiento. |
| print_document_with_settings(page_settings, printer_settings) | Imprime el documento Pdf con la configuración. Si el tamaño del documento no es compatible con el tamaño de página, pdf.kit lo ampliará para ajustarse al tamaño de página. |
| print_document_with_settings(printer_settings) | Imprime el documento Pdf con la configuración. Si el tamaño del documento no es compatible con el tamaño de página, pdf.kit lo ampliará para ajustarse al tamaño de página. |
| open_pdf_file(file_path) | Abre un archivo Pdf, pero no decodifica realmente las páginas del archivo Pdf. |
| open_pdf_file(input_stream) | Abre una secuencia de archivo Pdf. Pero no decodifica realmente las páginas del archivo Pdf. |
| bind_pdf(src_file) | Inicializa la fachada. |
| bind_pdf(src_stream) | Inicializa la fachada. |
| bind_pdf(src_doc) | Inicializa la fachada. |
| save(dest_file) | Guarda el documento PDF resultante en un archivo. |
| save(dest_stream) | Guarda el documento PDF resultante en una secuencia. |
| decode_all_pages() | Obtiene las páginas del archivo pdf actual. |
| decode_page(page_number) | Decodifica una página de un archivo Pdf. |
| print_document_with_setup() | Imprime el documento Pdf con un cuadro de diálogo de configuración. Elija una impresora usando el cuadro de diálogo. |
| print_document() | Imprime el documento Pdf con un cuadro de diálogo de configuración. Elija una impresora usando el cuadro de diálogo. |
| get_default_page_settings() | Obtiene la configuración de página predeterminada. |
| get_default_printer_settings() | Obtiene la configuración de impresora predeterminada. |
| close_pdf_file() | Cierra el archivo Pdf actual. |
| close() | Cierra el archivo Pdf actual. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)


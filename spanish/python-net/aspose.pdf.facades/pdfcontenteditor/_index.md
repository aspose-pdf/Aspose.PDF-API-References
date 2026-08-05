---
title: "PdfContentEditor"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una clase para editar el contenido de un archivo PDF."
type: docs
weight: 190
url: /es/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

Representa una clase para editar el contenido de un archivo PDF.

El tipo PdfContentEditor expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfContentEditor() | El constructor del objeto PdfContentEditor. |
| PdfContentEditor(document) | Inicializa una nueva instancia de la clase PdfContentEditor |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| text_search_options | Obtiene o establece las opciones de búsqueda de texto. |
| text_edit_options | Obtiene o establece las opciones de edición de texto. |
| text_replace_options | Obtiene o establece las opciones de reemplazo de texto. |
| replace_text_strategy | Un conjunto de parámetros para la operación de reemplazo de texto |
| DOCUMENT_OPEN | Tipo de evento de documento. Abre un documento. |
| DOCUMENT_CLOSE | Tipo de evento de documento. Cierra un documento. |
| DOCUMENT_WILL_SAVE | Tipo de evento de documento. Ejecuta una acción antes de guardar. |
| DOCUMENT_SAVED | Tipo de evento de documento. Ejecuta una acción después de guardar. |
| DOCUMENT_WILL_PRINT | Tipo de evento de documento. Ejecuta una acción antes de imprimir. |
| DOCUMENT_PRINTED | Un tipo de evento de documento. Ejecuta una acción después de imprimir. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(input_file) | Vincula un archivo PDF para editar. |
| bind_pdf(input_stream) | Vincula un flujo PDF para editar. |
| bind_pdf(src_doc) | Vincula el documento PDF para su edición. |
| save(dest_file) | Guarda el documento PDF en el archivo especificado. |
| save(dest_stream) | Guarda el documento PDF en el flujo especificado. |
| create_web_link(rect, url, original_page, clr) | Crea un enlace web en el documento PDF. |
| create_web_link(rect, url, original_page) | Crea un enlace web en el documento PDF. |
| create_local_link(rect, des_page, original_page, clr) | Crea un enlace local en el documento PDF. |
| create_local_link(rect, des_page, original_page) | Crea un enlace local en el documento PDF. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | Crea un enlace a otra página de documento PDF. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | Crea un enlace a otra página de documento PDF. |
| create_application_link(rect, application, page, clr) | Crea un enlace para lanzar una aplicación en el documento PDF. |
| create_application_link(rect, application, page) | Crea un enlace para lanzar una aplicación en el documento PDF. |
| create_file_attachment(rect, contents, file_path, page, name) | Crea una anotación de adjunto de archivo. |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | Crea una anotación de adjunto de archivo. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | Crea una anotación de adjunto de archivo. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | Crea una anotación de adjunto de archivo. |
| add_document_attachment(file_attachment_path, description) | Agrega un adjunto de documento sin anotación. |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | Agrega un adjunto de documento sin anotación. |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | Crea una anotación de sello de goma. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | Crea una anotación de sello de goma. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | Crea una anotación de sello de goma. |
| delete_image(page_number, index) | Elimina las imágenes especificadas en la página especificada. |
| delete_image() | Elimina las imágenes especificadas en la página especificada. |
| replace_text(src_string, the_page, dest_string, text_state) | Reemplaza texto en el archivo PDF en la página especificada. El objeto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (familia de fuente, color) puede especificarse para el texto reemplazado. |
| replace_text(src_string, dest_string) | Reemplaza texto en el archivo PDF en la página especificada. El objeto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (familia de fuente, color) puede especificarse para el texto reemplazado. |
| replace_text(src_string, the_page, dest_string) | Reemplaza texto en el archivo PDF en la página especificada. El objeto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (familia de fuente, color) puede especificarse para el texto reemplazado. |
| replace_text(src_string, dest_string, text_state) | Reemplaza texto en el archivo PDF en la página especificada. El objeto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (familia de fuente, color) puede especificarse para el texto reemplazado. |
| replace_text(src_string, dest_string, font_size) | Reemplaza texto en el archivo PDF en la página especificada. El objeto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (familia de fuente, color) puede especificarse para el texto reemplazado. |
| delete_stamp_by_ids(stamp_ids) | Elimina los sellos con los IDs especificados de todas las páginas del documento. |
| delete_stamp_by_ids(page_number, stamp_ids) | Elimina los sellos con los IDs especificados de todas las páginas del documento. |
| delete_stamp_by_id(page_number, stamp_id) | Elimina los sellos con los IDs especificados de todas las páginas del documento. |
| delete_stamp_by_id(stamp_id) | Elimina los sellos con los IDs especificados de todas las páginas del documento. |
| close() | Cierra el documento abierto. |
| extract_link() | Extrae la colección de instancias de Link contenidas en el documento PDF. |
| create_java_script_link(code, rect, original_page, color) | Crea un enlace a JavaScript en el documento PDF. |
| create_text(rect, title, contents, open, icon, page) | Crea una anotación de texto en el documento PDF |
| create_free_text(rect, contents, page) | Crea una anotación de texto libre en el documento PDF |
| create_markup(rect, contents, type, page, clr) | Crea una anotación de marcado en el documento PDF. |
| create_popup(rect, contents, open, page) | Crea una anotación emergente en el documento PDF. |
| delete_attachments() | Elimina todos los archivos adjuntos en el documento PDF. |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | Crea una anotación de línea. |
| create_square_circle(rect, contents, clr, square, page, border_width) | Crea una anotación de cuadrado-círculo. |
| draw_curve(line_info, page, annot_rect, annot_contents) | Crea una anotación de curva. |
| create_polygon(line_info, page, annot_rect, annot_contents) | Crea una anotación de polígono. |
| create_poly_line(line_info, page, annot_rect, annot_contents) | Crea una anotación de polilínea. |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | Crea una anotación de caret. |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | Crea un marcador con la acción especificada. |
| add_document_additional_action(event_type, code) | Añade una acción adicional para el evento del documento. |
| remove_document_open_action() | Elimina la acción de apertura del documento. Esta operación es útil al concatenar varios documentos que utilizan una acción explícita 'GoTo' al iniciar. |
| change_viewer_preference(viewer_attribution) | Cambia la preferencia de vista. |
| get_viewer_preference() | Devuelve la preferencia de vista. |
| replace_image(page_number, index, image_file) | Reemplaza la imagen especificada en la página especificada del documento PDF con otra imagen. |
| create_movie(rect, file_path, page) | Crea anotaciones de película. |
| create_sound(rect, file_path, name, page, rate) | Crea anotaciones de sonido. |
| delete_stamp(page_number, index) | Elimina varios sellos en la página especificada por índices de sello. |
| hide_stamp_by_id(page_number, stamp_id) | Oculta el sello. Después de ocultarlo, la visibilidad del sello puede restaurarse con el método ShowStampById. |
| show_stamp_by_id(page_number, stamp_id) | Muestra el sello que fue ocultado por HiddenStampById. |
| move_stamp_by_id(page_number, stamp_id, x, y) | Cambia la posición del sello en la página. |
| move_stamp(page_number, stamp_index, x, y) | Cambia la posición del sello en la página. |
| get_stamps(page_number) | Devuelve una matriz de sellos en la página. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)


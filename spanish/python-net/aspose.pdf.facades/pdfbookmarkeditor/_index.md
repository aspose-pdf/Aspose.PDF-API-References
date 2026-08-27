---
title: "PdfBookmarkEditor"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una clase para trabajar con los marcadores de archivos PDF, incluyendo crear, modificar, exportar, importar y eliminar."
type: docs
weight: 180
url: /es/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

Representa una clase para trabajar con los marcadores de archivos PDF, incluyendo crear, modificar, exportar, importar y eliminar.

El tipo PdfBookmarkEditor expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfBookmarkEditor() | Inicializa un nuevo objeto [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/). |
| PdfBookmarkEditor(document) | Inicializa una nueva instancia de la clase PdfBookmarkEditor |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(src_file) | Vincula el documento PDF para su edición. |
| bind_pdf(src_stream) | Vincula el documento PDF para su edición. |
| bind_pdf(src_doc) | Vincula el documento PDF para su edición. |
| save(dest_file) | Guarda el documento PDF en el archivo especificado. |
| save(dest_stream) | Guarda el documento PDF en el flujo especificado. |
| create_bookmarks() | Crea marcadores para todas las páginas. |
| create_bookmarks(bookmark) | Crea marcadores para todas las páginas. |
| create_bookmarks(color, bold_flag, italic_flag) | Crear marcadores para todas las páginas con el color y estilo especificados (negrita, cursiva). |
| create_bookmark_of_page(bookmark_name, page_number) | Crea un marcador para la página especificada. |
| create_bookmark_of_page(bookmark_name, page_number) | Crea marcadores para las páginas especificadas. |
| delete_bookmarks() | Elimina todos los marcadores del documento PDF. |
| delete_bookmarks(title) | Elimina el marcador del documento PDF. |
| extract_bookmarks() | Extrae los marcadores de todos los niveles del documento. |
| extract_bookmarks(upper_level) | Extrae los marcadores de todos los niveles del documento. |
| extract_bookmarks(title) | Extrae los marcadores con el título especificado. |
| extract_bookmarks(bookmark) | Extrae los marcadores de todos los niveles del documento. |
| export_bookmarks_to_xml(xml_file) | Exporta los marcadores a un archivo XML. |
| export_bookmarks_to_xml(stream) | Exporta los marcadores a un flujo XML. |
| import_bookmarks_with_xml(xml_file) | Importa los marcadores al documento desde un archivo XML. |
| import_bookmarks_with_xml(stream) | Importa los marcadores al documento desde un archivo XML. |
| close() | Libera cualquier recurso asociado con la fachada actual. |
| modify_bookmarks(s_title, d_title) | Modifica el título del marcador según el título de marcador especificado. |
| extract_bookmarks_to_html(pdf_file, css_file) | Exporta los marcadores a un archivo HTML. |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | Exporta los marcadores a un archivo HTML. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)


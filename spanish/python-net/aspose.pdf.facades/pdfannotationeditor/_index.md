---
title: "PdfAnnotationEditor"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una clase para trabajar con anotaciones (comentarios) de documentos PDF."
type: docs
weight: 170
url: /es/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

Representa una clase para trabajar con anotaciones (comentarios) de documentos PDF.

El tipo PdfAnnotationEditor expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfAnnotationEditor() | Inicializa un nuevo objeto [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/). |
| PdfAnnotationEditor(document) | Inicializa una nueva instancia de la clase PdfAnnotationEditor |
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
| import_annotations_from_xfdf(xfdf_file) | Importa todas las anotaciones del archivo XFDF. |
| import_annotations_from_xfdf(xfdf_stream) | Importa todas las anotaciones del flujo de datos XFDF. |
| import_annotation_from_xfdf(xfdf_file) | Importa todas las anotaciones del archivo XFDF. |
| import_annotation_from_xfdf(xfdf_file, annot_type) | Importa las anotaciones especificadas del archivo XFDF. |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | Importa las anotaciones especificadas del flujo de datos XFDF. |
| import_annotation_from_xfdf(xfdf_stream) | Importa las anotaciones especificadas del flujo de datos XFDF. |
| import_annotations(annot_file, annot_type) | Importa las anotaciones especificadas al documento desde una matriz de otros documentos PDF. |
| import_annotations(annot_file) | Importa las anotaciones especificadas al documento desde una matriz de otros documentos PDF. |
| import_annotations(annot_file_stream, annot_type) | Importa las anotaciones especificadas en el documento desde una matriz de flujos de otro documento PDF. |
| import_annotations(annot_file_stream) | Importa las anotaciones especificadas en el documento desde una matriz de flujos de otro documento PDF. |
| flattening_annotations() | Aplana todas las anotaciones en el documento. |
| flattening_annotations(flatten_settings) | Aplana todas las anotaciones en el documento. |
| flattening_annotations(start, end, annot_type) | Aplana las anotaciones de los tipos especificados. |
| delete_annotations() | Elimina todas las anotaciones en el documento. |
| delete_annotations(annot_type) | Elimina todas las anotaciones del tipo especificado en el documento. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Exporta el contenido de los tipos de anotación especificados a XFDF |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Exporta el contenido de los tipos de anotaciones especificados a XFDF |
| extract_annotations(start, end, annot_types) | Obtiene la lista de anotaciones de los tipos especificados. |
| extract_annotations(start, end, annot_types) | Obtiene la lista de anotaciones de los tipos especificados. |
| close() | Libera cualquier recurso asociado con la fachada actual. |
| modify_annotations_author(start, end, src_author, des_author) | Modifica el autor de las anotaciones en el rango de páginas especificado. |
| delete_annotation(annot_name) | Elimina todas las anotaciones del tipo especificado en el documento. |
| export_annotations_to_xfdf(xml_output_stream) | Exporta anotaciones a un flujo. |
| modify_annotations(start, end, annotation) | Modifica las anotaciones del tipo especificado en el rango de páginas especificado.<br/>            Soporta la modificación de las siguientes propiedades de anotación: Modified, Title, Contents, Color, Subject y Open. |
| redact_area(page_index, rect, color) | Redacta el área en la página especificada. Todo el contenido es eliminado. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)


---
title: "PdfPageEditor"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una clase para editar la página del archivo PDF, incluyendo rotar la página, hacer zoom, mover la posición y cambiar el tamaño de la página."
type: docs
weight: 340
url: /es/python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

Representa una clase para editar la página del archivo PDF, incluyendo rotar la página, hacer zoom, mover la posición y cambiar el tamaño de la página.

El tipo PdfPageEditor expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfPageEditor() | Constructor de la clase PdfPageEditor. |
| PdfPageEditor(document) | Inicializa una nueva instancia de la clase PdfPageEditor |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| transition_duration | Obtiene o establece la duración del efecto de transición. |
| transition_type | Obtiene o establece el estilo de transición a usar al pasar a esta página desde otra durante una presentación. |
| display_duration | Obtiene o establece la duración de visualización de las páginas. |
| process_pages | Obtiene o establece los números de página a editar. Por defecto, se editará cada página. |
| rotation | Obtiene o establece la rotación de las páginas, la rotación debe ser 0, 90, 180 o 270.<br/>            Valor predeterminado es 0. |
| zoom | Obtiene o establece el coeficiente de zoom. El valor 1.0 corresponde al 100%.<br/>            El valor predeterminado es 1.0. |
| page_size | Obtiene o establece el tamaño de página del archivo de salida. |
| alineación | Obtiene o establece la alineación horizontal del contenido PDF original en la página resultante, el predeterminado es AlignmentType.Left. |
| horizontal_alignment | Obtiene o establece la alineación horizontal del contenido PDF original en la página resultante, el predeterminado es AlignmentType.Left. |
| vertical_alignment | Obtiene o establece la alineación vertical del contenido PDF original en la página resultante, el predeterminado es VerticalAlignmentType.Bottom. |
| vertical_alignment_type | Obtiene o establece la alineación vertical del contenido PDF original en la página resultante, el predeterminado es VerticalAlignmentType.Bottom. |
| SPLITVOUT | División vertical de salida |
| SPLITHOUT | División horizontal de salida |
| SPLITVIN | División vertical interna |
| SPLITHIN | División horizontal interna |
| BLINDV | Persianas verticales |
| BLINDH | Persianas verticales |
| INBOX | Caja interior |
| OUTBOX | Caja exterior |
| LRWIPE | Deslizamiento izquierda-derecha |
| RLWIPE | Deslizamiento derecha-izquierda |
| BTWIPE | Deslizamiento Inferior-Superior |
| TBWIPE | Deslizamiento Superior-Inferior |
| DISSOLVE | La página antigua se disuelve |
| LRGLITTER | Brillo Izquierda-Derecha |
| TBGLITTER | Brillo Superior-Inferior |
| DGLITTER | Brillo Diagonal |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(src_file) | Vincula el documento PDF para su edición. |
| bind_pdf(src_stream) | Vincula el documento PDF para su edición. |
| bind_pdf(src_doc) | Vincula el documento PDF para su edición. |
| save(output_file) | Guarda el documento modificado en un archivo. |
| save(output_stream) | Guarda el documento modificado en un flujo. |
| close() | Libera cualquier recurso asociado con la fachada actual. |
| move_position(move_x, move_y) | Mueve el origen de (0, 0) al punto indicado. <br/> El origen está en la esquina inferior izquierda y la unidad es punto (1 pulgada = 72 puntos). |
| get_pages() | Devuelve el número total de páginas. |
| get_page_size(page) | Devuelve el tamaño de página de la página especificada. |
| get_page_rotation(page) | Devuelve la rotación de la página especificada. |
| get_page_box_size(page, page_box_name) | El tipo PdfFileInfo expone los siguientes miembros: |
| apply_changes() | Aplica los cambios realizados en las páginas del documento. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)


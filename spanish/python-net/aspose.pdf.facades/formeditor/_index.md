---
title: "FormEditor"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase para editar formularios (agregar/eliminar campos, etc.)"
type: docs
weight: 110
url: /es/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

Clase para editar formularios (agregar/eliminar campos, etc.)

El tipo FormEditor expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| FormEditor(src_stream, dest_stream) | Inicializa una nueva instancia de la clase FormEditor |
| FormEditor(src_file_name, dest_file_name) | Inicializa una nueva instancia de la clase FormEditor |
| FormEditor() | Constructor de FormEditor. |
| FormEditor(document) | Inicializa una nueva instancia de la clase FormEditor |
| FormEditor(document, dest_file_name) | Inicializa una nueva instancia de la clase FormEditor |
| FormEditor(document, dest_stream) | Inicializa una nueva instancia de la clase FormEditor |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| src_file_name | Obtiene o establece el nombre del archivo fuente. |
| dest_file_name | Obtiene o establece el nombre del archivo de destino. |
| src_stream | Obtiene o establece el flujo de origen. |
| dest_stream | Obtiene o establece el flujo de destino. |
| items | Establece los elementos que se agregarán a un list box o combo box recién creado. |
| export_items | Establece opciones para el combo box con valores de exportación. |
| facade | Establece los atributos visuales del campo. |
| radio_gap | El miembro para registrar la distancia entre dos botones de radio adyacentes en píxeles, el valor predeterminado es 50. |
| radio_horiz | La bandera que indica si los botones de radio se organizan horizontalmente o verticalmente, el valor predeterminado es verdadero. |
| radio_button_item_size | Obtiene o establece el tamaño del elemento del botón de radio (cuando se agrega un nuevo campo de botón de radio). |
| submit_flag | Establece las banderas de envío del botón de envío |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(src_file) | Vincula el documento PDF para su edición. |
| bind_pdf(src_stream) | Vincula el documento PDF para su edición. |
| bind_pdf(src_doc) | Vincula el documento PDF para su edición. |
| save() | Guarda los cambios en el archivo de destino. |
| save(dest_file) | Guarda los cambios en el archivo de destino. |
| save(dest_stream) | Guarda los cambios en el archivo de destino. |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | Agrega un campo del tipo especificado al formulario. |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | Agrega un campo del tipo especificado al formulario. |
| copy_inner_field(field_name, new_field_name, page_num) | Copia un campo existente a la misma posición en el número de página especificado.<br/>            Se producirá un nuevo documento, que contiene todo lo que tiene el documento origen, excepto el campo recién copiado. |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | Copia un campo existente a una nueva posición especificada tanto por el número de página como por las coordenadas.<br/>            Se producirá un nuevo documento, que contiene todo lo que tiene el documento origen, excepto el campo recién copiado. |
| copy_outer_field(src_file_name, field_name) | Copia un campo existente de un documento PDF a otro documento con el número de página y coordenadas originales.<br/>            Aviso: Solo para campos AcroForm (excluyendo casillas de radio). |
| copy_outer_field(src_file_name, field_name, page_num) | Copia un campo existente de un documento PDF a otro documento con el número de página especificado y las coordenadas originales.<br/>             Aviso: Solo para campos AcroForm (excluyendo casillas de radio). |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | Copia un campo existente de un documento PDF a otro documento con el número de página y coordenadas especificados.<br/>            Aviso: Solo para campos AcroForm (excluyendo casillas de radio). |
| decorate_field(field_name) | Cambia los atributos visuales del campo especificado. |
| decorate_field(field_type) | Cambia los atributos visuales de todos los campos con el tipo de campo especificado. |
| decorate_field() | Cambia los atributos visuales del campo especificado. |
| add_list_item(field_name, item_name) | Agrega un nuevo elemento al cuadro de lista. |
| add_list_item(field_name, export_name) | Agrega un nuevo elemento con valor Export al campo de cuadro de lista existente, solo para el campo de cuadro combinado AcroForm. |
| close() | Cierra la fachada. |
| set_field_attribute(field_name, flag) | Establece atributos del campo. |
| set_field_appearance(field_name, flags) | Establecer banderas del campo |
| get_field_appearance(field_name) | Obtener banderas del campo. |
| set_submit_flag(field_name, submit_form_flag) | Establecer bandera de envío del botón de envío. |
| set_submit_url(field_name, url) | Establece la URL del botón. |
| set_field_limit(field_name, field_limit) | Establece el recuento máximo de caracteres del campo de texto. |
| set_field_comb_number(field_name, comb_number) | Establece el número de divisiones (combs) para un campo de texto de una sola línea regular (el campo se <br/>            divide automáticamente en tantas posiciones equidistantes, o divisiones, <br/>            como el valor del parámetro combNumber). |
| move_field(field_name, llx, lly, urx, ury) | Establecer nueva posición del campo. |
| remove_field(field_name) | Eliminar campo del formulario. |
| reset_facade() | Restablecer todos los atributos visuales a valor vacío. |
| reset_inner_facade() | Restablecer todos los atributos visuales de la fachada interna a valor vacío. |
| rename_field(field_name, new_field_name) | Cambiar el nombre del campo. |
| remove_field_action(field_name) | Eliminar la acción de envío del campo. |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | Agregar botón de envío al formulario. |
| del_list_item(field_name, item_name) | Eliminar elemento del campo de lista. |
| set_field_script(field_name, script) | Establecer JavaScript para un campo PushButton. Si existía JavaScript anterior, será reemplazado por el nuevo. |
| add_field_script(field_name, script) | Agregar JavaScript para un campo PushButton. Si existe un evento anterior, el nuevo evento se agrega después de él. |
| single_2_multiple(field_name) | Cambiar un campo de texto de una sola línea a uno de varias líneas. |
| set_field_alignment(field_name, alignment) | Establecer el estilo de alineación de un campo de texto. |
| set_field_alignment_v(field_name, alignment) | Establecer el estilo de alineación vertical de un campo de texto. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)


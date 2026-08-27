---
title: "Form"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa un objeto de formulario."
type: docs
weight: 110
url: /es/python-net/aspose.pdf.forms/form/
---

## Form class

Clase que representa un objeto de formulario.

El tipo Form expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| is_synchronized | Devuelve true si el objeto es seguro para subprocesos. |
| sync_root | Devuelve el objeto de sincronización. |
| auto_recalculate | Si está establecido, todos los campos del formulario se recalcularán cuando se cambie cualquier campo. El valor predeterminado es true. Establézcalo en false para aumentar el rendimiento al rellenar el formulario con una gran cantidad de campos calculados. |
| auto_restore_form | Si está establecido, los campos de formulario ausentes se crearán automáticamente si están presentes en las anotaciones. |
| default_resources | Obtiene los recursos predeterminados ubicados en este formulario. |
| default_appearance | Obtiene o establece la apariencia predeterminada del formulario (objeto que describe la fuente predeterminada, el tamaño del texto y el color para los campos del formulario). |
| xfa | Obtiene los datos XFA del formulario (si están presentes). |
| ignore_needs_rendering | Si esta propiedad es verdadera, el valor de la clave NeedsRendering será ignorado durante la conversión <br/>            del formulario XFA al formulario estándar. Es falso por defecto. |
| remove_permission | Si esta propiedad es verdadera, el diccionario "Perms" será eliminado del documento PDF después de la conversión <br/>            de documentos dinámicos a estándar. El diccionario "Perms" puede contener reglas que alteren la visualización de la selección de <br/>            campos obligatorios en el lector Adobe Acrobat.<br/>            Es falso por defecto. |
| emulate_requierd_groups | Si esta propiedad es verdadera, se dibujarán rectángulos rojos adicionales alrededor de los contenedores de elementos exclGroup requeridos de Xfa<br/>            Esta propiedad se introdujo debido a la ausencia de análogos para exclGroup durante la conversión de la representación Xfa de formularios <br/>            a estándar.<br/>            Es falso por defecto. |
| type | Obtiene el tipo del formulario. Los valores posibles son: Standard, Static, Dynamic. |
| fields | Obtiene la lista de todos los campos en el nivel más bajo del formulario jerárquico. |
| signatures_exist | Si está establecido, el documento contiene al menos un campo de firma. |
| signatures_append_only | Si está establecido, el documento contiene firmas que pueden invalidarse si el archivo se guarda (escribe) de una manera que altere su contenido previo, <br/>            en contraposición a una actualización incremental. |
| sign_dependent_elements_rendering_mode_when_converted | Los formularios pueden contener información de firma, es decir, pueden estar firmados o sin firmar.<br/>              Y la vista del formulario a veces debe depender de si el formulario está firmado o no.<br/>              Esta propiedad indica al convertidor de formularios (p.ej. durante la conversión de formulario XFA a formulario estándar)<br/>              si el formulario resultante debe renderizarse como firmado o como sin firmar. |
## Indexer
| Nombre | Descripción |
| :- | :- |
| [index] | Obtiene el campo del formulario por índice de campo. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| delete(field) | Elimina el campo del formulario. |
| delete(field_name) | Elimina el campo del formulario por su nombre. |
| add(field, page_number) | Agrega un campo al formulario. |
| add(field) | Agrega un campo al formulario. |
| add(field, partial_name, page_number) | Agrega un nuevo campo al formulario; si este campo ya está colocado en otro o en este formulario, se crea una copia del campo. |
| has_field(field) | Verifique si el formulario ya tiene el campo especificado. |
| has_field(field_name) | Determina si el campo con el nombre especificado ya está añadido al formulario. |
| copy_to(array, index) | Copia los campos colocados en el formulario a una matriz. |
| flatten() | Elimina todos los campos del formulario y coloca sus valores directamente en la página. |
| add_field_appearance(field, page_number, rect) | Agrega una apariencia adicional del campo a la página especificada del documento en la ubicación indicada. |
| get_fields_in_rect(rect) | Devuelve los campos dentro del rectángulo especificado. |

### Ver también

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)


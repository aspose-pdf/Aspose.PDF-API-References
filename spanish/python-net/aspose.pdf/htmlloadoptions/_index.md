---
title: "HtmlLoadOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa opciones para cargar/importar un archivo html en un documento pdf."
type: docs
weight: 480
url: /es/python-net/aspose.pdf/htmlloadoptions/
---

## HtmlLoadOptions class

Representa opciones para cargar/importar un archivo html en un documento pdf.

El tipo HtmlLoadOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| HtmlLoadOptions() | Crea opciones de carga para convertir html en documento pdf con ruta base vacía. |
| HtmlLoadOptions(base_path) | Inicializa una nueva instancia de la clase HtmlLoadOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| warning_handler | Función de devolución de llamada para manejar cualquier advertencia generada. <br/>            El WarningHandler devuelve el elemento enum ReturnAction que especifica Continuar o Abort. <br/>            Continuar es la acción predeterminada y la operación de Carga continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación de Carga debe detenerse. |
| load_format | Representa el formato de archivo que describe [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| is_render_to_single_page | Obtiene o establece la renderización de todo el documento en una sola página |
| is_embed_fonts | Obtiene o establece la incrustación de fuentes en el documento resultante |
| page_layout_option | Obtiene o establece la opción de diseño. |
| html_media_type | Obtiene o establece los tipos de medios posibles utilizados durante la renderización. |
| input_encoding | Obtiene o establece el atributo que especifica la codificación utilizada para este documento en el momento del análisis. Si este atributo es nulo, la codificación se determinará a partir del atributo de conjunto de caracteres del documento. |
| base_path | La ruta/base URL para el archivo html. |
| page_info | Obtiene o establece la información de la página del documento |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)


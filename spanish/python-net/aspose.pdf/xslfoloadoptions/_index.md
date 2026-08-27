---
title: "XslFoLoadOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa opciones para cargar/importar un archivo XSL-FO en un documento pdf."
type: docs
weight: 1820
url: /es/python-net/aspose.pdf/xslfoloadoptions/
---

## XslFoLoadOptions class

Representa opciones para cargar/importar un archivo XSL-FO en un documento pdf.

El tipo XslFoLoadOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| XslFoLoadOptions() | Crea un objeto [XslFoLoadOptions](/pdf/python-net/aspose.pdf/xslfoloadoptions/) sin datos xsl. |
| XslFoLoadOptions(xsl_file) | Inicializa una nueva instancia de la clase XslFoLoadOptions |
| XslFoLoadOptions(xsl_stream) | Inicializa una nueva instancia de la clase XslFoLoadOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| warning_handler | Función de devolución de llamada para manejar cualquier advertencia generada. <br/>            El WarningHandler devuelve el elemento enum ReturnAction que especifica Continuar o Abort. <br/>            Continuar es la acción predeterminada y la operación de Carga continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación de Carga debe detenerse. |
| load_format | Representa el formato de archivo que describe [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| xsl_stream | Obtiene datos xsl para convertir xml en documento pdf. |
| base_path | La ruta/base URL desde la cual se buscan rutas relativas a recursos externos (si los hay) referenciados en el archivo SVG cargado. |
| parsing_errors_handling_type | El documento XSLFO de origen puede contener errores de formato. Este enum enumera posibles estrategias para manejar esos errores. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)


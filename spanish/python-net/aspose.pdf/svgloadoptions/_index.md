---
title: "SvgLoadOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa opciones para cargar/importar un archivo SVG en un documento pdf."
type: docs
weight: 1450
url: /es/python-net/aspose.pdf/svgloadoptions/
---

## SvgLoadOptions class

Representa opciones para cargar/importar un archivo SVG en un documento pdf.

El tipo SvgLoadOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| SvgLoadOptions() | Inicializa una nueva instancia de la clase SvgLoadOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| warning_handler | Función de devolución de llamada para manejar cualquier advertencia generada. <br/>            El WarningHandler devuelve el elemento enum ReturnAction que especifica Continuar o Abort. <br/>            Continuar es la acción predeterminada y la operación de Carga continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación de Carga debe detenerse. |
| load_format | Representa el formato de archivo que describe [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| page_info | Obtiene o establece la información de página que debe aplicarse durante la carga del documento.<br/>            NOTA que este parámetro solo funciona cuando ConversionEngine == ConversionEngines.NewEngine |
| adjust_page_size | Ajusta el tamaño de página PDF al tamaño SVG |
| conversion_engine | Permite seleccionar el motor de conversión que se utilizará durante la conversión.<br/>            Actualmente el nuevo motor está en fase de pruebas B, por lo que este valor se establece por defecto en <br/>            ConversionEngines.LegacyEngine |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)


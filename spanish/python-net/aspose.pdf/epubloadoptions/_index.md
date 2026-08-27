---
title: "EpubLoadOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Contiene opciones para cargar/importar un archivo EPUB en el documento pdf."
type: docs
weight: 310
url: /es/python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

Contiene opciones para cargar/importar un archivo EPUB en el documento pdf.

El tipo EpubLoadOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| EpubLoadOptions() | Crea opciones de carga predeterminadas para convertir un archivo EPUB en un documento pdf. <br/>            Tamaño de página pdf predeterminado - A4 300dpi 2480 X 3508. |
| EpubLoadOptions(page_size) | Inicializa una nueva instancia de la clase EpubLoadOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| warning_handler | Función de devolución de llamada para manejar cualquier advertencia generada. <br/>            El WarningHandler devuelve el elemento enum ReturnAction que especifica Continuar o Abort. <br/>            Continuar es la acción predeterminada y la operación de Carga continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación de Carga debe detenerse. |
| load_format | Representa el formato de archivo que describe [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| page_size | Obtiene o establece el tamaño de página de salida para la importación. |
| margen | Obtiene una referencia al objeto que representa la información de márgenes. |
| margins_area_usage_mode | Representa el modo de uso del área de márgenes - define el tratamiento <br/>              de instrucciones (si las hay) de CSS del documento importado<br/>              relacionadas con el uso de los márgenes. |
| page_size_adjustment_mode | ¡ATENCIÓN! La característica está implementada pero aún no se ha puesto en la API pública debido a un problema bloqueador en <br/>              la capa OSHARED revelado para el documento de ejemplo.<br/>              <br/>             <br/>              Representa el modo de uso del tamaño de página durante la conversión.<br/>             Los formatos (como HTML, EPUB, etc.), usualmente tienen un diseño flotante, por lo que permite ajustar el tamaño de página requerido.<br/>             Pero a veces el contenido tiene posiciones horizontales o tamaños especificados que <br/>             no permiten colocar el contenido en el tamaño de página requerido.<br/>               En tal caso podemos definir qué se debe hacer (p.ej., cuando el tamaño del contenido no cabe <br/>             en el tamaño de página inicial requerido del documento PDF resultante). |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)


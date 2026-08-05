---
title: "PdfSaveOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Opciones de guardado para exportar al formato Pdf"
type: docs
weight: 1240
url: /es/python-net/aspose.pdf/pdfsaveoptions/
---

## PdfSaveOptions class

Opciones de guardado para exportar al formato Pdf

El tipo PdfSaveOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfSaveOptions() | Inicializa una nueva instancia de la clase PdfSaveOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| warning_handler | Función de devolución de llamada para manejar cualquier advertencia generada. <br/>            El WarningHandler devuelve el elemento enum ReturnAction que especifica Continuar o Abort. <br/>            Continuar es la acción predeterminada y la operación Guardar continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Guardar debe detenerse. |
| save_format | Formato de guardado de datos. |
| close_response | Obtiene o establece un valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta. |
| temp_path | Ruta para archivos temporales. |
| default_font_name | Nombre de fuente usado por defecto para fuentes que están ausentes en el ordenador.<br/>            Cuando el documento PDF que se guarda contiene fuentes que no están disponibles <br/>            en el propio documento y en el dispositivo, la API reemplaza estas fuentes con la <br/>            fuente predeterminada (si se encuentra una fuente con [default_font_name](/pdf/python-net/aspose.pdf/pdfsaveoptions/) en el dispositivo) |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)


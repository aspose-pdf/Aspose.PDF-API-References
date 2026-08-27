---
title: "ApsSaveOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Opciones de guardado para exportar al formato XML de APS."
type: docs
weight: 20
url: /es/python-net/aspose.pdf/apssaveoptions/
---

## ApsSaveOptions class

Opciones de guardado para exportar al formato XML de APS.

El tipo ApsSaveOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| ApsSaveOptions() | Inicializa una nueva instancia de la clase ApsSaveOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| warning_handler | Función de devolución de llamada para manejar cualquier advertencia generada. <br/>            El WarningHandler devuelve el elemento enum ReturnAction que especifica Continuar o Abort. <br/>            Continuar es la acción predeterminada y la operación Guardar continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Guardar debe detenerse. |
| save_format | Formato de guardado de datos. |
| close_response | Obtiene o establece un valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta. |
| extract_ocr_sublayer_only | Este atributo habilita la funcionalidad para extraer imagen o texto <br/>            de documentos PDF con subcapa OCR. |
| try_merge_adjacent_same_background_images | A veces los PDF contienen imágenes de fondo (de páginas o celdas de tabla)<br/>              construidas a partir de varias imágenes de fondo de mosaico idénticas colocadas una junto a otra.<br/>              En tal caso, los renderizadores de formatos de destino (p.ej., MsWord para formato DOCS) a veces generan<br/>              bordes visibles entre partes de las imágenes de fondo,<br/>              porque sus técnicas de suavizado de bordes de imagen (anti-aliasing) son diferentes de las de Acrobat Reader.<br/>               Si parece que el documento exportado contiene dichos bordes visibles entre <br/>              partes de las mismas imágenes de fondo, por favor intente usar esta configuración para eliminar <br/>              ese efecto no deseado. <br/>                ¡ATENCIÓN! Esta optimización de calidad generalmente ralentiza considerablemente la conversión,<br/>              por lo que, por favor, use esta opción solo cuando sea realmente necesario. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)


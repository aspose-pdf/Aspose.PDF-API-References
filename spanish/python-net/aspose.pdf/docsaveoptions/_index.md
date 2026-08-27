---
title: "DocSaveOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Opciones de guardado para exportar al formato Doc"
type: docs
weight: 220
url: /es/python-net/aspose.pdf/docsaveoptions/
---

## DocSaveOptions class

Opciones de guardado para exportar al formato Doc

El tipo DocSaveOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| DocSaveOptions() | Inicializa una nueva instancia de la clase DocSaveOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| warning_handler | Función de devolución de llamada para manejar cualquier advertencia generada. <br/>            El WarningHandler devuelve el elemento enum ReturnAction que especifica Continuar o Abort. <br/>            Continuar es la acción predeterminada y la operación Guardar continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Guardar debe detenerse. |
| save_format | Formato de guardado de datos. |
| close_response | Obtiene o establece un valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta. |
| extract_ocr_sublayer_only | Este atributo habilita la funcionalidad para extraer imagen o texto <br/>            de documentos PDF con subcapa OCR. |
| try_merge_adjacent_same_background_images | A veces los PDF contienen imágenes de fondo (de páginas o celdas de tabla)<br/>              construidas a partir de varias imágenes de fondo de mosaico idénticas colocadas una junto a otra.<br/>              En tal caso, los renderizadores de formatos de destino (p.ej., MsWord para formato DOCS) a veces generan<br/>              bordes visibles entre partes de las imágenes de fondo,<br/>              porque sus técnicas de suavizado de bordes de imagen (anti-aliasing) son diferentes de las de Acrobat Reader.<br/>               Si parece que el documento exportado contiene dichos bordes visibles entre <br/>              partes de las mismas imágenes de fondo, por favor intente usar esta configuración para eliminar <br/>              ese efecto no deseado. <br/>                ¡ATENCIÓN! Esta optimización de calidad generalmente ralentiza considerablemente la conversión,<br/>              por lo que, por favor, use esta opción solo cuando sea realmente necesario. |
| modo | Modo de reconocimiento. |
| relative_horizontal_proximity | En Pdf las palabras pueden estar representadas internamente con operadores que imprimen palabras<br/>              imprimiendo independientemente sus letras o sílabas. Por lo tanto, para detectar palabras a veces necesitamos detectar grupos<br/>              de caracteres independientes que en realidad son palabras.<br/>                Esta configuración define el ancho del espacio entre elementos de texto (letras, sílabas) <br/>              que debe considerarse como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen.<br/>              (la presencia de un espacio vacío de al menos este ancho entre letras indica que <br/>               los elementos textuales pertenecen a palabras diferentes).<br/>              Está normalizado al tamaño de fuente: 1.0 significa el 100 % del supuesto tamaño de fuente de la palabra.<br/>             ¡ATENCIÓN! Se usa solo en casos en que el PDF de origen contiene fuentes específicas de uso raro<br/>             para las que no se puede calcular un valor óptimo a partir de la fuente. <br/>               Así, en la gran mayoría de los casos este parámetro no cambia nada en el documento resultante. |
| max_distance_between_text_lines | Este parámetro se utiliza para agrupar líneas de texto en párrafos.<br/>            Determina cuán separadas pueden estar dos líneas de texto relativas. Especificado en cientos de por ciento de la altura de las líneas de texto. |
| recognize_bullets | Activar el reconocimiento de viñetas |
| add_return_to_line_end | Usar saltos de párrafo o de línea |
| image_resolution_x | Resolución X de las imágenes convertidas. |
| image_resolution_y | Resolución Y de las imágenes convertidas. |
| formato | Formato de salida |
| batch_size | Define el tamaño del lote si la conversión por lotes es aplicable<br/>            al par de formatos de origen y destino. |
| memory_save_mode_path | Define la ruta (nombre de archivo o nombre de directorio) para almacenar<br/>            datos temporales al convertir en modo de guardado en memoria. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)


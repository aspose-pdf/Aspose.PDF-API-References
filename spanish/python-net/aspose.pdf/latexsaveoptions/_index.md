---
title: "LaTeXSaveOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Opciones de guardado para exportar al formato TeX."
type: docs
weight: 800
url: /es/python-net/aspose.pdf/latexsaveoptions/
---

## LaTeXSaveOptions class

Opciones de guardado para exportar al formato TeX.

El tipo LaTeXSaveOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| LaTeXSaveOptions() | Inicializa una nueva instancia de la clase LaTeXSaveOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| warning_handler | Ninguno |
| save_format | Ninguno |
| close_response | Ninguno |
| extract_ocr_sublayer_only | Este atributo habilita la funcionalidad para extraer imagen o texto <br/>            de documentos PDF con subcapa OCR. |
| try_merge_adjacent_same_background_images | A veces los PDF contienen imágenes de fondo (de páginas o celdas de tabla)<br/>              construidas a partir de varias imágenes de fondo de mosaico idénticas colocadas una junto a otra.<br/>              En tal caso, los renderizadores de formatos de destino (p.ej., MsWord para formato DOCS) a veces generan<br/>              bordes visibles entre partes de las imágenes de fondo,<br/>              porque sus técnicas de suavizado de bordes de imagen (anti-aliasing) son diferentes de las de Acrobat Reader.<br/>               Si parece que el documento exportado contiene dichos bordes visibles entre <br/>              partes de las mismas imágenes de fondo, por favor intente usar esta configuración para eliminar <br/>              ese efecto no deseado. <br/>                ¡ATENCIÓN! Esta optimización de calidad generalmente ralentiza considerablemente la conversión,<br/>              por lo que, por favor, use esta opción solo cuando sea realmente necesario. |
| out_directory_path | Propiedad para |
| pages_count | Devuelve el número de páginas después de la conversión. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| add_font_encs(font_encs) | Añade una codificación de fuente a la lista de codificaciones de fuentes |
| clear_font_encs() | Borra la lista de codificación de fuentes |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)


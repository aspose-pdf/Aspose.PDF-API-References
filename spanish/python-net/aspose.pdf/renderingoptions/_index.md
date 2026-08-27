---
title: "RenderingOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa opciones de renderizado."
type: docs
weight: 1330
url: /es/python-net/aspose.pdf/renderingoptions/
---

## RenderingOptions class

Representa opciones de renderizado.

El tipo RenderingOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| RenderingOptions() | Inicializa una nueva instancia de la clase RenderingOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| barcode_optimization | Obtiene o establece el modo de optimización de códigos de barras. |
| optimize_dimensions | Obtiene o establece el modo de optimización de dimensiones. |
| system_fonts_native_rendering | Obtiene o establece un modo donde las fuentes del sistema se renderizan de forma nativa. |
| use_new_imaging_engine | Obtiene o establece una bandera que determina si se utiliza o no el nuevo motor de imágenes. |
| width_extra_units | Obtiene o establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle. |
| height_extra_units | Obtiene o establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle. |
| convert_fonts_to_unicode_ttf | Indica que todas las fuentes se convertirán a versiones unicode TTF. Eso es útil por razones de compatibilidad <br/>             y para optimizar el uso de fuentes, ya que cada nueva fuente TTF no tendrá todos los símbolos <br/>             de la fuente original, sino solo los símbolos que se usan en el texto. |
| use_font_hinting | El uso de esta bandera activa el mecanismo de ajuste de fuentes. El ajuste de fuentes es el uso de instrucciones matemáticas para ajustar la visualización <br/>            de una fuente de contorno. En algunos casos, activar esta bandera puede resolver problemas de legibilidad del texto. <br/>            En el momento actual, el uso de esta bandera solo puede tener efecto para fuentes TTF, si estas fuentes se utilizan en el documento de origen. |
| scale_images_to_fit_page_width | Obtiene o establece valores utilizados para escalar todas las imágenes de la página para que se ajusten al ancho de la página. |
| interpolation_high_quality | Obtiene o establece el modo de alta calidad para la interpolación. |
| max_fonts_cache_size | Cantidad máxima de fuentes en la caché de fuentes. El valor predeterminado es 10. |
| max_symbols_cache_size | Cantidad máxima de símbolos en la caché de símbolos. El valor predeterminado es 100. |
| default_font_name | Obtiene/establece el nombre predeterminado de la fuente utilizada para sustituir fuentes faltantes. |
| ignore_resource_font_errors | Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuentes se ignorarán.<br/>            true - indica que los errores de ausencia de fuentes se ignorarán. Los segmentos de texto que hacen referencia a recursos incorrectos se omitirán durante el procesamiento.<br/>            false por defecto |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)


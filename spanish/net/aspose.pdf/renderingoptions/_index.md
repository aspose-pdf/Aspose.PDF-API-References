---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.RenderingOptions. Representa opciones de renderizado
type: docs
weight: 9760
url: /es/net/aspose.pdf/renderingoptions/
---
## Clase RenderingOptions

Representa opciones de renderizado.

```csharp
public sealed class RenderingOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Reemplaza fuentes según sea necesario para garantizar que todos los caracteres en el texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos: 1. Si el usuario establece explícitamente la propiedad DefaultFontName, verifica si la fuente especificada puede mostrar los caracteres deseados. 2. Si no se establece ninguna fuente definida por el usuario, busca entre las fuentes añadidas a través de !:FontRepository.Sources. 3. Analiza el texto para identificar su alfabeto o escritura y sugiere nombres de fuentes en consecuencia. Intenta localizar y usar estas fuentes del sistema. 4. Como alternativa, busca en el sistema cualquier fuente capaz de mostrar los caracteres requeridos. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Obtiene o establece el modo de optimización de códigos de barras. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Indica que todas las fuentes se convertirán a versiones TTF unicode. Eso es útil por razones de compatibilidad y para optimizar el uso de fuentes, ya que cada nueva fuente TTF no tendrá todos los símbolos de la fuente original, sino solo los símbolos que se utilizan en el texto. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Obtiene/establece el nombre predeterminado de la fuente utilizada para sustituir fuentes faltantes. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Obtiene o establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Obtiene o establece la indicación de que se ignorarán los errores relacionados con la ausencia de fuentes. true - significa que se ignorarán los errores de ausencia de fuentes. Los segmentos de texto que se refieren a recursos incorrectos se omitirán durante el procesamiento. false por defecto |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Obtiene o establece el modo de alta calidad para la interpolación. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Cantidad máxima de fuentes en la caché de fuentes. El valor predeterminado es 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Cantidad máxima de símbolos en la caché de símbolos. El valor predeterminado es 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Obtiene o establece el modo de optimización de dimensiones. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Obtiene o establece un modo donde las fuentes del sistema se renderizan de forma nativa. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | El uso de esta bandera activa el mecanismo de sugerencia de fuentes. La sugerencia de fuentes es el uso de instrucciones matemáticas para ajustar la visualización de una fuente de contorno. En algunos casos, activar esta bandera puede resolver problemas de legibilidad del texto. En este momento, el uso de esta bandera solo podría tener efecto para fuentes TTF, si estas fuentes se utilizan en el documento fuente. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Obtiene o establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle. |

### Ver También

* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)
---
title: "Aspose::Pdf::RenderingOptions class"
linktitle: "RenderingOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::RenderingOptions class. Representa opciones de renderizado en C++."
type: docs
weight: 16400
url: /es/cpp/aspose.pdf/renderingoptions/
---
## RenderingOptions class


Representa opciones de renderizado.

```cpp
class RenderingOptions : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AnalyzeFonts](./get_analyzefonts/)() const | Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos: |
| [get_BarcodeOptimization](./get_barcodeoptimization/)() const | Obtiene el modo de optimización de códigos de barras. |
| [get_ConvertFontsToUnicodeTTF](./get_convertfontstounicodettf/)() const | Indica que todas las fuentes se convertirán a versiones Unicode TTF. Esto es útil por razones de compatibilidad y para optimizar el uso de fuentes, ya que cada nueva fuente TTF no tendrá todos los símbolos de la fuente original, sino solo los símbolos que se utilizan en el texto. |
| [get_DefaultFontName](./get_defaultfontname/)() const | Obtiene/establece el nombre predeterminado de la fuente utilizada para sustituir fuentes faltantes. |
| [get_HeightExtraUnits](./get_heightextraunits/)() const | Obtiene un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle. |
| [get_IgnoreResourceFontErrors](./get_ignoreresourcefonterrors/)() const | Obtiene la indicación de que los errores relacionados con la ausencia de fuentes serán ignorados. true - significa que los errores de ausencia de fuentes serán ignorados. Los segmentos de [Text](../../aspose.pdf.text/) que hacen referencia a recursos incorrectos se omitirán durante el procesamiento. false por defecto. |
| [get_InterpolationHighQuality](./get_interpolationhighquality/)() const | Obtiene el modo hiqh de calidad para interpolación. |
| [get_MaxFontsCacheSize](./get_maxfontscachesize/)() const | Cantidad máxima de fuentes en la caché de fuentes. El valor predeterminado es 10. |
| [get_MaxSymbolsCacheSize](./get_maxsymbolscachesize/)() const | Cantidad máxima de símbolos en la caché de símbolos. El valor predeterminado es 100. |
| [get_OptimizeDimensions](./get_optimizedimensions/)() const | Obtiene el modo de optimización de dimensiones. |
| [get_ScaleImagesToFitPageWidth](./get_scaleimagestofitpagewidth/)() const | Obtiene un valor utilizado para escalar todas las imágenes en la página para ajustarse al ancho de la página. |
| [get_SystemFontsNativeRendering](./get_systemfontsnativerendering/)() const | Obtiene un modo en el que las fuentes del sistema se renderizan de forma nativa. |
| [get_UseFontHinting](./get_usefonthinting/)() const | El uso de esta bandera activa el mecanismo de hinting de fuentes. El hinting de fuentes es el uso de instrucciones matemáticas para ajustar la visualización de una fuente contorneada. En algunos casos, activar esta bandera puede resolver problemas de legibilidad del texto. En el momento actual, el uso de esta bandera solo puede tener efecto para fuentes TTF, si esas fuentes se utilizan en el documento fuente. |
| [get_UseNewImagingEngine](./get_usenewimagingengine/)() const | Obtiene una bandera que determina si se utiliza o no el nuevo motor de imágenes. |
| [get_WidthExtraUnits](./get_widthextraunits/)() const | Obtiene un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle. |
| [RenderingOptions](./renderingoptions/)() | Inicializa una nueva instancia del objeto [RenderingOptions](./). |
| [set_AnalyzeFonts](./set_analyzefonts/)(bool) | Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos: |
| [set_BarcodeOptimization](./set_barcodeoptimization/)(bool) | Establece el modo de optimización de códigos de barras. |
| [set_ConvertFontsToUnicodeTTF](./set_convertfontstounicodettf/)(bool) | Indica que todas las fuentes se convertirán a versiones Unicode TTF. Esto es útil por razones de compatibilidad y para optimizar el uso de fuentes, ya que cada nueva fuente TTF no tendrá todos los símbolos de la fuente original, sino solo los símbolos que se utilizan en el texto. |
| [set_DefaultFontName](./set_defaultfontname/)(const System::String\&) | Obtiene/establece el nombre predeterminado de la fuente utilizada para sustituir fuentes faltantes. |
| [set_HeightExtraUnits](./set_heightextraunits/)(float) | Establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle. |
| [set_IgnoreResourceFontErrors](./set_ignoreresourcefonterrors/)(bool) | Establece la indicación de que los errores relacionados con la ausencia de fuentes serán ignorados. true - significa que los errores de ausencia de fuentes serán ignorados. Los segmentos de [Text](../../aspose.pdf.text/) que hacen referencia a recursos incorrectos se omitirán durante el procesamiento. false por defecto. |
| [set_InterpolationHighQuality](./set_interpolationhighquality/)(bool) | Establece el modo hiqh de calidad para interpolación. |
| [set_MaxFontsCacheSize](./set_maxfontscachesize/)(int32_t) | Cantidad máxima de fuentes en la caché de fuentes. El valor predeterminado es 10. |
| [set_MaxSymbolsCacheSize](./set_maxsymbolscachesize/)(int32_t) | Cantidad máxima de símbolos en la caché de símbolos. El valor predeterminado es 100. |
| [set_OptimizeDimensions](./set_optimizedimensions/)(bool) | Establece el modo de optimización de dimensiones. |
| [set_ScaleImagesToFitPageWidth](./set_scaleimagestofitpagewidth/)(bool) | Establece un valor utilizado para escalar todas las imágenes de la página y ajustarlas al ancho de la página. |
| [set_SystemFontsNativeRendering](./set_systemfontsnativerendering/)(bool) | Establece un modo en el que las fuentes del sistema se renderizan de forma nativa. |
| [set_UseFontHinting](./set_usefonthinting/)(bool) | El uso de esta bandera activa el mecanismo de hinting de fuentes. El hinting de fuentes es el uso de instrucciones matemáticas para ajustar la visualización de una fuente contorneada. En algunos casos, activar esta bandera puede resolver problemas de legibilidad del texto. En el momento actual, el uso de esta bandera solo puede tener efecto para fuentes TTF, si esas fuentes se utilizan en el documento fuente. |
| [set_UseNewImagingEngine](./set_usenewimagingengine/)(bool) | Establece una bandera que determina si se utiliza o no el nuevo motor de imágenes. |
| [set_WidthExtraUnits](./set_widthextraunits/)(float) | Establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)

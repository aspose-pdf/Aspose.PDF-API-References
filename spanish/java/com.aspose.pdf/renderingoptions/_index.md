---
title: "RenderingOptions"
linktitle: "RenderingOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa opciones de renderizado"
type: docs
weight: 4150
url: /es/java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RenderingOptions

```
public final class RenderingOptions extends Object
```

Representa opciones de renderizado

## Constructores

| Constructor | Descripción |
| --- | --- |
| [RenderingOptions](#RenderingOptions--) | Inicializa una nueva instancia del objeto {@code RenderingOptions}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getAnalyzeFonts](#getAnalyzeFonts--) | Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos: 1. Si el usuario establece explícitamente la propiedad DefaultFontName, verifica si la fuente especificada puede mostrar los caracteres deseados. 2. Si no se ha definido una fuente por el usuario, busca entre las fuentes añadidas a través de {@code FontRepository.Sources}. 3. Analiza el texto para identificar su alfabeto o escritura y sugiere nombres de fuentes en consecuencia. Intenta localizar y usar esas fuentes del sistema. 4. Como alternativa, busca en el sistema cualquier fuente capaz de mostrar los caracteres requeridos. |
| [getBarcodeOptimization](#getBarcodeOptimization--) | Obtiene el modo de optimización de códigos de barras. |
| [getConvertFontsToUnicodeTTF](#getConvertFontsToUnicodeTTF--) | Indica que todas las fuentes se convertirán a versiones TTF Unicode. Esto es útil por razones de compatibilidad y para optimizar el uso de fuentes, ya que cada nueva fuente TTF no tendrá todos los símbolos de la fuente original, sino solo los símbolos que se utilizan en el texto. |
| [getDefaultFontName](#getDefaultFontName--) | Obtiene/establece el nombre predeterminado de la fuente utilizada para sustituir fuentes faltantes. |
| [getHeightExtraUnits](#getHeightExtraUnits--) | Obtiene o establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuentes se ignorarán. true - significa que se ignorarán los errores de ausencia de fuentes. Los segmentos de texto que hagan referencia a recursos incorrectos se omitirán durante el procesamiento. false por defecto |
| [getInterpolationHighQuality](#getInterpolationHighQuality--) | Obtiene o establece el modo de alta calidad para la interpolación. |
| [getMaxFontsCacheSize](#getMaxFontsCacheSize--) | Cantidad máxima de fuentes en la caché de fuentes. El valor predeterminado es 10. |
| [getMaxSymbolsCacheSize](#getMaxSymbolsCacheSize--) | Cantidad máxima de símbolos en la caché de símbolos. El valor predeterminado es 100. |
| [getOptimizeDimensions](#getOptimizeDimensions--) | Obtiene o establece el modo de optimización de dimensiones. |
| [getScaleImagesToFitPageWidth](#getScaleImagesToFitPageWidth--) | Obtiene o establece un valor utilizado para escalar todas las imágenes en la página para que se ajuste al ancho de la página. |
| [getSystemFontsNativeRendering](#getSystemFontsNativeRendering--) | Obtiene un modo en el que las fuentes del sistema se renderizan de forma nativa |
| [getUseFontHinting](#getUseFontHinting--) | El uso de esta bandera activa el mecanismo de ajuste de fuentes. El ajuste de fuentes es el uso de instrucciones matemáticas para ajustar la visualización de una fuente de contorno. En algunos casos, activar esta bandera puede resolver problemas de legibilidad del texto. En el momento actual, el uso de esta bandera solo puede tener efecto para fuentes TTF, si estas fuentes se utilizan en el documento fuente. |
| [getUseNewImagingEngine](#getUseNewImagingEngine--) | Obtiene una bandera que determina si se utiliza o no el nuevo motor de imágenes. |
| [getWidthExtraUnits](#getWidthExtraUnits--) | Obtiene o establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle. |
| [isTryToSkipDocumentErrors](#isTryToSkipDocumentErrors--) | Obtiene un valor utilizado para omitir errores durante el procesamiento del archivo PDF. |
| [setAnalyzeFonts](#setAnalyzeFonts-boolean-) | Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos: 1. Si el usuario establece explícitamente la propiedad DefaultFontName, verifica si la fuente especificada puede mostrar los caracteres deseados. 2. Si no se ha definido una fuente por el usuario, busca entre las fuentes añadidas a través de {@code FontRepository.Sources}. 3. Analiza el texto para identificar su alfabeto o escritura y sugiere nombres de fuentes en consecuencia. Intenta localizar y usar esas fuentes del sistema. 4. Como alternativa, busca en el sistema cualquier fuente capaz de mostrar los caracteres requeridos. |
| [setBarcodeOptimization](#setBarcodeOptimization-boolean-) | Establece el modo de optimización de códigos de barras. |
| [setConvertFontsToUnicodeTTF](#setConvertFontsToUnicodeTTF-boolean-) | Indica que todas las fuentes se convertirán a versiones TTF Unicode. Esto es útil por razones de compatibilidad y para optimizar el uso de fuentes, ya que cada nueva fuente TTF no tendrá todos los símbolos de la fuente original, sino solo los símbolos que se utilizan en el texto. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Obtiene/establece el nombre predeterminado de la fuente utilizada para sustituir fuentes faltantes. |
| [setHeightExtraUnits](#setHeightExtraUnits-float-) | Obtiene o establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuentes se ignorarán. true - significa que se ignorarán los errores de ausencia de fuentes. Los segmentos de texto que hagan referencia a recursos incorrectos se omitirán durante el procesamiento. false por defecto |
| [setInterpolationHighQuality](#setInterpolationHighQuality-boolean-) | Obtiene o establece el modo de alta calidad para la interpolación. |
| [setMaxFontsCacheSize](#setMaxFontsCacheSize-int-) | Cantidad máxima de fuentes en la caché de fuentes. El valor predeterminado es 10. |
| [setMaxSymbolsCacheSize](#setMaxSymbolsCacheSize-int-) | Cantidad máxima de símbolos en la caché de símbolos. El valor predeterminado es 100. |
| [setOptimizeDimensions](#setOptimizeDimensions-boolean-) | Obtiene o establece el modo de optimización de dimensiones. |
| [setScaleImagesToFitPageWidth](#setScaleImagesToFitPageWidth-boolean-) | Obtiene o establece un valor utilizado para escalar todas las imágenes en la página para que se ajuste al ancho de la página. |
| [setSystemFontsNativeRendering](#setSystemFontsNativeRendering-boolean-) | Establece un modo en el que las fuentes del sistema se renderizan de forma nativa. |
| [setTryToSkipDocumentErrors](#setTryToSkipDocumentErrors-boolean-) | Establece un valor utilizado para omitir errores durante el procesamiento del archivo PDF. |
| [setUseFontHinting](#setUseFontHinting-boolean-) | El uso de esta bandera activa el mecanismo de ajuste de fuentes. El ajuste de fuentes es el uso de instrucciones matemáticas para ajustar la visualización de una fuente de contorno. En algunos casos, activar esta bandera puede resolver problemas de legibilidad del texto. En el momento actual, el uso de esta bandera solo puede tener efecto para fuentes TTF, si estas fuentes se utilizan en el documento fuente. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Establece una bandera que determina si se utiliza o no el nuevo motor de imágenes. |
| [setWidthExtraUnits](#setWidthExtraUnits-float-) | Obtiene o establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle. |

### RenderingOptions {#RenderingOptions--}
```
public RenderingOptions()
```

Inicializa una nueva instancia del objeto {@code RenderingOptions}.

### getAnalyzeFonts {#getAnalyzeFonts--}
```
public final boolean getAnalyzeFonts()
```

Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos: 1. Si el usuario establece explícitamente la propiedad DefaultFontName, verifica si la fuente especificada puede mostrar los caracteres deseados. 2. Si no se ha definido una fuente por el usuario, busca entre las fuentes añadidas a través de {@code FontRepository.Sources}. 3. Analiza el texto para identificar su alfabeto o escritura y sugiere nombres de fuentes en consecuencia. Intenta localizar y usar esas fuentes del sistema. 4. Como alternativa, busca en el sistema cualquier fuente capaz de mostrar los caracteres requeridos.

**Returns:**
valor booleano

### getBarcodeOptimization {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```

Obtiene el modo de optimización de códigos de barras.

**Returns:**
valor booleano

### getConvertFontsToUnicodeTTF {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```

Indica que todas las fuentes se convertirán a versiones TTF Unicode. Esto es útil por razones de compatibilidad y para optimizar el uso de fuentes, ya que cada nueva fuente TTF no tendrá todos los símbolos de la fuente original, sino solo los símbolos que se utilizan en el texto.

**Returns:**
valor booleano

### getDefaultFontName {#getDefaultFontName--}
```
public final String getDefaultFontName()
```

Obtiene/establece el nombre predeterminado de la fuente utilizada para sustituir fuentes faltantes.

**Returns:**
valor String

### getHeightExtraUnits {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```

Obtiene o establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle.

**Returns:**
valor flotante

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuentes se ignorarán. true - significa que se ignorarán los errores de ausencia de fuentes. Los segmentos de texto que hagan referencia a recursos incorrectos se omitirán durante el procesamiento. false por defecto

**Returns:**
valor booleano

### getInterpolationHighQuality {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```

Obtiene o establece el modo de alta calidad para la interpolación.

**Returns:**
valor booleano

### getMaxFontsCacheSize {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```

Cantidad máxima de fuentes en la caché de fuentes. El valor predeterminado es 10.

**Returns:**
valor int

### getMaxSymbolsCacheSize {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```

Cantidad máxima de símbolos en la caché de símbolos. El valor predeterminado es 100.

**Returns:**
valor int

### getOptimizeDimensions {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```

Obtiene o establece el modo de optimización de dimensiones.

**Returns:**
valor booleano

### getScaleImagesToFitPageWidth {#getScaleImagesToFitPageWidth--}
```
@Deprecated public final boolean getScaleImagesToFitPageWidth()
```

Obtiene o establece un valor utilizado para escalar todas las imágenes en la página para que se ajuste al ancho de la página.

**Returns:**
valor booleano @deprecated ScaleImagesToFitPageWidth está obsoleto.

### getSystemFontsNativeRendering {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```

Obtiene un modo en el que las fuentes del sistema se renderizan de forma nativa

**Returns:**
valor booleano

### getUseFontHinting {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```

El uso de esta bandera activa el mecanismo de ajuste de fuentes. El ajuste de fuentes es el uso de instrucciones matemáticas para ajustar la visualización de una fuente de contorno. En algunos casos, activar esta bandera puede resolver problemas de legibilidad del texto. En el momento actual, el uso de esta bandera solo puede tener efecto para fuentes TTF, si estas fuentes se utilizan en el documento fuente.

**Returns:**
valor booleano

### getUseNewImagingEngine {#getUseNewImagingEngine--}
```
@Deprecated public boolean getUseNewImagingEngine()
```

Obtiene una bandera que determina si se utiliza o no el nuevo motor de imágenes.

**Returns:**
valor booleano @deprecated UseNewImagingEngine está obsoleto

### getWidthExtraUnits {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```

Obtiene o establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle.

**Returns:**
valor flotante

### isTryToSkipDocumentErrors {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```

Obtiene un valor utilizado para omitir errores durante el procesamiento del archivo PDF.

**Returns:**
valor booleano

### setAnalyzeFonts {#setAnalyzeFonts-boolean-}
```
public final void setAnalyzeFonts(boolean value)
```

Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos: 1. Si el usuario establece explícitamente la propiedad DefaultFontName, verifica si la fuente especificada puede mostrar los caracteres deseados. 2. Si no se ha definido una fuente por el usuario, busca entre las fuentes añadidas a través de {@code FontRepository.Sources}. 3. Analiza el texto para identificar su alfabeto o escritura y sugiere nombres de fuentes en consecuencia. Intenta localizar y usar esas fuentes del sistema. 4. Como alternativa, busca en el sistema cualquier fuente capaz de mostrar los caracteres requeridos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setBarcodeOptimization {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```

Establece el modo de optimización de códigos de barras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setConvertFontsToUnicodeTTF {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```

Indica que todas las fuentes se convertirán a versiones TTF Unicode. Esto es útil por razones de compatibilidad y para optimizar el uso de fuentes, ya que cada nueva fuente TTF no tendrá todos los símbolos de la fuente original, sino solo los símbolos que se utilizan en el texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Obtiene/establece el nombre predeterminado de la fuente utilizada para sustituir fuentes faltantes.

### setHeightExtraUnits {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```

Obtiene o establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuentes se ignorarán. true - significa que se ignorarán los errores de ausencia de fuentes. Los segmentos de texto que hagan referencia a recursos incorrectos se omitirán durante el procesamiento. false por defecto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setInterpolationHighQuality {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```

Obtiene o establece el modo de alta calidad para la interpolación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMaxFontsCacheSize {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```

Cantidad máxima de fuentes en la caché de fuentes. El valor predeterminado es 10.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setMaxSymbolsCacheSize {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```

Cantidad máxima de símbolos en la caché de símbolos. El valor predeterminado es 100.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setOptimizeDimensions {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```

Obtiene o establece el modo de optimización de dimensiones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setScaleImagesToFitPageWidth {#setScaleImagesToFitPageWidth-boolean-}
```
@Deprecated public final void setScaleImagesToFitPageWidth(boolean value)
```

Obtiene o establece un valor utilizado para escalar todas las imágenes en la página para que se ajuste al ancho de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano @deprecated ScaleImagesToFitPageWidth está obsoleto. |

### setSystemFontsNativeRendering {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```

Establece un modo en el que las fuentes del sistema se renderizan de forma nativa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setTryToSkipDocumentErrors {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```

Establece un valor utilizado para omitir errores durante el procesamiento del archivo PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseFontHinting {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```

El uso de esta bandera activa el mecanismo de ajuste de fuentes. El ajuste de fuentes es el uso de instrucciones matemáticas para ajustar la visualización de una fuente de contorno. En algunos casos, activar esta bandera puede resolver problemas de legibilidad del texto. En el momento actual, el uso de esta bandera solo puede tener efecto para fuentes TTF, si estas fuentes se utilizan en el documento fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public void setUseNewImagingEngine(boolean value)
```

Establece una bandera que determina si se utiliza o no el nuevo motor de imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano @deprecated UseNewImagingEngine está obsoleto |

### setWidthExtraUnits {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```

Obtiene o establece un valor utilizado para aumentar o disminuir el ancho del rectángulo para el operador AppendRectangle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

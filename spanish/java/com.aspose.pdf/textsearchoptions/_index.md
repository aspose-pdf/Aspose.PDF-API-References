---
title: "TextSearchOptions"
linktitle: "TextSearchOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa opciones de búsqueda de texto"
type: docs
weight: 5290
url: /es/java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextSearchOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextSearchOptions

```
public final class TextSearchOptions extends TextOptions
```

Representa opciones de búsqueda de texto

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextSearchOptions](#TextSearchOptions-boolean-) | Inicializa una nueva instancia del objeto {@code TextSearchOptions}. Especifica el modo de uso de expresiones regulares. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-) | Inicializa una nueva instancia del objeto TextSearchOptions. Especifica el rectángulo que delimita el texto buscado. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | Inicializa una nueva instancia del objeto TextSearchOptions. Especifica el rectángulo que delimita el texto buscado y el modo de uso de expresiones regulares. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getExcludeRectangles](#getExcludeRectangles--) | Obtiene o establece los rectángulos cuyos bordes excluyen el texto de la búsqueda. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuente serán ignorados por el absorbente de texto (fragmento). true - significa que los errores de ausencia de fuente serán ignorados. Los segmentos de texto que hacen referencia a recursos incorrectos se omitirán durante el procesamiento. false (predeterminado) - el error de ausencia de fuente terminará el procesamiento lanzando una excepción. |
| [getLimitToPageBounds](#getLimitToPageBounds--) | Obtiene la indicación de que el texto se busca dentro de los límites de la página. |
| [getLogTextExtractionErrors](#getLogTextExtractionErrors--) | Obtiene o establece la indicación de que los errores de extracción de texto (decodificación) se registrarán en el absorbente de texto (fragmento). true - significa que los errores de extracción de texto (decodificación) se registrarán. Puede disminuir el rendimiento. false (predeterminado) - no hay registro de errores. |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo que delimita el texto buscado. La propiedad puede usarse en caso de que sea necesario delimitar la extracción de texto o la región de reemplazo de texto. |
| [getSearchForTextRelatedGraphics](#getSearchForTextRelatedGraphics--) | Obtiene o establece el valor que permite buscar gráficos relacionados con el texto (subrayado, fondo, etc.) durante la búsqueda de texto. true - se realizará la búsqueda de gráficos relacionados con el texto (valor predeterminado). false - los elementos gráficos que puedan estar presentes en el documento fuente se ignorarán. Configure esto en caso de problemas de rendimiento o si no es necesario manejar subrayado, fondo o recorte. |
| [getStoredGraphicElementsMaxCount](#getStoredGraphicElementsMaxCount--) | Obtiene el valor que limita la búsqueda de gráficos relacionados con el texto (subrayado, fondo, etc.) en una página al número especificado de elementos. El valor predeterminado es 250. Establezca un valor menor en caso de problemas de rendimiento, pruebe un valor mayor si algunos elementos gráficos no se encuentran. |
| [getUseFontEngineEncoding](#getUseFontEngineEncoding--) | Obtiene la indicación de que el texto se buscará usando la codificación del motor de fuentes. true - significa que se usará la codificación del motor de fuentes (pruebe esto si la búsqueda de texto falla debido a una codificación imperfecta en el documento). false - significa que se usará la codificación de fuentes del documento (valor predeterminado). |
| [isDotallMode](#isDotallMode--) | <p> En modo dotall, la expresión <tt>.</tt> coincide con cualquier carácter, incluido un terminador de línea. Por defecto, esta expresión no coincide con los terminadores de línea. |
| [isIgnoreShadowText](#isIgnoreShadowText--) | Obtiene o establece la indicación de que los fragmentos de texto que representan la sombra del texto normal se ignorarán durante la búsqueda. true - significa que el texto en sombra no se encontrará (pruebe esto si la búsqueda de texto devuelve fragmentos duplicados en posiciones cercanas). false - significa que el texto en sombra se encontrará junto con el texto normal (valor predeterminado). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Indica si se usa o no una expresión regular. |
| [isSearchInAnnotations](#isSearchInAnnotations--) | Obtiene o establece el valor que permite buscar texto en Anotaciones. true - el texto se buscará en Anotaciones. false - el texto en Anotaciones no será analizado por TextFragmentAbsorber. |
| [setDotallMode](#setDotallMode-boolean-) | Habilita el modo dotall. <p> En modo dotall, la expresión <tt>.</tt> coincide con cualquier carácter, incluido un terminador de línea. Por defecto, esta expresión no coincide con los terminadores de línea. |
| [setExcludeRectangles](#setExcludeRectangles-com.aspose.pdf.Rectangle:A-) | Obtiene o establece los rectángulos cuyos bordes excluyen el texto de la búsqueda. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuente serán ignorados por el absorbente de texto (fragmento). true - significa que los errores de ausencia de fuente serán ignorados. Los segmentos de texto que hacen referencia a recursos incorrectos se omitirán durante el procesamiento. false (predeterminado) - el error de ausencia de fuente terminará el procesamiento lanzando una excepción. |
| [setIgnoreShadowText](#setIgnoreShadowText-boolean-) | Obtiene o establece la indicación de que los fragmentos de texto que representan la sombra del texto normal se ignorarán durante la búsqueda. true - significa que el texto en sombra no se encontrará (pruebe esto si la búsqueda de texto devuelve fragmentos duplicados en posiciones cercanas). false - significa que el texto en sombra se encontrará junto con el texto normal (valor predeterminado). |
| [setLimitToPageBounds](#setLimitToPageBounds-boolean-) | Establece la indicación de que el texto se busca dentro de los límites de la página. |
| [setLogTextExtractionErrors](#setLogTextExtractionErrors-boolean-) | Obtiene o establece la indicación de que los errores de extracción de texto (decodificación) se registrarán en el absorbente de texto (fragmento). true - significa que los errores de extracción de texto (decodificación) se registrarán. Puede disminuir el rendimiento. false (predeterminado) - no hay registro de errores. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Establece el rectángulo que delimita el texto buscado. La propiedad puede usarse en caso de que sea necesario delimitar la extracción de texto o la región de reemplazo de texto. |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Indica si se usa o no una expresión regular. |
| [setSearchForTextRelatedGraphics](#setSearchForTextRelatedGraphics-boolean-) | Obtiene o establece el valor que permite buscar gráficos relacionados con el texto (subrayado, fondo, etc.) durante la búsqueda de texto. true - se realizará la búsqueda de gráficos relacionados con el texto (valor predeterminado). false - los elementos gráficos que puedan estar presentes en el documento fuente se ignorarán. Configure esto en caso de problemas de rendimiento o si no es necesario manejar subrayado, fondo o recorte. |
| [setSearchInAnnotations](#setSearchInAnnotations-boolean-) | Obtiene o establece el valor que permite buscar texto en Anotaciones. true - el texto se buscará en Anotaciones. false - el texto en Anotaciones no será analizado por TextFragmentAbsorber. |
| [setStoredGraphicElementsMaxCount](#setStoredGraphicElementsMaxCount-int-) | Establece el valor que limita la búsqueda de gráficos relacionados con el texto (subrayado, fondo, etc.) en una página al número especificado de elementos. El valor predeterminado es 250. Establezca un valor menor en caso de problemas de rendimiento, pruebe un valor mayor si algunos elementos gráficos no se encontraron. |
| [setUseFontEngineEncoding](#setUseFontEngineEncoding-boolean-) | Establece la indicación de que el texto se buscará usando la codificación del motor de fuentes. true - significa que se usará la codificación del motor de fuentes (pruebe esto si la búsqueda de texto falla debido a una codificación imperfecta en el documento). false - significa que se usará la codificación de fuentes del documento (valor predeterminado). |

### TextSearchOptions {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```

Inicializa una nueva instancia del objeto {@code TextSearchOptions}. Especifica el modo de uso de expresiones regulares.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isRegularExpressionUsed |  | Valor que indica que se usa una expresión regular. |

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-}
Inicializa una nueva instancia del objeto TextSearchOptions. Especifica el rectángulo que delimita el texto buscado.

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
Inicializa una nueva instancia del objeto TextSearchOptions. Especifica el rectángulo que delimita el texto buscado y el modo de uso de expresiones regulares.

### getExcludeRectangles {#getExcludeRectangles--}
```
public final Rectangle [] getExcludeRectangles()
```

Obtiene o establece los rectángulos cuyos bordes excluyen el texto de la búsqueda.

**Returns:**
matriz de instancias de Rectangle

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuente serán ignorados por el absorbente de texto (fragmento). true - significa que los errores de ausencia de fuente serán ignorados. Los segmentos de texto que hacen referencia a recursos incorrectos se omitirán durante el procesamiento. false (predeterminado) - el error de ausencia de fuente terminará el procesamiento lanzando una excepción.

**Returns:**
valor booleano

### getLimitToPageBounds {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```

Obtiene la indicación de que el texto se busca dentro de los límites de la página.

**Returns:**
valor booleano

### getLogTextExtractionErrors {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```

Obtiene o establece la indicación de que los errores de extracción de texto (decodificación) se registrarán en el absorbente de texto (fragmento). true - significa que los errores de extracción de texto (decodificación) se registrarán. Puede disminuir el rendimiento. false (predeterminado) - no hay registro de errores.

**Returns:**
valor booleano

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo que delimita el texto buscado. La propiedad puede usarse en caso de que sea necesario delimitar la extracción de texto o la región de reemplazo de texto.

**Returns:**
Valor de rectángulo

### getSearchForTextRelatedGraphics {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```

Obtiene o establece el valor que permite buscar gráficos relacionados con el texto (subrayado, fondo, etc.) durante la búsqueda de texto. true - se realizará la búsqueda de gráficos relacionados con el texto (valor predeterminado). false - los elementos gráficos que puedan estar presentes en el documento fuente se ignorarán. Configure esto en caso de problemas de rendimiento o si no es necesario manejar subrayado, fondo o recorte.

**Returns:**
valor booleano

### getStoredGraphicElementsMaxCount {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```

Obtiene el valor que limita la búsqueda de gráficos relacionados con el texto (subrayado, fondo, etc.) en una página al número especificado de elementos. El valor predeterminado es 250. Establezca un valor menor en caso de problemas de rendimiento, pruebe un valor mayor si algunos elementos gráficos no se encuentran.

**Returns:**
valor int

### getUseFontEngineEncoding {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```

Obtiene la indicación de que el texto se buscará usando la codificación del motor de fuentes. true - significa que se usará la codificación del motor de fuentes (pruebe esto si la búsqueda de texto falla debido a una codificación imperfecta en el documento). false - significa que se usará la codificación de fuentes del documento (valor predeterminado).

**Returns:**
valor booleano

### isDotallMode {#isDotallMode--}
```
public static boolean isDotallMode()
```

<p> En modo dotall, la expresión <tt>.</tt> coincide con cualquier carácter, incluido un terminador de línea. Por defecto, esta expresión no coincide con los terminadores de línea.

**Returns:**
valor booleano

### isIgnoreShadowText {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```

Obtiene o establece la indicación de que los fragmentos de texto que representan la sombra del texto normal se ignorarán durante la búsqueda. true - significa que el texto en sombra no se encontrará (pruebe esto si la búsqueda de texto devuelve fragmentos duplicados en posiciones cercanas). false - significa que el texto en sombra se encontrará junto con el texto normal (valor predeterminado).

**Returns:**
valor booleano

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Indica si se usa o no una expresión regular.

**Returns:**
valor booleano

### isSearchInAnnotations {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```

Obtiene o establece el valor que permite buscar texto en Anotaciones. true - el texto se buscará en Anotaciones. false - el texto en Anotaciones no será analizado por TextFragmentAbsorber.

**Returns:**
valor booleano

### setDotallMode {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```

Habilita el modo dotall. <p> En modo dotall, la expresión <tt>.</tt> coincide con cualquier carácter, incluido un terminador de línea. Por defecto, esta expresión no coincide con los terminadores de línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dotallMode |  | valor booleano |

### setExcludeRectangles {#setExcludeRectangles-com.aspose.pdf.Rectangle:A-}
Obtiene o establece los rectángulos cuyos bordes excluyen el texto de la búsqueda.

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuente serán ignorados por el absorbente de texto (fragmento). true - significa que los errores de ausencia de fuente serán ignorados. Los segmentos de texto que hacen referencia a recursos incorrectos se omitirán durante el procesamiento. false (predeterminado) - el error de ausencia de fuente terminará el procesamiento lanzando una excepción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setIgnoreShadowText {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```

Obtiene o establece la indicación de que los fragmentos de texto que representan la sombra del texto normal se ignorarán durante la búsqueda. true - significa que el texto en sombra no se encontrará (pruebe esto si la búsqueda de texto devuelve fragmentos duplicados en posiciones cercanas). false - significa que el texto en sombra se encontrará junto con el texto normal (valor predeterminado).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setLimitToPageBounds {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```

Establece la indicación de que el texto se busca dentro de los límites de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setLogTextExtractionErrors {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```

Obtiene o establece la indicación de que los errores de extracción de texto (decodificación) se registrarán en el absorbente de texto (fragmento). true - significa que los errores de extracción de texto (decodificación) se registrarán. Puede disminuir el rendimiento. false (predeterminado) - no hay registro de errores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Establece el rectángulo que delimita el texto buscado. La propiedad puede usarse en caso de que sea necesario delimitar la extracción de texto o la región de reemplazo de texto.

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Indica si se usa o no una expresión regular.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSearchForTextRelatedGraphics {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```

Obtiene o establece el valor que permite buscar gráficos relacionados con el texto (subrayado, fondo, etc.) durante la búsqueda de texto. true - se realizará la búsqueda de gráficos relacionados con el texto (valor predeterminado). false - los elementos gráficos que puedan estar presentes en el documento fuente se ignorarán. Configure esto en caso de problemas de rendimiento o si no es necesario manejar subrayado, fondo o recorte.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSearchInAnnotations {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```

Obtiene o establece el valor que permite buscar texto en Anotaciones. true - el texto se buscará en Anotaciones. false - el texto en Anotaciones no será analizado por TextFragmentAbsorber.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setStoredGraphicElementsMaxCount {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```

Establece el valor que limita la búsqueda de gráficos relacionados con el texto (subrayado, fondo, etc.) en una página al número especificado de elementos. El valor predeterminado es 250. Establezca un valor menor en caso de problemas de rendimiento, pruebe un valor mayor si algunos elementos gráficos no se encontraron.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setUseFontEngineEncoding {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```

Establece la indicación de que el texto se buscará usando la codificación del motor de fuentes. true - significa que se usará la codificación del motor de fuentes (pruebe esto si la búsqueda de texto falla debido a una codificación imperfecta en el documento). false - significa que se usará la codificación de fuentes del documento (valor predeterminado).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

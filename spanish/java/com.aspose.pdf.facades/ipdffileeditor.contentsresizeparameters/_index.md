---
title: "IPdfFileEditor.ContentsResizeParameters"
linktitle: "IPdfFileEditor.ContentsResizeParameters"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase para especificar los parámetros de redimensionamiento de página. Permite establecer los siguientes parámetros: Tamaño de la página resultante (ancho, alto) en unidades de espacio predeterminadas o en porcentajes de las páginas iniciales."
type: docs
weight: 300
url: /es/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

Clase para especificar los parámetros de redimensionamiento de página. Permite establecer los siguientes parámetros: Tamaño de la página resultante (ancho, alto) en unidades de espacio predeterminadas o en porcentajes del tamaño de la página inicial; márgenes izquierdo, superior, inferior y derecho en unidades de espacio predeterminadas o en porcentajes del tamaño de la página inicial; Algunos valores pueden dejarse nulos para cálculo automático. Estos valores se calcularán a partir del resto del tamaño de la página después de calcular los valores especificados explícitamente. Por ejemplo: si el ancho de la página = 100 y el nuevo ancho de página especificado es 60 unidades, entonces los márgenes izquierdo y derecho se calculan automáticamente: (100 - 60) / 2 = 15. Esta clase se usa en el método ResizeContents.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | Crea parámetros de redimensionamiento donde todos los valores están establecidos en "auto". Más tarde se pueden especificar los márgenes y el tamaño del contenido si es necesario. |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Crea parámetros de redimensionamiento donde todos los valores están establecidos en "auto". Más tarde se pueden especificar los márgenes y el tamaño del contenido si es necesario. |

## Métodos

| Método | Descripción |
| --- | --- |
| [contentSize](#contentSize-double-double-) | Crea parámetros de redimensionamiento con el tamaño de contenido especificado. |
| [contentSizePercent](#contentSizePercent-double-double-) | Crea parámetros de redimensionamiento con el tamaño de contenido especificado en porcentajes del tamaño de la página inicial. Los márgenes se calculan automáticamente. |
| [getBottomMargin](#getBottomMargin--) | Obtiene o establece el margen inferior en la página resultante. |
| [getContentsHeight](#getContentsHeight--) | Obtiene o establece la altura del contenido de la página de origen en la página resultante. |
| [getContentsWidth](#getContentsWidth--) | Obtiene o establece el ancho del contenido de la página de origen en la página resultante. |
| [getLeftMargin](#getLeftMargin--) | Obtiene o establece el margen izquierdo en la página resultante. |
| [getRightMargin](#getRightMargin--) | Obtiene o establece el margen derecho en la página resultante. |
| [getTopMargin](#getTopMargin--) | Obtiene o establece el margen superior en la página resultante. |
| [isChangeMediaBox](#isChangeMediaBox--) | Obtiene si se debe ajustar el MediaBox de una página PDF durante la operación de redimensionamiento. El valor predeterminado es {@code false}. Configurar este parámetro permite ajustar el MediaBox al valor del CropBox durante el redimensionamiento. |
| [margins](#margins-double-double-double-double-) | Crea parámetros de redimensionamiento con el valor de márgenes especificado. El tamaño del contenido se calcula automáticamente. |
| [marginsPercent](#marginsPercent-double-double-double-double-) | Crea parámetros de redimensionamiento. Los márgenes se especifican en porcentajes del tamaño inicial de la página. |
| [pageResize](#pageResize-double-double-) | Crea parámetros de redimensionamiento para el redimensionamiento de la página. |
| [pageResizePct](#pageResizePct-double-double-) | Crea parámetros de redimensionamiento para el redimensionamiento de la página. Los nuevos tamaños se especifican en porcentaje. |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtiene o establece el margen inferior en la página resultante. |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | Establece si se debe ajustar el MediaBox de una página PDF durante la operación de redimensionamiento. El valor predeterminado es {@code false}. Configurar este parámetro permite ajustar el MediaBox al valor del CropBox durante el redimensionamiento. |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtiene o establece la altura del contenido de la página de origen en la página resultante. |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtiene o establece el ancho del contenido de la página de origen en la página resultante. |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtiene o establece el margen izquierdo en la página resultante. |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtiene o establece el margen derecho en la página resultante. |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtiene o establece el margen superior en la página resultante. |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

Crea parámetros de redimensionamiento donde todos los valores están establecidos en "auto". Más tarde se pueden especificar los márgenes y el tamaño del contenido si es necesario.

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Crea parámetros de redimensionamiento donde todos los valores están establecidos en "auto". Más tarde se pueden especificar los márgenes y el tamaño del contenido si es necesario.

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

Crea parámetros de redimensionamiento con el tamaño de contenido especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Nuevo ancho del contenido. |
| altura |  | Nueva altura del contenido. |

**Returns:**
Devuelve nuevos parámetros de redimensionamiento.

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

Crea parámetros de redimensionamiento con el tamaño de contenido especificado en porcentajes del tamaño de la página inicial. Los márgenes se calculan automáticamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Nuevo ancho del contenido en porcentajes. |
| altura |  | Nueva altura del contenido en porcentajes. |

**Returns:**
Nuevos parámetros de redimensionamiento.

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

Obtiene o establece el margen inferior en la página resultante.

**Returns:**
Objeto ContentsResizeValue

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

Obtiene o establece la altura del contenido de la página de origen en la página resultante.

**Returns:**
Objeto ContentsResizeValue

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

Obtiene o establece el ancho del contenido de la página de origen en la página resultante.

**Returns:**
Objeto ContentsResizeValue

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

Obtiene o establece el margen izquierdo en la página resultante.

**Returns:**
Objeto ContentsResizeValue

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

Obtiene o establece el margen derecho en la página resultante.

**Returns:**
Objeto ContentsResizeValue

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

Obtiene o establece el margen superior en la página resultante.

**Returns:**
Objeto ContentsResizeValue

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

Obtiene si se debe ajustar el MediaBox de una página PDF durante la operación de redimensionamiento. El valor predeterminado es {@code false}. Configurar este parámetro permite ajustar el MediaBox al valor del CropBox durante el redimensionamiento.

**Returns:**
si se debe ajustar el MediaBox de una página PDF durante la operación de redimensionamiento.

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

Crea parámetros de redimensionamiento con el valor de márgenes especificado. El tamaño del contenido se calcula automáticamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda |  | Margen izquierdo. |
| derecha |  | Margen derecho. |
| arriba |  | Margen superior. |
| inferior |  | Margen inferior. |

**Returns:**
Parámetros de redimensionamiento creados.

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

Crea parámetros de redimensionamiento. Los márgenes se especifican en porcentajes del tamaño inicial de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda |  | Margen izquierdo (en porcentajes del ancho de la página). |
| derecha |  | Margen derecho (en porcentajes de la altura de la página). |
| arriba |  | Margen superior (en porcentajes de la altura de la página). |
| inferior |  | Margen inferior (en porcentajes de la altura de la página). |

**Returns:**
Devuelve nuevos parámetros de redimensionamiento.

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

Crea parámetros de redimensionamiento para el redimensionamiento de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Nuevo ancho de página en unidades. |
| altura |  | Nueva altura de página en unidades. |

**Returns:**
Nuevos parámetros de redimensionamiento.

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

Crea parámetros de redimensionamiento para el redimensionamiento de la página. Los nuevos tamaños se especifican en porcentaje.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| widthPct |  | Nuevo ancho de página en porcentajes. |
| heightPct |  | Nueva altura de página en porcentajes. |

**Returns:**
Nuevos parámetros de redimensionamiento.

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtiene o establece el margen inferior en la página resultante.

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

Establece si se debe ajustar el MediaBox de una página PDF durante la operación de redimensionamiento. El valor predeterminado es {@code false}. Configurar este parámetro permite ajustar el MediaBox al valor del CropBox durante el redimensionamiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | si se debe ajustar el MediaBox de una página PDF durante la operación de redimensionamiento. |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtiene o establece la altura del contenido de la página de origen en la página resultante.

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtiene o establece el ancho del contenido de la página de origen en la página resultante.

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtiene o establece el margen izquierdo en la página resultante.

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtiene o establece el margen derecho en la página resultante.

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtiene o establece el margen superior en la página resultante.

---
title: "Graph"
linktitle: "Graph"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa gráfico - párrafo del generador de gráficos."
type: docs
weight: 70
url: /es/java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.drawing.Graph, com.aspose.pdf.BaseParagraph, com.aspose.pdf.drawing.Graph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Graph extends BaseParagraph
```

Representa gráfico - párrafo del generador de gráficos.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Graph](#Graph--) | Solo para uso interno |
| [Graph](#Graph-double-double-) | Inicializa una nueva instancia de la clase {@link Graph}. |
| [Graph](#Graph-float-float-) | Inicializa una nueva instancia de la clase {@code Graph}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone](#deepClone--) | Clona el gráfico. |
| [getBorder](#getBorder--) | Obtiene el borde. |
| [getGraphInfo](#getGraphInfo--) | Obtiene un objeto {@code GraphInfo} que indica la información del gráfico, como color, ancho de línea, etc. |
| [getHeight](#getHeight--) | Obtiene un valor flotante que indica la altura del gráfico. La unidad es punto. En XML, la unidad predeterminada es punto, pero también se admiten cm y pulgada. Por ejemplo, GraphHeight="10cm" o GraphHeight="5inch". |
| [getLeft](#getLeft--) | Obtiene la coordenada izquierda de la tabla. |
| [getShapes](#getShapes--) | Obtiene una colección que indica todas las formas del gráfico. |
| [getTitle](#getTitle--) | Obtiene el valor de cadena que indica el título del gráfico. |
| [getTop](#getTop--) | Obtiene la coordenada superior de la tabla. |
| [getWidth](#getWidth--) | Obtiene un valor flotante que indica el ancho del gráfico. La unidad es punto. En XML, la unidad predeterminada es punto, pero también se admiten cm y pulgada. Por ejemplo, GraphWidth="10cm" o GraphWidth="5inch". |
| [isChangePosition](#isChangePosition--) | Obtiene si cambia la posición actual después de procesar el párrafo.(valor predeterminado true) |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Establece el borde. |
| [setChangePosition](#setChangePosition-boolean-) | Establece si cambia la posición actual después de procesar el párrafo.(valor predeterminado true) |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Obtiene o establece un objeto {@code GraphInfo} que indica la información del gráfico, como color, ancho de línea, etc. |
| [setHeight](#setHeight-double-) | Establece un valor flotante que indica la altura del gráfico. La unidad es punto. En XML, la unidad predeterminada es punto, pero también se admiten cm y pulgada. Por ejemplo, GraphHeight="10cm" o GraphHeight="5inch". |
| [setLeft](#setLeft-double-) | Establece la coordenada izquierda de la tabla. |
| [setShapes](#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-) | Establece una colección que indica todas las formas del gráfico. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Establece el valor de cadena que indica el título del gráfico. |
| [setTop](#setTop-double-) | Establece la coordenada superior de la tabla. |
| [setWidth](#setWidth-double-) | Establece un valor flotante que indica el ancho del gráfico. La unidad es punto. En XML, la unidad predeterminada es punto, pero también se admiten cm y pulgada. Por ejemplo, GraphWidth="10cm" o GraphWidth="5inch". |

### Graph {#Graph--}
```
public Graph()
```

Solo para uso interno

### Graph {#Graph-double-double-}
```
public Graph(double width, double height)
```

Inicializa una nueva instancia de la clase {@link Graph}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | El ancho del gráfico. |
| altura |  | La altura del gráfico. |

### Graph {#Graph-float-float-}
```
@Deprecated public Graph(float width, float height)
```

Inicializa una nueva instancia de la clase {@code Graph}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | El ancho del gráfico. |
| altura |  | La altura del gráfico. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona el gráfico.

**Returns:**
El objeto clonado

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Obtiene el borde.

**Returns:**
Elemento BorderInfo

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Obtiene un objeto {@code GraphInfo} que indica la información del gráfico, como color, ancho de línea, etc.

**Returns:**
Objeto GraphInfo

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtiene un valor flotante que indica la altura del gráfico. La unidad es punto. En XML, la unidad predeterminada es punto, pero también se admiten cm y pulgada. Por ejemplo, GraphHeight="10cm" o GraphHeight="5inch".

**Returns:**
valor que indica la altura del gráfico.

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtiene la coordenada izquierda de la tabla.

**Returns:**
coordenada izquierda de la tabla.

### getShapes {#getShapes--}
```
public final BoundsCheckableList < Shape > getShapes()
```

Obtiene una colección que indica todas las formas del gráfico.

**Returns:**
BoundsCheckableList de Shapes.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Obtiene el valor de cadena que indica el título del gráfico.

**Returns:**
título del gráfico.

### getTop {#getTop--}
```
public double getTop()
```

Obtiene la coordenada superior de la tabla.

**Returns:**
la coordenada superior de la tabla.

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtiene un valor flotante que indica el ancho del gráfico. La unidad es punto. En XML, la unidad predeterminada es punto, pero también se admiten cm y pulgada. Por ejemplo, GraphWidth="10cm" o GraphWidth="5inch".

**Returns:**
valor float que indica el ancho del gráfico.

### isChangePosition {#isChangePosition--}
```
public boolean isChangePosition()
```

Obtiene si cambia la posición actual después de procesar el párrafo.(valor predeterminado true)

**Returns:**
valor booleano

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Establece el borde.

### setChangePosition {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```

Establece si cambia la posición actual después de procesar el párrafo.(valor predeterminado true)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Obtiene o establece un objeto {@code GraphInfo} que indica la información del gráfico, como color, ancho de línea, etc.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Establece un valor flotante que indica la altura del gráfico. La unidad es punto. En XML, la unidad predeterminada es punto, pero también se admiten cm y pulgada. Por ejemplo, GraphHeight="10cm" o GraphHeight="5inch".

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | que indica la altura del gráfico. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Establece la coordenada izquierda de la tabla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | coordenada izquierda de la tabla. |

### setShapes {#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-}
Establece una colección que indica todas las formas del gráfico.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Establece el valor de cadena que indica el título del gráfico.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Establece la coordenada superior de la tabla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | la coordenada superior de la tabla. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Establece un valor flotante que indica el ancho del gráfico. La unidad es punto. En XML, la unidad predeterminada es punto, pero también se admiten cm y pulgada. Por ejemplo, GraphWidth="10cm" o GraphWidth="5inch".

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor float que indica el ancho del gráfico. |

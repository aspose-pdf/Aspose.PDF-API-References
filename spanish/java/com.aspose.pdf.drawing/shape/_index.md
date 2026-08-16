---
title: "Shape"
linktitle: "Shape"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa forma - el objeto gráfico base."
type: docs
weight: 130
url: /es/java/com.aspose.pdf.drawing/shape/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public abstract class Shape extends Object implements IBoundsCheckableItem
```

Representa forma - el objeto gráfico base.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Shape](#Shape--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Comprueba si el elemento cabe dentro de las dimensiones del contenedor dadas (inclusive). |
| [getGraphInfo](#getGraphInfo--) | Obtiene el objeto que indica la información del gráfico, como color, ancho de línea, etc. |
| [getText](#getText--) | Obtiene o establece un texto para shape |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Establece el objeto que indica la información del gráfico, como color, ancho de línea, etc. |
| [setText](#setText-com.aspose.pdf.TextFragment-) | Obtiene o establece un texto para shape |

### Shape {#Shape--}
```
public Shape()
```



### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Comprueba si el elemento cabe dentro de las dimensiones del contenedor dadas (inclusive).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
Verdadero si cabe; de lo contrario, falso.

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Obtiene el objeto que indica la información del gráfico, como color, ancho de línea, etc.

**Returns:**
objeto que indica la información del gráfico.

### getText {#getText--}
```
public TextFragment getText()
```

Obtiene o establece un texto para shape

**Returns:**
Objeto TextFragment

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Establece el objeto que indica la información del gráfico, como color, ancho de línea, etc.

### setText {#setText-com.aspose.pdf.TextFragment-}
Obtiene o establece un texto para shape

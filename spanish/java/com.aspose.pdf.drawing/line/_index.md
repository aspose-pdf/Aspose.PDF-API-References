---
title: "Line"
linktitle: "Line"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una línea."
type: docs
weight: 90
url: /es/java/com.aspose.pdf.drawing/line/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Line, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Line

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Line extends Shape
```

Representa una línea.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Line](#Line--) | Solo para uso interno |
| [Line](#Line-float:A-) | Inicializa una nueva instancia de la clase {@code Line}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Comprueba si el elemento cabe dentro de las dimensiones del contenedor dadas (inclusive). |
| [getPositionArray](#getPositionArray--) | Obtiene el objeto que indica la matriz de posiciones. La matriz está compuesta por coordenadas de cada punto de control de la línea, directamente. |
| [setPositionArray](#setPositionArray-float:A-) | Establece el objeto que indica la matriz de posiciones. La matriz está compuesta por coordenadas de cada punto de control de la línea, directamente. |

### Line {#Line--}
```
public Line()
```

Solo para uso interno

### Line {#Line-float:A-}
```
public Line(float[] positionArray)
```

Inicializa una nueva instancia de la clase {@code Line}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| positionArray |  | La matriz de posiciones de la línea. |

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

### getPositionArray {#getPositionArray--}
```
public float[] getPositionArray()
```

Obtiene el objeto que indica la matriz de posiciones. La matriz está compuesta por coordenadas de cada punto de control de la línea, directamente.

**Returns:**
que indica la matriz de posiciones.

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Establece el objeto que indica la matriz de posiciones. La matriz está compuesta por coordenadas de cada punto de control de la línea, directamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | que indica la matriz de posiciones. |

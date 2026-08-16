---
title: "Curve"
linktitle: "Curve"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una curva Bézier."
type: docs
weight: 30
url: /es/java/com.aspose.pdf.drawing/curve/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Curve, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Curve

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Curve extends Shape
```

Representa una curva Bézier.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Curve](#Curve--) | Solo para uso interno |
| [Curve](#Curve-float:A-) | Inicializa una nueva instancia de la clase {@code Curve}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Comprueba si el elemento cabe dentro de las dimensiones del contenedor dadas (inclusive). |
| [getPositionArray](#getPositionArray--) | Obtiene una matriz de posiciones float. |
| [setPositionArray](#setPositionArray-float:A-) | Establece una matriz de posiciones float. |

### Curve {#Curve--}
```
public Curve()
```

Solo para uso interno

### Curve {#Curve-float:A-}
```
public Curve(float[] positionArray)
```

Inicializa una nueva instancia de la clase {@code Curve}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| positionArray |  | La matriz de posiciones de los puntos de control de la curva. Debería haber cuatro puntos de control, por lo que la longitud de la matriz debería ser ocho. |

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

Obtiene una matriz de posiciones float.

**Returns:**
float[] array

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Establece una matriz de posiciones float.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | float[] array |

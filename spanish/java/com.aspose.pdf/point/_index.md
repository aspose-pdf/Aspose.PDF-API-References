---
title: "Punto"
linktitle: "Punto"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un punto con coordenadas fraccionarias."
type: docs
weight: 3870
url: /es/java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Point

```
public final class Point extends Object
```

Representa un punto con coordenadas fraccionarias.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Point](#Point-double-double-) | Inicializa una nueva instancia de {@code Point}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [distance](#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Calcula la distancia entre dos puntos. |
| [getTrivial](#getTrivial--) | Obtiene el punto con coordenadas cero. |
| [getX](#getX--) | Obtiene el valor de la coordenada X. |
| [getY](#getY--) | Obtiene el valor de la coordenada Y. |
| [setX](#setX-double-) | Establece el valor de la coordenada X. |
| [setY](#setY-double-) | Establece el valor de la coordenada Y. |
| [toPoint](#toPoint--) | Convierte el punto en un objeto java.awt.geom.Point2D.Float. |
| [toString](#toString--) | Devuelve la representación en cadena del punto actual. |

### Point {#Point-double-double-}
```
public Point(double x, double y)
```

Inicializa una nueva instancia de {@code Point}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x |  | Valor de la coordenada x. |
| y |  | Valor de la coordenada y. |

### distance {#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Calcula la distancia entre dos puntos.

### getTrivial {#getTrivial--}
```
public static Point getTrivial()
```

Obtiene el punto con coordenadas cero.

**Returns:**
Objeto Point

### getX {#getX--}
```
public double getX()
```

Obtiene el valor de la coordenada X.

**Returns:**
valor double

### getY {#getY--}
```
public double getY()
```

Obtiene el valor de la coordenada Y.

**Returns:**
valor double

### setX {#setX-double-}
```
public void setX(double value)
```

Establece el valor de la coordenada X.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setY {#setY-double-}
```
public void setY(double value)
```

Establece el valor de la coordenada Y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### toPoint {#toPoint--}
```
public Point2D.Float toPoint()
```

Convierte el punto en un objeto java.awt.geom.Point2D.Float.

**Returns:**
Estructura Float.

### toString {#toString--}
```
public String toString()
```

Devuelve la representación en cadena del punto actual.

**Returns:**
Cadena que representa el punto actual.

---
title: "GraphInfo"
linktitle: "GraphInfo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa información gráfica."
type: docs
weight: 1840
url: /es/java/com.aspose.pdf/graphinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.GraphInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class GraphInfo extends Object implements com.aspose.ms.System.ICloneable
```

Representa información gráfica.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [GraphInfo](#GraphInfo--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone](#deepClone--) | Clona la información gráfica. |
| [getColor](#getColor--) | Obtiene un objeto {@code Color} que indica el color del gráfico. |
| [getDashArray](#getDashArray--) | Obtiene una matriz de guiones. |
| [getDashPhase](#getDashPhase--) | Obtiene una fase de guiones. |
| [getFillColor](#getFillColor--) | Obtiene un objeto {@code Color} que indica el color de relleno del gráfico. |
| [getLineWidth](#getLineWidth--) | Obtiene un valor float que indica el ancho de línea del gráfico. |
| [getRotationAngle](#getRotationAngle--) | Obtiene un valor float que indica el ángulo de rotación del sistema de coordenadas al transformar un sistema de coordenadas. |
| [getScalingRateX](#getScalingRateX--) | Obtiene un valor float que indica la tasa de escala de la coordenada x al transformar un sistema de coordenadas. |
| [getScalingRateY](#getScalingRateY--) | Obtiene un valor float que indica la tasa de escala de la coordenada y al transformar un sistema de coordenadas. |
| [getSkewAngleX](#getSkewAngleX--) | Obtiene un valor float que indica el ángulo de sesgo de la coordenada x al transformar un sistema de coordenadas. |
| [getSkewAngleY](#getSkewAngleY--) | Obtiene un valor float que indica el ángulo de sesgo de la coordenada y al transformar un sistema de coordenadas. |
| [getX](#getX--) | Recupera la coordenada X de un borde vertical al usar TableAbsorber, y devuelve "-1" para un borde horizontal. |
| [getY](#getY--) | Recupera la coordenada Y de un borde horizontal al usar TableAbsorber, y devuelve "-1" para un borde vertical. |
| [isDoubled](#isDoubled--) | Obtiene si el borde está duplicado. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Establece un objeto {@code Color} que indica el color del gráfico. |
| [setDashArray](#setDashArray-int:A-) | Establece un array de guiones. |
| [setDashPhase](#setDashPhase-int-) | Establece una fase de guiones. |
| [setDoubled](#setDoubled-boolean-) | Establece si el borde está duplicado. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | Establece un objeto {@code Color} que indica el color de relleno del gráfico. |
| [setLineWidth](#setLineWidth-float-) | Establece un valor float que indica el ancho de línea del gráfico. |
| [setRotationAngle](#setRotationAngle-double-) | Establece un valor float que indica el ángulo de rotación del sistema de coordenadas al transformar un sistema de coordenadas. |
| [setScalingRateX](#setScalingRateX-double-) | Establece un valor float que indica la tasa de escala de la coordenada x al transformar un sistema de coordenadas. |
| [setScalingRateY](#setScalingRateY-double-) | Establece un valor float que indica la tasa de escala de la coordenada y al transformar un sistema de coordenadas. |
| [setSkewAngleX](#setSkewAngleX-double-) | Establece un valor float que indica el ángulo de sesgo de la coordenada x al transformar un sistema de coordenadas. |
| [setSkewAngleY](#setSkewAngleY-double-) | Establece un valor float que indica el ángulo de sesgo de la coordenada y al transformar un sistema de coordenadas. |

### GraphInfo {#GraphInfo--}
```
public GraphInfo()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona la información gráfica.

**Returns:**
El objeto clonado

### getColor {#getColor--}
```
public Color getColor()
```

Obtiene un objeto {@code Color} que indica el color del gráfico.

**Returns:**
objeto que indica el color

### getDashArray {#getDashArray--}
```
public int[] getDashArray()
```

Obtiene una matriz de guiones.

**Returns:**
array de guiones

### getDashPhase {#getDashPhase--}
```
public int getDashPhase()
```

Obtiene una fase de guiones.

**Returns:**
fase de guiones.

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

Obtiene un objeto {@code Color} que indica el color de relleno del gráfico.

**Returns:**
objeto que indica el color de relleno

### getLineWidth {#getLineWidth--}
```
public float getLineWidth()
```

Obtiene un valor float que indica el ancho de línea del gráfico.

**Returns:**
valor que indica el ancho de línea.

### getRotationAngle {#getRotationAngle--}
```
public double getRotationAngle()
```

Obtiene un valor float que indica el ángulo de rotación del sistema de coordenadas al transformar un sistema de coordenadas.

**Returns:**
valor double

### getScalingRateX {#getScalingRateX--}
```
public double getScalingRateX()
```

Obtiene un valor float que indica la tasa de escala de la coordenada x al transformar un sistema de coordenadas.

**Returns:**
valor double

### getScalingRateY {#getScalingRateY--}
```
public double getScalingRateY()
```

Obtiene un valor float que indica la tasa de escala de la coordenada y al transformar un sistema de coordenadas.

**Returns:**
valor double

### getSkewAngleX {#getSkewAngleX--}
```
public double getSkewAngleX()
```

Obtiene un valor float que indica el ángulo de sesgo de la coordenada x al transformar un sistema de coordenadas.

**Returns:**
valor double

### getSkewAngleY {#getSkewAngleY--}
```
public double getSkewAngleY()
```

Obtiene un valor float que indica el ángulo de sesgo de la coordenada y al transformar un sistema de coordenadas.

**Returns:**
valor double

### getX {#getX--}
```
public final double getX()
```

Recupera la coordenada X de un borde vertical al usar TableAbsorber, y devuelve "-1" para un borde horizontal.

**Returns:**
valor double

### getY {#getY--}
```
public final double getY()
```

Recupera la coordenada Y de un borde horizontal al usar TableAbsorber, y devuelve "-1" para un borde vertical.

**Returns:**
valor double

### isDoubled {#isDoubled--}
```
public boolean isDoubled()
```

Obtiene si el borde está duplicado.

**Returns:**
valor booleano

### setColor {#setColor-com.aspose.pdf.Color-}
Establece un objeto {@code Color} que indica el color del gráfico.

### setDashArray {#setDashArray-int:A-}
```
public void setDashArray(int[] value)
```

Establece un array de guiones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | array de guiones |

### setDashPhase {#setDashPhase-int-}
```
public void setDashPhase(int value)
```

Establece una fase de guiones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | fase de guiones. |

### setDoubled {#setDoubled-boolean-}
```
public void setDoubled(boolean value)
```

Establece si el borde está duplicado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
Establece un objeto {@code Color} que indica el color de relleno del gráfico.

### setLineWidth {#setLineWidth-float-}
```
public void setLineWidth(float value)
```

Establece un valor float que indica el ancho de línea del gráfico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor que indica el ancho de línea. |

### setRotationAngle {#setRotationAngle-double-}
```
public void setRotationAngle(double value)
```

Establece un valor float que indica el ángulo de rotación del sistema de coordenadas al transformar un sistema de coordenadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setScalingRateX {#setScalingRateX-double-}
```
public void setScalingRateX(double value)
```

Establece un valor float que indica la tasa de escala de la coordenada x al transformar un sistema de coordenadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setScalingRateY {#setScalingRateY-double-}
```
public void setScalingRateY(double value)
```

Establece un valor float que indica la tasa de escala de la coordenada y al transformar un sistema de coordenadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setSkewAngleX {#setSkewAngleX-double-}
```
public void setSkewAngleX(double value)
```

Establece un valor float que indica el ángulo de sesgo de la coordenada x al transformar un sistema de coordenadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setSkewAngleY {#setSkewAngleY-double-}
```
public void setSkewAngleY(double value)
```

Establece un valor float que indica el ángulo de sesgo de la coordenada y al transformar un sistema de coordenadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

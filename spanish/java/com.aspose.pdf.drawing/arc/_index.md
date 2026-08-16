---
title: "Arc"
linktitle: "Arc"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un arco."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.drawing/arc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Arc, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Arc

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Arc extends Shape
```

Representa un arco.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Arc](#Arc--) | Solo para uso interno |
| [Arc](#Arc-double-double-double-double-double-) | Inicializa una nueva instancia de la clase {@code Arc}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Comprueba si el elemento cabe dentro de las dimensiones del contenedor dadas (inclusive). |
| [getAlpha](#getAlpha--) | Obtiene el valor float que indica el grado del ángulo inicial del arco. |
| [getBeta](#getBeta--) | Obtiene el valor float que indica el grado del ángulo final del arco. |
| [getPosX](#getPosX--) | Obtiene el valor flotante que indica la coordenada x del centro del arco. |
| [getPosY](#getPosY--) | Obtiene el valor flotante que indica la coordenada y del centro del arco. |
| [getRadius](#getRadius--) | Obtiene el valor float que indica el radio del arco. |
| [setAlpha](#setAlpha-double-) | Establece el valor float que indica el grado del ángulo inicial del arco. |
| [setBeta](#setBeta-double-) | Establece el valor float que indica el grado del ángulo final del arco. |
| [setPosX](#setPosX-double-) | Establece el valor flotante que indica la coordenada x del centro del arco. |
| [setPosY](#setPosY-double-) | Establece el valor flotante que indica la coordenada y del centro del arco. |
| [setRadius](#setRadius-double-) | Establece el valor float que indica el radio del arco. |

### Arc {#Arc--}
```
public Arc()
```

Solo para uso interno

### Arc {#Arc-double-double-double-double-double-}
```
public Arc(double posX, double posY, double radius, double alpha, double beta)
```

Inicializa una nueva instancia de la clase {@code Arc}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posX |  | La coordenada x del punto central del arco. |
| posY |  | La coordenada y del punto central del arco. |
| radius |  | El valor del radio del arco. |
| alpha |  | El valor del ángulo inicial del arco. |
| beta |  | El valor del ángulo final del arco. |

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

### getAlpha {#getAlpha--}
```
public double getAlpha()
```

Obtiene el valor float que indica el grado del ángulo inicial del arco.

**Returns:**
valor alpha.

### getBeta {#getBeta--}
```
public double getBeta()
```

Obtiene el valor float que indica el grado del ángulo final del arco.

**Returns:**
valor beta

### getPosX {#getPosX--}
```
public double getPosX()
```

Obtiene el valor flotante que indica la coordenada x del centro del arco.

**Returns:**
Coordenada x del centro del arco.

### getPosY {#getPosY--}
```
public double getPosY()
```

Obtiene el valor flotante que indica la coordenada y del centro del arco.

**Returns:**
Coordenada y del centro del arco.

### getRadius {#getRadius--}
```
public double getRadius()
```

Obtiene el valor float que indica el radio del arco.

**Returns:**
valor que indica el radio del arco.

### setAlpha {#setAlpha-double-}
```
public void setAlpha(double value)
```

Establece el valor float que indica el grado del ángulo inicial del arco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor alpha. |

### setBeta {#setBeta-double-}
```
public void setBeta(double value)
```

Establece el valor float que indica el grado del ángulo final del arco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor beta |

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

Establece el valor flotante que indica la coordenada x del centro del arco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Coordenada x del centro del arco. |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

Establece el valor flotante que indica la coordenada y del centro del arco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Coordenada y del centro del arco. |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

Establece el valor float que indica el radio del arco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | que indica el radio del arco. |

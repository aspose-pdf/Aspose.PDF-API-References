---
title: "Circle"
linktitle: "Circle"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un círculo."
type: docs
weight: 20
url: /es/java/com.aspose.pdf.drawing/circle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Circle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Circle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Circle extends Shape
```

Representa un círculo.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Circle](#Circle--) | Solo para uso interno |
| [Circle](#Circle-float-float-float-) | Inicializa una nueva instancia de la clase {@code Circle}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Comprueba si el elemento cabe dentro de las dimensiones del contenedor dadas (inclusive). |
| [getPosX](#getPosX--) | Obtiene el valor flotante que indica la coordenada x del centro del arco. |
| [getPosY](#getPosY--) | Obtiene el valor flotante que indica la coordenada y del centro del arco. |
| [getRadius](#getRadius--) | Obtiene el valor flotante que indica el radio del círculo. |
| [setPosX](#setPosX-double-) | Establece el valor flotante que indica la coordenada x del centro del arco. |
| [setPosY](#setPosY-double-) | Establece el valor flotante que indica la coordenada y del centro del arco. |
| [setRadius](#setRadius-double-) | Establece el valor flotante que indica el radio del círculo. |

### Circle {#Circle--}
```
public Circle()
```

Solo para uso interno

### Circle {#Circle-float-float-float-}
```
public Circle(float posX, float posY, float radius)
```

Inicializa una nueva instancia de la clase {@code Circle}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posX |  | La coordenada x del centro del círculo. |
| posY |  | La coordenada y del centro del círculo. |
| radius |  | El radio del círculo. |

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

Obtiene el valor flotante que indica el radio del círculo.

**Returns:**
valor que indica el radio del círculo.

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

Establece el valor flotante que indica el radio del círculo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | que indica el radio del círculo. |

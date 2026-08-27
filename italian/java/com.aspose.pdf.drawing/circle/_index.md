---
title: "Cerchio"
linktitle: "Cerchio"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un cerchio."
type: docs
weight: 20
url: /it/java/com.aspose.pdf.drawing/circle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Circle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Circle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Circle extends Shape
```

Rappresenta un cerchio.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Circle](#Circle--) | Solo per uso interno |
| [Circle](#Circle-float-float-float-) | Inizializza una nuova istanza della classe {@code Circle}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Verifica se l'elemento si adatta alle dimensioni del contenitore specificate (inclusivo). |
| [getPosX](#getPosX--) | Restituisce il valore float che indica la coordinata x del centro dell'arco. |
| [getPosY](#getPosY--) | Restituisce il valore float che indica la coordinata y del centro dell'arco. |
| [getRadius](#getRadius--) | Restituisce il valore float che indica il raggio del cerchio. |
| [setPosX](#setPosX-double-) | Imposta il valore float che indica la coordinata x del centro dell'arco. |
| [setPosY](#setPosY-double-) | Imposta il valore float che indica la coordinata y del centro dell'arco. |
| [setRadius](#setRadius-double-) | Imposta il valore float che indica il raggio del cerchio. |

### Circle {#Circle--}
```
public Circle()
```

Solo per uso interno

### Circle {#Circle-float-float-float-}
```
public Circle(float posX, float posY, float radius)
```

Inizializza una nuova istanza della classe {@code Circle}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| posX |  | La coordinata x del centro del cerchio. |
| posY |  | La coordinata y del centro del cerchio. |
| raggio |  | Il raggio del cerchio. |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Verifica se l'elemento si adatta alle dimensioni del contenitore specificate (inclusivo).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
Vero se si adatta; altrimenti, falso.

### getPosX {#getPosX--}
```
public double getPosX()
```

Restituisce il valore float che indica la coordinata x del centro dell'arco.

**Returns:**
coordinata x del centro dell'arco.

### getPosY {#getPosY--}
```
public double getPosY()
```

Restituisce il valore float che indica la coordinata y del centro dell'arco.

**Returns:**
coordinata y del centro dell'arco.

### getRadius {#getRadius--}
```
public double getRadius()
```

Restituisce il valore float che indica il raggio del cerchio.

**Returns:**
valore che indica il raggio del cerchio.

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

Imposta il valore float che indica la coordinata x del centro dell'arco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | coordinata x del centro dell'arco. |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

Imposta il valore float che indica la coordinata y del centro dell'arco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | coordinata y del centro dell'arco. |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

Imposta il valore float che indica il raggio del cerchio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | che indica il raggio del cerchio. |

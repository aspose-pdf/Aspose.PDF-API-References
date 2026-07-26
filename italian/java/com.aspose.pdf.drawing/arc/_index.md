---
title: "Arco"
linktitle: "Arco"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un arco."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.drawing/arc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Arc, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Arc

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Arc extends Shape
```

Rappresenta un arco.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Arc](#Arc--) | Solo per uso interno |
| [Arc](#Arc-double-double-double-double-double-) | Inizializza una nuova istanza della classe {@code Arc}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Verifica se l'elemento si adatta alle dimensioni del contenitore specificate (inclusivo). |
| [getAlpha](#getAlpha--) | Restituisce il valore float che indica il grado dell'angolo iniziale dell'arco. |
| [getBeta](#getBeta--) | Restituisce il valore float che indica il grado dell'angolo finale dell'arco. |
| [getPosX](#getPosX--) | Restituisce il valore float che indica la coordinata x del centro dell'arco. |
| [getPosY](#getPosY--) | Restituisce il valore float che indica la coordinata y del centro dell'arco. |
| [getRadius](#getRadius--) | Restituisce il valore float che indica il raggio dell'arco. |
| [setAlpha](#setAlpha-double-) | Imposta il valore float che indica il grado dell'angolo iniziale dell'arco. |
| [setBeta](#setBeta-double-) | Imposta il valore float che indica il grado dell'angolo finale dell'arco. |
| [setPosX](#setPosX-double-) | Imposta il valore float che indica la coordinata x del centro dell'arco. |
| [setPosY](#setPosY-double-) | Imposta il valore float che indica la coordinata y del centro dell'arco. |
| [setRadius](#setRadius-double-) | Imposta il valore float che indica il raggio dell'arco. |

### Arc {#Arc--}
```
public Arc()
```

Solo per uso interno

### Arc {#Arc-double-double-double-double-double-}
```
public Arc(double posX, double posY, double radius, double alpha, double beta)
```

Inizializza una nuova istanza della classe {@code Arc}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| posX |  | La coordinata x del punto centrale dell'arco. |
| posY |  | La coordinata y del punto centrale dell'arco. |
| raggio |  | Il valore del raggio dell'arco. |
| alpha |  | Il valore dell'angolo iniziale dell'arco. |
| beta |  | Il valore dell'angolo finale dell'arco. |

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

### getAlpha {#getAlpha--}
```
public double getAlpha()
```

Restituisce il valore float che indica il grado dell'angolo iniziale dell'arco.

**Returns:**
valore alpha.

### getBeta {#getBeta--}
```
public double getBeta()
```

Restituisce il valore float che indica il grado dell'angolo finale dell'arco.

**Returns:**
valore beta

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

Restituisce il valore float che indica il raggio dell'arco.

**Returns:**
valore che indica il raggio dell'arco.

### setAlpha {#setAlpha-double-}
```
public void setAlpha(double value)
```

Imposta il valore float che indica il grado dell'angolo iniziale dell'arco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore alpha. |

### setBeta {#setBeta-double-}
```
public void setBeta(double value)
```

Imposta il valore float che indica il grado dell'angolo finale dell'arco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore beta |

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

Imposta il valore float che indica il raggio dell'arco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | che indica il raggio dell'arco. |

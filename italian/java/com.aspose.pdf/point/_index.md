---
title: "Punto"
linktitle: "Punto"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un punto con coordinate frazionarie."
type: docs
weight: 3870
url: /it/java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Point

```
public final class Point extends Object
```

Rappresenta un punto con coordinate frazionarie.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Point](#Point-double-double-) | Inizializza una nuova istanza di {@code Point}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [distance](#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Calcola la distanza tra due punti. |
| [getTrivial](#getTrivial--) | Ottiene il punto con coordinate zero. |
| [getX](#getX--) | Ottiene il valore della coordinata X. |
| [getY](#getY--) | Ottiene il valore della coordinata Y. |
| [setX](#setX-double-) | Imposta il valore della coordinata X. |
| [setY](#setY-double-) | Imposta il valore della coordinata Y. |
| [toPoint](#toPoint--) | Converte il punto in un oggetto java.awt.geom.Point2D.Float. |
| [toString](#toString--) | Restituisce la rappresentazione stringa del punto corrente. |

### Point {#Point-double-double-}
```
public Point(double x, double y)
```

Inizializza una nuova istanza di {@code Point}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x |  | Valore della coordinata x. |
| y |  | Valore della coordinata y. |

### distance {#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Calcola la distanza tra due punti.

### getTrivial {#getTrivial--}
```
public static Point getTrivial()
```

Ottiene il punto con coordinate zero.

**Returns:**
Oggetto Point

### getX {#getX--}
```
public double getX()
```

Ottiene il valore della coordinata X.

**Returns:**
valore double

### getY {#getY--}
```
public double getY()
```

Ottiene il valore della coordinata Y.

**Returns:**
valore double

### setX {#setX-double-}
```
public void setX(double value)
```

Imposta il valore della coordinata X.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setY {#setY-double-}
```
public void setY(double value)
```

Imposta il valore della coordinata Y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### toPoint {#toPoint--}
```
public Point2D.Float toPoint()
```

Converte il punto in un oggetto java.awt.geom.Point2D.Float.

**Returns:**
Struttura Float.

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione stringa del punto corrente.

**Returns:**
Stringa, che rappresenta il punto corrente.

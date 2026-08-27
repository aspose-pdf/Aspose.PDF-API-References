---
title: "MoveTo"
linktitle: "MoveTo"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta {@code operators.m} (sposta a e inizia un nuovo sottopercorso)."
type: docs
weight: 410
url: /it/java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.MoveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.MoveTo

```
public class MoveTo extends Operator
```

Classe che rappresenta {@code operators.m} (sposta a e inizia un nuovo sottopercorso).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MoveTo](#MoveTo-double-double-) | Inizializza un nuovo {@code Operator.m} (move to) operatore. |
| [MoveTo](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getX](#getX--) | Coordinata X |
| [getY](#getY--) | Coordinata Y |
| [setX](#setX-double-) | Coordinata X |
| [setY](#setY-double-) | Coordinata Y |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### MoveTo {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```

Inizializza un nuovo {@code Operator.m} (move to) operatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x |  | La coordinata x. |
| y |  | La coordinata y. |

### MoveTo {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getX {#getX--}
```
public double getX()
```

Coordinata X

**Returns:**
valore double

### getY {#getY--}
```
public double getY()
```

Coordinata Y

**Returns:**
valore double

### setX {#setX-double-}
```
public void setX(double value)
```

Coordinata X

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordinata Y

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale dell'operatore.

**Returns:**
Rappresentazione testuale dell'operatore.

---
title: "LineTo"
linktitle: "LineTo"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore l (aggiunge una linea al percorso)."
type: docs
weight: 380
url: /it/java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.LineTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.LineTo

```
public class LineTo extends Operator
```

Classe che rappresenta l'operatore l (aggiunge una linea al percorso).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LineTo](#LineTo-double-double-) | Inizializza l'operatore di linea. |
| [LineTo](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getX](#getX--) | Coordinata X del punto di linea. |
| [getY](#getY--) | Coordinata Y del punto della linea. |
| [setX](#setX-double-) | Coordinata X del punto di linea. |
| [setY](#setY-double-) | Coordinata Y del punto della linea. |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### LineTo {#LineTo-double-double-}
```
public LineTo(double x, double y)
```

Inizializza l'operatore di linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x |  | Coordinata X. |
| y |  | Coordinata Y. |

### LineTo {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-}
Costruttore per la classe operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getX {#getX--}
```
public double getX()
```

Coordinata X del punto di linea.

**Returns:**
valore double

### getY {#getY--}
```
public double getY()
```

Coordinata Y del punto della linea.

**Returns:**
valore double

### setX {#setX-double-}
```
public void setX(double value)
```

Coordinata X del punto di linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordinata Y del punto della linea.

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

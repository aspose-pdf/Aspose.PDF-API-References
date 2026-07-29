---
title: "MoveTextPosition"
linktitle: "MoveTextPosition"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore Td (sposta la posizione del testo)."
type: docs
weight: 390
url: /it/java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPosition

```
public class MoveTextPosition extends TextPlaceOperator
```

Classe che rappresenta l'operatore Td (sposta la posizione del testo).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MoveTextPosition](#MoveTextPosition-double-double-) | Inizializza l'operatore. |
| [MoveTextPosition](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-) | Inizializza l'operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getX](#getX--) | Coordinata X della posizione del testo. |
| [getY](#getY--) | Coordinata Y della posizione del testo. |
| [setX](#setX-double-) | Coordinata X della posizione del testo. |
| [setY](#setY-double-) | Coordinata Y della posizione del testo. |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### MoveTextPosition {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```

Inizializza l'operatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x |  | Coordinata X della posizione del testo. |
| y |  | Coordinata Y della posizione del testo. |

### MoveTextPosition {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-}
Inizializza l'operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getX {#getX--}
```
public double getX()
```

Coordinata X della posizione del testo.

**Returns:**
valore double

### getY {#getY--}
```
public double getY()
```

Coordinata Y della posizione del testo.

**Returns:**
valore double

### setX {#setX-double-}
```
public void setX(double value)
```

Coordinata X della posizione del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordinata Y della posizione del testo.

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

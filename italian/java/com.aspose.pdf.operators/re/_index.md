---
title: "Re"
linktitle: "Re"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore re (aggiunge un rettangolo al percorso)."
type: docs
weight: 460
url: /it/java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Re, com.aspose.pdf.Operator, com.aspose.pdf.operators.Re

```
public class Re extends Operator
```

Classe che rappresenta l'operatore re (aggiunge un rettangolo al percorso).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Re](#Re--) | Costruttore per l'estrazione degli obiettivi. |
| [Re](#Re-double-double-double-double-) | Costruttore per il programma di scrittura. |
| [Re](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-) | Costruttore per l'estrazione degli obiettivi. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getHeight](#getHeight--) | Altezza del rettangolo. |
| [getWidth](#getWidth--) | Ottiene la larghezza del rettangolo. |
| [getX](#getX--) | Coordinata X del lato più sinistro del rettangolo. |
| [getY](#getY--) | Coordinata Y del lato inferiore del rettangolo. |
| [setHeight](#setHeight-double-) | Altezza del rettangolo. |
| [setWidth](#setWidth-double-) | Imposta la larghezza del rettangolo. |
| [setX](#setX-double-) | Coordinata X del lato più sinistro del rettangolo. |
| [setY](#setY-double-) | Coordinata Y del lato inferiore del rettangolo. |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### Re {#Re--}
```
public Re()
```

Costruttore per l'estrazione degli obiettivi.

### Re {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```

Costruttore per il programma di scrittura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x |  | La coordinata x dell'angolo in basso a sinistra del rettangolo. |
| y |  | La coordinata y dell'angolo in basso a sinistra del rettangolo. |
| larghezza |  | La larghezza del rettangolo. |
| altezza |  | L'altezza del rettangolo. |

### Re {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-}
Costruttore per l'estrazione degli obiettivi.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getHeight {#getHeight--}
```
public double getHeight()
```

Altezza del rettangolo.

**Returns:**
Altezza del rettangolo.

### getWidth {#getWidth--}
```
public double getWidth()
```

Ottiene la larghezza del rettangolo.

**Returns:**
larghezza del rettangolo.

### getX {#getX--}
```
public double getX()
```

Coordinata X del lato più sinistro del rettangolo.

**Returns:**
valore double

### getY {#getY--}
```
public double getY()
```

Coordinata Y del lato inferiore del rettangolo.

**Returns:**
valore double

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Altezza del rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Altezza del rettangolo. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Imposta la larghezza del rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | larghezza del rettangolo. |

### setX {#setX-double-}
```
public void setX(double value)
```

Coordinata X del lato più sinistro del rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordinata Y del lato inferiore del rettangolo.

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

---
title: "SetLineWidth"
linktitle: "SetLineWidth"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore w (imposta la larghezza della linea)."
type: docs
weight: 690
url: /it/java/com.aspose.pdf.operators/setlinewidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetLineWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetLineWidth

```
public class SetLineWidth extends Operator
```

Classe che rappresenta l'operatore w (imposta la larghezza della linea).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetLineWidth](#SetLineWidth-double-) | Inizializza l'operatore con il valore della larghezza. |
| [SetLineWidth](#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getWidth](#getWidth--) | Ottiene la larghezza della linea. |
| [setWidth](#setWidth-double-) | Imposta la larghezza della linea. |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### SetLineWidth {#SetLineWidth-double-}
```
public SetLineWidth(double width)
```

Inizializza l'operatore con il valore della larghezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Valore della larghezza. |

### SetLineWidth {#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-}
Costruttore per la classe operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getWidth {#getWidth--}
```
public double getWidth()
```

Ottiene la larghezza della linea.

**Returns:**
larghezza della linea.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Imposta la larghezza della linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | larghezza della linea. |

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale dell'operatore.

**Returns:**
Rappresentazione testuale dell'operatore.

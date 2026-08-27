---
title: "SetTextLeading"
linktitle: "SetTextLeading"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore TL (imposta l'interlinea del testo)."
type: docs
weight: 740
url: /it/java/com.aspose.pdf.operators/settextleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetTextLeading

```
public class SetTextLeading extends TextStateOperator
```

Classe che rappresenta l'operatore TL (imposta l'interlinea del testo).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetTextLeading](#SetTextLeading-double-) | Costruttore per l'operatore di interlinea del testo. |
| [SetTextLeading](#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getLeading](#getLeading--) | Restituisce l'interlinea del testo. |
| [setLeading](#setLeading-double-) | Imposta l'interlinea del testo. |
| [toString](#toString--) | Genera il codice di testo dell'operatore. |

### SetTextLeading {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```

Costruttore per l'operatore di interlinea del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leading |  | Interlinea del testo. |

### SetTextLeading {#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getLeading {#getLeading--}
```
public double getLeading()
```

Restituisce l'interlinea del testo.

**Returns:**
valore double

### setLeading {#setLeading-double-}
```
public void setLeading(double value)
```

Imposta l'interlinea del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### toString {#toString--}
```
public String toString()
```

Genera il codice di testo dell'operatore.

**Returns:**
Rappresentazione testuale dell'operatore.

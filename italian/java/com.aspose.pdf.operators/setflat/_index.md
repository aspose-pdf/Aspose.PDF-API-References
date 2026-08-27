---
title: "SetFlat"
linktitle: "SetFlat"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore i (imposta la tolleranza di piattezza)."
type: docs
weight: 620
url: /it/java/com.aspose.pdf.operators/setflat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetFlat, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetFlat

```
public class SetFlat extends Operator
```

Classe che rappresenta l'operatore i (imposta la tolleranza di piattezza).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetFlat](#SetFlat-double-) | Inizializza l'operatore. |
| [SetFlat](#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta un oggetto visitor per elaborare l'operatore. |
| [getFlatness](#getFlatness--) | Restituisce la planarità. |
| [setFlatness](#setFlatness-double-) | Imposta la planarità. |
| [toCommand](#toCommand--) | Solo per uso interno! |

### SetFlat {#SetFlat-double-}
```
public SetFlat(double flatness)
```

Inizializza l'operatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| piattezza |  | Il valore della piattezza. |

### SetFlat {#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-}
Costruttore per la classe operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta un oggetto visitor per elaborare l'operatore.

### getFlatness {#getFlatness--}
```
public double getFlatness()
```

Restituisce la planarità.

**Returns:**
valore double

### setFlatness {#setFlatness-double-}
```
public void setFlatness(double value)
```

Imposta la planarità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Solo per uso interno!

**Returns:**
ICommand valore oggetto ICommand

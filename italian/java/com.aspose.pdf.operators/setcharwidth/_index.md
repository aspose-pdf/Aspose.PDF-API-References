---
title: "SetCharWidth"
linktitle: "SetCharWidth"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore d0 (imposta la larghezza del glifo)."
type: docs
weight: 510
url: /it/java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidth

```
public class SetCharWidth extends Operator
```

Classe che rappresenta l'operatore d0 (imposta la larghezza del glifo).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SetCharWidth](#SetCharWidth-double-double-) | Costruttore. |
| [SetCharWidth](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getWx](#getWx--) | Spostamento orizzontale della coordinata del glifo. |
| [getWy](#getWy--) | Spostamento verticale della coordinata del glifo. |
| [toCommand](#toCommand--) | Solo per uso interno! |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### SetCharWidth {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```

Costruttore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| wx |  | Spostamento orizzontale del glifo. |
| wy |  | Spostamento verticale del glifo. |

### SetCharWidth {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Costruttore per la classe operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getWx {#getWx--}
```
public double getWx()
```

Spostamento orizzontale della coordinata del glifo.

**Returns:**
valore double

### getWy {#getWy--}
```
public double getWy()
```

Spostamento verticale della coordinata del glifo.

**Returns:**
valore double

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Solo per uso interno!

**Returns:**
ICommand valore oggetto ICommand

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale dell'operatore.

**Returns:**
Rappresentazione testuale della rappresentazione

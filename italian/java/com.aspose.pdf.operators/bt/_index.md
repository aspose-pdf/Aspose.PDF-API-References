---
title: "BT"
linktitle: "BT"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore BT (Inizio del blocco di testo)."
type: docs
weight: 70
url: /it/java/com.aspose.pdf.operators/bt/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.BlockTextOperator com.aspose.pdf.operators.BT, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.BlockTextOperator com.aspose.pdf.operators.BT, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.BlockTextOperator com.aspose.pdf.operators.BT, com.aspose.pdf.operators.BlockTextOperator, com.aspose.pdf.operators.BT

```
public class BT extends BlockTextOperator
```

Classe che rappresenta l'operatore BT (Inizio del blocco di testo).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BT](#BT--) | Costruttore per il programma di scrittura. |
| [BT](#BT-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Costruttore per il programma di scrittura. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [toCommand](#toCommand--) | Solo per uso interno! |
| [toString](#toString--) | Genera il codice di testo dell'operatore. |

### BT {#BT--}
```
public BT()
```

Costruttore per il programma di scrittura.

### BT {#BT-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Costruttore per il programma di scrittura.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

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

Genera il codice di testo dell'operatore.

**Returns:**
Rappresentazione testuale dell'operatore.

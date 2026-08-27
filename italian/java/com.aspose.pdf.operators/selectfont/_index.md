---
title: "SelectFont"
linktitle: "SelectFont"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore Tf (imposta il font del testo e la dimensione)."
type: docs
weight: 470
url: /it/java/com.aspose.pdf.operators/selectfont/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SelectFont

```
public class SelectFont extends TextStateOperator
```

Classe che rappresenta l'operatore Tf (imposta il font del testo e la dimensione).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SelectFont](#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-) | Costruttore per la classe operatore. |
| [SelectFont](#SelectFont-java.lang.String-double-) | Costruttore per il programma di scrittura. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getName](#getName--) | Ottiene il nome del carattere. |
| [getSize](#getSize--) | Ottiene la dimensione del testo. |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### SelectFont {#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-}
Costruttore per la classe operatore.

### SelectFont {#SelectFont-java.lang.String-double-}
Costruttore per il programma di scrittura.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getName {#getName--}
```
public String getName()
```

Ottiene il nome del carattere.

**Returns:**
valore String

### getSize {#getSize--}
```
public double getSize()
```

Ottiene la dimensione del testo.

**Returns:**
valore double

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale dell'operatore.

**Returns:**
Rappresentazione testuale dell'operatore.

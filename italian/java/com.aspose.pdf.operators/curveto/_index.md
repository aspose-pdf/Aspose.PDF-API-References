---
title: "CurveTo"
linktitle: "CurveTo"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore c (aggiunge una curva al percorso)."
type: docs
weight: 150
url: /it/java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo

```
public class CurveTo extends Operator
```

Classe che rappresenta l'operatore c (aggiunge una curva al percorso).

## Campi

| Campo | Descrizione |
| --- | --- |
| [X1](#X1) | Ottiene o imposta la coordinata X1. |
| [X2](#X2) | Ottiene o imposta la coordinata X2. |
| [X3](#X3) | Ottiene o imposta la coordinata X3. |
| [Y1](#Y1) | Ottiene o imposta la coordinata Y1. |
| [Y2](#Y2) | Ottiene o imposta la coordinata Y2. |
| [Y3](#Y3) | Ottiene o imposta la coordinata Y3. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CurveTo](#CurveTo-double-double-double-double-double-double-) | Inizializza l'operatore di curva. |
| [CurveTo](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [toCommand](#toCommand--) | Solo per uso interno! |
| [toString](#toString--) | Restituisce la rappresentazione testuale dell'operatore. |

### X1 {#X1}
```
public double X1
```

Ottiene o imposta la coordinata X1.

### X2 {#X2}
```
public double X2
```

Ottiene o imposta la coordinata X2.

### X3 {#X3}
```
public double X3
```

Ottiene o imposta la coordinata X3.

### Y1 {#Y1}
```
public double Y1
```

Ottiene o imposta la coordinata Y1.

### Y2 {#Y2}
```
public double Y2
```

Ottiene o imposta la coordinata Y2.

### Y3 {#Y3}
```
public double Y3
```

Ottiene o imposta la coordinata Y3.

### CurveTo {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```

Inizializza l'operatore di curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 |  | Ascissa del primo punto. |
| y1 |  | Ordinata del primo punto. |
| x2 |  | Ascissa del secondo punto. |
| y2 |  | Ordinata del secondo punto. |
| x3 |  | Ascissa del terzo punto. |
| y3 |  | Ordinata del terzo punto. |

### CurveTo {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-}
Costruttore per la classe operatore.

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

Restituisce la rappresentazione testuale dell'operatore.

**Returns:**
Rappresentazione testuale dell'operatore.

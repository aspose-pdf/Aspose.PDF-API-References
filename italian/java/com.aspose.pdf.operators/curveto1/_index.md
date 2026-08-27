---
title: "CurveTo1"
linktitle: "CurveTo1"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore v (aggiunge una curva al percorso, replicando il punto iniziale)."
type: docs
weight: 160
url: /it/java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo1, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo1

```
public class CurveTo1 extends Operator
```

Classe che rappresenta l'operatore v (aggiunge una curva al percorso, replicando il punto iniziale).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CurveTo1](#CurveTo1-double-double-double-double-) | Inizializza l'operatore di curva. |
| [CurveTo1](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta il selettore dell'operatore. |
| [getPoints](#getPoints--) | Punti della curva. |

### CurveTo1 {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```

Inizializza l'operatore di curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x2 |  | Ascissa del secondo punto. |
| y2 |  | Ordinata del secondo punto. |
| x3 |  | Ascissa del terzo punto. |
| y3 |  | Ordinata del terzo punto. |

### CurveTo1 {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-}
Costruttore per la classe operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta il selettore dell'operatore.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Punti della curva.

**Returns:**
array di istanze di Point

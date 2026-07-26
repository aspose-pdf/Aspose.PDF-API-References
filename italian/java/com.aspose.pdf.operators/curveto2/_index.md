---
title: "CurveTo2"
linktitle: "CurveTo2"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'operatore y (aggiunge una curva al percorso, replicando il punto finale)."
type: docs
weight: 170
url: /it/java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo2, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo2

```
public class CurveTo2 extends Operator
```

Classe che rappresenta l'operatore y (aggiunge una curva al percorso, replicando il punto finale).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CurveTo2](#CurveTo2-double-double-double-double-) | Inizializza l'operatore di curva. |
| [CurveTo2](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-) | Costruttore per la classe operatore. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accetta l'oggetto visitor per elaborare l'operatore. |
| [getPoints](#getPoints--) | Punti della curva. |

### CurveTo2 {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```

Inizializza l'operatore di curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 |  | Ascissa del secondo punto. |
| y1 |  | Ordinata del secondo punto. |
| x3 |  | Ascissa del terzo punto. |
| y3 |  | Ordinata del terzo punto. |

### CurveTo2 {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-}
Costruttore per la classe operatore.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accetta l'oggetto visitor per elaborare l'operatore.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Punti della curva.

**Returns:**
array di istanze di Point

---
title: "CurveTo1"
linktitle: "CurveTo1"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen representerar v-operatorn (append curve to path, initial point replicated)."
type: docs
weight: 160
url: /sv/java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo1, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo1

```
public class CurveTo1 extends Operator
```

Klassen representerar v-operatorn (append curve to path, initial point replicated).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CurveTo1](#CurveTo1-double-double-double-double-) | Initierar kurvoperatorn. |
| [CurveTo1](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar operatörsväljare. |
| [getPoints](#getPoints--) | Punkter på kurvan. |

### CurveTo1 {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```

Initierar kurvoperatorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x2 |  | Abskissa för andra punkten. |
| y2 |  | Ordinat för andra punkten. |
| x3 |  | Abskissa för tredje punkten. |
| y3 |  | Ordinat för tredje punkten. |

### CurveTo1 {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-}
Konstruktor för operator-klassen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar operatörsväljare.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Punkter på kurvan.

**Returns:**
array av Point-instans

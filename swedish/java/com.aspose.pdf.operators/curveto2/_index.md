---
title: "CurveTo2"
linktitle: "CurveTo2"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen representerar y-operatorn (append curve to path, final point replicated)."
type: docs
weight: 170
url: /sv/java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo2, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo2

```
public class CurveTo2 extends Operator
```

Klassen representerar y-operatorn (append curve to path, final point replicated).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CurveTo2](#CurveTo2-double-double-double-double-) | Initierar kurvoperatorn. |
| [CurveTo2](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getPoints](#getPoints--) | Punkter på kurvan. |

### CurveTo2 {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```

Initierar kurvoperatorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 |  | Abskissa för andra punkten. |
| y1 |  | Ordinat för andra punkten. |
| x3 |  | Abskissa för tredje punkten. |
| y3 |  | Ordinat för tredje punkten. |

### CurveTo2 {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-}
Konstruktor för operator-klassen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Punkter på kurvan.

**Returns:**
array av Point-instans

---
title: "CurveTo1"
linktitle: "CurveTo1"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den v‑Operator (Kurve zum Pfad hinzufügen, Anfangspunkt repliziert) darstellt."
type: docs
weight: 160
url: /de/java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo1, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo1

```
public class CurveTo1 extends Operator
```

Klasse, die den v‑Operator (Kurve zum Pfad hinzufügen, Anfangspunkt repliziert) darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CurveTo1](#CurveTo1-double-double-double-double-) | Initialisiert den Kurvenoperator. |
| [CurveTo1](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert Operator-Selektor. |
| [getPoints](#getPoints--) | Punkte der Kurve. |

### CurveTo1 {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```

Initialisiert den Kurvenoperator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x2 |  | Abszisse des zweiten Punktes. |
| y2 |  | Ordinate des zweiten Punktes. |
| x3 |  | Abszisse des dritten Punktes. |
| y3 |  | Ordinate des dritten Punktes. |

### CurveTo1 {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-}
Konstruktor für die Operator-Klasse.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert Operator-Selektor.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Punkte der Kurve.

**Returns:**
Array von Point-Instanzen

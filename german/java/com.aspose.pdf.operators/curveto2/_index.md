---
title: "CurveTo2"
linktitle: "CurveTo2"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den y‑Operator (Kurve zum Pfad hinzufügen, Endpunkt repliziert) darstellt."
type: docs
weight: 170
url: /de/java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo2, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo2

```
public class CurveTo2 extends Operator
```

Klasse, die den y‑Operator (Kurve zum Pfad hinzufügen, Endpunkt repliziert) darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CurveTo2](#CurveTo2-double-double-double-double-) | Initialisiert den Kurvenoperator. |
| [CurveTo2](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getPoints](#getPoints--) | Punkte der Kurve. |

### CurveTo2 {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```

Initialisiert den Kurvenoperator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 |  | Abszisse des zweiten Punktes. |
| y1 |  | Ordinate des zweiten Punktes. |
| x3 |  | Abszisse des dritten Punktes. |
| y3 |  | Ordinate des dritten Punktes. |

### CurveTo2 {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-}
Konstruktor für die Operator-Klasse.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Punkte der Kurve.

**Returns:**
Array von Point-Instanzen

---
title: "CurveTo"
linktitle: "CurveTo"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den c‑Operator (Kurve zum Pfad hinzufügen) darstellt."
type: docs
weight: 150
url: /de/java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo

```
public class CurveTo extends Operator
```

Klasse, die den c‑Operator (Kurve zum Pfad hinzufügen) darstellt.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [X1](#X1) | Liest oder setzt die X1-Koordinate. |
| [X2](#X2) | Liest oder setzt die X2-Koordinate. |
| [X3](#X3) | Liest oder setzt die X3-Koordinate. |
| [Y1](#Y1) | Liest oder setzt die Y1-Koordinate. |
| [Y2](#Y2) | Liest oder setzt die Y2-Koordinate. |
| [Y3](#Y3) | Liest oder setzt die Y3-Koordinate. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CurveTo](#CurveTo-double-double-double-double-double-double-) | Initialisiert den Kurvenoperator. |
| [CurveTo](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [toCommand](#toCommand--) | Nur für den internen Gebrauch! |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### X1 {#X1}
```
public double X1
```

Liest oder setzt die X1-Koordinate.

### X2 {#X2}
```
public double X2
```

Liest oder setzt die X2-Koordinate.

### X3 {#X3}
```
public double X3
```

Liest oder setzt die X3-Koordinate.

### Y1 {#Y1}
```
public double Y1
```

Liest oder setzt die Y1-Koordinate.

### Y2 {#Y2}
```
public double Y2
```

Liest oder setzt die Y2-Koordinate.

### Y3 {#Y3}
```
public double Y3
```

Liest oder setzt die Y3-Koordinate.

### CurveTo {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```

Initialisiert den Kurvenoperator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 |  | Abszisse des ersten Punktes. |
| y1 |  | Ordinate des ersten Punktes. |
| x2 |  | Abszisse des zweiten Punktes. |
| y2 |  | Ordinate des zweiten Punktes. |
| x3 |  | Abszisse des dritten Punktes. |
| y3 |  | Ordinate des dritten Punktes. |

### CurveTo {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-}
Konstruktor für die Operator-Klasse.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Nur für den internen Gebrauch!

**Returns:**
ICommand-Wert ICommand-Objekt

### toString {#toString--}
```
public String toString()
```

Gibt die Textdarstellung des Operators zurück.

**Returns:**
Textdarstellung des Operators.

---
title: "CurveTo"
linktitle: "CurveTo"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen representerar c-operatorn (append curve to path)."
type: docs
weight: 150
url: /sv/java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo

```
public class CurveTo extends Operator
```

Klassen representerar c-operatorn (append curve to path).

## Fält

| Fält | Beskrivning |
| --- | --- |
| [X1](#X1) | Hämtar eller anger X1-koordinaten. |
| [X2](#X2) | Hämtar eller anger X2-koordinaten. |
| [X3](#X3) | Hämtar eller anger X3-koordinaten. |
| [Y1](#Y1) | Hämtar eller anger Y1-koordinaten. |
| [Y2](#Y2) | Hämtar eller anger Y2-koordinaten. |
| [Y3](#Y3) | Hämtar eller anger Y3-koordinaten. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CurveTo](#CurveTo-double-double-double-double-double-double-) | Initierar kurvoperatorn. |
| [CurveTo](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [toCommand](#toCommand--) | Endast för internt bruk! |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### X1 {#X1}
```
public double X1
```

Hämtar eller anger X1-koordinaten.

### X2 {#X2}
```
public double X2
```

Hämtar eller anger X2-koordinaten.

### X3 {#X3}
```
public double X3
```

Hämtar eller anger X3-koordinaten.

### Y1 {#Y1}
```
public double Y1
```

Hämtar eller anger Y1-koordinaten.

### Y2 {#Y2}
```
public double Y2
```

Hämtar eller anger Y2-koordinaten.

### Y3 {#Y3}
```
public double Y3
```

Hämtar eller anger Y3-koordinaten.

### CurveTo {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```

Initierar kurvoperatorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 |  | Abskissa för första punkten. |
| y1 |  | Ordinat för första punkten. |
| x2 |  | Abskissa för andra punkten. |
| y2 |  | Ordinat för andra punkten. |
| x3 |  | Abskissa för tredje punkten. |
| y3 |  | Ordinat för tredje punkten. |

### CurveTo {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-}
Konstruktor för operator-klassen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Endast för internt bruk!

**Returns:**
ICommand värde ICommand objekt

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av operator.

---
title: "MoveTo"
linktitle: "MoveTo"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar {@code operators.m} (flytta till och börja ny delväg)."
type: docs
weight: 410
url: /sv/java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.MoveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.MoveTo

```
public class MoveTo extends Operator
```

Klass som representerar {@code operators.m} (flytta till och börja ny delväg).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MoveTo](#MoveTo-double-double-) | Initierar ny {@code Operator.m} (flytta till) operator. |
| [MoveTo](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getX](#getX--) | X-koordinat |
| [getY](#getY--) | Y-koordinat |
| [setX](#setX-double-) | X-koordinat |
| [setY](#setY-double-) | Y-koordinat |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### MoveTo {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```

Initierar ny {@code Operator.m} (flytta till) operator.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x |  | X-koordinaten. |
| y |  | Y-koordinaten. |

### MoveTo {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getX {#getX--}
```
public double getX()
```

X-koordinat

**Returns:**
double-värde

### getY {#getY--}
```
public double getY()
```

Y-koordinat

**Returns:**
double-värde

### setX {#setX-double-}
```
public void setX(double value)
```

X-koordinat

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setY {#setY-double-}
```
public void setY(double value)
```

Y-koordinat

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av operatorn.

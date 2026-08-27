---
title: "LineTo"
linktitle: "LineTo"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar l operator (lägg till linje till banan)."
type: docs
weight: 380
url: /sv/java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.LineTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.LineTo

```
public class LineTo extends Operator
```

Klass som representerar l operator (lägg till linje till banan).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [LineTo](#LineTo-double-double-) | Initierar linjeoperator. |
| [LineTo](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getX](#getX--) | X-koordinat för linjepunkt. |
| [getY](#getY--) | Y-koordinat för linjepunkt. |
| [setX](#setX-double-) | X-koordinat för linjepunkt. |
| [setY](#setY-double-) | Y-koordinat för linjepunkt. |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### LineTo {#LineTo-double-double-}
```
public LineTo(double x, double y)
```

Initierar linjeoperator.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x |  | X-koordinat. |
| y |  | Y-koordinat. |

### LineTo {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-}
Konstruktor för operator-klassen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getX {#getX--}
```
public double getX()
```

X-koordinat för linjepunkt.

**Returns:**
double-värde

### getY {#getY--}
```
public double getY()
```

Y-koordinat för linjepunkt.

**Returns:**
double-värde

### setX {#setX-double-}
```
public void setX(double value)
```

X-koordinat för linjepunkt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setY {#setY-double-}
```
public void setY(double value)
```

Y-koordinat för linjepunkt.

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

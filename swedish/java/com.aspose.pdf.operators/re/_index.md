---
title: "Re"
linktitle: "Re"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar re-operatorn (lägger till en rektangel till sökvägen)."
type: docs
weight: 460
url: /sv/java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Re, com.aspose.pdf.Operator, com.aspose.pdf.operators.Re

```
public class Re extends Operator
```

Klass som representerar re-operatorn (lägger till en rektangel till sökvägen).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Re](#Re--) | Konstruktor för att extrahera mål. |
| [Re](#Re-double-double-double-double-) | Konstruktor för skrivprogrammet. |
| [Re](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-) | Konstruktor för att extrahera mål. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getHeight](#getHeight--) | Höjd på rektangeln. |
| [getWidth](#getWidth--) | Hämtar bredden på rektangeln. |
| [getX](#getX--) | X-koordinat för den mest vänstra sidan av rektangeln. |
| [getY](#getY--) | Y-koordinat för den nedre sidan av rektangeln. |
| [setHeight](#setHeight-double-) | Höjd på rektangeln. |
| [setWidth](#setWidth-double-) | Ställer in bredden på rektangeln. |
| [setX](#setX-double-) | X-koordinat för den mest vänstra sidan av rektangeln. |
| [setY](#setY-double-) | Y-koordinat för den nedre sidan av rektangeln. |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### Re {#Re--}
```
public Re()
```

Konstruktor för att extrahera mål.

### Re {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```

Konstruktor för skrivprogrammet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x |  | X-koordinaten för det nedre vänstra hörnet av rektangeln. |
| y |  | Y-koordinaten för det nedre vänstra hörnet av rektangeln. |
| bredd |  | Rektangelns bredd. |
| höjd |  | Rektangelns höjd. |

### Re {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-}
Konstruktor för att extrahera mål.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getHeight {#getHeight--}
```
public double getHeight()
```

Höjd på rektangeln.

**Returns:**
Höjd på rektangeln.

### getWidth {#getWidth--}
```
public double getWidth()
```

Hämtar bredden på rektangeln.

**Returns:**
bredd på rektangeln.

### getX {#getX--}
```
public double getX()
```

X-koordinat för den mest vänstra sidan av rektangeln.

**Returns:**
double-värde

### getY {#getY--}
```
public double getY()
```

Y-koordinat för den nedre sidan av rektangeln.

**Returns:**
double-värde

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Höjd på rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Höjd på rektangeln. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Ställer in bredden på rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | bredd på rektangeln. |

### setX {#setX-double-}
```
public void setX(double value)
```

X-koordinat för den mest vänstra sidan av rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setY {#setY-double-}
```
public void setY(double value)
```

Y-koordinat för den nedre sidan av rektangeln.

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

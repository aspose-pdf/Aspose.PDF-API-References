---
title: "SetGray"
linktitle: "SetGray"
second_title: "Aspose.PDF för Java API-referens"
description: "Ställ in grånivå för icke‑strokande operationer."
type: docs
weight: 640
url: /sv/java/com.aspose.pdf.operators/setgray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGray

```
public class SetGray extends SetColorOperator
```

Ställ in grånivå för icke‑strokande operationer.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetGray](#SetGray-double-) | Konstruktor för skrivprogrammet. |
| [SetGray](#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getColor](#getColor--) | Returnerar färg som specificerats av operator. |
| [getGray](#getGray--) | Hämtar eller anger gråvärdesnivån. |
| [setGray](#setGray-double-) | Hämtar eller anger gråvärdesnivån. |
| [toString](#toString--) | Returnerar strängrepresentation av operatorn. |

### SetGray {#SetGray-double-}
```
public SetGray(double gray)
```

Konstruktor för skrivprogrammet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gray |  | Gråvärdesnivån. |

### SetGray {#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-}
Konstruktor för operator-klassen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getColor {#getColor--}
```
public Color getColor()
```

Returnerar färg som specificerats av operator.

**Returns:**
Färg som specificerats av operator.

### getGray {#getGray--}
```
public final double getGray()
```

Hämtar eller anger gråvärdesnivån.

**Returns:**
double-värde

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

Hämtar eller anger gråvärdesnivån.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### toString {#toString--}
```
public String toString()
```

Returnerar strängrepresentation av operatorn.

**Returns:**
Strängrepresentation av operatorn.

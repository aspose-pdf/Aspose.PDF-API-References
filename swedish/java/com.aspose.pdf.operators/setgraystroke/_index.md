---
title: "SetGrayStroke"
linktitle: "SetGrayStroke"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar grånivå för strokande operationer."
type: docs
weight: 650
url: /sv/java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGrayStroke

```
public class SetGrayStroke extends SetColorOperator
```

Klass som representerar grånivå för strokande operationer.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetGrayStroke](#SetGrayStroke-double-) | Initierar operator med den angivna färgen. |
| [SetGrayStroke](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getColor](#getColor--) | Returnerar färg som specificerats av operator. |
| [getGray](#getGray--) | Hämtar eller anger gråvärdesnivån. |
| [setGray](#setGray-double-) | Hämtar eller anger gråvärdesnivån. |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### SetGrayStroke {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```

Initierar operator med den angivna färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gray |  | Gråvärdesnivån. |

### SetGrayStroke {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-}
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

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av operator.

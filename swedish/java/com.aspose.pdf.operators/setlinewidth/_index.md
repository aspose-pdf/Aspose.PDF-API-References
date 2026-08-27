---
title: "SetLineWidth"
linktitle: "SetLineWidth"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar w-operatorn (ställer in linjebredd)."
type: docs
weight: 690
url: /sv/java/com.aspose.pdf.operators/setlinewidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetLineWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetLineWidth

```
public class SetLineWidth extends Operator
```

Klass som representerar w-operatorn (ställer in linjebredd).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetLineWidth](#SetLineWidth-double-) | Initierar operator med breddvärde. |
| [SetLineWidth](#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getWidth](#getWidth--) | Hämtar bredden på linjen. |
| [setWidth](#setWidth-double-) | Ställer in bredden på linjen. |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### SetLineWidth {#SetLineWidth-double-}
```
public SetLineWidth(double width)
```

Initierar operator med breddvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Värde för bredd. |

### SetLineWidth {#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-}
Konstruktor för operator-klassen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getWidth {#getWidth--}
```
public double getWidth()
```

Hämtar bredden på linjen.

**Returns:**
bredden på linjen.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Ställer in bredden på linjen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | bredden på linjen. |

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av operator.

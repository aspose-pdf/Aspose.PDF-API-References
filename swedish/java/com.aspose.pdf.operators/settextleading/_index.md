---
title: "SetTextLeading"
linktitle: "SetTextLeading"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar TL-operatorn (sätter radavstånd)."
type: docs
weight: 740
url: /sv/java/com.aspose.pdf.operators/settextleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetTextLeading

```
public class SetTextLeading extends TextStateOperator
```

Klass som representerar TL-operatorn (sätter radavstånd).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetTextLeading](#SetTextLeading-double-) | Konstruktor för textledningsoperator. |
| [SetTextLeading](#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getLeading](#getLeading--) | Hämtar textledning. |
| [setLeading](#setLeading-double-) | Ställer in textledning. |
| [toString](#toString--) | Producerar textkod för operatorn. |

### SetTextLeading {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```

Konstruktor för textledningsoperator.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| radavstånd |  | Textradavstånd. |

### SetTextLeading {#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getLeading {#getLeading--}
```
public double getLeading()
```

Hämtar textledning.

**Returns:**
double-värde

### setLeading {#setLeading-double-}
```
public void setLeading(double value)
```

Ställer in textledning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### toString {#toString--}
```
public String toString()
```

Producerar textkod för operatorn.

**Returns:**
Textrepresentation av operator.

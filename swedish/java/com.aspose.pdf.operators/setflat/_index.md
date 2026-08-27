---
title: "SetFlat"
linktitle: "SetFlat"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar i-operatorn (ställer in planhetstolerans)."
type: docs
weight: 620
url: /sv/java/com.aspose.pdf.operators/setflat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetFlat, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetFlat

```
public class SetFlat extends Operator
```

Klass som representerar i-operatorn (ställer in planhetstolerans).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetFlat](#SetFlat-double-) | Initierar operatorn. |
| [SetFlat](#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar ett besöksobjekt för att bearbeta operatorn. |
| [getFlatness](#getFlatness--) | Hämtar planheten. |
| [setFlatness](#setFlatness-double-) | Ställer in planheten. |
| [toCommand](#toCommand--) | Endast för internt bruk! |

### SetFlat {#SetFlat-double-}
```
public SetFlat(double flatness)
```

Initierar operatorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| planhet |  | Värdet för planhet. |

### SetFlat {#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-}
Konstruktor för operator-klassen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar ett besöksobjekt för att bearbeta operatorn.

### getFlatness {#getFlatness--}
```
public double getFlatness()
```

Hämtar planheten.

**Returns:**
double-värde

### setFlatness {#setFlatness-double-}
```
public void setFlatness(double value)
```

Ställer in planheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Endast för internt bruk!

**Returns:**
ICommand värde ICommand objekt

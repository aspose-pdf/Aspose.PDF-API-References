---
title: "SetDash"
linktitle: "SetDash"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar d-operatorn (ställer in linjestreckningsmönster)."
type: docs
weight: 610
url: /sv/java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetDash, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetDash

```
public class SetDash extends Operator
```

Klass som representerar d-operatorn (ställer in linjestreckningsmönster).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetDash](#SetDash-int:A-int-) | Skapar en operator för dash-mönster. |
| [SetDash](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getPattern](#getPattern--) | Dash-mönster. Arrayens element ska vara tal som specificerar längderna på alternerande streck och mellanrum. Vid en array med ett element är streck- och mellanrumslängderna lika. |
| [getPhase](#getPhase--) | Dash-fas. Innan en bana börjar kontureras ska dash-arrayen cyklas igenom, där längderna på streck och mellanrum summeras. När den ackumulerade längden motsvarar värdet som anges av dash-fasen ska konturering av banan påbörjas, och dash-arrayen ska användas cykliskt från den punkten. |
| [setPattern](#setPattern-int:A-) | Dash-mönster. Arrayens element ska vara tal som specificerar längderna på alternerande streck och mellanrum. Vid en array med ett element är streck- och mellanrumslängderna lika. |
| [setPhase](#setPhase-int-) | Dash-fas. Innan en bana börjar kontureras ska dash-arrayen cyklas igenom, där längderna på streck och mellanrum summeras. När den ackumulerade längden motsvarar värdet som anges av dash-fasen ska konturering av banan påbörjas, och dash-arrayen ska användas cykliskt från den punkten. |
| [toCommand](#toCommand--) | Endast för internt bruk! |
| [toString](#toString--) | Hämtar operatorns strängrepresentation. |

### SetDash {#SetDash-int:A-int-}
```
public SetDash(int[] pattern, int phase)
```

Skapar en operator för dash-mönster.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mönster |  | Array som definierar dash-mönster. |
| phase |  | Dash-fas. |

### SetDash {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-}
Konstruktor för operator-klassen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getPattern {#getPattern--}
```
public int[] getPattern()
```

Dash-mönster. Arrayens element ska vara tal som specificerar längderna på alternerande streck och mellanrum. Vid en array med ett element är streck- och mellanrumslängderna lika.

**Returns:**
int-array

### getPhase {#getPhase--}
```
public int getPhase()
```

Dash-fas. Innan en bana börjar kontureras ska dash-arrayen cyklas igenom, där längderna på streck och mellanrum summeras. När den ackumulerade längden motsvarar värdet som anges av dash-fasen ska konturering av banan påbörjas, och dash-arrayen ska användas cykliskt från den punkten.

**Returns:**
int‑värde

### setPattern {#setPattern-int:A-}
```
public void setPattern(int[] value)
```

Dash-mönster. Arrayens element ska vara tal som specificerar längderna på alternerande streck och mellanrum. Vid en array med ett element är streck- och mellanrumslängderna lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int-array |

### setPhase {#setPhase-int-}
```
public void setPhase(int value)
```

Dash-fas. Innan en bana börjar kontureras ska dash-arrayen cyklas igenom, där längderna på streck och mellanrum summeras. När den ackumulerade längden motsvarar värdet som anges av dash-fasen ska konturering av banan påbörjas, och dash-arrayen ska användas cykliskt från den punkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

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

Hämtar operatorns strängrepresentation.

**Returns:**
[x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.

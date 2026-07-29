---
title: "SetDash"
linktitle: "SetDash"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den d-Operator darstellt (Linien-Strichmuster festlegen)."
type: docs
weight: 610
url: /de/java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetDash, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetDash

```
public class SetDash extends Operator
```

Klasse, die den d-Operator darstellt (Linien-Strichmuster festlegen).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetDash](#SetDash-int:A-int-) | Erstellt den Set-Dash-Pattern-Operator. |
| [SetDash](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getPattern](#getPattern--) | Dash-Muster. Die Elemente des Arrays müssen Zahlen sein, die die Längen von abwechselnden Strichen und Lücken angeben. Im Falle eines Arrays mit einem Element sind die Strich- und Lückenlängen gleich. |
| [getPhase](#getPhase--) | Dash-Phase. Bevor ein Pfad konturiert wird, muss das Dash-Array durchlaufen werden, wobei die Längen von Strichen und Lücken addiert werden. Wenn die akkumulierte Länge dem durch die Dash-Phase angegebenen Wert entspricht, beginnt das Konturieren des Pfades, und das Dash-Array wird von diesem Punkt an zyklisch verwendet. |
| [setPattern](#setPattern-int:A-) | Dash-Muster. Die Elemente des Arrays müssen Zahlen sein, die die Längen von abwechselnden Strichen und Lücken angeben. Im Falle eines Arrays mit einem Element sind die Strich- und Lückenlängen gleich. |
| [setPhase](#setPhase-int-) | Dash-Phase. Bevor ein Pfad konturiert wird, muss das Dash-Array durchlaufen werden, wobei die Längen von Strichen und Lücken addiert werden. Wenn die akkumulierte Länge dem durch die Dash-Phase angegebenen Wert entspricht, beginnt das Konturieren des Pfades, und das Dash-Array wird von diesem Punkt an zyklisch verwendet. |
| [toCommand](#toCommand--) | Nur für den internen Gebrauch! |
| [toString](#toString--) | Liefert die String‑Darstellung des Operators. |

### SetDash {#SetDash-int:A-int-}
```
public SetDash(int[] pattern, int phase)
```

Erstellt den Set-Dash-Pattern-Operator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Muster |  | Array, das das Dash-Muster definiert. |
| Phase |  | Dash-Phase. |

### SetDash {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-}
Konstruktor für die Operator-Klasse.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getPattern {#getPattern--}
```
public int[] getPattern()
```

Dash-Muster. Die Elemente des Arrays müssen Zahlen sein, die die Längen von abwechselnden Strichen und Lücken angeben. Im Falle eines Arrays mit einem Element sind die Strich- und Lückenlängen gleich.

**Returns:**
int‑Array

### getPhase {#getPhase--}
```
public int getPhase()
```

Dash-Phase. Bevor ein Pfad konturiert wird, muss das Dash-Array durchlaufen werden, wobei die Längen von Strichen und Lücken addiert werden. Wenn die akkumulierte Länge dem durch die Dash-Phase angegebenen Wert entspricht, beginnt das Konturieren des Pfades, und das Dash-Array wird von diesem Punkt an zyklisch verwendet.

**Returns:**
int-Wert

### setPattern {#setPattern-int:A-}
```
public void setPattern(int[] value)
```

Dash-Muster. Die Elemente des Arrays müssen Zahlen sein, die die Längen von abwechselnden Strichen und Lücken angeben. Im Falle eines Arrays mit einem Element sind die Strich- und Lückenlängen gleich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int‑Array |

### setPhase {#setPhase-int-}
```
public void setPhase(int value)
```

Dash-Phase. Bevor ein Pfad konturiert wird, muss das Dash-Array durchlaufen werden, wobei die Längen von Strichen und Lücken addiert werden. Wenn die akkumulierte Länge dem durch die Dash-Phase angegebenen Wert entspricht, beginnt das Konturieren des Pfades, und das Dash-Array wird von diesem Punkt an zyklisch verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Nur für den internen Gebrauch!

**Returns:**
ICommand-Wert ICommand-Objekt

### toString {#toString--}
```
public String toString()
```

Liefert die String‑Darstellung des Operators.

**Returns:**
[x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.

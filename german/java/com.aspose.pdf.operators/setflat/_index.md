---
title: "SetFlat"
linktitle: "SetFlat"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den i-Operator darstellt (Flachheitstoleranz festlegen)."
type: docs
weight: 620
url: /de/java/com.aspose.pdf.operators/setflat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetFlat, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetFlat

```
public class SetFlat extends Operator
```

Klasse, die den i-Operator darstellt (Flachheitstoleranz festlegen).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetFlat](#SetFlat-double-) | Initialisiert den Operator. |
| [SetFlat](#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getFlatness](#getFlatness--) | Ruft die Flachheit ab. |
| [setFlatness](#setFlatness-double-) | Setzt die Flachheit. |
| [toCommand](#toCommand--) | Nur für den internen Gebrauch! |

### SetFlat {#SetFlat-double-}
```
public SetFlat(double flatness)
```

Initialisiert den Operator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Flachheit |  | Der Wert der Flachheit. |

### SetFlat {#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-}
Konstruktor für die Operator-Klasse.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getFlatness {#getFlatness--}
```
public double getFlatness()
```

Ruft die Flachheit ab.

**Returns:**
double-Wert

### setFlatness {#setFlatness-double-}
```
public void setFlatness(double value)
```

Setzt die Flachheit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Nur für den internen Gebrauch!

**Returns:**
ICommand-Wert ICommand-Objekt

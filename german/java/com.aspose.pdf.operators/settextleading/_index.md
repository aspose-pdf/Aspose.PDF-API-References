---
title: "SetTextLeading"
linktitle: "SetTextLeading"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den TL-Operator (setzt den Textabstand) darstellt."
type: docs
weight: 740
url: /de/java/com.aspose.pdf.operators/settextleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetTextLeading

```
public class SetTextLeading extends TextStateOperator
```

Klasse, die den TL-Operator (setzt den Textabstand) darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetTextLeading](#SetTextLeading-double-) | Konstruktor für den Text‑Führungsoperator. |
| [SetTextLeading](#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getLeading](#getLeading--) | Liest die Textführung. |
| [setLeading](#setLeading-double-) | Setzt die Textführung. |
| [toString](#toString--) | Erzeugt den Textcode des Operators. |

### SetTextLeading {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```

Konstruktor für den Text‑Führungsoperator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Führung |  | Textführung. |

### SetTextLeading {#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getLeading {#getLeading--}
```
public double getLeading()
```

Liest die Textführung.

**Returns:**
double-Wert

### setLeading {#setLeading-double-}
```
public void setLeading(double value)
```

Setzt die Textführung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### toString {#toString--}
```
public String toString()
```

Erzeugt den Textcode des Operators.

**Returns:**
Textdarstellung des Operators.

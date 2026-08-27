---
title: "SelectFont"
linktitle: "SelectFont"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den Tf-Operator darstellt (Textschriftart und -größe festlegen)."
type: docs
weight: 470
url: /de/java/com.aspose.pdf.operators/selectfont/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SelectFont

```
public class SelectFont extends TextStateOperator
```

Klasse, die den Tf-Operator darstellt (Textschriftart und -größe festlegen).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SelectFont](#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-) | Konstruktor für die Operator-Klasse. |
| [SelectFont](#SelectFont-java.lang.String-double-) | Konstruktor für das Schreibprogramm. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getName](#getName--) | Liest den Namen der Schriftart. |
| [getSize](#getSize--) | Liest die Größe des Textes. |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### SelectFont {#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-}
Konstruktor für die Operator-Klasse.

### SelectFont {#SelectFont-java.lang.String-double-}
Konstruktor für das Schreibprogramm.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getName {#getName--}
```
public String getName()
```

Liest den Namen der Schriftart.

**Returns:**
String Wert

### getSize {#getSize--}
```
public double getSize()
```

Liest die Größe des Textes.

**Returns:**
double-Wert

### toString {#toString--}
```
public String toString()
```

Gibt die Textdarstellung des Operators zurück.

**Returns:**
Textdarstellung des Operators.

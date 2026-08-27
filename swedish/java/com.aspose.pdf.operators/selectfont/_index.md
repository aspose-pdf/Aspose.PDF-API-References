---
title: "SelectFont"
linktitle: "SelectFont"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar Tf-operatorn (ställer in textens teckensnitt och storlek)."
type: docs
weight: 470
url: /sv/java/com.aspose.pdf.operators/selectfont/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SelectFont

```
public class SelectFont extends TextStateOperator
```

Klass som representerar Tf-operatorn (ställer in textens teckensnitt och storlek).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SelectFont](#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-) | Konstruktor för operator-klassen. |
| [SelectFont](#SelectFont-java.lang.String-double-) | Konstruktor för skrivprogram. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getName](#getName--) | Hämtar namn på teckensnitt. |
| [getSize](#getSize--) | Hämtar storlek på text. |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### SelectFont {#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-}
Konstruktor för operator-klassen.

### SelectFont {#SelectFont-java.lang.String-double-}
Konstruktor för skrivprogram.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getName {#getName--}
```
public String getName()
```

Hämtar namn på teckensnitt.

**Returns:**
String värde

### getSize {#getSize--}
```
public double getSize()
```

Hämtar storlek på text.

**Returns:**
double-värde

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av operator.

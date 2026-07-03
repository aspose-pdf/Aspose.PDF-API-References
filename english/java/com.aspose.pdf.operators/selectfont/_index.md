---
title: SelectFont
second_title: Aspose.PDF for Java API Reference
description: Class representing Tf operator (set text font and size).
type: docs
weight: 470
url: /java/com.aspose.pdf.operators/selectfont/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SelectFont, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SelectFont

```
public class SelectFont extends TextStateOperator
```

Class representing Tf operator (set text font and size).

## Constructors

| Constructor | Description |
| --- | --- |
| [SelectFont](#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-) | Constructor for operator class. |
| [SelectFont](#SelectFont-java.lang.String-double-) | Constructor for writin program. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getName](#getName--) | Gets name of font. |
| [getSize](#getSize--) | Gets size of text. |
| [toString](#toString--) | Returns text representation of operator. |

### SelectFont {#SelectFont-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextFont-}
Constructor for operator class.

### SelectFont {#SelectFont-java.lang.String-double-}
Constructor for writin program.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getName {#getName--}
```
public String getName()
```

Gets name of font.

**Returns:**
String value

### getSize {#getSize--}
```
public double getSize()
```

Gets size of text.

**Returns:**
double value

### toString {#toString--}
```
public String toString()
```

Returns text representation of operator.

**Returns:**
Text representation of operator.

---
title: SelectFont
second_title: Aspose.PDF for Java API Reference
description: Class representing Tf operator set text font and size.
type: docs
weight: 53
url: /java/com.aspose.pdf.operators/selectfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextStateOperator](../../com.aspose.pdf.operators/textstateoperator)
```
public class SelectFont extends TextStateOperator
```

Class representing Tf operator (set text font and size).
## Constructors

| Constructor | Description |
| --- | --- |
| [SelectFont(String resName, double size)](#SelectFont-java.lang.String-double-) | Constructor for writin program. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets name of font. |
| [getSize()](#getSize--) | Gets size of text. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
### SelectFont(String resName, double size) {#SelectFont-java.lang.String-double-}
```
public SelectFont(String resName, double size)
```


Constructor for writin program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resName | java.lang.String | The name of font resource, e.g. F1, F2 etc. |
| size | double | Size of the font. |

### getName() {#getName--}
```
public String getName()
```


Gets name of font.

**Returns:**
java.lang.String - String value
### getSize() {#getSize--}
```
public double getSize()
```


Gets size of text.

**Returns:**
double - double value
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

### toString() {#toString--}
```
public String toString()
```


Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of operator.

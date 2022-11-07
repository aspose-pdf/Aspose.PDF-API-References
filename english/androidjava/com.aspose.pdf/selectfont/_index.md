---
title: Operator.SelectFont
second_title: Aspose.PDF for Java API Reference
description: Class representing Tf operator set text font and size.
type: docs
weight: 50
url: /java/com.aspose.pdf/operator.selectfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.TextOperator](../../com.aspose.pdf/textoperator), [com.aspose.pdf.Operator.TextStateOperator](../../com.aspose.pdf/textstateoperator)
```
public static class Operator.SelectFont extends Operator.TextStateOperator
```

Class representing Tf operator (set text font and size).
## Constructors

| Constructor | Description |
| --- | --- |
| [SelectFont(String resName, double size)](#SelectFont-java.lang.String-double-) | Constructor for writin program. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Name of font. |
| [getSize()](#getSize--) | Size of text. |
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


Name of font.

**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public double getSize()
```


Size of text.

**Returns:**
double
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

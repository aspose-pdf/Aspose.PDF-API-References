---
title: Operator.SetTextLeading
second_title: Aspose.PDF for Java API Reference
description: Class represenging TL operator set text leading.
type: docs
weight: 77
url: /java/com.aspose.pdf/operator.settextleading/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.TextOperator](../../com.aspose.pdf/textoperator), [com.aspose.pdf.Operator.TextStateOperator](../../com.aspose.pdf/textstateoperator)
```
public static class Operator.SetTextLeading extends Operator.TextStateOperator
```

Class represenging TL operator (set text leading).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetTextLeading(double leading)](#SetTextLeading-double-) | Constructor for text leadign operator. |
## Methods

| Method | Description |
| --- | --- |
| [getLeading()](#getLeading--) | Gets the text leading. |
| [setLeading(double value)](#setLeading-double-) | Sets the text leading. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Produces text code of operator. |
### SetTextLeading(double leading) {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```


Constructor for text leadign operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leading | double | Text leading. |

### getLeading() {#getLeading--}
```
public double getLeading()
```


Gets the text leading.

**Returns:**
double
### setLeading(double value) {#setLeading-double-}
```
public void setLeading(double value)
```


Sets the text leading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

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


Produces text code of operator.

**Returns:**
java.lang.String - Text representation of operator.

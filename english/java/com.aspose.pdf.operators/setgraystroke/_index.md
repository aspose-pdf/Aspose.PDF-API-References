---
title: SetGrayStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing gray level for stroking operations.
type: docs
weight: 71
url: /java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator)
```
public class SetGrayStroke extends SetColorOperator
```

Class representing gray level for stroking operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [SetGrayStroke(double gray)](#SetGrayStroke-double-) | Initializes operator with the specified color. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color specified by operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
### SetGrayStroke(double gray) {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```


Initializes operator with the specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gray | double | The level of gray value. |

### getColor() {#getColor--}
```
public Color getColor()
```


Returns color specified by operator.

**Returns:**
[Color](../../java.awt/color) - Color specified by operator.
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

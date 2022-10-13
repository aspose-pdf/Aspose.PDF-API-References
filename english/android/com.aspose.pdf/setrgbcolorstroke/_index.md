---
title: Operator.SetRGBColorStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing RG operator set RGB color for stroking operators.
type: docs
weight: 75
url: /java/com.aspose.pdf/operator.setrgbcolorstroke/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.SetColorOperator](../../com.aspose.pdf/setcoloroperator)
```
public static class Operator.SetRGBColorStroke extends Operator.SetColorOperator
```

Class representing RG operator (set RGB color for stroking operators).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetRGBColorStroke(double r, double g, double b)](#SetRGBColorStroke-double-double-double-) | Constructor for writing program. |
| [SetRGBColorStroke(Color color)](#SetRGBColorStroke-com.aspose.pdf.java.awt.Color-) | Initializes operator with color. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color specified by operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
### SetRGBColorStroke(double r, double g, double b) {#SetRGBColorStroke-double-double-double-}
```
public SetRGBColorStroke(double r, double g, double b)
```


Constructor for writing program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r | double |  |
| g | double |  |
| b | double |  |

### SetRGBColorStroke(Color color) {#SetRGBColorStroke-com.aspose.pdf.java.awt.Color-}
```
public SetRGBColorStroke(Color color)
```


Initializes operator with color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.pdf.java.awt/color) | Operator color. |

### getColor() {#getColor--}
```
public Color getColor()
```


Returns color specified by operator.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color) - Operator color.
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

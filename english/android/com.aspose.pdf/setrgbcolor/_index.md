---
title: Operator.SetRGBColor
second_title: Aspose.PDF for Java API Reference
description: Class representing rg operator set RGB color for non-stroknig operators.
type: docs
weight: 74
url: /java/com.aspose.pdf/operator.setrgbcolor/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.SetColorOperator](../../com.aspose.pdf/setcoloroperator)
```
public static class Operator.SetRGBColor extends Operator.SetColorOperator
```

Class representing rg operator (set RGB color for non-stroknig operators).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetRGBColor(double r, double g, double b)](#SetRGBColor-double-double-double-) | Constructor for writing program. |
| [SetRGBColor(Color color)](#SetRGBColor-com.aspose.pdf.java.awt.Color-) | Initializes operator with color. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color specified by operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of the operator. |
### SetRGBColor(double r, double g, double b) {#SetRGBColor-double-double-double-}
```
public SetRGBColor(double r, double g, double b)
```


Constructor for writing program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r | double |  |
| g | double |  |
| b | double |  |

### SetRGBColor(Color color) {#SetRGBColor-com.aspose.pdf.java.awt.Color-}
```
public SetRGBColor(Color color)
```


Initializes operator with color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.pdf.java.awt/color) | Specfied color. |

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


Returns text representation of the operator.

**Returns:**
java.lang.String - 

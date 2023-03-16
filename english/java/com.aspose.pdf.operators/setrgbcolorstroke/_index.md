---
title: SetRGBColorStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing RG operator set RGB color for stroking operators.
type: docs
weight: 78
url: /java/com.aspose.pdf.operators/setrgbcolorstroke/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator)
```
public class SetRGBColorStroke extends SetColorOperator
```

Class representing RG operator (set RGB color for stroking operators).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetRGBColorStroke(double r, double g, double b)](#SetRGBColorStroke-double-double-double-) | Constructor for writing program. |
| [SetRGBColorStroke(Color color)](#SetRGBColorStroke-java.awt.Color-) | Initializes operator with color. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color specified by operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
| [getCMYKColor(double[] rgb, double[] cmykOut)](#getCMYKColor-double---double---) |  |
### SetRGBColorStroke(double r, double g, double b) {#SetRGBColorStroke-double-double-double-}
```
public SetRGBColorStroke(double r, double g, double b)
```


Constructor for writing program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r | double | The level of red from 0.0 to 1.0 |
| g | double | The level of green from 0.0 to 1.0 |
| b | double | The level of blue from 0.0 to 1.0 |

### SetRGBColorStroke(Color color) {#SetRGBColorStroke-java.awt.Color-}
```
public SetRGBColorStroke(Color color)
```


Initializes operator with color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | java.awt.Color | java.awt.Color object |

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
### getCMYKColor(double[] rgb, double[] cmykOut) {#getCMYKColor-double---double---}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rgb | double[] |  |
| cmykOut | double[] |  |


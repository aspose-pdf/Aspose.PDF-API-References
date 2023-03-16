---
title: SetCMYKColor
second_title: Aspose.PDF for Java API Reference
description: Class representing k operator set CMYK color for non-stroking operations.
type: docs
weight: 56
url: /java/com.aspose.pdf.operators/setcmykcolor/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator)
```
public class SetCMYKColor extends SetColorOperator
```

Class representing k operator (set CMYK color for non-stroking operations).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetCMYKColor(double c, double m, double y, double k)](#SetCMYKColor-double-double-double-double-) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getRGBColor(double[] cmyk, double[] rgbOut)](#getRGBColor-double---double---) |  |
### SetCMYKColor(double c, double m, double y, double k) {#SetCMYKColor-double-double-double-double-}
```
public SetCMYKColor(double c, double m, double y, double k)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | double | The level of cyan from 0.0 to 1.0 |
| m | double | The level of magenta from 0.0 to 1.0 |
| y | double | The level of yellow from 0.0 to 1.0 |
| k | double | The level of black from 0.0 to 1.0 |

### getColor() {#getColor--}
```
public Color getColor()
```


Returns color.

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

### getRGBColor(double[] cmyk, double[] rgbOut) {#getRGBColor-double---double---}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmyk | double[] |  |
| rgbOut | double[] |  |


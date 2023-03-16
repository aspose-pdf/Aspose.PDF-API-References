---
title: SetColor
second_title: Aspose.PDF for Java API Reference
description: Represents class for sc operator set color for non-stroking operations.
type: docs
weight: 61
url: /java/com.aspose.pdf.operators/setcolor/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator), [com.aspose.pdf.operators.BasicSetColorOperator](../../com.aspose.pdf.operators/basicsetcoloroperator)
```
public class SetColor extends BasicSetColorOperator
```

Represents class for sc operator (set color for non-stroking operations).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetColor()](#SetColor--) | Initializes operator. |
| [SetColor(double g)](#SetColor-double-) | Set color for stroking operators for DeviceGrey, CalGrey and Indexed color spaces. |
| [SetColor(double r, double g, double b)](#SetColor-double-double-double-) | Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces |
| [SetColor(double c, double m, double y, double k)](#SetColor-double-double-double-double-) | Set color for non-stroking operator for CMYK color space |
| [SetColor(double[] color)](#SetColor-double---) | Constructor which allows to specify color components. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Not supported yet. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns string representation of color. |
### SetColor() {#SetColor--}
```
public SetColor()
```


Initializes operator.

### SetColor(double g) {#SetColor-double-}
```
public SetColor(double g)
```


Set color for stroking operators for DeviceGrey, CalGrey and Indexed color spaces.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | double | Color value. |

### SetColor(double r, double g, double b) {#SetColor-double-double-double-}
```
public SetColor(double r, double g, double b)
```


Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r | double | Red component. |
| g | double | Green component. |
| b | double | Blue component. |

### SetColor(double c, double m, double y, double k) {#SetColor-double-double-double-double-}
```
public SetColor(double c, double m, double y, double k)
```


Set color for non-stroking operator for CMYK color space

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | double | Cyan component. |
| m | double | Magenta component. |
| y | double | Yellow component. |
| k | double | Black component. |

### SetColor(double[] color) {#SetColor-double---}
```
public SetColor(double[] color)
```


Constructor which allows to specify color components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | double[] | Array of color components. |

### getColor() {#getColor--}
```
public Color getColor()
```


Not supported yet.

Returns color specified by the operator.

**Returns:**
[Color](../../java.awt/color) - Operator color.
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


Returns string representation of color.

**Returns:**
java.lang.String - String representation of color.

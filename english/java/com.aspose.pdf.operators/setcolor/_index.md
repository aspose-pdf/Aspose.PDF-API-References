---
title: SetColor
second_title: Aspose.PDF for Java API Reference
description: Represents class for sc operator set color for non-stroking operations.
type: docs
weight: 63
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
| [SetColor(int index, ICommand command)](#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetColor(double g)](#SetColor-double-) | Set color for stroking operators for DeviceGray, CalGray and Indexed color spaces. |
| [SetColor(double r, double g, double b)](#SetColor-double-double-double-) | Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces |
| [SetColor(double c, double m, double y, double k)](#SetColor-double-double-double-double-) | Set color for non-stroking operator for CMYK color space |
| [SetColor(double[] color)](#SetColor-double---) | Constructor which allows to specify color components. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Not supported yet. |
| [getC()](#getC--) | Gets or sets the cyan component. |
| [setC(double value)](#setC-double-) | Gets or sets the cyan component. |
| [getM()](#getM--) | Gets or sets the magenta component. |
| [setM(double value)](#setM-double-) | Gets or sets the magenta component. |
| [getY()](#getY--) | Gets or sets the yellow component. |
| [setY(double value)](#setY-double-) | Gets or sets the yellow component. |
| [getK()](#getK--) | Gets or sets the black component. |
| [setK(double value)](#setK-double-) | Gets or sets the black component. |
| [getR()](#getR--) | Gets or sets the red component. |
| [setR(double value)](#setR-double-) | Gets or sets the red component. |
| [getG()](#getG--) | Gets or sets the green component. |
| [setG(double value)](#setG-double-) | Gets or sets the green component. |
| [getB()](#getB--) | Gets or sets the blue component. |
| [setB(double value)](#setB-double-) | Gets or sets the blue component. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns string representation of color. |
### SetColor() {#SetColor--}
```
public SetColor()
```


Initializes operator.

### SetColor(int index, ICommand command) {#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetColor(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetColor(double g) {#SetColor-double-}
```
public SetColor(double g)
```


Set color for stroking operators for DeviceGray, CalGray and Indexed color spaces.

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
### getC() {#getC--}
```
public final double getC()
```


Gets or sets the cyan component.

**Returns:**
double - doable value
### setC(double value) {#setC-double-}
```
public final void setC(double value)
```


Gets or sets the cyan component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | doable value |

### getM() {#getM--}
```
public final double getM()
```


Gets or sets the magenta component.

**Returns:**
double - doable value
### setM(double value) {#setM-double-}
```
public final void setM(double value)
```


Gets or sets the magenta component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | doable value |

### getY() {#getY--}
```
public final double getY()
```


Gets or sets the yellow component.

**Returns:**
double - doable value
### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Gets or sets the yellow component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | doable value |

### getK() {#getK--}
```
public final double getK()
```


Gets or sets the black component.

**Returns:**
double - doable value
### setK(double value) {#setK-double-}
```
public final void setK(double value)
```


Gets or sets the black component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | doable value |

### getR() {#getR--}
```
public final double getR()
```


Gets or sets the red component.

Value: The level of red from 0.0 to 1.0

**Returns:**
double - doable value
### setR(double value) {#setR-double-}
```
public final void setR(double value)
```


Gets or sets the red component.

Value: The level of red from 0.0 to 1.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | doable value |

### getG() {#getG--}
```
public final double getG()
```


Gets or sets the green component.

Value: The level of green from 0.0 to 1.0

**Returns:**
double - doable value
### setG(double value) {#setG-double-}
```
public final void setG(double value)
```


Gets or sets the green component.

Value: The level of green from 0.0 to 1.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | doable value |

### getB() {#getB--}
```
public final double getB()
```


Gets or sets the blue component.

Value: The level of blue from 0.0 to 1.0

**Returns:**
double - doable value
### setB(double value) {#setB-double-}
```
public final void setB(double value)
```


Gets or sets the blue component.

Value: The level of blue from 0.0 to 1.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | doable value |

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

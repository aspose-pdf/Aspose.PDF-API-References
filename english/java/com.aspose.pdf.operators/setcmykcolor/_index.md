---
title: SetCMYKColor
second_title: Aspose.PDF for Java API Reference
description: Class representing k operator set CMYK color for non-stroking operations.
type: docs
weight: 58
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
| [SetCMYKColor(int index, ICommand command)](#SetCMYKColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color. |
| [getC()](#getC--) | Gets or sets the cyan component. |
| [setC(double value)](#setC-double-) | Gets or sets the cyan component. |
| [getM()](#getM--) | Gets or sets the magenta component. |
| [setM(double value)](#setM-double-) | Gets or sets the magenta component. |
| [getY()](#getY--) | Gets or sets the yellow component. |
| [setY(double value)](#setY-double-) | Gets or sets the yellow component. |
| [getK()](#getK--) | Gets or sets the black component. |
| [setK(double value)](#setK-double-) | Gets or sets the black component. |
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

### SetCMYKColor(int index, ICommand command) {#SetCMYKColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetCMYKColor(int index, ICommand command)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

### getColor() {#getColor--}
```
public Color getColor()
```


Returns color.

**Returns:**
[Color](../../java.awt/color) - Color specified by operator.
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


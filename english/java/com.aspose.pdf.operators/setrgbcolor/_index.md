---
title: SetRGBColor
second_title: Aspose.PDF for Java API Reference
description: Class representing rg operator set RGB color for non-stroking operators.
type: docs
weight: 77
url: /java/com.aspose.pdf.operators/setrgbcolor/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator)
```
public class SetRGBColor extends SetColorOperator
```

Class representing rg operator (set RGB color for non-stroking operators).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetRGBColor(int index, ICommand command)](#SetRGBColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetRGBColor(double r, double g, double b)](#SetRGBColor-double-double-double-) | Constructor for writing program. |
| [SetRGBColor(Color color)](#SetRGBColor-java.awt.Color-) | Initializes operator with color. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color specified by operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of the operator. |
| [getCMYKColor(double[] rgb, double[] cmykOut)](#getCMYKColor-double---double---) |  |
### SetRGBColor(int index, ICommand command) {#SetRGBColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetRGBColor(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetRGBColor(double r, double g, double b) {#SetRGBColor-double-double-double-}
```
public SetRGBColor(double r, double g, double b)
```


Constructor for writing program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r | double | The level of red from 0.0 to 1.0 |
| g | double | The level of green from 0.0 to 1.0 |
| b | double | The level of blue from 0.0 to 1.0 |

### SetRGBColor(Color color) {#SetRGBColor-java.awt.Color-}
```
public SetRGBColor(Color color)
```


Initializes operator with color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | java.awt.Color | Specified color. |

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


Returns text representation of the operator.

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


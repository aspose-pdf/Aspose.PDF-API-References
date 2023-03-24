---
title: SetColorStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing SC operator set color for stroking color operators.
type: docs
weight: 66
url: /java/com.aspose.pdf.operators/setcolorstroke/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator), [com.aspose.pdf.operators.BasicSetColorOperator](../../com.aspose.pdf.operators/basicsetcoloroperator)
```
public class SetColorStroke extends BasicSetColorOperator
```

Class representing SC operator set color for stroking color operators.
## Constructors

| Constructor | Description |
| --- | --- |
| [SetColorStroke()](#SetColorStroke--) | Initializes operator. |
| [SetColorStroke(int index, ICommand command)](#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetColorStroke(double g)](#SetColorStroke-double-) | Set color for stroking operators for DeviceGrey, CalGrey and Indexed color spaces. |
| [SetColorStroke(double r, double g, double b)](#SetColorStroke-double-double-double-) | Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces |
| [SetColorStroke(double[] color)](#SetColorStroke-double---) | Constructor which allows to set color components. |
| [SetColorStroke(double c, double m, double y, double k)](#SetColorStroke-double-double-double-double-) | Set color for stroking operator for CMYK color space |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color specified by operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetColorStroke() {#SetColorStroke--}
```
public SetColorStroke()
```


Initializes operator.

### SetColorStroke(int index, ICommand command) {#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetColorStroke(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetColorStroke(double g) {#SetColorStroke-double-}
```
public SetColorStroke(double g)
```


Set color for stroking operators for DeviceGrey, CalGrey and Indexed color spaces.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | double | Color value. |

### SetColorStroke(double r, double g, double b) {#SetColorStroke-double-double-double-}
```
public SetColorStroke(double r, double g, double b)
```


Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r | double | Red component. |
| g | double | Green component. |
| b | double | Blue component. |

### SetColorStroke(double[] color) {#SetColorStroke-double---}
```
public SetColorStroke(double[] color)
```


Constructor which allows to set color components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | double[] | Array of color components. |

### SetColorStroke(double c, double m, double y, double k) {#SetColorStroke-double-double-double-double-}
```
public SetColorStroke(double c, double m, double y, double k)
```


Set color for stroking operator for CMYK color space

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | double | cyan component. |
| m | double | Magenta component. |
| y | double | Yellow component. |
| k | double | Black component. |

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


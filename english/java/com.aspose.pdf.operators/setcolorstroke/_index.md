---
title: SetColorStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing SC operator set color for stroking color operators.
type: docs
weight: 600
url: /java/com.aspose.pdf.operators/setcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColorStroke

```
public class SetColorStroke extends BasicSetColorOperator
```

Class representing SC operator set color for stroking color operators.

## Constructors

| Constructor | Description |
| --- | --- |
| [SetColorStroke](#SetColorStroke--) | Initializes operator. |
| [SetColorStroke](#SetColorStroke-double-) | Set color for stroking operators for DeviceGray, CalGray and Indexed color spaces. |
| [SetColorStroke](#SetColorStroke-double:A-) | Constructor which allows to set color components. |
| [SetColorStroke](#SetColorStroke-double-double-double-) | Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces |
| [SetColorStroke](#SetColorStroke-double-double-double-double-) | Set color for stroking operator for CMYK color space |
| [SetColorStroke](#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-) | Initializes operator. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getB](#getB--) | Gets or sets the blue component. Value: The level of blue from 0.0 to 1.0 |
| [getC](#getC--) | Gets or sets the cyan component. |
| [getColor](#getColor--) | Returns color specified by operator. |
| [getG](#getG--) | Gets or sets the green component. Value: The level of green from 0.0 to 1.0 |
| [getK](#getK--) | Gets or sets the black component. |
| [getM](#getM--) | Gets or sets the magenta component. |
| [getR](#getR--) | Gets or sets the red component. Value: The level of red from 0.0 to 1.0 |
| [getY](#getY--) | Gets or sets the yellow component. |
| [setB](#setB-double-) | Gets or sets the blue component. Value: The level of blue from 0.0 to 1.0 |
| [setC](#setC-double-) | Gets or sets the cyan component. |
| [setG](#setG-double-) | Gets or sets the green component. Value: The level of green from 0.0 to 1.0 |
| [setK](#setK-double-) | Gets or sets the black component. |
| [setM](#setM-double-) | Gets or sets the magenta component. |
| [setR](#setR-double-) | Gets or sets the red component. Value: The level of red from 0.0 to 1.0 |
| [setY](#setY-double-) | Gets or sets the yellow component. |

### SetColorStroke {#SetColorStroke--}
```
public SetColorStroke()
```

Initializes operator.

### SetColorStroke {#SetColorStroke-double-}
```
public SetColorStroke(double g)
```

Set color for stroking operators for DeviceGray, CalGray and Indexed color spaces.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g |  | Color value. |

### SetColorStroke {#SetColorStroke-double:A-}
```
public SetColorStroke(double[] color)
```

Constructor which allows to set color components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color |  | Array of color components. |

### SetColorStroke {#SetColorStroke-double-double-double-}
```
public SetColorStroke(double r, double g, double b)
```

Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r |  | Red component. |
| g |  | Green component. |
| b |  | Blue component. |

### SetColorStroke {#SetColorStroke-double-double-double-double-}
```
public SetColorStroke(double c, double m, double y, double k)
```

Set color for stroking operator for CMYK color space

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c |  | Cyan component. |
| m |  | Magenta component. |
| y |  | Yellow component. |
| k |  | Black component. |

### SetColorStroke {#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-}
Initializes operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getB {#getB--}
```
public final double getB()
```

Gets or sets the blue component. Value: The level of blue from 0.0 to 1.0

**Returns:**
doable value

### getC {#getC--}
```
public final double getC()
```

Gets or sets the cyan component.

**Returns:**
doable value

### getColor {#getColor--}
```
public Color getColor()
```

Returns color specified by operator.

**Returns:**
Color specified by operator.

### getG {#getG--}
```
public final double getG()
```

Gets or sets the green component. Value: The level of green from 0.0 to 1.0

**Returns:**
doable value

### getK {#getK--}
```
public final double getK()
```

Gets or sets the black component.

**Returns:**
doable value

### getM {#getM--}
```
public final double getM()
```

Gets or sets the magenta component.

**Returns:**
doable value

### getR {#getR--}
```
public final double getR()
```

Gets or sets the red component. Value: The level of red from 0.0 to 1.0

**Returns:**
doable value

### getY {#getY--}
```
public final double getY()
```

Gets or sets the yellow component.

**Returns:**
doable value

### setB {#setB-double-}
```
public final void setB(double value)
```

Gets or sets the blue component. Value: The level of blue from 0.0 to 1.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | doable value |

### setC {#setC-double-}
```
public final void setC(double value)
```

Gets or sets the cyan component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | doable value |

### setG {#setG-double-}
```
public final void setG(double value)
```

Gets or sets the green component. Value: The level of green from 0.0 to 1.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setK {#setK-double-}
```
public final void setK(double value)
```

Gets or sets the black component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | doable value |

### setM {#setM-double-}
```
public final void setM(double value)
```

Gets or sets the magenta component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | doable value |

### setR {#setR-double-}
```
public final void setR(double value)
```

Gets or sets the red component. Value: The level of red from 0.0 to 1.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | doable value |

### setY {#setY-double-}
```
public final void setY(double value)
```

Gets or sets the yellow component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | doable value |

---
title: SetRGBColor
linktitle: SetRGBColor
second_title: Aspose.PDF for Java API Reference
description: Class representing rg operator (set RGB color for non-stroking operators).
type: docs
weight: 710
url: /java/com.aspose.pdf.operators/setrgbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColor

```
public class SetRGBColor extends SetColorOperator
```

Class representing rg operator (set RGB color for non-stroking operators).

## Constructors

| Constructor | Description |
| --- | --- |
| [SetRGBColor](#SetRGBColor-java.awt.Color-) | Initializes operator with color. |
| [SetRGBColor](#SetRGBColor-double-double-double-) | Constructor for writing program. |
| [SetRGBColor](#SetRGBColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBNonstrokingColor-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getB](#getB--) | Gets or sets the blue component. Value: The level of blue from 0.0 to 1.0 |
| [getCMYKColor](#getCMYKColor-double:A-double:A-) |  |
| [getColor](#getColor--) | Returns color specified by operator. |
| [getG](#getG--) | Gets or sets the green component. Value: The level of green from 0.0 to 1.0 |
| [getR](#getR--) | Gets or sets the red component. Value: The level of red from 0.0 to 1.0 |
| [setB](#setB-double-) | Gets or sets the blue component. Value: The level of blue from 0.0 to 1.0 |
| [setG](#setG-double-) | Gets or sets the green component. Value: The level of green from 0.0 to 1.0 |
| [setR](#setR-double-) | Gets or sets the red component. Value: The level of red from 0.0 to 1.0 |
| [toString](#toString--) | Returns text representation of the operator. |

### SetRGBColor {#SetRGBColor-java.awt.Color-}
Initializes operator with color.

### SetRGBColor {#SetRGBColor-double-double-double-}
```
public SetRGBColor(double r, double g, double b)
```

Constructor for writing program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r |  | The level of red from 0.0 to 1.0 |
| g |  | The level of green from 0.0 to 1.0 |
| b |  | The level of blue from 0.0 to 1.0 |

### SetRGBColor {#SetRGBColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBNonstrokingColor-}
Constructor for operator class.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getB {#getB--}
```
public final double getB()
```

Gets or sets the blue component. Value: The level of blue from 0.0 to 1.0

**Returns:**
doable value

### getCMYKColor {#getCMYKColor-double:A-double:A-}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rgb |  |  |
| cmykOut |  |  |

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

### getR {#getR--}
```
public final double getR()
```

Gets or sets the red component. Value: The level of red from 0.0 to 1.0

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

### setG {#setG-double-}
```
public final void setG(double value)
```

Gets or sets the green component. Value: The level of green from 0.0 to 1.0

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

### toString {#toString--}
```
public String toString()
```

Returns text representation of the operator.

**Returns:**
Text representation of operator.

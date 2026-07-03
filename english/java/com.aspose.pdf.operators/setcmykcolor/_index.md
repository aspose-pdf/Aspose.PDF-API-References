---
title: SetCMYKColor
second_title: Aspose.PDF for Java API Reference
description: Class representing k operator (set CMYK color for non-stroking operations).
type: docs
weight: 530
url: /java/com.aspose.pdf.operators/setcmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColor

```
public class SetCMYKColor extends SetColorOperator
```

Class representing k operator (set CMYK color for non-stroking operations).

## Constructors

| Constructor | Description |
| --- | --- |
| [SetCMYKColor](#SetCMYKColor-double-double-double-double-) | Initializes operator. |
| [SetCMYKColor](#SetCMYKColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKNonstrokingColor-) |  |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getC](#getC--) | Gets or sets the cyan component. |
| [getColor](#getColor--) | Returns color. |
| [getK](#getK--) | Gets or sets the black component. |
| [getM](#getM--) | Gets or sets the magenta component. |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | Gets or sets the yellow component. |
| [setC](#setC-double-) | Gets or sets the cyan component. |
| [setK](#setK-double-) | Gets or sets the black component. |
| [setM](#setM-double-) | Gets or sets the magenta component. |
| [setY](#setY-double-) | Gets or sets the yellow component. |

### SetCMYKColor {#SetCMYKColor-double-double-double-double-}
```
public SetCMYKColor(double c, double m, double y, double k)
```

Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c |  | The level of cyan from 0.0 to 1.0 |
| m |  | The level of magenta from 0.0 to 1.0 |
| y |  | The level of yellow from 0.0 to 1.0 |
| k |  | The level of black from 0.0 to 1.0 |

### SetCMYKColor {#SetCMYKColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKNonstrokingColor-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

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

Returns color.

**Returns:**
Color specified by operator.

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

### getRGBColor {#getRGBColor-double:A-double:A-}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmyk |  |  |
| rgbOut |  |  |

### getY {#getY--}
```
public final double getY()
```

Gets or sets the yellow component.

**Returns:**
doable value

### setC {#setC-double-}
```
public final void setC(double value)
```

Gets or sets the cyan component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | doable value |

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

### setY {#setY-double-}
```
public final void setY(double value)
```

Gets or sets the yellow component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | doable value |

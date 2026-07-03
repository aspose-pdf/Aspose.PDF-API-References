---
title: SetCMYKColorStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing K operator (set CMYK color for stroking operations).
type: docs
weight: 540
url: /java/com.aspose.pdf.operators/setcmykcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColorStroke

```
public class SetCMYKColorStroke extends SetColorOperator
```

Class representing K operator (set CMYK color for stroking operations).

## Constructors

| Constructor | Description |
| --- | --- |
| [SetCMYKColorStroke](#SetCMYKColorStroke-double-double-double-double-) | Initializes operator. |
| [SetCMYKColorStroke](#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getC](#getC--) | Gets or sets the cyan component. |
| [getColor](#getColor--) | Returns the RGB color |
| [getK](#getK--) | Gets or sets the black component. |
| [getM](#getM--) | Gets or sets the magenta component. |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | Gets or sets the yellow component. |
| [setC](#setC-double-) | Gets or sets the cyan component. |
| [setK](#setK-double-) | Gets or sets the black component. |
| [setM](#setM-double-) | Gets or sets the magenta component. |
| [setY](#setY-double-) | Gets or sets the yellow component. |

### SetCMYKColorStroke {#SetCMYKColorStroke-double-double-double-double-}
```
public SetCMYKColorStroke(double c, double m, double y, double k)
```

Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c |  | The level of cyan from 0.0 to 1.0 |
| m |  | The level of magenta from 0.0 to 1.0 |
| y |  | The level of yellow from 0.0 to 1.0 |
| k |  | The level of black from 0.0 to 1.0 |

### SetCMYKColorStroke {#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-}
Constructor for operator class.

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

Returns the RGB color

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

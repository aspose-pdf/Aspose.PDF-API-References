---
title: SetGrayStroke
linktitle: SetGrayStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing gray level for stroking operations.
type: docs
weight: 650
url: /java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGrayStroke

```
public class SetGrayStroke extends SetColorOperator
```

Class representing gray level for stroking operations.

## Constructors

| Constructor | Description |
| --- | --- |
| [SetGrayStroke](#SetGrayStroke-double-) | Initializes operator with the specified color. |
| [SetGrayStroke](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getColor](#getColor--) | Returns color specified by operator. |
| [getGray](#getGray--) | Gets or sets the level of gray value. |
| [setGray](#setGray-double-) | Gets or sets the level of gray value. |
| [toString](#toString--) | Returns text representation of operator. |

### SetGrayStroke {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```

Initializes operator with the specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gray |  | The level of gray value. |

### SetGrayStroke {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-}
Constructor for operator class.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getColor {#getColor--}
```
public Color getColor()
```

Returns color specified by operator.

**Returns:**
Color specified by operator.

### getGray {#getGray--}
```
public final double getGray()
```

Gets or sets the level of gray value.

**Returns:**
double value

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

Gets or sets the level of gray value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### toString {#toString--}
```
public String toString()
```

Returns text representation of operator.

**Returns:**
Text representation of operator.

---
title: SetGray
second_title: Aspose.PDF for Java API Reference
description: Set gray level for non-stroking operations.
type: docs
weight: 640
url: /java/com.aspose.pdf.operators/setgray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGray

```
public class SetGray extends SetColorOperator
```

Set gray level for non-stroking operations.

## Constructors

| Constructor | Description |
| --- | --- |
| [SetGray](#SetGray-double-) | Constructor for writing program. |
| [SetGray](#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getColor](#getColor--) | Returns color specified by operator. |
| [getGray](#getGray--) | Gets or sets the level of gray value. |
| [setGray](#setGray-double-) | Gets or sets the level of gray value. |
| [toString](#toString--) | Returns string represnetation of operator. |

### SetGray {#SetGray-double-}
```
public SetGray(double gray)
```

Constructor for writing program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gray |  | The level of gray value. |

### SetGray {#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-}
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

Returns string represnetation of operator.

**Returns:**
String representation of operator.

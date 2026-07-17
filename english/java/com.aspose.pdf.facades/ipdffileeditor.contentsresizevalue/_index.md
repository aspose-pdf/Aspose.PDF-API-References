---
title: IPdfFileEditor.ContentsResizeValue
linktitle: IPdfFileEditor.ContentsResizeValue
second_title: Aspose.PDF for Java API Reference
description: Value of margin or content size specified in percents of default space units. This class is used in ContentsResizeParameters.
type: docs
weight: 310
url: /java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

Value of margin or content size specified in percents of default space units. This class is used in ContentsResizeParameters.

## Methods

| Method | Description |
| --- | --- |
| [auto](#auto--) | Initializes automatically calculated value. |
| [getValue](#getValue--) | Gets specified value. Use Unit property to get value units. |
| [isPercent](#isPercent--) | Gets true if value is expressed in percents; False if value is expressed in default units. |
| [percents](#percents-double-) | Initializes value in percents. |
| [setPercentValue](#setPercentValue-double-) | Sets value in percents of page size. |
| [setUnitValue](#setUnitValue-double-) | Sets value in default space units. |
| [units](#units-double-) | Initializes value in default space units. |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

Initializes automatically calculated value.

**Returns:**
New value instance.

### getValue {#getValue--}
```
public final double getValue()
```

Gets specified value. Use Unit property to get value units.

**Returns:**
double value

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

Gets true if value is expressed in percents; False if value is expressed in default units.

**Returns:**
boolean value

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

Initializes value in percents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | Value in percents. |

**Returns:**
New value instance.

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

Sets value in percents of page size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

Sets value in default space units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

Initializes value in default space units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | Value in units. |

**Returns:**
New value instance.

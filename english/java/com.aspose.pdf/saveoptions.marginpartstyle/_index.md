---
title: SaveOptions.MarginPartStyle
linktitle: SaveOptions.MarginPartStyle
second_title: Aspose.PDF for Java API Reference
description: Represents information of one part of margin(top, botom, left side or right side)
type: docs
weight: 4420
url: /java/com.aspose.pdf/saveoptions.marginpartstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.MarginPartStyle

```
public static class SaveOptions.MarginPartStyle extends Object
```

Represents information of one part of margin(top, botom, left side or right side)

## Constructors

| Constructor | Description |
| --- | --- |
| [MarginPartStyle](#MarginPartStyle-boolean-) | Creates instance of MarginPartStyle class and initializes its value in points |
| [MarginPartStyle](#MarginPartStyle-int-) | Creates instance of MarginPartStyle class and set its value in points |

## Methods

| Method | Description |
| --- | --- |
| [getValueInPoints](#getValueInPoints--) | Represents margin in points. Must be number greater then zero. |
| [isAuto](#isAuto--) | Gets or sets a value indicating whether this instance is auto. Value: {@code true} if this instance is auto; otherwise, {@code false}. |
| [setAuto](#setAuto-boolean-) | Gets or sets a value indicating whether this instance is auto. Value: {@code true} if this instance is auto; otherwise, {@code false}. |
| [setValueInPoints](#setValueInPoints-int-) | Represents margin in points. Must be number greater then zero. |

### MarginPartStyle {#MarginPartStyle-boolean-}
```
public MarginPartStyle(boolean isAuto)
```

Creates instance of MarginPartStyle class and initializes its value in points

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isAuto |  | Mark margin auto |

### MarginPartStyle {#MarginPartStyle-int-}
```
public MarginPartStyle(int valueInPoints)
```

Creates instance of MarginPartStyle class and set its value in points

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| valueInPoints |  | Integer value in points |

### getValueInPoints {#getValueInPoints--}
```
public final int getValueInPoints()
```

Represents margin in points. Must be number greater then zero.

**Returns:**
int value

### isAuto {#isAuto--}
```
public final boolean isAuto()
```

Gets or sets a value indicating whether this instance is auto. Value: {@code true} if this instance is auto; otherwise, {@code false}.

**Returns:**
boolean value

### setAuto {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```

Gets or sets a value indicating whether this instance is auto. Value: {@code true} if this instance is auto; otherwise, {@code false}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setValueInPoints {#setValueInPoints-int-}
```
public final void setValueInPoints(int value)
```

Represents margin in points. Must be number greater then zero.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

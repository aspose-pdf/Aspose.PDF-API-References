---
title: Dash
linktitle: Dash
second_title: Aspose.PDF for Java API Reference
description: Class representing line dash pattern.
type: docs
weight: 910
url: /java/com.aspose.pdf/dash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Dash

```
public final class Dash extends Object
```

Class representing line dash pattern.

## Constructors

| Constructor | Description |
| --- | --- |
| [Dash](#Dash-int:A-) | Constructor for Dash. Defines a pattern of dashes and gaps that shall be used in drawing a dashed border. |
| [Dash](#Dash-int-int-) | Constructor for Dash. Defines dashed border with specified dash and gap, which are unchanged for the entire dashed border. |

## Methods

| Method | Description |
| --- | --- |
| [getOff](#getOff--) | Gets or sets length of first gap between dashes. |
| [getOn](#getOn--) | Gets or sets length of first dash. |
| [getPattern](#getPattern--) | Gets dash array defining a pattern of dashes and gaps that shall be used in drawing a dashed border. |
| [setOff](#setOff-int-) | Gets or sets length of first gap between dashes. |
| [setOn](#setOn-int-) | Gets or sets length of first dash. |

### Dash {#Dash-int:A-}
```
public Dash(int[] pattern)
```

Constructor for Dash. Defines a pattern of dashes and gaps that shall be used in drawing a dashed border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pattern |  | A dash array (of two values minimum) defining a pattern of dashes and gaps that shall be used in drawing a dashed border. |

### Dash {#Dash-int-int-}
```
public Dash(int on, int off)
```

Constructor for Dash. Defines dashed border with specified dash and gap, which are unchanged for the entire dashed border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| on |  | Length of the dash. |
| off |  | Length of the gap. |

### getOff {#getOff--}
```
public final int getOff()
```

Gets or sets length of first gap between dashes.

**Returns:**
int value

### getOn {#getOn--}
```
public final int getOn()
```

Gets or sets length of first dash.

**Returns:**
int value

### getPattern {#getPattern--}
```
public final int[] getPattern()
```

Gets dash array defining a pattern of dashes and gaps that shall be used in drawing a dashed border.

**Returns:**
int array

### setOff {#setOff-int-}
```
public final void setOff(int value)
```

Gets or sets length of first gap between dashes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setOn {#setOn-int-}
```
public final void setOn(int value)
```

Gets or sets length of first dash.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

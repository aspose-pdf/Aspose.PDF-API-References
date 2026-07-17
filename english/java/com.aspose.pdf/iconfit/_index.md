---
title: IconFit
linktitle: IconFit
second_title: Aspose.PDF for Java API Reference
description: Describes how the widget annotation's icon shall be displayed within its annotation rectangle.
type: docs
weight: 2210
url: /java/com.aspose.pdf/iconfit/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.IconFit

```
public final class IconFit extends Object
```

Describes how the widget annotation's icon shall be displayed within its annotation rectangle.

## Methods

| Method | Description |
| --- | --- |
| [getLeftoverBottom](#getLeftoverBottom--) | Gets space to allocate at the bottom of the icon. |
| [getLeftoverLeft](#getLeftoverLeft--) | Gets space to allocate at the left of the icon. |
| [getScalingMode](#getScalingMode--) | The type of scaling that shall be used. |
| [getScalingReason](#getScalingReason--) | Gets scaling reason. |
| [isSpreadOnBorder](#isSpreadOnBorder--) | If true, indicates that the button appearance shall be scaled to fit fully within the bounds of the annotation without taking into consideration the line width of the border. |
| [nameToScalingMode](#nameToScalingMode-java.lang.String-) | Converts scaling mode name into ScalingMode object. |
| [nameToScalingReason](#nameToScalingReason-java.lang.String-) | Converts name of scaling reason into ScalingReason object. |
| [scalingModeToName](#scalingModeToName-int-) | Converts scaling mode object into name. |
| [scalingReasonToName](#scalingReasonToName-int-) | Converts scaling reason obejct to name. |
| [setLeftoverBottom](#setLeftoverBottom-double-) | Sets space to allocate at the bottom of the icon. |
| [setLeftoverLeft](#setLeftoverLeft-double-) | Sets space to allocate at the left of the icon. |
| [setScalingMode](#setScalingMode-int-) | The type of scaling that shall be used. |
| [setScalingReason](#setScalingReason-int-) | Sets scaling reason. |
| [setSpreadOnBorder](#setSpreadOnBorder-boolean-) | If true, indicates that the button appearance shall be scaled to fit fully within the bounds of the annotation without taking into consideration the line width of the border. |

### getLeftoverBottom {#getLeftoverBottom--}
```
public double getLeftoverBottom()
```

Gets space to allocate at the bottom of the icon.

**Returns:**
space to allocate at the bottom

### getLeftoverLeft {#getLeftoverLeft--}
```
public double getLeftoverLeft()
```

Gets space to allocate at the left of the icon.

**Returns:**
space to allocate at the left of the icon.

### getScalingMode {#getScalingMode--}
```
public int getScalingMode()
```

The type of scaling that shall be used.

**Returns:**
ScalingMode value @see ScalingMode

### getScalingReason {#getScalingReason--}
```
public int getScalingReason()
```

Gets scaling reason.

**Returns:**
ScalingReason value @see ScalingReason

### isSpreadOnBorder {#isSpreadOnBorder--}
```
public boolean isSpreadOnBorder()
```

If true, indicates that the button appearance shall be scaled to fit fully within the bounds of the annotation without taking into consideration the line width of the border.

**Returns:**
boolean value

### nameToScalingMode {#nameToScalingMode-java.lang.String-}
Converts scaling mode name into ScalingMode object.

### nameToScalingReason {#nameToScalingReason-java.lang.String-}
Converts name of scaling reason into ScalingReason object.

### scalingModeToName {#scalingModeToName-int-}
```
public static String scalingModeToName(int mode)
```

Converts scaling mode object into name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mode |  | Scaling mode object. |

**Returns:**
Scaling mode name.

### scalingReasonToName {#scalingReasonToName-int-}
```
public static String scalingReasonToName(int reason)
```

Converts scaling reason obejct to name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| reason |  | Scaling reason object to be converted. |

**Returns:**
Name of scaling reasong.

### setLeftoverBottom {#setLeftoverBottom-double-}
```
public void setLeftoverBottom(double value)
```

Sets space to allocate at the bottom of the icon.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | space to allocate at the bottom |

### setLeftoverLeft {#setLeftoverLeft-double-}
```
public void setLeftoverLeft(double value)
```

Sets space to allocate at the left of the icon.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | space to allocate at the left of the icon. |

### setScalingMode {#setScalingMode-int-}
```
public void setScalingMode(int value)
```

The type of scaling that shall be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ScalingMode value @see ScalingMode |

### setScalingReason {#setScalingReason-int-}
```
public void setScalingReason(int value)
```

Sets scaling reason.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ScalingReason value @see ScalingReason |

### setSpreadOnBorder {#setSpreadOnBorder-boolean-}
```
public void setSpreadOnBorder(boolean value)
```

If true, indicates that the button appearance shall be scaled to fit fully within the bounds of the annotation without taking into consideration the line width of the border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

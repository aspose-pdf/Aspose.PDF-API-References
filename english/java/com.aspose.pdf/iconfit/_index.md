---
title: IconFit
second_title: Aspose.PDF for Java API Reference
description: Describes how the widget annotations icon shall be displayed within its annotation rectangle.
type: docs
weight: 167
url: /java/com.aspose.pdf/iconfit/
---
**Inheritance:**
java.lang.Object
```
public final class IconFit
```

Describes how the widget annotation's icon shall be displayed within its annotation rectangle.
## Methods

| Method | Description |
| --- | --- |
| [getScalingReason()](#getScalingReason--) | Gets scaling reason. |
| [setScalingReason(int value)](#setScalingReason-int-) | Sets scaling reason. |
| [getScalingMode()](#getScalingMode--) | The type of scaling that shall be used. |
| [setScalingMode(int value)](#setScalingMode-int-) | The type of scaling that shall be used. |
| [getLeftoverLeft()](#getLeftoverLeft--) | Gets space to allocate at the left of the icon. |
| [setLeftoverLeft(double value)](#setLeftoverLeft-double-) | Sets space to allocate at the left of the icon. |
| [getLeftoverBottom()](#getLeftoverBottom--) | Gets space to allocate at the bottom of the icon. |
| [setLeftoverBottom(double value)](#setLeftoverBottom-double-) | Sets space to allocate at the bottom of the icon. |
| [isSpreadOnBorder()](#isSpreadOnBorder--) | If true, indicates that the button appearance shall be scaled to fit fully within the bounds of the annotation without taking into consideration the line width of the border. |
| [setSpreadOnBorder(boolean value)](#setSpreadOnBorder-boolean-) | If true, indicates that the button appearance shall be scaled to fit fully within the bounds of the annotation without taking into consideration the line width of the border. |
| [nameToScalingReason(String reason)](#nameToScalingReason-java.lang.String-) | Converts name of scaling reason into ScalingReason object. |
| [scalingReasonToName(int reason)](#scalingReasonToName-int-) | Converts scaling reason obejct to name. |
| [nameToScalingMode(String mode)](#nameToScalingMode-java.lang.String-) | Converts scaling mode name into ScalingMode object. |
| [scalingModeToName(int mode)](#scalingModeToName-int-) | Converts scaling mode object into name. |
### getScalingReason() {#getScalingReason--}
```
public int getScalingReason()
```


Gets scaling reason.

**Returns:**
int - ScalingReason value
### setScalingReason(int value) {#setScalingReason-int-}
```
public void setScalingReason(int value)
```


Sets scaling reason.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ScalingReason value |

### getScalingMode() {#getScalingMode--}
```
public int getScalingMode()
```


The type of scaling that shall be used.

**Returns:**
int - ScalingMode value
### setScalingMode(int value) {#setScalingMode-int-}
```
public void setScalingMode(int value)
```


The type of scaling that shall be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ScalingMode value |

### getLeftoverLeft() {#getLeftoverLeft--}
```
public double getLeftoverLeft()
```


Gets space to allocate at the left of the icon.

**Returns:**
double - space to allocate at the left of the icon.
### setLeftoverLeft(double value) {#setLeftoverLeft-double-}
```
public void setLeftoverLeft(double value)
```


Sets space to allocate at the left of the icon.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | space to allocate at the left of the icon. |

### getLeftoverBottom() {#getLeftoverBottom--}
```
public double getLeftoverBottom()
```


Gets space to allocate at the bottom of the icon.

**Returns:**
double - space to allocate at the bottom
### setLeftoverBottom(double value) {#setLeftoverBottom-double-}
```
public void setLeftoverBottom(double value)
```


Sets space to allocate at the bottom of the icon.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | space to allocate at the bottom |

### isSpreadOnBorder() {#isSpreadOnBorder--}
```
public boolean isSpreadOnBorder()
```


If true, indicates that the button appearance shall be scaled to fit fully within the bounds of the annotation without taking into consideration the line width of the border.

**Returns:**
boolean - boolean value
### setSpreadOnBorder(boolean value) {#setSpreadOnBorder-boolean-}
```
public void setSpreadOnBorder(boolean value)
```


If true, indicates that the button appearance shall be scaled to fit fully within the bounds of the annotation without taking into consideration the line width of the border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### nameToScalingReason(String reason) {#nameToScalingReason-java.lang.String-}
```
public static int nameToScalingReason(String reason)
```


Converts name of scaling reason into ScalingReason object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| reason | java.lang.String | Name of scaling reason. |

**Returns:**
int - Scaling reason object.
### scalingReasonToName(int reason) {#scalingReasonToName-int-}
```
public static String scalingReasonToName(int reason)
```


Converts scaling reason obejct to name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| reason | int | Scaling reason object to be converted. |

**Returns:**
java.lang.String - Name of scaling reasong.
### nameToScalingMode(String mode) {#nameToScalingMode-java.lang.String-}
```
public static int nameToScalingMode(String mode)
```


Converts scaling mode name into ScalingMode object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mode | java.lang.String | Scaling mode name. |

**Returns:**
int - Scaling mode object.
### scalingModeToName(int mode) {#scalingModeToName-int-}
```
public static String scalingModeToName(int mode)
```


Converts scaling mode object into name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mode | int | Scaling mode object. |

**Returns:**
java.lang.String - Scaling mode name.

---
title: Stamp
second_title: Aspose.PDF for Java API Reference
description: An abstract class for various kinds of stamps which come as descendants.
type: docs
weight: 338
url: /java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object
```
public abstract class Stamp
```

An abstract class for various kinds of stamps which come as descendants.
## Constructors

| Constructor | Description |
| --- | --- |
| [Stamp()](#Stamp--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isBackground()](#isBackground--) | Gets a bool value that indicates the content is stamped as background. |
| [setBackground(boolean value)](#setBackground-boolean-) | Sets a bool value that indicates the content is stamped as background. |
| [getOpacity()](#getOpacity--) | Gets a value to indicate the stamp opacity. |
| [setOpacity(double value)](#setOpacity-double-) | Sets a value to indicate the stamp opacity. |
| [getOutlineOpacity()](#getOutlineOpacity--) | Gets a value to indicate the stamp outline opacity. |
| [setOutlineOpacity(double value)](#setOutlineOpacity-double-) | Sets a value to indicate the stamp outline opacity. |
| [getOutlineWidth()](#getOutlineWidth--) | Gets a value of the stamp outline width. |
| [setOutlineWidth(double value)](#setOutlineWidth-double-) | Sets a value of the stamp outline width. |
| [getRotate()](#getRotate--) | Gets the rotation of stamp content according  Rotation  values. |
| [setRotate(int value)](#setRotate-int-) | Sets the rotation of stamp content according  Rotation  values. |
| [getXIndent()](#getXIndent--) | Get horizontal stamp coordinate, starting from the left. |
| [setXIndent(double value)](#setXIndent-double-) | Set horizontal stamp coordinate, starting from the left. |
| [getYIndent()](#getYIndent--) | Get vertical stamp coordinate, starting from the bottom. |
| [setYIndent(double value)](#setYIndent-double-) | Set vertical stamp coordinate, starting from the bottom. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets horizontal alignment of stamp on the page. |
| [setHorizontalAlignment(HorizontalAlignment value)](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets Horizontal alignment of stamp on the page. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets vertical alignment of stamp on page. |
| [setVerticalAlignment(VerticalAlignment value)](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Sets vertical alignment of stamp on page. |
| [getLeftMargin()](#getLeftMargin--) | Gets left margin of stamp. |
| [setLeftMargin(double value)](#setLeftMargin-double-) | Sets left margin of stamp. |
| [getRightMargin()](#getRightMargin--) | Gets right margin of stamp. |
| [setRightMargin(double value)](#setRightMargin-double-) | Sets right margin of stamp. |
| [getBottomMargin()](#getBottomMargin--) | Gets bottom margin of stamp. |
| [setBottomMargin(double value)](#setBottomMargin-double-) | Sets bottom margin of stamp. |
| [getTopMargin()](#getTopMargin--) | Get top margin of stamp. |
| [setTopMargin(double value)](#setTopMargin-double-) | Sets top margin of stamp. |
| [getZoomX()](#getZoomX--) | Gets horizontal zooming factor of the stamp. |
| [setZoomX(double value)](#setZoomX-double-) | Sets horizontal zooming factor of the stamp. |
| [getWidth()](#getWidth--) | Gets desired width of the stamp on the page. |
| [setWidth(double value)](#setWidth-double-) | Sets desired width of the stamp on the page. |
| [getHeight()](#getHeight--) | Gets desired height of the stamp on the page. |
| [setHeight(double value)](#setHeight-double-) | Sets desired height of the stamp on the page. |
| [getZoomY()](#getZoomY--) | Gets vertical zooming factor of the stamp. |
| [setZoomY(double value)](#setZoomY-double-) | Sets vertical zooming factor of the stamp. |
| [getZoom()](#getZoom--) | Gets zooming factor of the stamp. |
| [setZoom(double value)](#setZoom-double-) | Gets zooming factor of the stamp. |
| [getRotateAngle()](#getRotateAngle--) | Gets rotate angle of stamp in degrees. |
| [setRotateAngle(double value)](#setRotateAngle-double-) | Sets rotate angle of stamp in degrees. |
| [put(Page page)](#put-com.aspose.pdf.Page-) | Adds stamp on the page. |
| [setStampId(int value)](#setStampId-int-) | Sets stamp Id. |
| [getStampId()](#getStampId--) | Gets stamp ID. |
### Stamp() {#Stamp--}
```
public Stamp()
```


### isBackground() {#isBackground--}
```
public boolean isBackground()
```


Gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top.

**Returns:**
boolean - boolean value
### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


Sets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By default, the value is false, the stamp content is layed at the top.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


Gets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0.

**Returns:**
double - double value
### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


Sets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getOutlineOpacity() {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```


Gets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0.

**Returns:**
double - double value
### setOutlineOpacity(double value) {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```


Sets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getOutlineWidth() {#getOutlineWidth--}
```
public double getOutlineWidth()
```


Gets a value of the stamp outline width. By default the value is 1.0.

**Returns:**
double - double value
### setOutlineWidth(double value) {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```


Sets a value of the stamp outline width. By default the value is 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getRotate() {#getRotate--}
```
public int getRotate()
```


Gets the rotation of stamp content according  Rotation  values. Note. This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns Rotation.None.

**Returns:**
int - Rotation value
### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


Sets the rotation of stamp content according  Rotation  values. Note. This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns Rotation.None.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getXIndent() {#getXIndent--}
```
public double getXIndent()
```


Get horizontal stamp coordinate, starting from the left.

**Returns:**
double - double value
### setXIndent(double value) {#setXIndent-double-}
```
public void setXIndent(double value)
```


Set horizontal stamp coordinate, starting from the left.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getYIndent() {#getYIndent--}
```
public double getYIndent()
```


Get vertical stamp coordinate, starting from the bottom.

**Returns:**
double - double value
### setYIndent(double value) {#setYIndent-double-}
```
public void setYIndent(double value)
```


Set vertical stamp coordinate, starting from the bottom.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```


Gets horizontal alignment of stamp on the page.

**Returns:**
[HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) - HorizontalAlignment value
### setHorizontalAlignment(HorizontalAlignment value) {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
```
public void setHorizontalAlignment(HorizontalAlignment value)
```


Sets Horizontal alignment of stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) | HorizontalAlignment value |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```


Gets vertical alignment of stamp on page.

**Returns:**
[VerticalAlignment](../../com.aspose.pdf/verticalalignment) - VerticalAlignment value
### setVerticalAlignment(VerticalAlignment value) {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
```
public void setVerticalAlignment(VerticalAlignment value)
```


Sets vertical alignment of stamp on page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VerticalAlignment](../../com.aspose.pdf/verticalalignment) | VerticalAlignment value |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Gets left margin of stamp.

**Returns:**
double - double value
### setLeftMargin(double value) {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```


Sets left margin of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Gets right margin of stamp.

**Returns:**
double - double value
### setRightMargin(double value) {#setRightMargin-double-}
```
public void setRightMargin(double value)
```


Sets right margin of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Gets bottom margin of stamp.

**Returns:**
double - double value
### setBottomMargin(double value) {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```


Sets bottom margin of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Get top margin of stamp.

**Returns:**
double - double value
### setTopMargin(double value) {#setTopMargin-double-}
```
public void setTopMargin(double value)
```


Sets top margin of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getZoomX() {#getZoomX--}
```
public double getZoomX()
```


Gets horizontal zooming factor of the stamp. Allows to scale stamp horizontally.

**Returns:**
double - double value
### setZoomX(double value) {#setZoomX-double-}
```
public void setZoomX(double value)
```


Sets horizontal zooming factor of the stamp. Allows to scale stamp horizontally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets desired width of the stamp on the page.

**Returns:**
double - double value
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets desired width of the stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets desired height of the stamp on the page.

**Returns:**
double - double value
### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Sets desired height of the stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getZoomY() {#getZoomY--}
```
public double getZoomY()
```


Gets vertical zooming factor of the stamp. Allows to scale stamp vertically.

**Returns:**
double - double value
### setZoomY(double value) {#setZoomY-double-}
```
public void setZoomY(double value)
```


Sets vertical zooming factor of the stamp. Allows to scale stamp vertically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getZoom() {#getZoom--}
```
public double getZoom()
```


Gets zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value.

**Returns:**
double - double value
### setZoom(double value) {#setZoom-double-}
```
public void setZoom(double value)
```


Gets zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle.

**Returns:**
double - double value
### setRotateAngle(double value) {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```


Sets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | rotate angle |

### put(Page page) {#put-com.aspose.pdf.Page-}
```
public abstract void put(Page page)
```


Adds stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to add stamp. |

### setStampId(int value) {#setStampId-int-}
```
public void setStampId(int value)
```


Sets stamp Id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | New value of Stamp ID. |

### getStampId() {#getStampId--}
```
public int getStampId()
```


Gets stamp ID.

**Returns:**
int - Identifier of the stamp.

---
title: Stamp
second_title: Aspose.PDF for Java API Reference
description: An abstract class for various kinds of stamps which come as descendants.
type: docs
weight: 4620
url: /java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp

```
public abstract class Stamp extends Object
```

An abstract class for various kinds of stamps which come as descendants.

## Constructors

| Constructor | Description |
| --- | --- |
| [Stamp](#Stamp--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getBottomMargin](#getBottomMargin--) | Gets bottom margin of stamp. |
| [getHeight](#getHeight--) | Gets desired height of the stamp on the page. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Gets horizontal alignment of stamp on the page. |
| [getLeftMargin](#getLeftMargin--) | Gets left margin of stamp. |
| [getOpacity](#getOpacity--) | Gets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [getOutlineOpacity](#getOutlineOpacity--) | Gets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [getOutlineWidth](#getOutlineWidth--) | Gets a value of the stamp outline width. By default the value is 1.0. |
| [getRightMargin](#getRightMargin--) | Gets right margin of stamp. |
| [getRotate](#getRotate--) | Gets the rotation of stamp content according {@code Rotation} values. Note. This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns Rotation.None. |
| [getRotateAngle](#getRotateAngle--) | Gets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [getStampId](#getStampId--) | Gets stamp ID. |
| [getTopMargin](#getTopMargin--) | Get top margin of stamp. |
| [getVerticalAlignment](#getVerticalAlignment--) | Gets vertical alignment of stamp on page. |
| [getWidth](#getWidth--) | Gets desired width of the stamp on the page. |
| [getXIndent](#getXIndent--) | Get horizontal stamp coordinate, starting from the left. |
| [getYIndent](#getYIndent--) | Get vertical stamp coordinate, starting from the bottom. |
| [getZoom](#getZoom--) | Gets zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value. |
| [getZoomX](#getZoomX--) | Gets horizontal zooming factor of the stamp. Allows to scale stamp horizontally. |
| [getZoomY](#getZoomY--) | Gets vertical zooming factor of the stamp. Allows to scale stamp vertically. |
| [isBackground](#isBackground--) | Gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top. |
| [put](#put-com.aspose.pdf.Page-) | Adds stamp on the page. |
| [setBackground](#setBackground-boolean-) | Sets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By default, the value is false, the stamp content is layed at the top. |
| [setBottomMargin](#setBottomMargin-double-) | Sets bottom margin of stamp. |
| [setHeight](#setHeight-double-) | Sets desired height of the stamp on the page. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets Horizontal alignment of stamp on the page. |
| [setLeftMargin](#setLeftMargin-double-) | Sets left margin of stamp. |
| [setOpacity](#setOpacity-double-) | Sets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [setOutlineOpacity](#setOutlineOpacity-double-) | Sets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [setOutlineWidth](#setOutlineWidth-double-) | Sets a value of the stamp outline width. By default the value is 1.0. |
| [setRightMargin](#setRightMargin-double-) | Sets right margin of stamp. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Sets the rotation of stamp content according {@code Rotation} values. Note. This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns Rotation.None. |
| [setRotateAngle](#setRotateAngle-double-) | Sets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [setStampId](#setStampId-int-) | Sets stamp Id. |
| [setTopMargin](#setTopMargin-double-) | Sets top margin of stamp. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Sets vertical alignment of stamp on page. |
| [setWidth](#setWidth-double-) | Sets desired width of the stamp on the page. |
| [setXIndent](#setXIndent-double-) | Set horizontal stamp coordinate, starting from the left. |
| [setYIndent](#setYIndent-double-) | Set vertical stamp coordinate, starting from the bottom. |
| [setZoom](#setZoom-double-) | Gets zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value. |
| [setZoomX](#setZoomX-double-) | Sets horizontal zooming factor of the stamp. Allows to scale stamp horizontally. |
| [setZoomY](#setZoomY-double-) | Sets vertical zooming factor of the stamp. Allows to scale stamp vertically. |

### Stamp {#Stamp--}
```
public Stamp()
```



### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Gets bottom margin of stamp.

**Returns:**
double value

### getHeight {#getHeight--}
```
public double getHeight()
```

Gets desired height of the stamp on the page.

**Returns:**
double value

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Gets horizontal alignment of stamp on the page.

**Returns:**
HorizontalAlignment value @see HorizontalAlignment

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Gets left margin of stamp.

**Returns:**
double value

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Gets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0.

**Returns:**
double value

### getOutlineOpacity {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```

Gets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0.

**Returns:**
double value

### getOutlineWidth {#getOutlineWidth--}
```
public double getOutlineWidth()
```

Gets a value of the stamp outline width. By default the value is 1.0.

**Returns:**
double value

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Gets right margin of stamp.

**Returns:**
double value

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Gets the rotation of stamp content according {@code Rotation} values. Note. This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns Rotation.None.

**Returns:**
Rotation value @see Rotation

### getRotateAngle {#getRotateAngle--}
```
public double getRotateAngle()
```

Gets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle.

**Returns:**
double value

### getStampId {#getStampId--}
```
public int getStampId()
```

Gets stamp ID.

**Returns:**
Identifier of the stamp.

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Get top margin of stamp.

**Returns:**
double value

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Gets vertical alignment of stamp on page.

**Returns:**
VerticalAlignment value @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Gets desired width of the stamp on the page.

**Returns:**
double value

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Get horizontal stamp coordinate, starting from the left.

**Returns:**
double value

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Get vertical stamp coordinate, starting from the bottom.

**Returns:**
double value

### getZoom {#getZoom--}
```
public double getZoom()
```

Gets zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value.

**Returns:**
double value

### getZoomX {#getZoomX--}
```
public double getZoomX()
```

Gets horizontal zooming factor of the stamp. Allows to scale stamp horizontally.

**Returns:**
double value

### getZoomY {#getZoomY--}
```
public double getZoomY()
```

Gets vertical zooming factor of the stamp. Allows to scale stamp vertically.

**Returns:**
double value

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top.

**Returns:**
boolean value

### put {#put-com.aspose.pdf.Page-}
Adds stamp on the page.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Sets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By default, the value is false, the stamp content is layed at the top.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Sets bottom margin of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Sets desired height of the stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Sets Horizontal alignment of stamp on the page.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Sets left margin of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Sets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setOutlineOpacity {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```

Sets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setOutlineWidth {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```

Sets a value of the stamp outline width. By default the value is 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Sets right margin of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Sets the rotation of stamp content according {@code Rotation} values. Note. This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns Rotation.None.

### setRotateAngle {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```

Sets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | rotate angle |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Sets stamp Id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | New value of Stamp ID. |

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Sets top margin of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Sets vertical alignment of stamp on page.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Sets desired width of the stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Set horizontal stamp coordinate, starting from the left.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Set vertical stamp coordinate, starting from the bottom.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setZoom {#setZoom-double-}
```
public void setZoom(double value)
```

Gets zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setZoomX {#setZoomX-double-}
```
public void setZoomX(double value)
```

Sets horizontal zooming factor of the stamp. Allows to scale stamp horizontally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setZoomY {#setZoomY-double-}
```
public void setZoomY(double value)
```

Sets vertical zooming factor of the stamp. Allows to scale stamp vertically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

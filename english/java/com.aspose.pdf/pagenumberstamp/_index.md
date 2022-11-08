---
title: PageNumberStamp
second_title: Aspose.PDF for Java API Reference
description: Represents page number stamp and used to number pages.
type: docs
weight: 267
url: /java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Stamp](../../com.aspose.pdf/stamp), [com.aspose.pdf.TextStamp](../../com.aspose.pdf/textstamp)
```
public final class PageNumberStamp extends TextStamp
```

Represents page number stamp and used to number pages.
## Constructors

| Constructor | Description |
| --- | --- |
| [PageNumberStamp(String format)](#PageNumberStamp-java.lang.String-) | Initializes a new instance of the  PageNumberStamp  class. |
| [PageNumberStamp()](#PageNumberStamp--) | Initializes a new instance of the  PageNumberStamp  class. |
| [PageNumberStamp(FormattedText formattedText)](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | Creates PageNumberStamp by formatted text. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | Gets bottom margin of stamp. |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Returns default font |
| [getDefaultFontSize()](#getDefaultFontSize--) | Default Font Size |
| [getDraw()](#getDraw--) | This property determines how stamp is drawn on page. |
| [getFormat()](#getFormat--) | Gets String value for stamping page numbers. |
| [getHeight()](#getHeight--) | Desired height of the stamp on the page. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets horizontal alignment of stamp on the page. |
| [getLeftMargin()](#getLeftMargin--) | Gets left margin of stamp. |
| [getMaxRowWidth()](#getMaxRowWidth--) | Max row height for WordWrap option. |
| [getNumberingStyle()](#getNumberingStyle--) | Numbering style which used by this stamp. |
| [getOpacity()](#getOpacity--) | Gets a value to indicate the stamp opacity. |
| [getOutlineOpacity()](#getOutlineOpacity--) | Gets a value to indicate the stamp outline opacity. |
| [getOutlineWidth()](#getOutlineWidth--) | Gets a value of the stamp outline width. |
| [getRightMargin()](#getRightMargin--) | Gets right margin of stamp. |
| [getRotate()](#getRotate--) | Gets the rotation of stamp content according  Rotation  values. |
| [getRotateAngle()](#getRotateAngle--) | Gets rotate angle of stamp in degrees. |
| [getStampId()](#getStampId--) | Gets stamp ID. |
| [getStartingNumber()](#getStartingNumber--) | Gets value of the number of starting page. |
| [getTextAlignment()](#getTextAlignment--) | Alignment of the text inside the stamp. |
| [getTextState()](#getTextState--) | Gets text properties of the stamp. |
| [getTopMargin()](#getTopMargin--) | Get top margin of stamp. |
| [getTreatYIndentAsBaseLine()](#getTreatYIndentAsBaseLine--) | Defines coordinate origin for placing text. |
| [getValue()](#getValue--) | Gets string value which is used as stamp on the page. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets vertical alignment of stamp on page. |
| [getWidth()](#getWidth--) | Desired width of the stamp on the page. |
| [getXIndent()](#getXIndent--) | Get horizontal stamp coordinate, starting from the left. |
| [getYIndent()](#getYIndent--) | Get vertical stamp coordinate, starting from the bottom. |
| [getZoom()](#getZoom--) | Gets zooming factor of the stamp. |
| [getZoomX()](#getZoomX--) | Gets horizontal zooming factor of the stamp. |
| [getZoomY()](#getZoomY--) | Gets vertical zooming factor of the stamp. |
| [hashCode()](#hashCode--) |  |
| [isBackground()](#isBackground--) | Gets a bool value that indicates the content is stamped as background. |
| [isJustify()](#isJustify--) | Defines text justification. |
| [isScale()](#isScale--) | Defines scaling of the text. |
| [isWordWrap()](#isWordWrap--) | Defines word wrap. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [put(Page page)](#put-com.aspose.pdf.Page-) | Adds page number. |
| [setBackground(boolean value)](#setBackground-boolean-) | Sets a bool value that indicates the content is stamped as background. |
| [setBottomMargin(double value)](#setBottomMargin-double-) | Sets bottom margin of stamp. |
| [setDraw(boolean value)](#setDraw-boolean-) | This property determines how stamp is drawn on page. |
| [setFormat(String value)](#setFormat-java.lang.String-) | Sets String value for stamping page numbers. |
| [setHeight(double value)](#setHeight-double-) | Desired height of the stamp on the page. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets Horizontal alignment of stamp on the page. |
| [setJustify(boolean value)](#setJustify-boolean-) | Defines text justification. |
| [setLeftMargin(double value)](#setLeftMargin-double-) | Sets left margin of stamp. |
| [setMaxRowWidth(double value)](#setMaxRowWidth-double-) | Max row height for WordWrap option. |
| [setNumberingStyle(int value)](#setNumberingStyle-int-) | Numbering style which used by this stamp. |
| [setOpacity(double value)](#setOpacity-double-) | Sets a value to indicate the stamp opacity. |
| [setOutlineOpacity(double value)](#setOutlineOpacity-double-) | Sets a value to indicate the stamp outline opacity. |
| [setOutlineWidth(double value)](#setOutlineWidth-double-) | Sets a value of the stamp outline width. |
| [setRightMargin(double value)](#setRightMargin-double-) | Sets right margin of stamp. |
| [setRotate(int value)](#setRotate-int-) | Sets the rotation of stamp content according  Rotation  values. |
| [setRotateAngle(double value)](#setRotateAngle-double-) | Sets rotate angle of stamp in degrees. |
| [setScale(boolean value)](#setScale-boolean-) | Defines scaling of the text. |
| [setStampId(int value)](#setStampId-int-) | Sets stamp Id. |
| [setStartingNumber(int value)](#setStartingNumber-int-) | Sets value of the number of starting page. |
| [setTextAlignment(int value)](#setTextAlignment-int-) | Alignment of the text inside the stamp. |
| [setTopMargin(double value)](#setTopMargin-double-) | Sets top margin of stamp. |
| [setTreatYIndentAsBaseLine(boolean value)](#setTreatYIndentAsBaseLine-boolean-) | Defines coordinate origin for placing text. |
| [setValue(String value)](#setValue-java.lang.String-) | Sets string value which is used as stamp on the page. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets vertical alignment of stamp on page. |
| [setWidth(double value)](#setWidth-double-) | Desired width of the stamp on the page. |
| [setWordWrap(boolean value)](#setWordWrap-boolean-) | Defines word wrap. |
| [setXIndent(double value)](#setXIndent-double-) | Set horizontal stamp coordinate, starting from the left. |
| [setYIndent(double value)](#setYIndent-double-) | Set vertical stamp coordinate, starting from the bottom. |
| [setZoom(double value)](#setZoom-double-) | Gets zooming factor of the stamp. |
| [setZoomX(double value)](#setZoomX-double-) | Sets horizontal zooming factor of the stamp. |
| [setZoomY(double value)](#setZoomY-double-) | Sets vertical zooming factor of the stamp. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PageNumberStamp(String format) {#PageNumberStamp-java.lang.String-}
```
public PageNumberStamp(String format)
```


Initializes a new instance of the  PageNumberStamp  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String | String value used for stamping. See  Format  property for details. |

### PageNumberStamp() {#PageNumberStamp--}
```
public PageNumberStamp()
```


Initializes a new instance of the  PageNumberStamp  class. Format is set to "\#".

### PageNumberStamp(FormattedText formattedText) {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
```
public PageNumberStamp(FormattedText formattedText)
```


Creates PageNumberStamp by formatted text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Formatted text which used to create Page Number Stamp. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Gets bottom margin of stamp.

**Returns:**
double - double value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFont() {#getDefaultFont--}
```
public static Font getDefaultFont()
```


Returns default font

**Returns:**
[Font](../../com.aspose.pdf/font) - com.aspose.pdf.Font object
### getDefaultFontSize() {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```


Default Font Size

**Returns:**
float - float value
### getDraw() {#getDraw--}
```
public boolean getDraw()
```


This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text.

**Returns:**
boolean - boolean value
### getFormat() {#getFormat--}
```
public String getFormat()
```


Gets String value for stamping page numbers. Value must include char '\#' which is replaced with the page number in the process of stamping.

**Returns:**
java.lang.String - String value
### getHeight() {#getHeight--}
```
public double getHeight()
```


Desired height of the stamp on the page.

**Returns:**
double - double value
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets horizontal alignment of stamp on the page.

**Returns:**
int - HorizontalAlignment value
### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Gets left margin of stamp.

**Returns:**
double - double value
### getMaxRowWidth() {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```


Max row height for WordWrap option.

**Returns:**
double - double value
### getNumberingStyle() {#getNumberingStyle--}
```
public int getNumberingStyle()
```


Numbering style which used by this stamp.

**Returns:**
int - NumberingStyle value
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


Gets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0.

**Returns:**
double - double value
### getOutlineOpacity() {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```


Gets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0.

**Returns:**
double - double value
### getOutlineWidth() {#getOutlineWidth--}
```
public double getOutlineWidth()
```


Gets a value of the stamp outline width. By default the value is 1.0.

**Returns:**
double - double value
### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Gets right margin of stamp.

**Returns:**
double - double value
### getRotate() {#getRotate--}
```
public int getRotate()
```


Gets the rotation of stamp content according  Rotation  values. Note. This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns Rotation.None.

**Returns:**
int - Rotation value
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle.

**Returns:**
double - double value
### getStampId() {#getStampId--}
```
public int getStampId()
```


Gets stamp ID.

**Returns:**
int - Identifier of the stamp.
### getStartingNumber() {#getStartingNumber--}
```
public int getStartingNumber()
```


Gets value of the number of starting page. Other pages will be numbered starting from this value.

**Returns:**
int - int value
### getTextAlignment() {#getTextAlignment--}
```
public int getTextAlignment()
```


Alignment of the text inside the stamp.

**Returns:**
int - HorizontalAlignment value
### getTextState() {#getTextState--}
```
public TextState getTextState()
```


Gets text properties of the stamp. See  TextState  for details.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState element
### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Get top margin of stamp.

**Returns:**
double - double value
### getTreatYIndentAsBaseLine() {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```


Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text.

**Returns:**
boolean - boolean value
### getValue() {#getValue--}
```
public String getValue()
```


Gets string value which is used as stamp on the page.

**Returns:**
java.lang.String - String value
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets vertical alignment of stamp on page.

**Returns:**
int - VerticalAlignment value
### getWidth() {#getWidth--}
```
public double getWidth()
```


Desired width of the stamp on the page.

**Returns:**
double - double value
### getXIndent() {#getXIndent--}
```
public double getXIndent()
```


Get horizontal stamp coordinate, starting from the left.

**Returns:**
double - double value
### getYIndent() {#getYIndent--}
```
public double getYIndent()
```


Get vertical stamp coordinate, starting from the bottom.

**Returns:**
double - double value
### getZoom() {#getZoom--}
```
public double getZoom()
```


Gets zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value.

**Returns:**
double - double value
### getZoomX() {#getZoomX--}
```
public double getZoomX()
```


Gets horizontal zooming factor of the stamp. Allows to scale stamp horizontally.

**Returns:**
double - double value
### getZoomY() {#getZoomY--}
```
public double getZoomY()
```


Gets vertical zooming factor of the stamp. Allows to scale stamp vertically.

**Returns:**
double - double value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBackground() {#isBackground--}
```
public boolean isBackground()
```


Gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top.

**Returns:**
boolean - boolean value
### isJustify() {#isJustify--}
```
public boolean isJustify()
```


Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false.

**Returns:**
boolean - boolean value
### isScale() {#isScale--}
```
public boolean isScale()
```


Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width.

**Returns:**
boolean - boolean value
### isWordWrap() {#isWordWrap--}
```
public boolean isWordWrap()
```


Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### put(Page page) {#put-com.aspose.pdf.Page-}
```
public void put(Page page)
```


Adds page number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page for stamping. |

### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


Sets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By default, the value is false, the stamp content is layed at the top.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setBottomMargin(double value) {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```


Sets bottom margin of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setDraw(boolean value) {#setDraw-boolean-}
```
public void setDraw(boolean value)
```


This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setFormat(String value) {#setFormat-java.lang.String-}
```
public void setFormat(String value)
```


Sets String value for stamping page numbers. Value must include char '\#' which is replaced with the page number in the process of stamping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Desired height of the stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets Horizontal alignment of stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### setJustify(boolean value) {#setJustify-boolean-}
```
public void setJustify(boolean value)
```


Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setLeftMargin(double value) {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```


Sets left margin of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setMaxRowWidth(double value) {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```


Max row height for WordWrap option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setNumberingStyle(int value) {#setNumberingStyle-int-}
```
public void setNumberingStyle(int value)
```


Numbering style which used by this stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | NumberingStyle value |

### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


Sets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setOutlineOpacity(double value) {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```


Sets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setOutlineWidth(double value) {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```


Sets a value of the stamp outline width. By default the value is 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setRightMargin(double value) {#setRightMargin-double-}
```
public void setRightMargin(double value)
```


Sets right margin of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


Sets the rotation of stamp content according  Rotation  values. Note. This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns Rotation.None.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```


Sets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | rotate angle |

### setScale(boolean value) {#setScale-boolean-}
```
public void setScale(boolean value)
```


Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setStampId(int value) {#setStampId-int-}
```
public void setStampId(int value)
```


Sets stamp Id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | New value of Stamp ID. |

### setStartingNumber(int value) {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```


Sets value of the number of starting page. Other pages will be numbered starting from this value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public void setTextAlignment(int value)
```


Alignment of the text inside the stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### setTopMargin(double value) {#setTopMargin-double-}
```
public void setTopMargin(double value)
```


Sets top margin of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setTreatYIndentAsBaseLine(boolean value) {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```


Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Sets string value which is used as stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets vertical alignment of stamp on page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment value |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Desired width of the stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setWordWrap(boolean value) {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```


Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setXIndent(double value) {#setXIndent-double-}
```
public void setXIndent(double value)
```


Set horizontal stamp coordinate, starting from the left.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setYIndent(double value) {#setYIndent-double-}
```
public void setYIndent(double value)
```


Set vertical stamp coordinate, starting from the bottom.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setZoom(double value) {#setZoom-double-}
```
public void setZoom(double value)
```


Gets zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setZoomX(double value) {#setZoomX-double-}
```
public void setZoomX(double value)
```


Sets horizontal zooming factor of the stamp. Allows to scale stamp horizontally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setZoomY(double value) {#setZoomY-double-}
```
public void setZoomY(double value)
```


Sets vertical zooming factor of the stamp. Allows to scale stamp vertically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


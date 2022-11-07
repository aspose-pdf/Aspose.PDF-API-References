---
title: FloatingBox
second_title: Aspose.PDF for Java API Reference
description: 
type: docs
weight: 109
url: /java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public class FloatingBox extends BaseParagraph implements System.ICloneable
```
## Constructors

| Constructor | Description |
| --- | --- |
| [FloatingBox(float width, float height)](#FloatingBox-float-float-) | Initializes a new instance of the  FloatingBox  class with specified width and height. |
| [FloatingBox()](#FloatingBox--) |  |
## Fields

| Field | Description |
| --- | --- |
| [_VerticalAlignment](#-VerticalAlignment) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) |  |
| [setWidth(double value)](#setWidth-double-) |  |
| [getHeight()](#getHeight--) |  |
| [setHeight(double value)](#setHeight-double-) |  |
| [isNeedRepeating()](#isNeedRepeating--) |  |
| [isNeedRepeating(boolean value)](#isNeedRepeating-boolean-) |  |
| [getParagraphs()](#getParagraphs--) |  |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) |  |
| [isExtraContentClip()](#isExtraContentClip--) |  |
| [isExtraContentClip(boolean value)](#isExtraContentClip-boolean-) |  |
| [getBorder()](#getBorder--) |  |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) |  |
| [getBackgroundColor()](#getBackgroundColor--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) |  |
| [getPadding()](#getPadding--) |  |
| [setPadding(MarginInfo value)](#setPadding-com.aspose.pdf.MarginInfo-) |  |
| [getLeft()](#getLeft--) | Gets or sets the table left coordinate. |
| [setLeft(double value)](#setLeft-double-) |  |
| [getTop()](#getTop--) | Gets or sets the table top coordinate. |
| [setTop(double value)](#setTop-double-) |  |
| [deepClone()](#deepClone--) | Clones a new  FloatingBox  object. |
### FloatingBox(float width, float height) {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```


Initializes a new instance of the  FloatingBox  class with specified width and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | The width of the box. |
| height | float | The height of the box. |

### FloatingBox() {#FloatingBox--}
```
public FloatingBox()
```


### _VerticalAlignment {#-VerticalAlignment}
```
public int _VerticalAlignment
```


### getWidth() {#getWidth--}
```
public double getWidth()
```




**Returns:**
double
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getHeight() {#getHeight--}
```
public double getHeight()
```




**Returns:**
double
### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isNeedRepeating() {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```




**Returns:**
boolean
### isNeedRepeating(boolean value) {#isNeedRepeating-boolean-}
```
public void isNeedRepeating(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```




**Returns:**
[Paragraphs](../../com.aspose.pdf/paragraphs)
### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) |  |

### isExtraContentClip() {#isExtraContentClip--}
```
public boolean isExtraContentClip()
```




**Returns:**
boolean
### isExtraContentClip(boolean value) {#isExtraContentClip-boolean-}
```
public void isExtraContentClip(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```




**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo)
### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```




**Returns:**
[Color](../../com.aspose.pdf/color)
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) |  |

### getPadding() {#getPadding--}
```
public MarginInfo getPadding()
```




**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo)
### setPadding(MarginInfo value) {#setPadding-com.aspose.pdf.MarginInfo-}
```
public void setPadding(MarginInfo value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) |  |

### getLeft() {#getLeft--}
```
public double getLeft()
```


Gets or sets the table left coordinate.

**Returns:**
double
### setLeft(double value) {#setLeft-double-}
```
public void setLeft(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTop() {#getTop--}
```
public double getTop()
```


Gets or sets the table top coordinate.

**Returns:**
double
### setTop(double value) {#setTop-double-}
```
public void setTop(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones a new  FloatingBox  object. Paragraphs in the floating box are not cloned.

**Returns:**
java.lang.Object - The new  FloatingBox  object.

---
title: FloatingBox
second_title: Aspose.PDF for Java API Reference
description: Represents a FloatingBox in a Pdf document.
type: docs
weight: 127
url: /java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public class FloatingBox extends BaseParagraph
```

Represents a FloatingBox in a Pdf document. FloatingBox is custom positioned.
## Constructors

| Constructor | Description |
| --- | --- |
| [FloatingBox(float width, float height)](#FloatingBox-float-float-) | Initializes a new instance of the  FloatingBox  class with specified width and height. |
| [FloatingBox()](#FloatingBox--) | Initializes a new instance of the  FloatingBox  class. |
## Methods

| Method | Description |
| --- | --- |
| [getColumnInfo()](#getColumnInfo--) | Gets a column info |
| [setColumnInfo(ColumnInfo value)](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Sets a column info |
| [getWidth()](#getWidth--) | Gets a float value that indicates the width of the floating box. |
| [setWidth(double value)](#setWidth-double-) | Sets a float value that indicates the width of the floating box. |
| [getHeight()](#getHeight--) | Gets a float value that indicates the height of the floating box. |
| [setHeight(double value)](#setHeight-double-) | Sets a float value that indicates the height of the floating box. |
| [isNeedRepeating()](#isNeedRepeating--) | Gets a boolean value that indicates whether the paragraph need to be repeated on next page. |
| [setNeedRepeating(boolean value)](#setNeedRepeating-boolean-) | Sets a boolean value that indicates whether the paragraph need to be repeated on next page. |
| [getParagraphs()](#getParagraphs--) | Gets a collection that indicates all paragraphs in the cell. |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) | Sets a collection that indicates all paragraphs in the cell. |
| [getBorder()](#getBorder--) | Gets a object that indicates the border info of the floating box. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Sets a object that indicates the border info of the floating box. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets a object that indicates the background color of the floating box. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Sets a object that indicates the background color of the floating box. |
| [getBackgroundImage()](#getBackgroundImage--) | Gets or sets background image for page (for generator only, not filled in when reading document). |
| [setBackgroundImage(Image value)](#setBackgroundImage-com.aspose.pdf.Image-) | Gets or sets background image for page (for generator only, not filled in when reading document). |
| [getPadding()](#getPadding--) | Gets a object that indicates the padding of the floating box. |
| [setPadding(MarginInfo value)](#setPadding-com.aspose.pdf.MarginInfo-) | Sets a object that indicates the padding of the floating box. |
| [getLeft()](#getLeft--) | Gets the table left coordinate. |
| [setLeft(double value)](#setLeft-double-) | Sets the table left coordinate. |
| [getTop()](#getTop--) | Gets the table top coordinate. |
| [setTop(double value)](#setTop-double-) | Sets the table top coordinate. |
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


Initializes a new instance of the  FloatingBox  class.

### getColumnInfo() {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```


Gets a column info

**Returns:**
[ColumnInfo](../../com.aspose.pdf/columninfo) - ColumnInfo object
### setColumnInfo(ColumnInfo value) {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
```
public void setColumnInfo(ColumnInfo value)
```


Sets a column info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ColumnInfo](../../com.aspose.pdf/columninfo) | ColumnInfo value |

### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets a float value that indicates the width of the floating box.

**Returns:**
double - double value
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets a float value that indicates the width of the floating box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets a float value that indicates the height of the floating box.

**Returns:**
double - value that indicates the height.
### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Sets a float value that indicates the height of the floating box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | value that indicates the height. |

### isNeedRepeating() {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```


Gets a boolean value that indicates whether the paragraph need to be repeated on next page. Default value is true.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows.

**Returns:**
boolean - boolean value
### setNeedRepeating(boolean value) {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```


Sets a boolean value that indicates whether the paragraph need to be repeated on next page. Default value is true.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```


Gets a collection that indicates all paragraphs in the cell.

**Returns:**
[Paragraphs](../../com.aspose.pdf/paragraphs) - collection that indicates all paragraphs.
### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```


Sets a collection that indicates all paragraphs in the cell.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) | collection that indicates all paragraphs. |

### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


Gets a object that indicates the border info of the floating box.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - object that indicates the border info.
### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


Sets a object that indicates the border info of the floating box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | object that indicates the border info. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets a object that indicates the background color of the floating box.

**Returns:**
[Color](../../com.aspose.pdf/color) - object that indicates the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


Sets a object that indicates the background color of the floating box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | object that indicates the background color. |

### getBackgroundImage() {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```


Gets or sets background image for page (for generator only, not filled in when reading document).

**Returns:**
[Image](../../com.aspose.pdf/image) - Image instance
### setBackgroundImage(Image value) {#setBackgroundImage-com.aspose.pdf.Image-}
```
public final void setBackgroundImage(Image value)
```


Gets or sets background image for page (for generator only, not filled in when reading document).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Image](../../com.aspose.pdf/image) | Image instance |

### getPadding() {#getPadding--}
```
public MarginInfo getPadding()
```


Gets a object that indicates the padding of the floating box.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - object that indicates the padding.
### setPadding(MarginInfo value) {#setPadding-com.aspose.pdf.MarginInfo-}
```
public void setPadding(MarginInfo value)
```


Sets a object that indicates the padding of the floating box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | object that indicates the padding. |

### getLeft() {#getLeft--}
```
public double getLeft()
```


Gets the table left coordinate.

**Returns:**
double - table left coordinate.
### setLeft(double value) {#setLeft-double-}
```
public void setLeft(double value)
```


Sets the table left coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | table left coordinate. |

### getTop() {#getTop--}
```
public double getTop()
```


Gets the table top coordinate.

**Returns:**
double - table top coordinate.
### setTop(double value) {#setTop-double-}
```
public void setTop(double value)
```


Sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | table top coordinate. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones a new  FloatingBox  object. Paragraphs in the floating box are not cloned.

**Returns:**
java.lang.Object - The new  FloatingBox  object.

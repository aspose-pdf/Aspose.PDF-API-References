---
title: Cell
second_title: Aspose.PDF for Java API Reference
description: Represents a cell of the tables row.
type: docs
weight: 52
url: /java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public final class Cell implements System.ICloneable
```

Represents a cell of the table's row.
## Constructors

| Constructor | Description |
| --- | --- |
| [Cell(Rectangle rect)](#Cell-com.aspose.pdf.Rectangle-) | Initializes a new instance of the Cell class. |
| [Cell()](#Cell--) | Initializes a new instance of the Cell class. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Clone the cell. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Gets the alignment. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the background color. |
| [getBackgroundImage()](#getBackgroundImage--) | Gets or sets the background image |
| [getBackgroundImageFile()](#getBackgroundImageFile--) | Gets the background image file. |
| [getBorder()](#getBorder--) | Gets the border. |
| [getClass()](#getClass--) |  |
| [getColSpan()](#getColSpan--) | Gets or sets the column span. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Gets the default cell text state. |
| [getMargin()](#getMargin--) | Gets the padding. |
| [getParagraphs()](#getParagraphs--) | Gets the cell's formatted text. |
| [getRowSpan()](#getRowSpan--) | Gets the row span. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets the vertical alignment. |
| [getWidth()](#getWidth--) | Gets the column width. |
| [hashCode()](#hashCode--) |  |
| [isNoBorder()](#isNoBorder--) | Gets the cell have border. |
| [isOverrideByFragment()](#isOverrideByFragment--) | Sets the cell's TextState property is overriden by TextFragment TextState property. |
| [isWordWrapped()](#isWordWrapped--) | Gets the cell's text word wrapped. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Sets the alignment. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Gets or sets the background color. |
| [setBackgroundImage(Image value)](#setBackgroundImage-com.aspose.pdf.Image-) | Gets or sets the background image |
| [setBackgroundImageFile(String value)](#setBackgroundImageFile-java.lang.String-) | Sets the background image file. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Sets the border. |
| [setColSpan(int value)](#setColSpan-int-) | Sets the column span. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Sets the default cell text state. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets the padding. |
| [setNoBorder(boolean value)](#setNoBorder-boolean-) | Sets the cell have border. |
| [setOverrideByFragment(boolean value)](#setOverrideByFragment-boolean-) | Sets the cell's TextState property is overriden by TextFragment TextState property. |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) | Sets the cell's formatted text. |
| [setRowSpan(int value)](#setRowSpan-int-) | Sets the row span. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets the vertical alignment. |
| [setWidth(double value)](#setWidth-double-) | Sets the column width. |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Sets the cell's text word wrapped. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cell(Rectangle rect) {#Cell-com.aspose.pdf.Rectangle-}
```
public Cell(Rectangle rect)
```


Initializes a new instance of the Cell class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The rectangle of the cell in page's coordinates. |

### Cell() {#Cell--}
```
public Cell()
```


Initializes a new instance of the Cell class.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the cell.

**Returns:**
java.lang.Object - The cloned object
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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Gets the alignment.

**Returns:**
int - HorizontalAlignment element
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets the background color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### getBackgroundImage() {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```


Gets or sets the background image

**Returns:**
[Image](../../com.aspose.pdf/image) - Image instance
### getBackgroundImageFile() {#getBackgroundImageFile--}
```
public String getBackgroundImageFile()
```


Gets the background image file.

**Returns:**
java.lang.String - String value
### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


Gets the border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo object
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColSpan() {#getColSpan--}
```
public int getColSpan()
```


Gets or sets the column span.

**Returns:**
int - int value
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```


Gets the default cell text state.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState object
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets the padding.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo object
### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```


Gets the cell's formatted text.

**Returns:**
[Paragraphs](../../com.aspose.pdf/paragraphs) - Paragraphs object
### getRowSpan() {#getRowSpan--}
```
public int getRowSpan()
```


Gets the row span.

**Returns:**
int - int value
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets the vertical alignment.

**Returns:**
int - VerticalAlignment element
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets the column width.

**Returns:**
double - double value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNoBorder() {#isNoBorder--}
```
public boolean isNoBorder()
```


Gets the cell have border.

**Returns:**
boolean - boolean value
### isOverrideByFragment() {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```


Sets the cell's TextState property is overriden by TextFragment TextState property.

**Returns:**
boolean - boolean value
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


Gets the cell's text word wrapped.

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




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Sets the alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment element |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


Gets or sets the background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color object |

### setBackgroundImage(Image value) {#setBackgroundImage-com.aspose.pdf.Image-}
```
public final void setBackgroundImage(Image value)
```


Gets or sets the background image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Image](../../com.aspose.pdf/image) | Image instance |

### setBackgroundImageFile(String value) {#setBackgroundImageFile-java.lang.String-}
```
public void setBackgroundImageFile(String value)
```


Sets the background image file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Color object |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


Sets the border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo object |

### setColSpan(int value) {#setColSpan-int-}
```
public void setColSpan(int value)
```


Sets the column span.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public void setDefaultCellTextState(TextState value)
```


Sets the default cell text state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState object |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Sets the padding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### setNoBorder(boolean value) {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```


Sets the cell have border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setOverrideByFragment(boolean value) {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```


Sets the cell's TextState property is overriden by TextFragment TextState property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```


Sets the cell's formatted text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) | Paragraphs object |

### setRowSpan(int value) {#setRowSpan-int-}
```
public void setRowSpan(int value)
```


Sets the row span.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets the vertical alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets the column width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


Sets the cell's text word wrapped.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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


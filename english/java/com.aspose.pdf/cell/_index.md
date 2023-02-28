---
title: Cell
second_title: Aspose.PDF for Java API Reference
description: Represents a cell of the tables row.
type: docs
weight: 51
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
| [isNoBorder()](#isNoBorder--) | Gets the cell have border. |
| [setNoBorder(boolean value)](#setNoBorder-boolean-) | Sets the cell have border. |
| [getMargin()](#getMargin--) | Gets the padding. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets the padding. |
| [getBorder()](#getBorder--) | Gets the border. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Sets the border. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Gets or sets the background color. |
| [getBackgroundImageFile()](#getBackgroundImageFile--) | Gets the background image file. |
| [setBackgroundImageFile(String value)](#setBackgroundImageFile-java.lang.String-) | Sets the background image file. |
| [getAlignment()](#getAlignment--) | Gets the alignment. |
| [getBackgroundImage()](#getBackgroundImage--) | Gets or sets the background image |
| [setBackgroundImage(Image value)](#setBackgroundImage-com.aspose.pdf.Image-) | Gets or sets the background image |
| [setAlignment(HorizontalAlignment value)](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets the alignment. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Gets the default cell text state. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Sets the default cell text state. |
| [isOverrideByFragment()](#isOverrideByFragment--) | Sets the cell's TextState property is overriden by TextFragment TextState property. |
| [setOverrideByFragment(boolean value)](#setOverrideByFragment-boolean-) | Sets the cell's TextState property is overriden by TextFragment TextState property. |
| [getParagraphs()](#getParagraphs--) | Gets the cell's formatted text. |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) | Sets the cell's formatted text. |
| [isWordWrapped()](#isWordWrapped--) | Gets the cell's text word wrapped. |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Sets the cell's text word wrapped. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets the vertical alignment. |
| [setVerticalAlignment(VerticalAlignment value)](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Sets the vertical alignment. |
| [getColSpan()](#getColSpan--) | Gets or sets the column span. |
| [setColSpan(int value)](#setColSpan-int-) | Sets the column span. |
| [getRowSpan()](#getRowSpan--) | Gets the row span. |
| [setRowSpan(int value)](#setRowSpan-int-) | Sets the row span. |
| [getWidth()](#getWidth--) | Gets the column width. |
| [setWidth(double value)](#setWidth-double-) | Sets the column width. |
| [deepClone()](#deepClone--) | Clone the cell. |
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

### isNoBorder() {#isNoBorder--}
```
public boolean isNoBorder()
```


Gets the cell have border.

**Returns:**
boolean - boolean value
### setNoBorder(boolean value) {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```


Sets the cell have border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets the padding.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo object
### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Sets the padding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


Gets the border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo object
### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


Sets the border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo object |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets the background color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


Gets or sets the background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color object |

### getBackgroundImageFile() {#getBackgroundImageFile--}
```
public String getBackgroundImageFile()
```


Gets the background image file.

**Returns:**
java.lang.String - String value
### setBackgroundImageFile(String value) {#setBackgroundImageFile-java.lang.String-}
```
public void setBackgroundImageFile(String value)
```


Sets the background image file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Color object |

### getAlignment() {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```


Gets the alignment.

**Returns:**
[HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) - HorizontalAlignment element
### getBackgroundImage() {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```


Gets or sets the background image

**Returns:**
[Image](../../com.aspose.pdf/image) - Image instance
### setBackgroundImage(Image value) {#setBackgroundImage-com.aspose.pdf.Image-}
```
public final void setBackgroundImage(Image value)
```


Gets or sets the background image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Image](../../com.aspose.pdf/image) | Image instance |

### setAlignment(HorizontalAlignment value) {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
```
public void setAlignment(HorizontalAlignment value)
```


Sets the alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) | HorizontalAlignment element |

### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```


Gets the default cell text state.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState object
### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public void setDefaultCellTextState(TextState value)
```


Sets the default cell text state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState object |

### isOverrideByFragment() {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```


Sets the cell's TextState property is overriden by TextFragment TextState property.

**Returns:**
boolean - boolean value
### setOverrideByFragment(boolean value) {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```


Sets the cell's TextState property is overriden by TextFragment TextState property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```


Gets the cell's formatted text.

**Returns:**
[Paragraphs](../../com.aspose.pdf/paragraphs) - Paragraphs object
### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```


Sets the cell's formatted text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) | Paragraphs object |

### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


Gets the cell's text word wrapped.

**Returns:**
boolean - boolean value
### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


Sets the cell's text word wrapped.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```


Gets the vertical alignment.

**Returns:**
[VerticalAlignment](../../com.aspose.pdf/verticalalignment) - VerticalAlignment element
### setVerticalAlignment(VerticalAlignment value) {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
```
public void setVerticalAlignment(VerticalAlignment value)
```


Sets the vertical alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VerticalAlignment](../../com.aspose.pdf/verticalalignment) | VerticalAlignment element |

### getColSpan() {#getColSpan--}
```
public int getColSpan()
```


Gets or sets the column span.

**Returns:**
int - int value
### setColSpan(int value) {#setColSpan-int-}
```
public void setColSpan(int value)
```


Sets the column span.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getRowSpan() {#getRowSpan--}
```
public int getRowSpan()
```


Gets the row span.

**Returns:**
int - int value
### setRowSpan(int value) {#setRowSpan-int-}
```
public void setRowSpan(int value)
```


Sets the row span.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets the column width.

**Returns:**
double - double value
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets the column width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the cell.

**Returns:**
java.lang.Object - The cloned object

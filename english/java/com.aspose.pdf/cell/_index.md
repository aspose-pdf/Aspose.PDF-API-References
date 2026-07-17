---
title: Cell
linktitle: Cell
second_title: Aspose.PDF for Java API Reference
description: Represents a cell of the table's row.
type: docs
weight: 510
url: /java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Cell

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Cell extends Object implements com.aspose.ms.System.ICloneable
```

Represents a cell of the table's row.

## Constructors

| Constructor | Description |
| --- | --- |
| [Cell](#Cell--) | Initializes a new instance of the Cell class. |
| [Cell](#Cell-com.aspose.pdf.Rectangle-) | Initializes a new instance of the Cell class. |

## Methods

| Method | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clone the cell. |
| [getAlignment](#getAlignment--) | Gets the alignment. |
| [getBackgroundColor](#getBackgroundColor--) | Gets the background color. |
| [getBackgroundImage](#getBackgroundImage--) | Gets or sets the background image |
| [getBackgroundImageFile](#getBackgroundImageFile--) | Gets the background image file. |
| [getBorder](#getBorder--) | Gets the border. |
| [getColSpan](#getColSpan--) | Gets or sets the column span. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Gets the default cell text state. |
| [getMargin](#getMargin--) | Gets the padding. |
| [getParagraphs](#getParagraphs--) | Gets the cell's formatted text. |
| [getRowSpan](#getRowSpan--) | Gets the row span. |
| [getVerticalAlignment](#getVerticalAlignment--) | Gets the vertical alignment. |
| [getWidth](#getWidth--) | Gets the column width. |
| [isNoBorder](#isNoBorder--) | Gets the cell have border. |
| [isOverrideByFragment](#isOverrideByFragment--) | Sets the cell's TextState property is overriden by TextFragment TextState property. |
| [isWordWrapped](#isWordWrapped--) | Gets the cell's text word wrapped. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets the alignment. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Gets or sets the background color. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Gets or sets the background image |
| [setBackgroundImageFile](#setBackgroundImageFile-java.lang.String-) | Sets the background image file. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Sets the border. |
| [setColSpan](#setColSpan-int-) | Sets the column span. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Sets the default cell text state. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Sets the padding. |
| [setNoBorder](#setNoBorder-boolean-) | Sets the cell have border. |
| [setOverrideByFragment](#setOverrideByFragment-boolean-) | Sets the cell's TextState property is overriden by TextFragment TextState property. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Sets the cell's formatted text. |
| [setRowSpan](#setRowSpan-int-) | Sets the row span. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Sets the vertical alignment. |
| [setWidth](#setWidth-double-) | Sets the column width. |
| [setWordWrapped](#setWordWrapped-boolean-) | Sets the cell's text word wrapped. |

### Cell {#Cell--}
```
public Cell()
```

Initializes a new instance of the Cell class.

### Cell {#Cell-com.aspose.pdf.Rectangle-}
Initializes a new instance of the Cell class.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone the cell.

**Returns:**
The cloned object

### getAlignment {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```

Gets the alignment.

**Returns:**
HorizontalAlignment element @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Gets the background color.

**Returns:**
Color object

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Gets or sets the background image

**Returns:**
Image instance

### getBackgroundImageFile {#getBackgroundImageFile--}
```
@Deprecated public String getBackgroundImageFile()
```

Gets the background image file.

**Returns:**
String value @deprecated Property was expanded please use BackgroundImage

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Gets the border.

**Returns:**
BorderInfo object

### getColSpan {#getColSpan--}
```
public int getColSpan()
```

Gets or sets the column span.

**Returns:**
int value

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Gets the default cell text state.

**Returns:**
TextState object

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Gets the padding.

**Returns:**
MarginInfo object

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Gets the cell's formatted text.

**Returns:**
Paragraphs object

### getRowSpan {#getRowSpan--}
```
public int getRowSpan()
```

Gets the row span.

**Returns:**
int value

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Gets the vertical alignment.

**Returns:**
VerticalAlignment element @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Gets the column width.

**Returns:**
double value

### isNoBorder {#isNoBorder--}
```
public boolean isNoBorder()
```

Gets the cell have border.

**Returns:**
boolean value

### isOverrideByFragment {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```

Sets the cell's TextState property is overriden by TextFragment TextState property.

**Returns:**
boolean value

### isWordWrapped {#isWordWrapped--}
```
public boolean isWordWrapped()
```

Gets the cell's text word wrapped.

**Returns:**
boolean value

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Sets the alignment.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Gets or sets the background color.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Gets or sets the background image

### setBackgroundImageFile {#setBackgroundImageFile-java.lang.String-}
Sets the background image file.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Sets the border.

### setColSpan {#setColSpan-int-}
```
public void setColSpan(int value)
```

Sets the column span.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Sets the default cell text state.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Sets the padding.

### setNoBorder {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```

Sets the cell have border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setOverrideByFragment {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```

Sets the cell's TextState property is overriden by TextFragment TextState property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Sets the cell's formatted text.

### setRowSpan {#setRowSpan-int-}
```
public void setRowSpan(int value)
```

Sets the row span.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Sets the vertical alignment.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Sets the column width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setWordWrapped {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```

Sets the cell's text word wrapped.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

---
title: Row
second_title: Aspose.PDF for Java API Reference
description: Represents a row of the table.
type: docs
weight: 320
url: /java/com.aspose.pdf/row/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public final class Row implements System.ICloneable
```

Represents a row of the table.
## Constructors

| Constructor | Description |
| --- | --- |
| [Row()](#Row--) | Initializes a new instance of the Row class. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Clone the row. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Sets the background color. |
| [getBorder()](#getBorder--) | Gets the border. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Sets the border. |
| [getCells()](#getCells--) | Gets the getCells() of the row. |
| [setCells(Cells value)](#setCells-com.aspose.pdf.Cells-) | Sets the getCells() of the row. |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | Gets default cell border; |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Sets default cell border; |
| [getMinRowHeight()](#getMinRowHeight--) | Gets height for row; |
| [setMinRowHeight(double value)](#setMinRowHeight-double-) | Sets height for row; |
| [getFixedRowHeight()](#getFixedRowHeight--) | Gets fixed row height - row may have fixed height; |
| [setFixedRowHeight(double value)](#setFixedRowHeight-double-) | Sets fixed row height - row may have fixed height; |
| [isInNewPage()](#isInNewPage--) | Gets fixed row is in new page - page with this property should be printed to next page Default false; |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Sets is row can be broken between two pages |
| [isRowBroken()](#isRowBroken--) | Gets is row can be broken between two pages |
| [setRowBroken(boolean value)](#setRowBroken-boolean-) | Sets is row can be broken between two pages |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Gets or sets default text state for row getCells() |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Sets default text state for row getCells() |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | Gets default margin for row getCells() |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Sets default margin for row getCells() |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets or sets the vertical alignment. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Gets or sets the vertical alignment. |
### Row() {#Row--}
```
public Row()
```


Initializes a new instance of the Row class.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the row.

**Returns:**
java.lang.Object - The cloned object
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets the background color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color value
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


Sets the background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color value |

### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


Gets the border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo value
### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


Sets the border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo value |

### getCells() {#getCells--}
```
public Cells getCells()
```


Gets the getCells() of the row.

**Returns:**
[Cells](../../com.aspose.pdf/cells) - getCells() value
### setCells(Cells value) {#setCells-com.aspose.pdf.Cells-}
```
public void setCells(Cells value)
```


Sets the getCells() of the row.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Cells](../../com.aspose.pdf/cells) | getCells() value |

### getDefaultCellBorder() {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```


Gets default cell border;

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo value
### setDefaultCellBorder(BorderInfo value) {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
```
public void setDefaultCellBorder(BorderInfo value)
```


Sets default cell border;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo value |

### getMinRowHeight() {#getMinRowHeight--}
```
public double getMinRowHeight()
```


Gets height for row;

**Returns:**
double - double value
### setMinRowHeight(double value) {#setMinRowHeight-double-}
```
public void setMinRowHeight(double value)
```


Sets height for row;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getFixedRowHeight() {#getFixedRowHeight--}
```
public double getFixedRowHeight()
```


Gets fixed row height - row may have fixed height;

**Returns:**
double - double value
### setFixedRowHeight(double value) {#setFixedRowHeight-double-}
```
public void setFixedRowHeight(double value)
```


Sets fixed row height - row may have fixed height;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Gets fixed row is in new page - page with this property should be printed to next page Default false;

**Returns:**
boolean - boolean value
### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Sets is row can be broken between two pages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isRowBroken() {#isRowBroken--}
```
public boolean isRowBroken()
```


Gets is row can be broken between two pages

**Returns:**
boolean - boolean value
### setRowBroken(boolean value) {#setRowBroken-boolean-}
```
public void setRowBroken(boolean value)
```


Sets is row can be broken between two pages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```


Gets or sets default text state for row getCells()

Gets default text state for row getCells()

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState value
### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public void setDefaultCellTextState(TextState value)
```


Sets default text state for row getCells()

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState value |

### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```


Gets default margin for row getCells()

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo value
### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public void setDefaultCellPadding(MarginInfo value)
```


Sets default margin for row getCells()

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo value |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets or sets the vertical alignment.

**Returns:**
int - VerticalAlignment element
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Gets or sets the vertical alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |


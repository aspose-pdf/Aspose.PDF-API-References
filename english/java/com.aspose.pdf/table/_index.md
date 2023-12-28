---
title: Table
second_title: Aspose.PDF for Java API Reference
description: Represents a table that can be added to the page.
type: docs
weight: 356
url: /java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public final class Table extends BaseParagraph
```

Represents a table that can be added to the page.
## Constructors

| Constructor | Description |
| --- | --- |
| [Table()](#Table--) | Default ctor |
## Methods

| Method | Description |
| --- | --- |
| [getBackgroundColor()](#getBackgroundColor--) | Gets table background color |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Sets table background color |
| [getBreakText()](#getBreakText--) | Gets break text for table |
| [setBreakText(TextFragment value)](#setBreakText-com.aspose.pdf.TextFragment-) | Sets break text for table |
| [getCornerStyle()](#getCornerStyle--) | Gets the styles of the border corners |
| [setCornerStyle(int value)](#setCornerStyle-int-) | Gets or sets the styles of the border corners |
| [getRepeatingRowsStyle()](#getRepeatingRowsStyle--) | Gets the style for repeating rows |
| [setRepeatingRowsStyle(TextState value)](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Gets the style for repeating rows |
| [getRepeatingColumnsCount()](#getRepeatingColumnsCount--) | Gets or sets the maximum columns count for table |
| [setRepeatingColumnsCount(int value)](#setRepeatingColumnsCount-int-) | Gets or sets the maximum columns count for table |
| [getRepeatingRowsCount()](#getRepeatingRowsCount--) | Gets the first rows count repeated for several pages |
| [setRepeatingRowsCount(int value)](#setRepeatingRowsCount-int-) | Gets the first rows count repeated for several pages |
| [getColumnWidths()](#getColumnWidths--) | Gets the column widths of the table. |
| [setColumnWidths(String value)](#setColumnWidths-java.lang.String-) | Gets the column widths of the table. |
| [getBroken()](#getBroken--) | Gets or sets table vertial broken; |
| [setBroken(int value)](#setBroken-int-) | Gets or sets table vertial broken; |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | Gets default cell border; |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Gets default cell border; |
| [getDefaultColumnWidth()](#getDefaultColumnWidth--) | Gets default cell border; |
| [setDefaultColumnWidth(String value)](#setDefaultColumnWidth-java.lang.String-) | Gets default cell border; |
| [getRows()](#getRows--) | Gets the rows of the table. |
| [getBorder()](#getBorder--) | Gets the border. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Sets the border. |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | Gets the default cell padding. |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Sets the default cell padding. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Gets the default cell text state. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Sets the default cell text state. |
| [getAlignment()](#getAlignment--) | Gets the table alignment. |
| [setAlignment(HorizontalAlignment value)](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets the table alignment. |
| [getLeft()](#getLeft--) | Gets the table left coordinate. |
| [setLeft(float value)](#setLeft-float-) | Sets the table left coordinate. |
| [getTop()](#getTop--) | Gets the table top coordinate. |
| [setTop(float value)](#setTop-float-) | Sets the table top coordinate. |
| [isBroken()](#isBroken--) | Gets the table is broken - will be truncated for next page. |
| [setBroken(boolean value)](#setBroken-boolean-) | Sets the table is broken - will be truncated for next page. |
| [isBordersIncluded()](#isBordersIncluded--) | Gets border included in column widths. |
| [setBordersIncluded(boolean value)](#setBordersIncluded-boolean-) | Sets border included in column widths. |
| [getColumnAdjustment()](#getColumnAdjustment--) | Gets the table column adjustment. |
| [setColumnAdjustment(int value)](#setColumnAdjustment-int-) | Sets the table column adjustment. |
| [drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius)](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-com.aspose.pdf.Operator--double-) | Add operators for rectangle. |
| [getColumnWidth(String stringColumnWidth)](#getColumnWidth-java.lang.String-) | Get column width |
| [getWidth()](#getWidth--) | Get width. |
| [getHeight()](#getHeight--) | Get height. |
| [getHeight(Page parentPage)](#getHeight-com.aspose.pdf.Page-) | Get height. |
| [setColumnTextState(int colNumber, TextState textState)](#setColumnTextState-int-com.aspose.pdf.TextState-) | Set height. |
| [deepClone()](#deepClone--) | Clone the table. |
### Table() {#Table--}
```
public Table()
```


Default ctor

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Gets table background color

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


Sets table background color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color object |

### getBreakText() {#getBreakText--}
```
public final TextFragment getBreakText()
```


Gets break text for table

**Returns:**
[TextFragment](../../com.aspose.pdf/textfragment) - TextFragment object
### setBreakText(TextFragment value) {#setBreakText-com.aspose.pdf.TextFragment-}
```
public final void setBreakText(TextFragment value)
```


Sets break text for table

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | TextFragment object |

### getCornerStyle() {#getCornerStyle--}
```
public final int getCornerStyle()
```


Gets the styles of the border corners

**Returns:**
int - BorderCornerStyle value
### setCornerStyle(int value) {#setCornerStyle-int-}
```
public final void setCornerStyle(int value)
```


Gets or sets the styles of the border corners

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | BorderCornerStyle value |

### getRepeatingRowsStyle() {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```


Gets the style for repeating rows

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState object
### setRepeatingRowsStyle(TextState value) {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
```
public final void setRepeatingRowsStyle(TextState value)
```


Gets the style for repeating rows

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState object |

### getRepeatingColumnsCount() {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```


Gets or sets the maximum columns count for table

**Returns:**
int - int value
### setRepeatingColumnsCount(int value) {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```


Gets or sets the maximum columns count for table

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getRepeatingRowsCount() {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```


Gets the first rows count repeated for several pages

**Returns:**
int - int value
### setRepeatingRowsCount(int value) {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```


Gets the first rows count repeated for several pages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getColumnWidths() {#getColumnWidths--}
```
public final String getColumnWidths()
```


Gets the column widths of the table.

**Returns:**
java.lang.String - String value
### setColumnWidths(String value) {#setColumnWidths-java.lang.String-}
```
public final void setColumnWidths(String value)
```


Gets the column widths of the table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getBroken() {#getBroken--}
```
public final int getBroken()
```


Gets or sets table vertial broken;

**Returns:**
int - TableBroken value
### setBroken(int value) {#setBroken-int-}
```
public final void setBroken(int value)
```


Gets or sets table vertial broken;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TableBroken value |

### getDefaultCellBorder() {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```


Gets default cell border;

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo object
### setDefaultCellBorder(BorderInfo value) {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
```
public final void setDefaultCellBorder(BorderInfo value)
```


Gets default cell border;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo object |

### getDefaultColumnWidth() {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```


Gets default cell border;

**Returns:**
java.lang.String - String object
### setDefaultColumnWidth(String value) {#setDefaultColumnWidth-java.lang.String-}
```
public final void setDefaultColumnWidth(String value)
```


Gets default cell border;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### getRows() {#getRows--}
```
public final Rows getRows()
```


Gets the rows of the table.

**Returns:**
[Rows](../../com.aspose.pdf/rows) - Rows object
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


Gets the border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo object
### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


Sets the border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo object |

### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```


Gets the default cell padding.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo object
### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public final void setDefaultCellPadding(MarginInfo value)
```


Sets the default cell padding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


Gets the default cell text state.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState value
### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


Sets the default cell text state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState value |

### getAlignment() {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```


Gets the table alignment.

**Returns:**
[HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) - HorizontalAlignment value
### setAlignment(HorizontalAlignment value) {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
```
public final void setAlignment(HorizontalAlignment value)
```


Sets the table alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) | HorizontalAlignment value |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


Gets the table left coordinate.

**Returns:**
float - float value
### setLeft(float value) {#setLeft-float-}
```
public final void setLeft(float value)
```


Sets the table left coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getTop() {#getTop--}
```
public final float getTop()
```


Gets the table top coordinate.

**Returns:**
float - float value
### setTop(float value) {#setTop-float-}
```
public final void setTop(float value)
```


Sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### isBroken() {#isBroken--}
```
public final boolean isBroken()
```


Gets the table is broken - will be truncated for next page.

**Returns:**
boolean - boolean value
### setBroken(boolean value) {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```


Sets the table is broken - will be truncated for next page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isBordersIncluded() {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```


Gets border included in column widths.

**Returns:**
boolean - boolean value
### setBordersIncluded(boolean value) {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```


Sets border included in column widths.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getColumnAdjustment() {#getColumnAdjustment--}
```
public final int getColumnAdjustment()
```


Gets the table column adjustment.

**Returns:**
int - ColumnAdjustment value
### setColumnAdjustment(int value) {#setColumnAdjustment-int-}
```
public final void setColumnAdjustment(int value)
```


Sets the table column adjustment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ColumnAdjustment value |

### drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius) {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-com.aspose.pdf.Operator--double-}
```
public static void drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius)
```


Add operators for rectangle.

For internal usage only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| info | [GraphInfo](../../com.aspose.pdf/graphinfo) | The border style. |
| topLeft | [Point](../../com.aspose.pdf/point) | The left top point. |
| rightBottom | [Point](../../com.aspose.pdf/point) | The right bottom point. |
| operators | java.util.List<com.aspose.pdf.Operator> | The operators list to be added into the page's content. |
| radius | double | The border radius. |

### getColumnWidth(String stringColumnWidth) {#getColumnWidth-java.lang.String-}
```
public static double getColumnWidth(String stringColumnWidth)
```


Get column width

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stringColumnWidth | java.lang.String | The string representation. |

**Returns:**
double - double value
### getWidth() {#getWidth--}
```
public double getWidth()
```


Get width.

**Returns:**
double - The table width
### getHeight() {#getHeight--}
```
public double getHeight()
```


Get height.

**Returns:**
double - The table height
### getHeight(Page parentPage) {#getHeight-com.aspose.pdf.Page-}
```
public double getHeight(Page parentPage)
```


Get height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentPage | [Page](../../com.aspose.pdf/page) | The table's parent page |

**Returns:**
double - The table height
### setColumnTextState(int colNumber, TextState textState) {#setColumnTextState-int-com.aspose.pdf.TextState-}
```
public void setColumnTextState(int colNumber, TextState textState)
```


Set height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colNumber | int | The column number. |
| textState | [TextState](../../com.aspose.pdf/textstate) | The text state for column. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the table.

**Returns:**
java.lang.Object - The cloned object

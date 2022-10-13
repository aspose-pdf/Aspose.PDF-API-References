---
title: Table
second_title: Aspose.PDF for Java API Reference
description: Represents a table that can be added to the page.
type: docs
weight: 283
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
| [drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius)](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-com.aspose.pdf.Operator--double-) | Add operators for rectangle. |
| [getColumnWidth(String stringColumnWidth)](#getColumnWidth-java.lang.String-) | Get column width |
| [getWidth_()](#getWidth---) | Get width. |
| [getHeight()](#getHeight--) | Get height. |
| [setColumnTextState(int colNumber, TextState textState)](#setColumnTextState-int-com.aspose.pdf.TextState-) | Set height. |
| [deepClone()](#deepClone--) | Clone the table. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets or sets table background color |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Sets or sets table background color |
| [getBreakText()](#getBreakText--) | Gets break text for table |
| [setBreakText(TextFragment value)](#setBreakText-com.aspose.pdf.TextFragment-) | Sets break text for table |
| [getCornerStyle()](#getCornerStyle--) | Gets the styles of the border corners |
| [setCornerStyle(int value)](#setCornerStyle-int-) | Sets the styles of the border corners |
| [getRepeatingRowsStyle()](#getRepeatingRowsStyle--) | Gets the style for repeating rows |
| [setRepeatingRowsStyle(TextState value)](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Sets the style for repeating rows |
| [getRepeatingRowsCount()](#getRepeatingRowsCount--) | Gets the first rows count repeated for several pages |
| [setRepeatingRowsCount(int value)](#setRepeatingRowsCount-int-) | Sets the first rows count repeated for several pages |
| [getColumnWidths()](#getColumnWidths--) | Gets the column widths of the table. |
| [setColumnWidths(String value)](#setColumnWidths-java.lang.String-) | Sets the column widths of the table. |
| [getBroken()](#getBroken--) | Gets table vertial broken.; |
| [setBroken(int value)](#setBroken-int-) | Sets table vertial broken.; |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | Gets default cell border; |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Sets default cell border; |
| [getDefaultColumnWidth()](#getDefaultColumnWidth--) | Gets default cell border; |
| [setDefaultColumnWidth(String value)](#setDefaultColumnWidth-java.lang.String-) | Sets default cell border; |
| [getRows()](#getRows--) | Gets the rows of the table. |
| [getBorder()](#getBorder--) | Gets the border. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Sets the border. |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | Gets the default cell padding. |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Sets the default cell padding. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Gets the default cell text state. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Sets the default cell text state. |
| [getAlignment()](#getAlignment--) | Gets the table alignment. |
| [setAlignment(int value)](#setAlignment-int-) | Sets the table alignment. |
| [getLeft()](#getLeft--) | Gets the table left coordinate. |
| [setLeft(float value)](#setLeft-float-) | Sets the table left coordinate. |
| [getTop()](#getTop--) | Gets the table top coordinate. |
| [setTop(float value)](#setTop-float-) | Sets the table top coordinate. |
| [isBroken()](#isBroken--) | Gets the table is broken - will be truncated for next page. |
| [setBroken(boolean value)](#setBroken-boolean-) | Sets the table is broken - will be truncated for next page. |
| [isBordersIncluded()](#isBordersIncluded--) | Gets or sets border included in column widths. |
| [setBordersIncluded(boolean value)](#setBordersIncluded-boolean-) | Gets or sets border included in column widths. |
| [getColumnAdjustment()](#getColumnAdjustment--) | Gets the table column adjustment. |
| [setColumnAdjustment(int value)](#setColumnAdjustment-int-) | Sets the table column adjustment. |
| [getParentTable()](#getParentTable--) | Gets or sets the parent table. |
| [setParentTable(Table value)](#setParentTable-com.aspose.pdf.Table-) | Gets or sets the parent table. |
### Table() {#Table--}
```
public Table()
```


Default ctor

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
### getWidth_() {#getWidth---}
```
public double getWidth_()
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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets or sets table background color

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


Sets or sets table background color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color object |

### getBreakText() {#getBreakText--}
```
public TextFragment getBreakText()
```


Gets break text for table

**Returns:**
[TextFragment](../../com.aspose.pdf/textfragment) - TextFragment object
### setBreakText(TextFragment value) {#setBreakText-com.aspose.pdf.TextFragment-}
```
public void setBreakText(TextFragment value)
```


Sets break text for table

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | TextFragment object |

### getCornerStyle() {#getCornerStyle--}
```
public int getCornerStyle()
```


Gets the styles of the border corners

**Returns:**
int - BorderCornerStyle value
### setCornerStyle(int value) {#setCornerStyle-int-}
```
public void setCornerStyle(int value)
```


Sets the styles of the border corners

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | BorderCornerStyle value |

### getRepeatingRowsStyle() {#getRepeatingRowsStyle--}
```
public TextState getRepeatingRowsStyle()
```


Gets the style for repeating rows

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState object
### setRepeatingRowsStyle(TextState value) {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
```
public void setRepeatingRowsStyle(TextState value)
```


Sets the style for repeating rows

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState object |

### getRepeatingRowsCount() {#getRepeatingRowsCount--}
```
public int getRepeatingRowsCount()
```


Gets the first rows count repeated for several pages

**Returns:**
int - int value
### setRepeatingRowsCount(int value) {#setRepeatingRowsCount-int-}
```
public void setRepeatingRowsCount(int value)
```


Sets the first rows count repeated for several pages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getColumnWidths() {#getColumnWidths--}
```
public String getColumnWidths()
```


Gets the column widths of the table.

**Returns:**
java.lang.String - String value
### setColumnWidths(String value) {#setColumnWidths-java.lang.String-}
```
public void setColumnWidths(String value)
```


Sets the column widths of the table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getBroken() {#getBroken--}
```
public int getBroken()
```


Gets table vertial broken.;

**Returns:**
int - TableBroken value
### setBroken(int value) {#setBroken-int-}
```
public void setBroken(int value)
```


Sets table vertial broken.;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TableBroken value |

### getDefaultCellBorder() {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```


Gets default cell border;

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo object
### setDefaultCellBorder(BorderInfo value) {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
```
public void setDefaultCellBorder(BorderInfo value)
```


Sets default cell border;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo object |

### getDefaultColumnWidth() {#getDefaultColumnWidth--}
```
public String getDefaultColumnWidth()
```


Gets default cell border;

**Returns:**
java.lang.String - String object
### setDefaultColumnWidth(String value) {#setDefaultColumnWidth-java.lang.String-}
```
public void setDefaultColumnWidth(String value)
```


Sets default cell border;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### getRows() {#getRows--}
```
public Rows getRows()
```


Gets the rows of the table.

**Returns:**
[Rows](../../com.aspose.pdf/rows) - Rows object
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

### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```


Gets the default cell padding.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo object
### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public void setDefaultCellPadding(MarginInfo value)
```


Sets the default cell padding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```


Gets the default cell text state.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState value
### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public void setDefaultCellTextState(TextState value)
```


Sets the default cell text state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState value |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Gets the table alignment.

**Returns:**
int - HorizontalAlignment value
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Sets the table alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### getLeft() {#getLeft--}
```
public float getLeft()
```


Gets the table left coordinate.

**Returns:**
float - float value
### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Sets the table left coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getTop() {#getTop--}
```
public float getTop()
```


Gets the table top coordinate.

**Returns:**
float - float value
### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### isBroken() {#isBroken--}
```
public boolean isBroken()
```


Gets the table is broken - will be truncated for next page.

**Returns:**
boolean - boolean value
### setBroken(boolean value) {#setBroken-boolean-}
```
public void setBroken(boolean value)
```


Sets the table is broken - will be truncated for next page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isBordersIncluded() {#isBordersIncluded--}
```
public boolean isBordersIncluded()
```


Gets or sets border included in column widths.

**Returns:**
boolean - boolean value
### setBordersIncluded(boolean value) {#setBordersIncluded-boolean-}
```
public void setBordersIncluded(boolean value)
```


Gets or sets border included in column widths.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getColumnAdjustment() {#getColumnAdjustment--}
```
public int getColumnAdjustment()
```


Gets the table column adjustment.

**Returns:**
int - ColumnAdjustment value
### setColumnAdjustment(int value) {#setColumnAdjustment-int-}
```
public void setColumnAdjustment(int value)
```


Sets the table column adjustment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ColumnAdjustment value |

### getParentTable() {#getParentTable--}
```
public Table getParentTable()
```


Gets or sets the parent table.

**Returns:**
[Table](../../com.aspose.pdf/table) - Table object
### setParentTable(Table value) {#setParentTable-com.aspose.pdf.Table-}
```
public void setParentTable(Table value)
```


Gets or sets the parent table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Table](../../com.aspose.pdf/table) | Table object |


---
title: Table
linktitle: Table
second_title: Aspose.PDF for Java API Reference
description: Represents a table that can be added to the page.
type: docs
weight: 4790
url: /java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Table, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Table

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Table extends BaseParagraph
```

Represents a table that can be added to the page.

## Constructors

| Constructor | Description |
| --- | --- |
| [Table](#Table--) | Default ctor |

## Methods

| Method | Description |
| --- | --- |
| [deepClone](#deepClone--) | / * / * Imports one-dimensional array of data into table. Import goes one cell per each array's item and / * starts from row and column defined in parameters. During import, if detected that necessary rows / * are still absent(i.e. target table is too small to absorb all data), necessary rows will be created / * / * |
| [drawRoundedRectangle](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-) | Add operators for rectangle. |
| [getAlignment](#getAlignment--) | Gets the table alignment. |
| [getBackgroundColor](#getBackgroundColor--) | Gets table background color |
| [getBorder](#getBorder--) | Gets the border. |
| [getBreakText](#getBreakText--) | Gets break text for table |
| [getBroken](#getBroken--) | Gets or sets table vertial broken; |
| [getColumnAdjustment](#getColumnAdjustment--) | Gets the table column adjustment. |
| [getColumnWidth](#getColumnWidth-java.lang.String-) | Get column width |
| [getColumnWidths](#getColumnWidths--) | Gets the column widths of the table. |
| [getCornerStyle](#getCornerStyle--) | Gets the styles of the border corners |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Gets default cell border; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Gets the default cell padding. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Gets the default cell text state. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Gets default cell border; |
| [getHeight](#getHeight--) | Get height. |
| [getHeight](#getHeight-com.aspose.pdf.Page-) | Get height. |
| [getLeft](#getLeft--) | Gets the table left coordinate. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Gets or sets the maximum columns count for table |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Gets the first rows count repeated for several pages |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Gets the style for repeating rows |
| [getRows](#getRows--) | Gets the rows of the table. |
| [getTop](#getTop--) | Gets the table top coordinate. |
| [getWidth](#getWidth--) | Get width. |
| [isBordersIncluded](#isBordersIncluded--) | Gets border included in column widths. |
| [isBroken](#isBroken--) | Gets the table is broken - will be truncated for next page. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets the table alignment. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Sets table background color |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Sets the border. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Sets border included in column widths. |
| [setBreakText](#setBreakText-com.aspose.pdf.TextFragment-) | Sets break text for table |
| [setBroken](#setBroken-boolean-) | Sets the table is broken - will be truncated for next page. |
| [setBroken](#setBroken-int-) | Gets or sets table vertial broken; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Sets the table column adjustment. |
| [setColumnTextState](#setColumnTextState-int-com.aspose.pdf.TextState-) | Set height. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Gets the column widths of the table. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Gets or sets the styles of the border corners |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Gets default cell border; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Sets the default cell padding. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Sets the default cell text state. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Gets default cell border; |
| [setLeft](#setLeft-float-) | Sets the table left coordinate. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Gets or sets the maximum columns count for table |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Gets the first rows count repeated for several pages |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Gets the style for repeating rows |
| [setTop](#setTop-float-) | Sets the table top coordinate. |

### Table {#Table--}
```
public Table()
```

Default ctor

### deepClone {#deepClone--}
```
public Object deepClone()
```

/ * / * Imports one-dimensional array of data into table. Import goes one cell per each array's item and / * starts from row and column defined in parameters. During import, if detected that necessary rows / * are still absent(i.e. target table is too small to absorb all data), necessary rows will be created / * / *

**Returns:**
The cloned object

### drawRoundedRectangle {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-}
Add operators for rectangle.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Gets the table alignment.

**Returns:**
HorizontalAlignment value @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Gets table background color

**Returns:**
Color object

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Gets the border.

**Returns:**
BorderInfo object

### getBreakText {#getBreakText--}
```
public final TextFragment getBreakText()
```

Gets break text for table

**Returns:**
TextFragment object

### getBroken {#getBroken--}
```
public final int getBroken()
```

Gets or sets table vertial broken;

**Returns:**
TableBroken value @see TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Gets the table column adjustment.

**Returns:**
ColumnAdjustment value @see ColumnAdjustment

### getColumnWidth {#getColumnWidth-java.lang.String-}
Get column width

### getColumnWidths {#getColumnWidths--}
```
public final String getColumnWidths()
```

Gets the column widths of the table.

**Returns:**
String value

### getCornerStyle {#getCornerStyle--}
```
public final BorderCornerStyle getCornerStyle()
```

Gets the styles of the border corners

**Returns:**
BorderCornerStyle value @see BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Gets default cell border;

**Returns:**
BorderInfo object

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Gets the default cell padding.

**Returns:**
MarginInfo object

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Gets the default cell text state.

**Returns:**
TextState value

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Gets default cell border;

**Returns:**
String object

### getHeight {#getHeight--}
```
public double getHeight()
```

Get height.

**Returns:**
The table height

### getHeight {#getHeight-com.aspose.pdf.Page-}
Get height.

**Returns:**
The table height

### getLeft {#getLeft--}
```
public final float getLeft()
```

Gets the table left coordinate.

**Returns:**
float value

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Gets or sets the maximum columns count for table

**Returns:**
int value

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Gets the first rows count repeated for several pages

**Returns:**
int value

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Gets the style for repeating rows

**Returns:**
TextState object

### getRows {#getRows--}
```
public final Rows getRows()
```

Gets the rows of the table.

**Returns:**
Rows object

### getTop {#getTop--}
```
public final float getTop()
```

Gets the table top coordinate.

**Returns:**
float value

### getWidth {#getWidth--}
```
public double getWidth()
```

Get width.

**Returns:**
The table width

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Gets border included in column widths.

**Returns:**
boolean value

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Gets the table is broken - will be truncated for next page.

**Returns:**
boolean value

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Sets the table alignment.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Sets table background color

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Sets the border.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Sets border included in column widths.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setBreakText {#setBreakText-com.aspose.pdf.TextFragment-}
Sets break text for table

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Sets the table is broken - will be truncated for next page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Gets or sets table vertial broken;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | TableBroken value @see TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Sets the table column adjustment.

### setColumnTextState {#setColumnTextState-int-com.aspose.pdf.TextState-}
Set height.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Gets the column widths of the table.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Gets or sets the styles of the border corners

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Gets default cell border;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Sets the default cell padding.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Sets the default cell text state.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Gets default cell border;

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Sets the table left coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Gets or sets the maximum columns count for table

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Gets the first rows count repeated for several pages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Gets the style for repeating rows

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

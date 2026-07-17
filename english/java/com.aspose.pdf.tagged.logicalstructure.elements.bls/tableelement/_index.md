---
title: TableElement
linktitle: TableElement
second_title: Aspose.PDF for Java API Reference
description: Represents Table structure element in logical structure.
type: docs
weight: 170
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement

**All Implemented Interfaces:**
IAdjustPosition

```
public final class TableElement extends BLSElement implements IAdjustPosition
```

Represents Table structure element in logical structure.

## Constructors

| Constructor | Description |
| --- | --- |
| [TableElement](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | constructor for internal usage only |

## Methods

| Method | Description |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Adjust position. |
| [createTBody](#createTBody--) | Creates {@link TableTHeadElement} and added it to current table. |
| [createTFoot](#createTFoot--) | Creates {@link TableTFootElement} and added it to current table. |
| [createTHead](#createTHead--) | Creates {@link TableTHeadElement} and added it to current table. |
| [getAlignment](#getAlignment--) | Gets or sets the table alignment. |
| [getBackgroundColor](#getBackgroundColor--) | Gets or sets the table background color. |
| [getBorder](#getBorder--) | Gets or sets the table border. |
| [getBroken](#getBroken--) | Gets or sets table vertical broken; |
| [getColumnAdjustment](#getColumnAdjustment--) | Gets or sets the table column adjustment. |
| [getColumnWidths](#getColumnWidths--) | Gets the column widths of the table. |
| [getCornerStyle](#getCornerStyle--) | Gets or sets the styles of the border corners |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Gets default cell border. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Gets or sets the default cell padding. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Gets or sets the default cell text state. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Gets or sets default column width. |
| [getLeft](#getLeft--) | Gets or sets the table left coordinate. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Gets or sets the maximum columns count for table. |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Gets the first rows count repeated for several pages. |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Gets the style for repeating rows. |
| [getTable](#getTable--) |  |
| [getTop](#getTop--) | Gets or sets the table top coordinate. |
| [isBordersIncluded](#isBordersIncluded--) | Gets or sets border included in column widhts. |
| [isBroken](#isBroken--) | Gets or sets the table is broken - will be truncated for next page. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Gets or sets the table alignment. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Gets or sets the table background color. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Gets or sets the table border. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Gets or sets border included in column widhts. |
| [setBroken](#setBroken-boolean-) | Gets or sets the table is broken - will be truncated for next page. |
| [setBroken](#setBroken-int-) | Gets or sets table vertical broken; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Gets or sets the table column adjustment. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Gets the column widths of the table. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Gets or sets the styles of the border corners |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Gets default cell border. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Gets or sets the default cell padding. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Gets or sets the default cell text state. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Gets or sets default column width. |
| [setLeft](#setLeft-float-) | Gets or sets the table left coordinate. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Gets or sets the maximum columns count for table. |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Gets the first rows count repeated for several pages. |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Gets the style for repeating rows. |
| [setTop](#setTop-float-) | Gets or sets the table top coordinate. |

### TableElement {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
constructor for internal usage only

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Adjust position.

### createTBody {#createTBody--}
```
public final TableTBodyElement createTBody()
```

Creates {@link TableTHeadElement} and added it to current table.

**Returns:**
Created structure element.

### createTFoot {#createTFoot--}
```
public final TableTFootElement createTFoot()
```

Creates {@link TableTFootElement} and added it to current table.

**Returns:**
Created structure element.

### createTHead {#createTHead--}
```
public final TableTHeadElement createTHead()
```

Creates {@link TableTHeadElement} and added it to current table.

**Returns:**
Created structure element.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Gets or sets the table alignment.

**Returns:**
HorizontalAlignment element

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Gets or sets the table background color.

**Returns:**
Color instance

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Gets or sets the table border.

**Returns:**
BorderInfo instance

### getBroken {#getBroken--}
```
public final int getBroken()
```

Gets or sets table vertical broken;

**Returns:**
TableBroken element

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Gets or sets the table column adjustment.

**Returns:**
ColumnAdjustment element

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

Gets or sets the styles of the border corners

**Returns:**
BorderCornerStyle element

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Gets default cell border.

**Returns:**
BorderInfo instance

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Gets or sets the default cell padding.

**Returns:**
MarginInfo instance

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Gets or sets the default cell text state.

**Returns:**
TextState instance

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Gets or sets default column width.

**Returns:**
String value

### getLeft {#getLeft--}
```
public final float getLeft()
```

Gets or sets the table left coordinate.

**Returns:**
float value

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Gets or sets the maximum columns count for table.

**Returns:**
int value

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Gets the first rows count repeated for several pages.

**Returns:**
int value

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Gets the style for repeating rows.

**Returns:**
TextState instance

### getTable {#getTable--}
```
public final Table getTable()
```



### getTop {#getTop--}
```
public final float getTop()
```

Gets or sets the table top coordinate.

**Returns:**
float value

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Gets or sets border included in column widhts.

**Returns:**
boolean value

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Gets or sets the table is broken - will be truncated for next page.

**Returns:**
boolean value

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Gets or sets the table alignment.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Gets or sets the table background color.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Gets or sets the table border.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Gets or sets border included in column widhts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Gets or sets the table is broken - will be truncated for next page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Gets or sets table vertical broken;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | TableBroken element |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Gets or sets the table column adjustment.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Gets the column widths of the table.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Gets or sets the styles of the border corners

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Gets default cell border.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Gets or sets the default cell padding.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Gets or sets the default cell text state.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Gets or sets default column width.

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Gets or sets the table left coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Gets or sets the maximum columns count for table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Gets the first rows count repeated for several pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Gets the style for repeating rows.

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Gets or sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

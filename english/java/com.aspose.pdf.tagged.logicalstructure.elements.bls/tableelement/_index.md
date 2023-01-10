---
title: TableElement
second_title: Aspose.PDF for Java API Reference
description: Represents Table structure element in logical structure.
type: docs
weight: 21
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/blselement)
```
public final class TableElement extends BLSElement
```

Represents Table structure element in logical structure.
## Constructors

| Constructor | Description |
| --- | --- |
| [TableElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | constructor for internal usage only |
## Methods

| Method | Description |
| --- | --- |
| [getTable()](#getTable--) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Gets or sets the table background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Gets or sets the table background color. |
| [getBorder()](#getBorder--) | Gets or sets the table border. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Gets or sets the table border. |
| [getAlignment()](#getAlignment--) | Gets or sets the table alignment. |
| [setAlignment(int value)](#setAlignment-int-) | Gets or sets the table alignment. |
| [getCornerStyle()](#getCornerStyle--) | Gets or sets the styles of the border corners |
| [setCornerStyle(int value)](#setCornerStyle-int-) | Gets or sets the styles of the border corners |
| [getBroken()](#getBroken--) | Gets or sets table vertical broken; |
| [setBroken(int value)](#setBroken-int-) | Gets or sets table vertical broken; |
| [getColumnAdjustment()](#getColumnAdjustment--) | Gets or sets the table column adjustment. |
| [setColumnAdjustment(int value)](#setColumnAdjustment-int-) | Gets or sets the table column adjustment. |
| [getColumnWidths()](#getColumnWidths--) | Gets the column widths of the table. |
| [setColumnWidths(String value)](#setColumnWidths-java.lang.String-) | Gets the column widths of the table. |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | Gets default cell border. |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Gets default cell border. |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | Gets or sets the default cell padding. |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Gets or sets the default cell padding. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Gets or sets the default cell text state. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Gets or sets the default cell text state. |
| [getDefaultColumnWidth()](#getDefaultColumnWidth--) | Gets or sets default column width. |
| [setDefaultColumnWidth(String value)](#setDefaultColumnWidth-java.lang.String-) | Gets or sets default column width. |
| [isBroken()](#isBroken--) | Gets or sets the table is broken - will be truncated for next page. |
| [setBroken(boolean value)](#setBroken-boolean-) | Gets or sets the table is broken - will be truncated for next page. |
| [isBordersIncluded()](#isBordersIncluded--) | Gets or sets border included in column widhts. |
| [setBordersIncluded(boolean value)](#setBordersIncluded-boolean-) | Gets or sets border included in column widhts. |
| [getLeft()](#getLeft--) | Gets or sets the table left coordinate. |
| [setLeft(float value)](#setLeft-float-) | Gets or sets the table left coordinate. |
| [getTop()](#getTop--) | Gets or sets the table top coordinate. |
| [setTop(float value)](#setTop-float-) | Gets or sets the table top coordinate. |
| [getRepeatingColumnsCount()](#getRepeatingColumnsCount--) | Gets or sets the maximum columns count for table. |
| [setRepeatingColumnsCount(int value)](#setRepeatingColumnsCount-int-) | Gets or sets the maximum columns count for table. |
| [getRepeatingRowsCount()](#getRepeatingRowsCount--) | Gets the first rows count repeated for several pages. |
| [setRepeatingRowsCount(int value)](#setRepeatingRowsCount-int-) | Gets the first rows count repeated for several pages. |
| [getRepeatingRowsStyle()](#getRepeatingRowsStyle--) | Gets the style for repeating rows. |
| [setRepeatingRowsStyle(TextState value)](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Gets the style for repeating rows. |
| [createTHead()](#createTHead--) | Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) and added it to current table. |
| [createTBody()](#createTBody--) | Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) and added it to current table. |
| [createTFoot()](#createTFoot--) | Creates [TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) and added it to current table. |
### TableElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public TableElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```


constructor for internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| taggedContext | [TaggedContext](../../com.aspose.pdf.tagged/taggedcontext) | TaggedContext instance |
| pdfEngineEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | internal instance |

### getTable() {#getTable--}
```
public final Table getTable()
```




**Returns:**
[Table](../../com.aspose.pdf/table)
### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Gets or sets the table background color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color instance
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


Gets or sets the table background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color instance |

### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


Gets or sets the table border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo instance
### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


Gets or sets the table border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo instance |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Gets or sets the table alignment.

**Returns:**
int - HorizontalAlignment element
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Gets or sets the table alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment element |

### getCornerStyle() {#getCornerStyle--}
```
public final int getCornerStyle()
```


Gets or sets the styles of the border corners

**Returns:**
int - BorderCornerStyle element
### setCornerStyle(int value) {#setCornerStyle-int-}
```
public final void setCornerStyle(int value)
```


Gets or sets the styles of the border corners

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | BorderCornerStyle element |

### getBroken() {#getBroken--}
```
public final int getBroken()
```


Gets or sets table vertical broken;

**Returns:**
int - TableBroken element
### setBroken(int value) {#setBroken-int-}
```
public final void setBroken(int value)
```


Gets or sets table vertical broken;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TableBroken element |

### getColumnAdjustment() {#getColumnAdjustment--}
```
public final int getColumnAdjustment()
```


Gets or sets the table column adjustment.

**Returns:**
int - ColumnAdjustment element
### setColumnAdjustment(int value) {#setColumnAdjustment-int-}
```
public final void setColumnAdjustment(int value)
```


Gets or sets the table column adjustment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ColumnAdjustment element |

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

### getDefaultCellBorder() {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```


Gets default cell border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo instance
### setDefaultCellBorder(BorderInfo value) {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
```
public final void setDefaultCellBorder(BorderInfo value)
```


Gets default cell border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo instance |

### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```


Gets or sets the default cell padding.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo instance
### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public final void setDefaultCellPadding(MarginInfo value)
```


Gets or sets the default cell padding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo instance |

### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


Gets or sets the default cell text state.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState instance
### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


Gets or sets the default cell text state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState instance |

### getDefaultColumnWidth() {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```


Gets or sets default column width.

**Returns:**
java.lang.String - String value
### setDefaultColumnWidth(String value) {#setDefaultColumnWidth-java.lang.String-}
```
public final void setDefaultColumnWidth(String value)
```


Gets or sets default column width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### isBroken() {#isBroken--}
```
public final boolean isBroken()
```


Gets or sets the table is broken - will be truncated for next page.

**Returns:**
boolean - boolean value
### setBroken(boolean value) {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```


Gets or sets the table is broken - will be truncated for next page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isBordersIncluded() {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```


Gets or sets border included in column widhts.

**Returns:**
boolean - boolean value
### setBordersIncluded(boolean value) {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```


Gets or sets border included in column widhts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getLeft() {#getLeft--}
```
public final float getLeft()
```


Gets or sets the table left coordinate.

**Returns:**
float - float value
### setLeft(float value) {#setLeft-float-}
```
public final void setLeft(float value)
```


Gets or sets the table left coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getTop() {#getTop--}
```
public final float getTop()
```


Gets or sets the table top coordinate.

**Returns:**
float - float value
### setTop(float value) {#setTop-float-}
```
public final void setTop(float value)
```


Gets or sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getRepeatingColumnsCount() {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```


Gets or sets the maximum columns count for table.

**Returns:**
int - int value
### setRepeatingColumnsCount(int value) {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```


Gets or sets the maximum columns count for table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getRepeatingRowsCount() {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```


Gets the first rows count repeated for several pages.

**Returns:**
int - int value
### setRepeatingRowsCount(int value) {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```


Gets the first rows count repeated for several pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getRepeatingRowsStyle() {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```


Gets the style for repeating rows.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState instance
### setRepeatingRowsStyle(TextState value) {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
```
public final void setRepeatingRowsStyle(TextState value)
```


Gets the style for repeating rows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState instance |

### createTHead() {#createTHead--}
```
public final TableTHeadElement createTHead()
```


Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) and added it to current table.

**Returns:**
[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) - Created structure element.
### createTBody() {#createTBody--}
```
public final TableTBodyElement createTBody()
```


Creates [TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) and added it to current table.

**Returns:**
[TableTBodyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletbodyelement) - Created structure element.
### createTFoot() {#createTFoot--}
```
public final TableTFootElement createTFoot()
```


Creates [TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) and added it to current table.

**Returns:**
[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) - Created structure element.

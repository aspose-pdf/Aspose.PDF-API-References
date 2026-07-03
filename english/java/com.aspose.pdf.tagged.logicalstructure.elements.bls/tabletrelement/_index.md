---
title: TableTRElement
second_title: Aspose.PDF for Java API Reference
description: Represents TR structure element in logical structure of the table.
type: docs
weight: 240
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement

```
public final class TableTRElement extends TableChildElement
```

Represents TR structure element in logical structure of the table.

## Constructors

| Constructor | Description |
| --- | --- |
| [TableTRElement](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | constructor for internal usage only |

## Methods

| Method | Description |
| --- | --- |
| [createTD](#createTD--) | Creates {@link TableTHElement} and added it to current table. |
| [createTH](#createTH--) | Creates {@link TableTHElement} and added it to current table. |
| [getBackgroundColor](#getBackgroundColor--) | Gets or sets the row background color. |
| [getBorder](#getBorder--) | Gets or sets the row border. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Gets default cell border. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Gets or sets default margin for row cells. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Gets or sets default text state for row cells |
| [getFixedRowHeight](#getFixedRowHeight--) | Gets fixed row height - row may have fixed height. |
| [getMinRowHeight](#getMinRowHeight--) | Gets height for row. |
| [getVerticalAlignment](#getVerticalAlignment--) | Gets or sets the vertical alignment. |
| [isInNewPage](#isInNewPage--) | Gets fixed row is in new page - page with this property should be printed to next page Default false. |
| [isRowBroken](#isRowBroken--) | Gets is row can be broken between two pages. |
| [preSave](#preSave--) |  |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Gets or sets the row background color. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Gets or sets the row border. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Gets default cell border. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Gets or sets default margin for row cells. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Gets or sets default text state for row cells |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Gets fixed row height - row may have fixed height. |
| [setInNewPage](#setInNewPage-boolean-) | Gets fixed row is in new page - page with this property should be printed to next page Default false. |
| [setMinRowHeight](#setMinRowHeight-double-) | Gets height for row. |
| [setRowBroken](#setRowBroken-boolean-) | Gets is row can be broken between two pages. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Gets or sets the vertical alignment. |

### TableTRElement {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
constructor for internal usage only

### createTD {#createTD--}
```
public final TableTDElement createTD()
```

Creates {@link TableTHElement} and added it to current table.

**Returns:**
Created structure element.

### createTH {#createTH--}
```
public final TableTHElement createTH()
```

Creates {@link TableTHElement} and added it to current table.

**Returns:**
Created structure element.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Gets or sets the row background color.

**Returns:**
Color instance

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Gets or sets the row border.

**Returns:**
BorderInfo instance

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

Gets or sets default margin for row cells.

**Returns:**
MarginInfo instance

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Gets or sets default text state for row cells

**Returns:**
TextState instance

### getFixedRowHeight {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```

Gets fixed row height - row may have fixed height.

**Returns:**
double value

### getMinRowHeight {#getMinRowHeight--}
```
public final double getMinRowHeight()
```

Gets height for row.

**Returns:**
double value

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Gets or sets the vertical alignment.

**Returns:**
VerticalAlignment element

### isInNewPage {#isInNewPage--}
```
public final boolean isInNewPage()
```

Gets fixed row is in new page - page with this property should be printed to next page Default false.

**Returns:**
boolean value

### isRowBroken {#isRowBroken--}
```
public final boolean isRowBroken()
```

Gets is row can be broken between two pages.

**Returns:**
boolean value

### preSave {#preSave--}
```
public void preSave()
```



### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Gets or sets the row background color.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Gets or sets the row border.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Gets default cell border.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Gets or sets default margin for row cells.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Gets or sets default text state for row cells

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```

Gets fixed row height - row may have fixed height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setInNewPage {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```

Gets fixed row is in new page - page with this property should be printed to next page Default false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMinRowHeight {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```

Gets height for row.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setRowBroken {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```

Gets is row can be broken between two pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Gets or sets the vertical alignment.

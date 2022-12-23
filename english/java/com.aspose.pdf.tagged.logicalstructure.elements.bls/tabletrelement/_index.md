---
title: TableTRElement
second_title: Aspose.PDF for Java API Reference
description: Represents TR structure element in logical structure of the table.
type: docs
weight: 28
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablechildelement)
```
public final class TableTRElement extends TableChildElement
```

Represents TR structure element in logical structure of the table.
## Constructors

| Constructor | Description |
| --- | --- |
| [TableTRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | constructor for internal usage only |
## Methods

| Method | Description |
| --- | --- |
| [getBackgroundColor()](#getBackgroundColor--) | Gets or sets the row background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Gets or sets the row background color. |
| [getBorder()](#getBorder--) | Gets or sets the row border. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Gets or sets the row border. |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | Gets default cell border. |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Gets default cell border. |
| [getMinRowHeight()](#getMinRowHeight--) | Gets height for row. |
| [setMinRowHeight(double value)](#setMinRowHeight-double-) | Gets height for row. |
| [getFixedRowHeight()](#getFixedRowHeight--) | Gets fixed row height - row may have fixed height. |
| [setFixedRowHeight(double value)](#setFixedRowHeight-double-) | Gets fixed row height - row may have fixed height. |
| [isInNewPage()](#isInNewPage--) | Gets fixed row is in new page - page with this property should be printed to next page Default false. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Gets fixed row is in new page - page with this property should be printed to next page Default false. |
| [isRowBroken()](#isRowBroken--) | Gets is row can be broken between two pages. |
| [setRowBroken(boolean value)](#setRowBroken-boolean-) | Gets is row can be broken between two pages. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Gets or sets default text state for row cells |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Gets or sets default text state for row cells |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | Gets or sets default margin for row cells. |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Gets or sets default margin for row cells. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets or sets the vertical alignment. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Gets or sets the vertical alignment. |
| [createTH()](#createTH--) | Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) and added it to current table. |
| [createTD()](#createTD--) | Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) and added it to current table. |
### TableTRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public TableTRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```


constructor for internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| taggedContext | [TaggedContext](../../com.aspose.pdf.tagged/taggedcontext) | TaggedContext instance |
| pdfEngineEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | internal instance |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Gets or sets the row background color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color instance
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


Gets or sets the row background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color instance |

### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


Gets or sets the row border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo instance
### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


Gets or sets the row border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo instance |

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

### getMinRowHeight() {#getMinRowHeight--}
```
public final double getMinRowHeight()
```


Gets height for row.

**Returns:**
double - double value
### setMinRowHeight(double value) {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```


Gets height for row.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getFixedRowHeight() {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```


Gets fixed row height - row may have fixed height.

**Returns:**
double - double value
### setFixedRowHeight(double value) {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```


Gets fixed row height - row may have fixed height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### isInNewPage() {#isInNewPage--}
```
public final boolean isInNewPage()
```


Gets fixed row is in new page - page with this property should be printed to next page Default false.

**Returns:**
boolean - boolean value
### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```


Gets fixed row is in new page - page with this property should be printed to next page Default false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isRowBroken() {#isRowBroken--}
```
public final boolean isRowBroken()
```


Gets is row can be broken between two pages.

**Returns:**
boolean - boolean value
### setRowBroken(boolean value) {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```


Gets is row can be broken between two pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


Gets or sets default text state for row cells

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState instance
### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


Gets or sets default text state for row cells

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState instance |

### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```


Gets or sets default margin for row cells.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo instance
### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public final void setDefaultCellPadding(MarginInfo value)
```


Gets or sets default margin for row cells.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo instance |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Gets or sets the vertical alignment.

**Returns:**
int - VerticalAlignment element
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Gets or sets the vertical alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

### createTH() {#createTH--}
```
public final TableTHElement createTH()
```


Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) and added it to current table.

**Returns:**
[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) - Created structure element.
### createTD() {#createTD--}
```
public final TableTDElement createTD()
```


Creates [TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) and added it to current table.

**Returns:**
[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement) - Created structure element.

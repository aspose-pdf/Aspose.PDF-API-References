---
title: TableCellElement
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for table cell elements TH and TD in logical structure.
type: docs
weight: 19
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablechildelement)

**All Implemented Interfaces:**
[com.aspose.pdf.tagged.logicalstructure.elements.ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement)
```
public abstract class TableCellElement extends TableChildElement implements ITextElement
```

Represents a base class for table cell elements (TH and TD) in logical structure.
## Methods

| Method | Description |
| --- | --- |
| [getCell()](#getCell--) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Gets or sets the cell background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Gets or sets the cell background color. |
| [getBorder()](#getBorder--) | Gets or sets the cell border. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Gets or sets the cell border. |
| [isNoBorder()](#isNoBorder--) | Gets or sets the cell have border. |
| [setNoBorder(boolean value)](#setNoBorder-boolean-) | Gets or sets the cell have border. |
| [getMargin()](#getMargin--) | Gets or sets the padding. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Gets or sets the padding. |
| [getAlignment()](#getAlignment--) | Gets or sets the cell alignment. |
| [setAlignment(int value)](#setAlignment-int-) | Gets or sets the cell alignment. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Gets or sets the default cell text state. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Gets or sets the default cell text state. |
| [isWordWrapped()](#isWordWrapped--) | Gets or sets the cell's text word wrapped. |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Gets or sets the cell's text word wrapped. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets or sets the vertical alignment. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Gets or sets the vertical alignment. |
| [getColSpan()](#getColSpan--) | Gets or sets the column span. |
| [setColSpan(int value)](#setColSpan-int-) | Gets or sets the column span. |
| [getRowSpan()](#getRowSpan--) | Gets or sets the row span. |
| [setRowSpan(int value)](#setRowSpan-int-) | Gets or sets the row span. |
| [getStructureTextState()](#getStructureTextState--) | Gets  /Aspose.Pdf.LogicalStructure.StructureTextState  object for current element. |
| [setText(String text)](#setText-java.lang.String-) | Appends text content to current text element. |
### getCell() {#getCell--}
```
public final Cell getCell()
```




**Returns:**
[Cell](../../com.aspose.pdf/cell)
### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Gets or sets the cell background color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color instance
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


Gets or sets the cell background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color instance |

### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


Gets or sets the cell border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo instance
### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


Gets or sets the cell border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo instance |

### isNoBorder() {#isNoBorder--}
```
public final boolean isNoBorder()
```


Gets or sets the cell have border.

**Returns:**
boolean - boolean value
### setNoBorder(boolean value) {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```


Gets or sets the cell have border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getMargin() {#getMargin--}
```
public final MarginInfo getMargin()
```


Gets or sets the padding.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo instance
### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public final void setMargin(MarginInfo value)
```


Gets or sets the padding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo instance |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Gets or sets the cell alignment.

**Returns:**
int - HorizontalAlignment element
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Gets or sets the cell alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment element |

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

### isWordWrapped() {#isWordWrapped--}
```
public final boolean isWordWrapped()
```


Gets or sets the cell's text word wrapped.

**Returns:**
boolean - boolean value
### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```


Gets or sets the cell's text word wrapped.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```


Gets or sets the column span.

**Returns:**
int - int value
### setColSpan(int value) {#setColSpan-int-}
```
public final void setColSpan(int value)
```


Gets or sets the column span.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```


Gets or sets the row span.

**Returns:**
int - int value
### setRowSpan(int value) {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```


Gets or sets the row span.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getStructureTextState() {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```


Gets  /Aspose.Pdf.LogicalStructure.StructureTextState  object for current element.

Value:  /Aspose.Pdf.LogicalStructure.StructureTextState  object for current element.

**Returns:**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) - StructureTextState instance
### setText(String text) {#setText-java.lang.String-}
```
public final void setText(String text)
```


Appends text content to current text element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text content |


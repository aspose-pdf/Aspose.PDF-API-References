---
title: TableCellElement
linktitle: TableCellElement
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for table cell elements (TH and TD) in logical structure.
type: docs
weight: 150
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class TableCellElement extends TableChildElement implements ITextElement , IAdjustPosition
```

Represents a base class for table cell elements (TH and TD) in logical structure.

## Methods

| Method | Description |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Adjust position. |
| [getAlignment](#getAlignment--) | Gets or sets the cell alignment. |
| [getBackgroundColor](#getBackgroundColor--) | Gets or sets the cell background color. |
| [getBorder](#getBorder--) | Gets or sets the cell border. |
| [getCell](#getCell--) |  |
| [getColSpan](#getColSpan--) | Gets or sets the column span. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Gets or sets the default cell text state. |
| [getMargin](#getMargin--) | Gets or sets the padding. |
| [getRowSpan](#getRowSpan--) | Gets or sets the row span. |
| [getStructureTextState](#getStructureTextState--) | Gets {@code /Aspose.Pdf.LogicalStructure.StructureTextState} object for current element. Value: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} object for current element. |
| [getVerticalAlignment](#getVerticalAlignment--) | Gets or sets the vertical alignment. |
| [isNoBorder](#isNoBorder--) | Gets or sets the cell have border. |
| [isWordWrapped](#isWordWrapped--) | Gets or sets the cell's text word wrapped. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Gets or sets the cell alignment. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Gets or sets the cell background color. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Gets or sets the cell border. |
| [setColSpan](#setColSpan-int-) | Gets or sets the column span. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Gets or sets the default cell text state. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Gets or sets the padding. |
| [setNoBorder](#setNoBorder-boolean-) | Gets or sets the cell have border. |
| [setRowSpan](#setRowSpan-int-) | Gets or sets the row span. |
| [setText](#setText-java.lang.String-) | Appends text content to current text element. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Gets or sets the vertical alignment. |
| [setWordWrapped](#setWordWrapped-boolean-) | Gets or sets the cell's text word wrapped. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Adjust position.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Gets or sets the cell alignment.

**Returns:**
HorizontalAlignment element

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Gets or sets the cell background color.

**Returns:**
Color instance

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Gets or sets the cell border.

**Returns:**
BorderInfo instance

### getCell {#getCell--}
```
public final Cell getCell()
```



### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Gets or sets the column span.

**Returns:**
int value

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Gets or sets the default cell text state.

**Returns:**
TextState instance

### getMargin {#getMargin--}
```
public final MarginInfo getMargin()
```

Gets or sets the padding.

**Returns:**
MarginInfo instance

### getRowSpan {#getRowSpan--}
```
public final int getRowSpan()
```

Gets or sets the row span.

**Returns:**
int value

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Gets {@code /Aspose.Pdf.LogicalStructure.StructureTextState} object for current element. Value: {@code /Aspose.Pdf.LogicalStructure.StructureTextState} object for current element.

**Returns:**
StructureTextState instance

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Gets or sets the vertical alignment.

**Returns:**
VerticalAlignment element

### isNoBorder {#isNoBorder--}
```
public final boolean isNoBorder()
```

Gets or sets the cell have border.

**Returns:**
boolean value

### isWordWrapped {#isWordWrapped--}
```
public final boolean isWordWrapped()
```

Gets or sets the cell's text word wrapped.

**Returns:**
boolean value

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Gets or sets the cell alignment.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Gets or sets the cell background color.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Gets or sets the cell border.

### setColSpan {#setColSpan-int-}
```
public final void setColSpan(int value)
```

Gets or sets the column span.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Gets or sets the default cell text state.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Gets or sets the padding.

### setNoBorder {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```

Gets or sets the cell have border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRowSpan {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```

Gets or sets the row span.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setText {#setText-java.lang.String-}
Appends text content to current text element.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Gets or sets the vertical alignment.

### setWordWrapped {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```

Gets or sets the cell's text word wrapped.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

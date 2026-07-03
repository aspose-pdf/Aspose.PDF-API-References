---
title: AbsorbedCell
linktitle: AbsorbedCell
second_title: Aspose.PDF for Java API Reference
description: Represents cell of table that exist on the page
type: docs
weight: 10
url: /java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedCell

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedCell >

```
public class AbsorbedCell extends Object implements ITableElement , Comparable < AbsorbedCell >
```

Represents cell of table that exist on the page

## Methods

| Method | Description |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedCell-) | Compares the current AbsorbedCell object with another AbsorbedCell object and returns an integer that indicates whether the current object precedes, follows, or occurs in the same position in the sort order as the other object. |
| [getBorderInfo](#getBorderInfo--) | Return the border information for the cell when the FlowEngine.TableAbsorber.UseFlowEngine property is set to true. |
| [getColSpan](#getColSpan--) | Return the number of columns the cell should span when TableAbsorber.UseFlowEngine property is set to true. |
| [getRectangle](#getRectangle--) | Gets rectangle that describes position of the cell on page |
| [getTextFragments](#getTextFragments--) | Gets collection of {@code TextFragment} objects that describes text containing in the cell |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedCell-}
Compares the current AbsorbedCell object with another AbsorbedCell object and returns an integer that indicates whether the current object precedes, follows, or occurs in the same position in the sort order as the other object.

### getBorderInfo {#getBorderInfo--}
```
public final BorderInfo getBorderInfo()
```

Return the border information for the cell when the FlowEngine.TableAbsorber.UseFlowEngine property is set to true.

**Returns:**
BorderInfo instance

### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Return the number of columns the cell should span when TableAbsorber.UseFlowEngine property is set to true.

**Returns:**
int value

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets rectangle that describes position of the cell on page

**Returns:**
Rectangle object

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

Gets collection of {@code TextFragment} objects that describes text containing in the cell

**Returns:**
TextFragmentCollection object

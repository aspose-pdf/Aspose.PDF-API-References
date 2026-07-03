---
title: AbsorbedTable
linktitle: AbsorbedTable
second_title: Aspose.PDF for Java API Reference
description: Represents table that exist on the page
type: docs
weight: 30
url: /java/com.aspose.pdf/absorbedtable/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedTable

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedTable >

```
public class AbsorbedTable extends Object implements ITableElement , Comparable < AbsorbedTable >
```

Represents table that exist on the page

## Methods

| Method | Description |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedTable-) | Compares the current AbsorbedTable object with another AbsorbedTable object and returns an integer that indicates whether the current object precedes, follows, or occurs in the same position in the sort order as the other object. |
| [getPageNum](#getPageNum--) | Gets number of the page containing this table |
| [getRectangle](#getRectangle--) | Gets rectangle that describes position of the table on page |
| [getRowList](#getRowList--) | <p> Gets readonly IList containing rows of the table </p> |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedTable-}
Compares the current AbsorbedTable object with another AbsorbedTable object and returns an integer that indicates whether the current object precedes, follows, or occurs in the same position in the sort order as the other object.

### getPageNum {#getPageNum--}
```
public int getPageNum()
```

Gets number of the page containing this table

**Returns:**
int value

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets rectangle that describes position of the table on page

**Returns:**
Rectangle object

### getRowList {#getRowList--}
```
public List < AbsorbedRow > getRowList()
```

<p> Gets readonly IList containing rows of the table </p>

**Returns:**
{@code IGenericList<AbsorbedRow>} object

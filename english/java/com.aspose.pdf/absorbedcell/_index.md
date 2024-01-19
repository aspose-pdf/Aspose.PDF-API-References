---
title: AbsorbedCell
second_title: Aspose.PDF for Java API Reference
description: Represents cell of table that exist on the page
type: docs
weight: 10
url: /java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.pdf.ITableElement](../../com.aspose.pdf/itableelement)
```
public class AbsorbedCell implements ITableElement
```

Represents cell of table that exist on the page
## Methods

| Method | Description |
| --- | --- |
| [getTextFragments()](#getTextFragments--) | Gets collection of  TextFragment  objects that describes text containing in the cell |
| [getRectangle()](#getRectangle--) | Gets rectangle that describes position of the cell on page |
| [getColSpan()](#getColSpan--) | Return the number of columns the cell should span when TableAbsorber.UseFlowEngine is true. |
### getTextFragments() {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```


Gets collection of  TextFragment  objects that describes text containing in the cell

**Returns:**
[TextFragmentCollection](../../com.aspose.pdf/textfragmentcollection) - TextFragmentCollection object
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle that describes position of the cell on page

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```


Return the number of columns the cell should span when TableAbsorber.UseFlowEngine is true.

**Returns:**
int - int value

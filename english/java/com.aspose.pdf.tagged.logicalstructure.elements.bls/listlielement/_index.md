---
title: ListLIElement
second_title: Aspose.PDF for Java API Reference
description: Represents LI structure element in logical structure of the list.
type: docs
weight: 110
url: /java/com.aspose.pdf.tagged.logicalstructure.elements.bls/listlielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement

**All Implemented Interfaces:**
ITociElement

```
public final class ListLIElement extends ListChildElement implements ITociElement
```

Represents LI structure element in logical structure of the list.

## Constructors

| Constructor | Description |
| --- | --- |
| [ListLIElement](#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Methods

| Method | Description |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Adds a reference to the specified {@link StructureElement} within this Table of Contents Item (TOCI) element. This is typically used when {@code ListLIElement} serves as a TOC header in nested tables of contents. |
| [getGetElement](#getGetElement--) | Gets the underlying PDF element that represents this TOCI structure. |
| [preSave](#preSave--) |  |

### ListLIElement {#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Adds a reference to the specified {@link StructureElement} within this Table of Contents Item (TOCI) element. This is typically used when {@code ListLIElement} serves as a TOC header in nested tables of contents.

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

Gets the underlying PDF element that represents this TOCI structure.

**Returns:**
The Element that forms the structural representation of this table of contents entry.

### preSave {#preSave--}
```
public void preSave()
```

---
title: "ListLIElement"
linktitle: "ListLIElement"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar LI-strukturselement i listans logiska struktur."
type: docs
weight: 110
url: /sv/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/listlielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement

**All Implemented Interfaces:**
ITociElement

```
public final class ListLIElement extends ListChildElement implements ITociElement
```

Representerar LI-strukturselement i listans logiska struktur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ListLIElement](#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Lägger till en referens till det angivna {@link StructureElement} inom detta innehållsförteckningselement (TOCI). Detta används vanligtvis när {@code ListLIElement} fungerar som en TOC‑rubrik i nästlade innehållsförteckningar. |
| [getGetElement](#getGetElement--) | Hämtar det underliggande PDF-elementet som representerar denna TOCI-struktur. |
| [preSave](#preSave--) |  |

### ListLIElement {#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Lägger till en referens till det angivna {@link StructureElement} inom detta innehållsförteckningselement (TOCI). Detta används vanligtvis när {@code ListLIElement} fungerar som en TOC‑rubrik i nästlade innehållsförteckningar.

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

Hämtar det underliggande PDF-elementet som representerar denna TOCI-struktur.

**Returns:**
Elementet som bildar den strukturella representationen av denna innehållsförteckningspost.

### preSave {#preSave--}
```
public void preSave()
```

---
title: "ListLIElement"
linktitle: "ListLIElement"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt das LI-Strukturelement in der logischen Struktur der Liste dar."
type: docs
weight: 110
url: /de/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/listlielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement

**All Implemented Interfaces:**
ITociElement

```
public final class ListLIElement extends ListChildElement implements ITociElement
```

Stellt das LI-Strukturelement in der logischen Struktur der Liste dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ListLIElement](#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Fügt einen Verweis auf das angegebene {@link StructureElement} innerhalb dieses Table of Contents Item (TOCI)-Elements hinzu. Dies wird typischerweise verwendet, wenn {@code ListLIElement} als TOC‑Kopf in verschachtelten Inhaltsverzeichnissen dient. |
| [getGetElement](#getGetElement--) | Liefert das zugrunde liegende PDF-Element, das diese TOCI-Struktur darstellt. |
| [preSave](#preSave--) |  |

### ListLIElement {#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Fügt einen Verweis auf das angegebene {@link StructureElement} innerhalb dieses Table of Contents Item (TOCI)-Elements hinzu. Dies wird typischerweise verwendet, wenn {@code ListLIElement} als TOC‑Kopf in verschachtelten Inhaltsverzeichnissen dient.

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

Liefert das zugrunde liegende PDF-Element, das diese TOCI-Struktur darstellt.

**Returns:**
Das Element, das die strukturelle Darstellung dieses Inhaltsverzeichniseintrags bildet.

### preSave {#preSave--}
```
public void preSave()
```

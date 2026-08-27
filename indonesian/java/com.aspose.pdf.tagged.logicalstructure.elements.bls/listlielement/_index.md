---
title: "ListLIElement"
linktitle: "ListLIElement"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili elemen struktur LI dalam struktur logis daftar."
type: docs
weight: 110
url: /id/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/listlielement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.ListLIElement

**All Implemented Interfaces:**
ITociElement

```
public final class ListLIElement extends ListChildElement implements ITociElement
```

Mewakili elemen struktur LI dalam struktur logis daftar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ListLIElement](#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addRef](#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Menambahkan referensi ke {@link StructureElement} yang ditentukan dalam elemen Item Daftar Isi (TOCI) ini. Ini biasanya digunakan ketika {@code ListLIElement} berfungsi sebagai header TOC dalam tabel isi bersarang. |
| [getGetElement](#getGetElement--) | Mendapatkan elemen PDF yang mendasari yang mewakili struktur TOCI ini. |
| [preSave](#preSave--) |  |

### ListLIElement {#ListLIElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### addRef {#addRef-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
Menambahkan referensi ke {@link StructureElement} yang ditentukan dalam elemen Item Daftar Isi (TOCI) ini. Ini biasanya digunakan ketika {@code ListLIElement} berfungsi sebagai header TOC dalam tabel isi bersarang.

### getGetElement {#getGetElement--}
```
public final StructureElement getGetElement()
```

Mendapatkan elemen PDF yang mendasari yang mewakili struktur TOCI ini.

**Returns:**
Elemen yang membentuk representasi struktural dari entri daftar isi ini.

### preSave {#preSave--}
```
public void preSave()
```

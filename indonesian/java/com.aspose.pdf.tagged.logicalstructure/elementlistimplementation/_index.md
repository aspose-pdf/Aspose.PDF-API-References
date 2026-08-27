---
title: "ElementListImplementation"
linktitle: "ElementListImplementation"
second_title: "Referensi API Aspose.PDF untuk Java"
description:
type: docs
weight: 50
url: /id/java/com.aspose.pdf.tagged.logicalstructure/elementlistimplementation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList com.aspose.pdf.tagged.logicalstructure.ElementListImplementation, com.aspose.pdf.tagged.logicalstructure.ElementList, com.aspose.pdf.tagged.logicalstructure.ElementListImplementation

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public class ElementListImplementation extends ElementList
```



## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ElementListImplementation](#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Tambahkan elemen ke daftar. |
| [getCount](#getCount--) | Mendapatkan jumlah elemen dalam ElementList. |
| [item](#item-int-) | Mengambil sebuah elemen pada indeks yang diberikan. |
| [iterator](#iterator--) | Mendapatkan enumerator yang mengiterasi koleksi elemen. |

### ElementListImplementation {#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Tambahkan elemen ke daftar.

### getCount {#getCount--}
```
public int getCount()
```

Mendapatkan jumlah elemen dalam ElementList.

**Returns:**
nilai int

### item {#item-int-}
```
public Element item(int index)
```

Mengambil sebuah elemen pada indeks yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  |  |

**Returns:**
Elemen /Aspose.Pdf.LogicalStructure.Element dengan indeks yang ditentukan dalam koleksi. Jika indeks lebih besar atau sama dengan jumlah elemen dalam daftar, ini mengembalikan null.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Mendapatkan enumerator yang mengiterasi koleksi elemen.

**Returns:**
Enumerator yang digunakan untuk mengiterasi koleksi elemen.

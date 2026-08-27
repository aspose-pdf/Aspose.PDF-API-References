---
title: "ElementList"
linktitle: "ElementList"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili koleksi elemen yang terurut."
type: docs
weight: 40
url: /id/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public abstract class ElementList extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

Mewakili koleksi elemen yang terurut.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Tambahkan elemen ke daftar. |
| [get_Item](#get_Item-int-) |  |
| [getCount](#getCount--) | Mendapatkan jumlah elemen dalam ElementList. |
| [insertElement](#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Masukkan elemen ke dalam daftar. |
| [item](#item-int-) | Mengambil sebuah elemen pada indeks yang diberikan. |
| [iterator](#iterator--) | Mendapatkan enumerator yang mengiterasi koleksi elemen. |
| [removeAt](#removeAt-int-) | Hapus elemen dari daftar. |
| [removeElement](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Hapus elemen dari daftar. |

### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Tambahkan elemen ke daftar.

### get_Item {#get_Item-int-}
```
public Element get_Item(int index)
```



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  |  |

### getCount {#getCount--}
```
public abstract int getCount()
```

Mendapatkan jumlah elemen dalam ElementList.

**Returns:**
nilai int

### insertElement {#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Masukkan elemen ke dalam daftar.

### item {#item-int-}
```
public abstract Element item(int index)
```

Mengambil sebuah elemen pada indeks yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks ke dalam daftar elemen. |

**Returns:**
Elemen {@code /Aspose.Pdf.LogicalStructure.Element} dengan indeks yang ditentukan dalam koleksi. Jika {@code index} lebih besar atau sama dengan jumlah elemen dalam daftar, ini mengembalikan null.

### iterator {#iterator--}
```
public abstract com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Mendapatkan enumerator yang mengiterasi koleksi elemen.

**Returns:**
Enumerator yang digunakan untuk mengiterasi koleksi elemen.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

Hapus elemen dari daftar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks yang akan dihapus. |

### removeElement {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Hapus elemen dari daftar.

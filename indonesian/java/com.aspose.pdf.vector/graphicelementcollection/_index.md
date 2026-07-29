---
title: "GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili koleksi {@link GraphicElement}."
type: docs
weight: 20
url: /id/java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
Iterable < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

Mewakili koleksi {@link GraphicElement}.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | Menginisialisasi koleksi baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | Menambahkan {@link GraphicElement} baru ke dalam koleksi. Semua item dalam koleksi harus memiliki {@code GraphicElement.Parent} yang sama ({@link GraphicElement#getParent}). |
| [clear](#clear--) | Mengosongkan koleksi. |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | Menentukan apakah sebuah elemen berada dalam koleksi. |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | Menyalin seluruh koleksi ke Array satu dimensi yang kompatibel, dimulai pada indeks yang ditentukan dari array target. |
| [get_Item](#get_Item-int-) | Mendapatkan elemen {@link GraphicElement} pada indeks yang ditentukan. |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah koleksi hanya-baca. Selalu mengembalikan false. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Mengembalikan enumerator untuk seluruh koleksi. |
| [iterator](#iterator--) | Mengembalikan enumerator untuk seluruh koleksi. |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) | Menghapus elemen {@link GraphicElement}. |
| [size](#size--) | Mendapatkan jumlah objek {@link GraphicElement} yang sebenarnya terdapat dalam koleksi. |
| [toList](#toList--) | Mengembalikan koleksi internal untuk enumerasi tanpa batas. |
| [toString](#toString--) | Mendapatkan representasi string dari koleksi ini. |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

Menginisialisasi koleksi baru.

### add {#add-com.aspose.pdf.vector.GraphicElement-}
Menambahkan {@link GraphicElement} baru ke dalam koleksi. Semua item dalam koleksi harus memiliki {@code GraphicElement.Parent} yang sama ({@link GraphicElement#getParent}).

### clear {#clear--}
```
public final void clear()
```

Mengosongkan koleksi.

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
Menentukan apakah sebuah elemen berada dalam koleksi.

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
Menyalin seluruh koleksi ke Array satu dimensi yang kompatibel, dimulai pada indeks yang ditentukan dari array target.

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

Mendapatkan elemen {@link GraphicElement} pada indeks yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks dalam koleksi. |

**Returns:**
{@link GraphicElement}.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah koleksi hanya-baca. Selalu mengembalikan false.

**Returns:**
nilai boolean

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Mengembalikan enumerator untuk seluruh koleksi.

**Returns:**
Objek Enumerator.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

Mengembalikan enumerator untuk seluruh koleksi.

**Returns:**
Objek Enumerator.

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
Menghapus elemen {@link GraphicElement}.

### size {#size--}
```
public final int size()
```

Mendapatkan jumlah objek {@link GraphicElement} yang sebenarnya terdapat dalam koleksi.

**Returns:**
nilai int

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

Mengembalikan koleksi internal untuk enumerasi tanpa batas.

**Returns:**
Daftar internal

### toString {#toString--}
```
public String toString()
```

Mendapatkan representasi string dari koleksi ini.

**Returns:**
String tersebut.

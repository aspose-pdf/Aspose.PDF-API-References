---
title: "DestinationCollection"
linktitle: "DestinationCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas mewakili koleksi semua tujuan (sebuah pohon nama yang memetakan string nama ke tujuan (lihat 12.3.2.3, \"Named Destinations\") dan (lihat 7.7.4, \"Name Dictionary\")) dalam."
type: docs
weight: 960
url: /id/java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DestinationCollection

**All Implemented Interfaces:**
Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, Object >>

```
public final class DestinationCollection extends Object implements Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >>
```

Kelas yang merepresentasikan koleksi semua tujuan (pohon nama yang memetakan string nama ke tujuan (lihat 12.3.2.3, "Named Destinations") dan (lihat 7.7.4, "Name Dictionary")) dalam dokumen pdf.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menambahkan item yang ditentukan. |
| [clear](#clear--) | Koleksi bersifat read-only. Selalu melemparkan pengecualian NotSupportedException. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menentukan apakah instance ini berisi objek tersebut. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Menyalin elemen koleksi ke sebuah Array, dimulai pada indeks Array tertentu. |
| [get_Item](#get_Item-int-) | Mendapatkan objek tujuan berdasarkan indeks. |
| [getExplicitDestination](#getExplicitDestination-java.lang.String-boolean-) | Mengembalikan tujuan eksplisit berdasarkan nama. |
| [getPageNumber](#getPageNumber-java.lang.String-boolean-) | Mengembalikan nomor halaman tujuan berdasarkan nama. |
| [indexOf](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Mengembalikan indeks tujuan dalam koleksi. |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only. |
| [iterator](#iterator--) | Mengembalikan enumerator. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menghapus item yang ditentukan. |
| [size](#size--) | Mendapatkan jumlah elemen yang terdapat dalam koleksi. |

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menambahkan item yang ditentukan.

### clear {#clear--}
```
public void clear()
```

Koleksi bersifat read-only. Selalu melemparkan pengecualian NotSupportedException.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menentukan apakah instance ini berisi objek tersebut.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Menyalin elemen koleksi ke sebuah Array, dimulai pada indeks Array tertentu.

### get_Item {#get_Item-int-}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object > get_Item(int index)
```

Mendapatkan objek tujuan berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks tujuan yang akan diambil. |

**Returns:**
Tujuan.

### getExplicitDestination {#getExplicitDestination-java.lang.String-boolean-}
Mengembalikan tujuan eksplisit berdasarkan nama.

### getPageNumber {#getPageNumber-java.lang.String-boolean-}
Mengembalikan nomor halaman tujuan berdasarkan nama.

### indexOf {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Mengembalikan indeks tujuan dalam koleksi.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only.

**Returns:**
nilai boolean

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >> iterator()
```

Mengembalikan enumerator.

**Returns:**
Enumerator.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menghapus item yang ditentukan.

### size {#size--}
```
public int size()
```

Mendapatkan jumlah elemen yang terdapat dalam koleksi.

**Returns:**
nilai int

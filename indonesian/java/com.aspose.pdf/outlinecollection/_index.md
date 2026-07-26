---
title: "OutlineCollection"
linktitle: "OutlineCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili hierarki garis besar dokumen."
type: docs
weight: 3260
url: /id/java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineCollection extends Outlines
```

Mewakili hierarki garis besar dokumen.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Menambahkan item outline ke koleksi. |
| [clear](#clear--) | Menghapus semua item dari koleksi. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Belum didukung. Memeriksa apakah koleksi berisi item yang diberikan. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Menyalin item outline ke System.Array, mulai pada indeks System.Array tertentu. |
| [delete](#delete--) | Menghapus semua item outline dari outline dokumen. |
| [delete](#delete-java.lang.String-) | Menghapus semua item outline dari outline dokumen. |
| [get_Item](#get_Item-int-) | Mendapatkan item outline dari koleksi berdasarkan indeks. |
| [getFirst](#getFirst--) | Mendapatkan item outline yang mewakili item tingkat atas pertama dalam outline. |
| [getLast](#getLast--) | Mendapatkan item outline yang mewakili item tingkat atas terakhir dalam outline. |
| [getSyncRoot](#getSyncRoot--) | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi ini. |
| [getVisibleCount](#getVisibleCount--) | Count adalah jumlah dari jumlah item outline turunan yang terlihat pada semua tingkat. Catatan: jangan bingung dengan Count yang merupakan jumlah item dalam koleksi. |
| [hasNext](#hasNext--) |  |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only. |
| [isSynchronized](#isSynchronized--) | Mendapatkan nilai yang menunjukkan apakah akses ke koleksi ini disinkronkan (aman untuk thread). |
| [iterator](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [next](#next--) |  |
| [remove](#remove-int-) | Hapus item berdasarkan indeks. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Belum didukung. Selalu melempar pengecualian. |
| [size](#size--) | Mendapatkan total jumlah item outline (bookmark) pada semua tingkat outline dokumen. |

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Menambahkan item outline ke koleksi.

### clear {#clear--}
```
public void clear()
```

Menghapus semua item dari koleksi.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Belum didukung. Memeriksa apakah koleksi berisi item yang diberikan.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Menyalin item outline ke System.Array, mulai pada indeks System.Array tertentu.

### delete {#delete--}
```
public void delete()
```

Menghapus semua item outline dari outline dokumen.

### delete {#delete-java.lang.String-}
Menghapus semua item outline dari outline dokumen.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Mendapatkan item outline dari koleksi berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks item yang diminta. |

**Returns:**
objek OutlineItemCollection

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Mendapatkan item outline yang mewakili item tingkat atas pertama dalam outline.

**Returns:**
objek OutlineItemCollection

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Mendapatkan item outline yang mewakili item tingkat atas terakhir dalam outline.

**Returns:**
objek OutlineItemCollection

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi ini.

**Returns:**
Objek untuk sinkronisasi

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Count adalah jumlah dari jumlah item outline turunan yang terlihat pada semua tingkat. Catatan: jangan bingung dengan Count yang merupakan jumlah item dalam koleksi.

**Returns:**
nilai int

### hasNext {#hasNext--}
```
public boolean hasNext()
```



### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only.

**Returns:**
nilai boolean

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Mendapatkan nilai yang menunjukkan apakah akses ke koleksi ini disinkronkan (aman untuk thread).

**Returns:**
nilai boolean

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Returns:**
Objek System.Collections.IEnumerator yang dapat digunakan untuk mengiterasi koleksi.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Hapus item berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks item yang akan dihapus. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Belum didukung. Selalu melempar pengecualian.

### size {#size--}
```
public int size()
```

Mendapatkan total jumlah item outline (bookmark) pada semua tingkat outline dokumen.

**Returns:**
nilai int

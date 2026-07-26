---
title: "OutlineItemCollection"
linktitle: "OutlineItemCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili entri garis besar dalam hierarki garis besar dokumen PDF."
type: docs
weight: 3270
url: /id/java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineItemCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineItemCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineItemCollection extends Outlines
```

Mewakili entri garis besar dalam hierarki garis besar dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | Menginisialisasi instance baru dari kelas ini menggunakan objek entri outline mesin internal. |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | Menginisialisasi instance item outline menggunakan objek hierarki akar. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Menambahkan item outline ke koleksi. |
| [clear](#clear--) | Menghapus semua item dari koleksi. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Belum didukung. Selalu melempar NotImplementedException |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Menyalin entri outline ke System.Array, dimulai pada indeks System.Array tertentu. |
| [delete](#delete--) | Menghapus item outline ini dari hierarki outline dokumen. |
| [delete](#delete-java.lang.String-) | Menghapus item outline ini dari hierarki outline dokumen. |
| [get_Item](#get_Item-int-) | Mendapatkan item outline dari koleksi menggunakan indeks. |
| [getAction](#getAction--) | Mendapatkan aksi untuk item outline ini. |
| [getBold](#getBold--) | Mendapatkan flag tebal untuk teks judul item outline ini |
| [getColor](#getColor--) | Mendapatkan warna untuk teks judul item outline ini. |
| [getDestination](#getDestination--) | Mendapatkan tujuan untuk item outline ini. |
| [getEngineDict](#getEngineDict--) | Hanya internal |
| [getEngineObj](#getEngineObj--) | Hanya internal |
| [getFirst](#getFirst--) | Mendapatkan item outline yang mewakili item tingkat atas pertama dalam hierarki outline. |
| [getItalic](#getItalic--) | Mendapatkan flag miring untuk teks judul item outline ini |
| [getLast](#getLast--) | Mendapatkan item outline yang mewakili item tingkat atas terakhir dalam hierarki outline. |
| [getLevel](#getLevel--) | Mendapatkan tingkat hierarki item outline. |
| [getNext](#getNext--) | Mendapatkan item outline yang mewakili item berikutnya relatif terhadap item ini dalam hierarki outline. |
| [getOpen](#getOpen--) | Dapatkan status terbuka (true/false) untuk item outline. |
| [getParent](#getParent--) | Mendapatkan objek induk dari item outline ini dalam hierarki outline. |
| [getPrev](#getPrev--) | Mendapatkan item outline yang mewakili item sebelumnya secara relatif terhadap item ini dalam hierarki outline. |
| [getSyncRoot](#getSyncRoot--) | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi ini. |
| [getTitle](#getTitle--) | Mendapatkan judul untuk item outline ini. |
| [getVisibleCount](#getVisibleCount--) | Mendapatkan total jumlah item outline pada semua tingkat dalam hierarki outline dokumen. |
| [hasNext](#hasNext--) | Periksa apakah item outline yang mewakili item berikutnya relatif terhadap item ini dalam hierarki outline. |
| [insert](#insert-int-com.aspose.pdf.OutlineItemCollection-) | Menyisipkan item outline ke dalam koleksi pada tempat yang ditentukan. |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only. |
| [isSynchronized](#isSynchronized--) | Mendapatkan nilai yang menunjukkan apakah akses ke koleksi ini disinkronkan (aman untuk thread). |
| [iterator](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [next](#next--) |  |
| [remove](#remove-int-) | Hapus item berdasarkan indeks. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Belum didukung. Selalu melempar NotImplementedException |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Mengatur aksi untuk item outline ini. |
| [setBold](#setBold-boolean-) | Mengatur flag tebal untuk teks judul item outline ini |
| [setColor](#setColor-java.awt.Color-) | Mengatur warna untuk teks judul item outline ini. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Mengatur tujuan untuk item outline ini. |
| [setItalic](#setItalic-boolean-) | Mengatur flag miring untuk teks judul item outline ini |
| [setOpen](#setOpen-boolean-) | Mengatur status terbuka (true/false) untuk item outline. |
| [setTitle](#setTitle-java.lang.String-) | Mengatur judul untuk item outline ini. |
| [size](#size--) | Jumlah item dalam koleksi. Harap jangan bingungkan dengan VisibleCount: VisibleCount mendapatkan jumlah item outline yang terlihat pada semua tingkat. |

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
Menginisialisasi instance baru dari kelas ini menggunakan objek entri outline mesin internal.

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
Menginisialisasi instance item outline menggunakan objek hierarki akar.

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Menambahkan item outline ke koleksi.

### clear {#clear--}
```
public void clear()
```

Menghapus semua item dari koleksi.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Belum didukung. Selalu melempar NotImplementedException

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Menyalin entri outline ke System.Array, dimulai pada indeks System.Array tertentu.

### delete {#delete--}
```
public void delete()
```

Menghapus item outline ini dari hierarki outline dokumen.

### delete {#delete-java.lang.String-}
Menghapus item outline ini dari hierarki outline dokumen.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Mendapatkan item outline dari koleksi menggunakan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks dalam koleksi. |

**Returns:**
Objek OutlineItemCollection.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Mendapatkan aksi untuk item outline ini.

**Returns:**
Nilai PdfAction

### getBold {#getBold--}
```
public boolean getBold()
```

Mendapatkan flag tebal untuk teks judul item outline ini

**Returns:**
nilai boolean

### getColor {#getColor--}
```
public Color getColor()
```

Mendapatkan warna untuk teks judul item outline ini.

**Returns:**
Nilai warna

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Mendapatkan tujuan untuk item outline ini.

**Returns:**
nilai IAppointment

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Hanya internal

**Returns:**
objek IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Hanya internal

**Returns:**
Objek IPdfObject

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Mendapatkan item outline yang mewakili item tingkat atas pertama dalam hierarki outline.

**Returns:**
Nilai OutlineItemCollection

### getItalic {#getItalic--}
```
public boolean getItalic()
```

Mendapatkan flag miring untuk teks judul item outline ini

**Returns:**
nilai boolean

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Mendapatkan item outline yang mewakili item tingkat atas terakhir dalam hierarki outline.

**Returns:**
Nilai OutlineItemCollection

### getLevel {#getLevel--}
```
public int getLevel()
```

Mendapatkan tingkat hierarki item outline.

**Returns:**
nilai int

### getNext {#getNext--}
```
public OutlineItemCollection getNext()
```

Mendapatkan item outline yang mewakili item berikutnya relatif terhadap item ini dalam hierarki outline.

**Returns:**
Nilai OutlineItemCollection

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Dapatkan status terbuka (true/false) untuk item outline.

**Returns:**
nilai boolean

### getParent {#getParent--}
```
public Outlines getParent()
```

Mendapatkan objek induk dari item outline ini dalam hierarki outline.

**Returns:**
Nilai Object

### getPrev {#getPrev--}
```
public OutlineItemCollection getPrev()
```

Mendapatkan item outline yang mewakili item sebelumnya secara relatif terhadap item ini dalam hierarki outline.

**Returns:**
Nilai OutlineItemCollection

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi ini.

**Returns:**
Nilai Object

### getTitle {#getTitle--}
```
public String getTitle()
```

Mendapatkan judul untuk item outline ini.

**Returns:**
nilai String

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Mendapatkan total jumlah item outline pada semua tingkat dalam hierarki outline dokumen.

**Returns:**
nilai int

### hasNext {#hasNext--}
```
public final boolean hasNext()
```

Periksa apakah item outline yang mewakili item berikutnya relatif terhadap item ini dalam hierarki outline.

**Returns:**
nilai boolean

### insert {#insert-int-com.aspose.pdf.OutlineItemCollection-}
Menyisipkan item outline ke dalam koleksi pada tempat yang ditentukan.

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
Belum didukung. Selalu melempar NotImplementedException

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Mengatur aksi untuk item outline ini.

### setBold {#setBold-boolean-}
```
public void setBold(boolean value)
```

Mengatur flag tebal untuk teks judul item outline ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setColor {#setColor-java.awt.Color-}
Mengatur warna untuk teks judul item outline ini.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Mengatur tujuan untuk item outline ini.

### setItalic {#setItalic-boolean-}
```
public void setItalic(boolean value)
```

Mengatur flag miring untuk teks judul item outline ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Mengatur status terbuka (true/false) untuk item outline.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setTitle {#setTitle-java.lang.String-}
Mengatur judul untuk item outline ini.

### size {#size--}
```
public int size()
```

Jumlah item dalam koleksi. Harap jangan bingungkan dengan VisibleCount: VisibleCount mendapatkan jumlah item outline yang terlihat pada semua tingkat.

**Returns:**
nilai int

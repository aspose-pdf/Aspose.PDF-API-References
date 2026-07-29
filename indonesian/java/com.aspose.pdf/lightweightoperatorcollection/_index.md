---
title: "LightweightOperatorCollection"
linktitle: "LightweightOperatorCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Koleksi operator ringan. Dimaksudkan untuk digunakan dalam skenario ketika aliran konten dasar tidak terlampir, di mana hanya koleksi operator yang diperlukan sebagai hasil."
type: docs
weight: 2700
url: /id/java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.LightweightOperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.LightweightOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

Koleksi operator ringan. Dimaksudkan untuk digunakan dalam skenario ketika aliran konten dasar tidak terlampir, di mana hanya koleksi operator yang diperlukan sebagai hasil.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LightweightOperatorCollection](#LightweightOperatorCollection--) | Inisialisasi objek |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-) | Inisialisasi objek |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | Inisialisasi objek |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Tambahkan operator |
| [addRange](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | Tambahkan LightweightOperatorCollection |
| [cancelUpdate](#cancelUpdate--) | Membatalkan pembaruan terakhir. Metode ini dapat dipanggil ketika perubahan tidak seharusnya memicu pembaruan konten. |
| [clear](#clear--) | Menghapus koleksi. |
| [contains](#contains-com.aspose.pdf.Operator-) | Periksa apakah item berada dalam koleksi. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | hapus internal Unrestrictedelement |
| [get_Item](#get_Item-int-) | <p> Mendapatkan operator berdasarkan indeksnya. </p> <hr> <pre> Contoh menunjukkan cara mendapatkan operator dari konten halaman berdasarkan indeks. Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Untuk penggunaan internal getUnrestricted operator |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Sisipkan operator |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Menunjukkan apakah koleksi dibatasi untuk ekstraksi teks cepat |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only. |
| [iterator](#iterator--) | Kembalikan iterator |
| [remove](#remove-com.aspose.pdf.Operator-) | Menghapus operator dari koleksi. |
| [resumeUpdate](#resumeUpdate--) | Melanjutkan pembaruan dokumen. Memperbarui aliran konten jika ada perubahan yang tertunda. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Mengatur operator berdasarkan indeksnya. <hr> <pre> Contoh menunjukkan cara mendapatkan operator dari konten halaman berdasarkan indeks. Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [size](#size--) | Jumlah operator |
| [suppressUpdate](#suppressUpdate--) | Menekan pembaruan data konten. Aliran konten tidak diperbarui sampai ResumeUpdate dipanggil. |
| [toList](#toList--) | Mengembalikan daftar operator. |
| [updateData](#updateData--) | internal |

### LightweightOperatorCollection {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```

Inisialisasi objek

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-}
Inisialisasi objek

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
Inisialisasi objek

### add {#add-com.aspose.pdf.Operator-}
Tambahkan operator

### addRange {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
Tambahkan LightweightOperatorCollection

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Membatalkan pembaruan terakhir. Metode ini dapat dipanggil ketika perubahan tidak seharusnya memicu pembaruan konten.

### clear {#clear--}
```
public void clear()
```

Menghapus koleksi.

### contains {#contains-com.aspose.pdf.Operator-}
Periksa apakah item berada dalam koleksi.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

hapus internal Unrestrictedelement

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | nilai int |

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Mendapatkan operator berdasarkan indeksnya. </p> <hr> <pre> Contoh menunjukkan cara mendapatkan operator dari konten halaman berdasarkan indeks. Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks operator. Penomoran dimulai dari 1. |

**Returns:**
Operator dari indeks yang diminta

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

Untuk penggunaan internal getUnrestricted operator

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | nilai int |

**Returns:**
Objek operator

### insert {#insert-int-com.aspose.pdf.Operator-}
Sisipkan operator

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Menunjukkan apakah koleksi dibatasi untuk ekstraksi teks cepat

**Returns:**
nilai boolean

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only.

**Returns:**
nilai boolean

### iterator {#iterator--}
```
public Iterator < Operator > iterator()
```

Kembalikan iterator

**Returns:**
{@code IGenericEnumerator<Operator>} objek

### remove {#remove-com.aspose.pdf.Operator-}
Menghapus operator dari koleksi.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Melanjutkan pembaruan dokumen. Memperbarui aliran konten jika ada perubahan yang tertunda.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Mengatur operator berdasarkan indeksnya. <hr> <pre> Contoh menunjukkan cara mendapatkan operator dari konten halaman berdasarkan indeks. Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

### size {#size--}
```
public int size()
```

Jumlah operator

**Returns:**
nilai int

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Menekan pembaruan data konten. Aliran konten tidak diperbarui sampai ResumeUpdate dipanggil.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Mengembalikan daftar operator.

**Returns:**
daftar operator.

### updateData {#updateData--}
```
public void updateData()
```

internal

---
title: "BaseOperatorCollection"
linktitle: "BaseOperatorCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas dasar untuk koleksi operator."
type: docs
weight: 270
url: /id/java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public abstract class BaseOperatorCollection extends Object implements Iterable < Operator >
```

Mewakili kelas dasar untuk koleksi operator.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BaseOperatorCollection](#BaseOperatorCollection--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Menambahkan operator baru ke dalam koleksi. |
| [cancelUpdate](#cancelUpdate--) | Membatalkan pembaruan terakhir. Metode ini dapat dipanggil ketika perubahan tidak seharusnya memicu pembaruan konten. |
| [clear](#clear--) | Menghapus koleksi. |
| [contains](#contains-com.aspose.pdf.Operator-) | Periksa apakah item berada dalam koleksi. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | internal |
| [get_Item](#get_Item-int-) | Mendapatkan operator berdasarkan indeksnya. |
| [getUnrestricted](#getUnrestricted-int-) | Hanya untuk penggunaan internal |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Menyisipkan operator ke dalam koleksi. |
| [isEmpty](#isEmpty--) | Mengembalikan TRUE jika koleksi kosong. |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Menunjukkan apakah koleksi dibatasi untuk ekstraksi teks cepat |
| [isReadOnly](#isReadOnly--) | Mengembalikan true jika koleksi hanya-baca. |
| [iterator](#iterator--) | Mengembalikan enumerator untuk koleksi. |
| [remove](#remove-com.aspose.pdf.Operator-) | Menghapus operator dari koleksi. |
| [resumeUpdate](#resumeUpdate--) | Melanjutkan pembaruan dokumen. Memperbarui aliran konten jika ada perubahan yang tertunda. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Menetapkan operator berdasarkan indeksnya. |
| [size](#size--) | Mengambil jumlah operator dalam koleksi. |
| [suppressUpdate](#suppressUpdate--) | Menekan pembaruan data konten. Aliran konten tidak diperbarui sampai ResumeUpdate dipanggil. |
| [toList](#toList--) | Mengembalikan daftar operator. |
| [updateData](#updateData--) | internal |

### BaseOperatorCollection {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```



### add {#add-com.aspose.pdf.Operator-}
Menambahkan operator baru ke dalam koleksi.

### cancelUpdate {#cancelUpdate--}
```
public abstract void cancelUpdate()
```

Membatalkan pembaruan terakhir. Metode ini dapat dipanggil ketika perubahan tidak seharusnya memicu pembaruan konten.

### clear {#clear--}
```
public abstract void clear()
```

Menghapus koleksi.

### contains {#contains-com.aspose.pdf.Operator-}
Periksa apakah item berada dalam koleksi.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```

internal

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | nilai int |

### get_Item {#get_Item-int-}
```
public abstract Operator get_Item(int index)
```

Mendapatkan operator berdasarkan indeksnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks operator. Penomoran dimulai dari 1. |

**Returns:**
Operator dari indeks yang diminta

### getUnrestricted {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```

Hanya untuk penggunaan internal

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | nilai int |

**Returns:**
Objek operator

### insert {#insert-int-com.aspose.pdf.Operator-}
Menyisipkan operator ke dalam koleksi.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Mengembalikan TRUE jika koleksi kosong.

**Returns:**
nilai boolean

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```

Menunjukkan apakah koleksi dibatasi untuk ekstraksi teks cepat

**Returns:**
nilai boolean

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

Mengembalikan true jika koleksi hanya-baca.

**Returns:**
nilai boolean

### iterator {#iterator--}
```
public abstract Iterator < Operator > iterator()
```

Mengembalikan enumerator untuk koleksi.

**Returns:**
Enumerator koleksi

### remove {#remove-com.aspose.pdf.Operator-}
Menghapus operator dari koleksi.

### resumeUpdate {#resumeUpdate--}
```
public abstract void resumeUpdate()
```

Melanjutkan pembaruan dokumen. Memperbarui aliran konten jika ada perubahan yang tertunda.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Menetapkan operator berdasarkan indeksnya.

### size {#size--}
```
public abstract int size()
```

Mengambil jumlah operator dalam koleksi.

**Returns:**
nilai integer

### suppressUpdate {#suppressUpdate--}
```
public abstract void suppressUpdate()
```

Menekan pembaruan data konten. Aliran konten tidak diperbarui sampai ResumeUpdate dipanggil.

### toList {#toList--}
```
public abstract com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Mengembalikan daftar operator.

**Returns:**
daftar operator.

### updateData {#updateData--}
```
public abstract void updateData()
```

internal

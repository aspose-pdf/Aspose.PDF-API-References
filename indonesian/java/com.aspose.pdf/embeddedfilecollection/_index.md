---
title: "EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili koleksi file tersemat."
type: docs
weight: 1200
url: /id/java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class EmbeddedFileCollection extends Object implements Iterable < FileSpecification >
```

Kelas yang mewakili koleksi file tersemat.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.FileSpecification-) | Menambahkan spesifikasi file tersemat ke dalam koleksi. |
| [add](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | Menambahkan file ke file tersemat dengan kunci yang ditentukan. |
| [clear](#clear--) | Hapus semua file tersemat dari dokumen. |
| [contains](#contains-com.aspose.pdf.FileSpecification-) | Menentukan apakah koleksi berisi FileSpecification yang ditentukan. Tidak didukung. |
| [copyTo](#copyTo-com.aspose.pdf.FileSpecification:A-int-) | Menyalin array objek FileSpecification ke dalam koleksi. |
| [delete](#delete--) | Hapus semua file tersemat dari dokumen. |
| [delete](#delete-java.lang.String-) | Hapus semua file tersemat dari dokumen. |
| [deleteByKey](#deleteByKey-java.lang.String-) | Menghapus file dari koleksi berdasarkan kuncinya dalam koleksi. |
| [findByName](#findByName-java.lang.String-) | Mengembalikan file tersemat berdasarkan namanya. |
| [get_Item](#get_Item-int-) | Mendapatkan file tersemat berdasarkan indeksnya. |
| [get_Item](#get_Item-java.lang.String-) | Mendapatkan file tersemat berdasarkan namanya. |
| [getKeys](#getKeys--) | Mengembalikan daftar kunci lampiran file. |
| [getSyncRoot](#getSyncRoot--) | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi ini. |
| [isEmbeddedFilesExist](#isEmbeddedFilesExist--) | Periksa apakah struktur File Tersemat ada. Kembalikan TRUE jika struktur ada, dan FALSE jika tidak. Jika dokumen belum pernah berisi file tersemat - struktur ini tidak dibuat dan tidak ada. |
| [isReadOnly](#isReadOnly--) | Menentukan apakah koleksi hanya-baca. Selalu mengembalikan false. |
| [isSynchronized](#isSynchronized--) | Mendapatkan nilai yang menunjukkan apakah akses ke koleksi ini disinkronkan (aman untuk thread). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Mengembalikan enumerator koleksi. |
| [iterator](#iterator--) | Mengembalikan enumerator koleksi. |
| [remove](#remove-com.aspose.pdf.FileSpecification-) | Menghapus FileSpecification yang ditentukan dari koleksi. Tidak didukung. |
| [size](#size--) | Mendapatkan jumlah file tersemat dalam koleksi. |

### add {#add-com.aspose.pdf.FileSpecification-}
Menambahkan spesifikasi file tersemat ke dalam koleksi.

### add {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
Menambahkan file ke file tersemat dengan kunci yang ditentukan.

### clear {#clear--}
```
public void clear()
```

Hapus semua file tersemat dari dokumen.

### contains {#contains-com.aspose.pdf.FileSpecification-}
Menentukan apakah koleksi berisi FileSpecification yang ditentukan. Tidak didukung.

### copyTo {#copyTo-com.aspose.pdf.FileSpecification:A-int-}
Menyalin array objek FileSpecification ke dalam koleksi.

### delete {#delete--}
```
public void delete()
```

Hapus semua file tersemat dari dokumen.

### delete {#delete-java.lang.String-}
Hapus semua file tersemat dari dokumen.

### deleteByKey {#deleteByKey-java.lang.String-}
Menghapus file dari koleksi berdasarkan kuncinya dalam koleksi.

### findByName {#findByName-java.lang.String-}
Mengembalikan file tersemat berdasarkan namanya.

### get_Item {#get_Item-int-}
```
public FileSpecification get_Item(int index)
```

Mendapatkan file tersemat berdasarkan indeksnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks file tersemat. Penomoran dimulai dari 1. |

**Returns:**
Spesifikasi file tersemat yang diambil

### get_Item {#get_Item-java.lang.String-}
Mendapatkan file tersemat berdasarkan namanya.

### getKeys {#getKeys--}
```
public final List < String > getKeys()
```

Mengembalikan daftar kunci lampiran file.

**Returns:**
Daftar nilai String

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi ini.

**Returns:**
Objek untuk sinkronisasi

### isEmbeddedFilesExist {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```

Periksa apakah struktur File Tersemat ada. Kembalikan TRUE jika struktur ada, dan FALSE jika tidak. Jika dokumen belum pernah berisi file tersemat - struktur ini tidak dibuat dan tidak ada.

**Returns:**
nilai boolean

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Menentukan apakah koleksi hanya-baca. Selalu mengembalikan false.

**Returns:**
nilai boolean

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Mendapatkan nilai yang menunjukkan apakah akses ke koleksi ini disinkronkan (aman untuk thread).

**Returns:**
nilai boolean

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< FileSpecification > iterator_Rename_Namesake()
```

Mengembalikan enumerator koleksi.

**Returns:**
Enumerator koleksi.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< FileSpecification > iterator()
```

Mengembalikan enumerator koleksi.

**Returns:**
Enumerator koleksi.

### remove {#remove-com.aspose.pdf.FileSpecification-}
Menghapus FileSpecification yang ditentukan dari koleksi. Tidak didukung.

### size {#size--}
```
public int size()
```

Mendapatkan jumlah file tersemat dalam koleksi.

**Returns:**
nilai int

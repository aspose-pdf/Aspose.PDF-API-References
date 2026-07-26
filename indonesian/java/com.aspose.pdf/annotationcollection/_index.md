---
title: "AnnotationCollection"
linktitle: "AnnotationCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili koleksi anotasi."
type: docs
weight: 80
url: /id/java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationCollection

**All Implemented Interfaces:**
Iterable < Annotation >

```
public final class AnnotationCollection extends Object implements Iterable < Annotation >
```

Kelas yang mewakili koleksi anotasi.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AnnotationCollection](#AnnotationCollection-com.aspose.pdf.Page-) | Konstruktor AnnotationCollection. Membuat koleksi anotasi untuk anotasi pada halaman yang diberikan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima visitor untuk memproses anotasi. |
| [add](#add-com.aspose.pdf.Annotation-) | Menambahkan anotasi ke koleksi. |
| [add](#add-com.aspose.pdf.Annotation-boolean-) | Menambahkan anotasi ke koleksi. Jika halaman diputar maka persegi panjang anotasi akan dihitung ulang secara sesuai. |
| [clear](#clear--) | Menghapus semua anotasi dari koleksi. |
| [contains](#contains-com.aspose.pdf.Annotation-) | Memeriksa apakah anotasi yang ditentukan termasuk dalam koleksi. |
| [copyTo](#copyTo-com.aspose.pdf.Annotation:A-int-) | Menyalin array anotasi ke dalam koleksi. |
| [delete](#delete--) | Menghapus semua anotasi dari koleksi. |
| [delete](#delete-com.aspose.pdf.Annotation-) | Menghapus semua anotasi dari koleksi. |
| [delete](#delete-int-) | Menghapus anotasi dari koleksi berdasarkan indeks. |
| [findByName](#findByName-java.lang.String-) | Mengembalikan anotasi berdasarkan namanya. |
| [get_Item](#get_Item-int-) | Indeks elemen yang ingin diambil. |
| [getSyncRoot](#getSyncRoot--) | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke com.aspose.pdf.AnnotationCollection. |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat hanya-baca. |
| [isSynchronized](#isSynchronized--) | Mendapatkan nilai yang menunjukkan apakah akses ke com.aspose.pdf.AnnotationCollection disinkronkan (aman untuk thread). |
| [iterator](#iterator--) | Mengembalikan enumerator koleksi. |
| [remove](#remove-com.aspose.pdf.Annotation-) | Menghapus anotasi yang ditentukan dari koleksi. |
| [size](#size--) | Mendapatkan jumlah anotasi dalam koleksi. |

### AnnotationCollection {#AnnotationCollection-com.aspose.pdf.Page-}
Konstruktor AnnotationCollection. Membuat koleksi anotasi untuk anotasi pada halaman yang diberikan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima visitor untuk memproses anotasi.

### add {#add-com.aspose.pdf.Annotation-}
Menambahkan anotasi ke koleksi.

### add {#add-com.aspose.pdf.Annotation-boolean-}
Menambahkan anotasi ke koleksi. Jika halaman diputar maka persegi panjang anotasi akan dihitung ulang secara sesuai.

### clear {#clear--}
```
public void clear()
```

Menghapus semua anotasi dari koleksi.

### contains {#contains-com.aspose.pdf.Annotation-}
Memeriksa apakah anotasi yang ditentukan termasuk dalam koleksi.

### copyTo {#copyTo-com.aspose.pdf.Annotation:A-int-}
Menyalin array anotasi ke dalam koleksi.

### delete {#delete--}
```
public void delete()
```

Menghapus semua anotasi dari koleksi.

### delete {#delete-com.aspose.pdf.Annotation-}
Menghapus semua anotasi dari koleksi.

### delete {#delete-int-}
```
public void delete(int index)
```

Menghapus anotasi dari koleksi berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks anotasi yang akan dihapus. |

### findByName {#findByName-java.lang.String-}
Mengembalikan anotasi berdasarkan namanya.

### get_Item {#get_Item-int-}
```
public Annotation get_Item(int index)
```

Indeks elemen yang ingin diambil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Nilai indeks dimulai dari satu. |

**Returns:**
Objek anotasi

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke com.aspose.pdf.AnnotationCollection.

**Returns:**
Objek untuk sinkronisasi

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah koleksi bersifat hanya-baca.

**Returns:**
nilai boolean

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Mendapatkan nilai yang menunjukkan apakah akses ke com.aspose.pdf.AnnotationCollection disinkronkan (aman untuk thread).

**Returns:**
nilai boolean

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Annotation > iterator()
```

Mengembalikan enumerator koleksi.

**Returns:**
Objek enumerator

### remove {#remove-com.aspose.pdf.Annotation-}
Menghapus anotasi yang ditentukan dari koleksi.

### size {#size--}
```
public int size()
```

Mendapatkan jumlah anotasi dalam koleksi.

**Returns:**
nilai int

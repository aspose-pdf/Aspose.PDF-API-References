---
title: "PageCollection"
linktitle: "PageCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kumpulan halaman dokumen PDF."
type: docs
weight: 3340
url: /id/java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageCollection

**All Implemented Interfaces:**
Iterable < Page >

```
public final class PageCollection extends Object implements Iterable < Page >
```

Kumpulan halaman dokumen PDF.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima objek pengunjung {@code AnnotationSelector} yang menyediakan fungsionalitas untuk bekerja dengan anotasi. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Menerima objek pengunjung {@code ImagePlacementAbsorber} yang menyediakan fungsionalitas untuk bekerja dengan objek penempatan gambar. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Menerima objek pengunjung {@code TextAbsorber} yang menyediakan fungsionalitas untuk bekerja dengan objek teks. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Menerima objek pengunjung {@code TextFragmentAbsorber} yang menyediakan fungsionalitas untuk bekerja dengan objek teks. |
| [add_Rename_Namesake](#add_Rename_Namesake-com.aspose.pdf.Page-) | Menambahkan halaman ke koleksi. |
| [add](#add--) | Menambahkan halaman kosong. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan. |
| [add](#add-java.lang.Iterable-) | Menambahkan halaman kosong. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan. |
| [add](#add-java.util.List-) | Menambahkan halaman kosong. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan. |
| [add](#add-com.aspose.pdf.Page-) | Menambahkan halaman kosong. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan. |
| [add](#add-com.aspose.pdf.Page:A-) | Menambahkan halaman kosong. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan. |
| [beginUpdate](#beginUpdate--) | Memperbarui saat perubahan grup dimulai. |
| [clear](#clear--) | Menghapus koleksi halaman. |
| [contains](#contains-com.aspose.pdf.Page-) | Menentukan apakah instance ini berisi objek tersebut. |
| [copyTo](#copyTo-com.aspose.pdf.Page:A-int-) | Menyalin halaman ke dalam dokumen. |
| [delete](#delete--) | Menghapus semua halaman dari koleksi. |
| [delete](#delete-int-) | Menghapus halaman yang ditentukan. |
| [delete](#delete-java.lang.Integer:A-) | Menghapus semua halaman dari koleksi. |
| [endUpdate](#endUpdate--) | Memperbarui saat perubahan grup selesai. |
| [findByPdfObject](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten](#flatten--) | Menghapus semua bidang yang terletak pada halaman dan menempatkan nilai mereka sebagai gantinya. |
| [freeMemory](#freeMemory--) | Menghapus data yang di-cache |
| [get_Item](#get_Item-int-) | Mengambil halaman berdasarkan indeks. |
| [getSyncRoot](#getSyncRoot--) | Mengambil objek sinkronisasi dari koleksi. |
| [getUnrestricted](#getUnrestricted-int-) | Mengembalikan halaman berdasarkan indeksnya. {@code Page} |
| [indexOf](#indexOf-com.aspose.pdf.Page-) | <p> Mengembalikan indeks halaman yang ditentukan. </p> |
| [insert](#insert-int-) | Menyisipkan halaman kosong ke dalam koleksi pada posisi yang ditentukan. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan. |
| [insert](#insert-int-java.lang.Iterable-) | Menyisipkan halaman dari koleksi ke dalam dokumen. |
| [insert](#insert-int-java.util.List-) | Menyisipkan halaman dari koleksi ke dalam dokumen. |
| [insert](#insert-int-com.aspose.pdf.Page-) | Menyisipkan halaman ke dalam koleksi halaman pada tempat yang ditentukan. |
| [insert](#insert-int-com.aspose.pdf.Page:A-) | Menyisipkan halaman dari array ke dalam dokumen. |
| [isEmpty](#isEmpty--) | Mengembalikan TRUE jika koleksi kosong. |
| [isReadOnly](#isReadOnly--) | Mengambil nilai yang menunjukkan apakah koleksi bersifat hanya-baca. Selalu mengembalikan false. |
| [isSynchronized](#isSynchronized--) | Mengembalikan true jika objek disinkronkan. |
| [iterator](#iterator--) | Mengembalikan enumerator halaman. |
| [remove](#remove-com.aspose.pdf.Page-) | Menghapus item yang ditentukan, melempar pengecualian. |
| [size](#size--) | Mendapatkan jumlah halaman dalam dokumen. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima objek pengunjung {@code AnnotationSelector} yang menyediakan fungsionalitas untuk bekerja dengan anotasi.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Menerima objek pengunjung {@code ImagePlacementAbsorber} yang menyediakan fungsionalitas untuk bekerja dengan objek penempatan gambar.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Menerima objek pengunjung {@code TextAbsorber} yang menyediakan fungsionalitas untuk bekerja dengan objek teks.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Menerima objek pengunjung {@code TextFragmentAbsorber} yang menyediakan fungsionalitas untuk bekerja dengan objek teks.

### add_Rename_Namesake {#add_Rename_Namesake-com.aspose.pdf.Page-}
Menambahkan halaman ke koleksi.

### add {#add--}
```
public Page add()
```

Menambahkan halaman kosong. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan.

**Returns:**
Halaman ditambahkan.

### add {#add-java.lang.Iterable-}
Menambahkan halaman kosong. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan.

**Returns:**
Halaman ditambahkan.

### add {#add-java.util.List-}
Menambahkan halaman kosong. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan.

**Returns:**
Halaman ditambahkan.

### add {#add-com.aspose.pdf.Page-}
Menambahkan halaman kosong. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan.

**Returns:**
Halaman ditambahkan.

### add {#add-com.aspose.pdf.Page:A-}
Menambahkan halaman kosong. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan.

**Returns:**
Halaman ditambahkan.

### beginUpdate {#beginUpdate--}
```
public final void beginUpdate()
```

Memperbarui saat perubahan grup dimulai.

### clear {#clear--}
```
public void clear()
```

Menghapus koleksi halaman.

### contains {#contains-com.aspose.pdf.Page-}
Menentukan apakah instance ini berisi objek tersebut.

### copyTo {#copyTo-com.aspose.pdf.Page:A-int-}
Menyalin halaman ke dalam dokumen.

### delete {#delete--}
```
public void delete()
```

Menghapus semua halaman dari koleksi.

### delete {#delete-int-}
```
public void delete(int index)
```

Menghapus halaman yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Nomor halaman yang akan dihapus. Nomor halaman dimulai dari 1. |

### delete {#delete-java.lang.Integer:A-}
Menghapus semua halaman dari koleksi.

### endUpdate {#endUpdate--}
```
public final void endUpdate()
```

Memperbarui saat perubahan grup selesai.

### findByPdfObject {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}


### flatten {#flatten--}
```
public void flatten()
```

Menghapus semua bidang yang terletak pada halaman dan menempatkan nilai mereka sebagai gantinya.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Menghapus data yang di-cache

### get_Item {#get_Item-int-}
```
public Page get_Item(int index)
```

Mengambil halaman berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks halaman. |

**Returns:**
Halaman diambil.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Mengambil objek sinkronisasi dari koleksi.

**Returns:**
Objek untuk sinkronisasi

### getUnrestricted {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```

Mengembalikan halaman berdasarkan indeksnya. {@code Page}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks halaman yang diminta. Halaman diberi nomor mulai dari 1. |

**Returns:**
Halaman yang diminta

### indexOf {#indexOf-com.aspose.pdf.Page-}
<p> Mengembalikan indeks halaman yang ditentukan. </p>

### insert {#insert-int-}
```
public Page insert(int pageNumber)
```

Menyisipkan halaman kosong ke dalam koleksi pada posisi yang ditentukan. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Posisi halaman baru. |

**Returns:**
Halaman disisipkan.

### insert {#insert-int-java.lang.Iterable-}
Menyisipkan halaman dari koleksi ke dalam dokumen.

### insert {#insert-int-java.util.List-}
Menyisipkan halaman dari koleksi ke dalam dokumen.

### insert {#insert-int-com.aspose.pdf.Page-}
Menyisipkan halaman ke dalam koleksi halaman pada tempat yang ditentukan.

### insert {#insert-int-com.aspose.pdf.Page:A-}
Menyisipkan halaman dari array ke dalam dokumen.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Mengembalikan TRUE jika koleksi kosong.

**Returns:**
nilai boolean

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Mengambil nilai yang menunjukkan apakah koleksi bersifat hanya-baca. Selalu mengembalikan false.

**Returns:**
nilai boolean

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Mengembalikan true jika objek disinkronkan.

**Returns:**
nilai boolean

### iterator {#iterator--}
```
public Iterator < Page > iterator()
```

Mengembalikan enumerator halaman.

**Returns:**
Enumerator halaman

### remove {#remove-com.aspose.pdf.Page-}
Menghapus item yang ditentukan, melempar pengecualian.

### size {#size--}
```
public int size()
```

Mendapatkan jumlah halaman dalam dokumen.

**Returns:**
nilai int

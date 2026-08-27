---
title: "OperatorCollection"
linktitle: "OperatorCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas mewakili kumpulan operator"
type: docs
weight: 3190
url: /id/java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.OperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.OperatorCollection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Iterable < Operator >

```
public class OperatorCollection extends BaseOperatorCollection implements com.aspose.ms.System.IDisposable
```

Kelas mewakili kumpulan operator

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | Hanya untuk penggunaan internal! |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-) | Hanya untuk penggunaan internal! |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung IOperatorSelector untuk memproses operator. |
| [add](#add-java.lang.Iterable-) | Menambahkan ke koleksi semua operator dari koleksi lain. |
| [add](#add-com.aspose.pdf.Operator-) | <p> Menambahkan operator baru ke dalam koleksi. </p> <hr> <p> Contoh menunjukkan cara menambahkan operator ke akhir page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p> |
| [add](#add-com.aspose.pdf.Operator:A-) | <p> Menambahkan operator di akhir konten. </p> <hr> <p> Contoh menunjukkan cara menambahkan operator ke akhir konten halaman. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [cancelUpdate](#cancelUpdate--) | Membatalkan pembaruan terakhir. Metode ini dapat dipanggil ketika perubahan tidak seharusnya memicu pembaruan konten. |
| [clear](#clear--) | <p> Menghapus semua operator dari daftar. </p> <hr> <p> Contoh menunjukkan cara membersihkan konten halaman. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p> |
| [close](#close--) | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mengatur ulang sumber daya yang tidak dikelola. |
| [contains](#contains-com.aspose.pdf.Operator-) | Mengembalikan true jika koleksi berisi operator yang diberikan. |
| [delete](#delete-int-) | <p> Menghapus operator dari koleksi. </p> <hr> <p> Contoh menunjukkan cara menghapus operator berdasarkan indeksnya. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p> |
| [delete](#delete-java.lang.Iterable-) | Menghapus operator dari koleksi. |
| [delete](#delete-com.aspose.pdf.Operator:A-) | <p> Menghapus operator dari koleksi. </p> <hr> <p> Contoh menunjukkan cara menghapus operator dari konten halaman. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p> |
| [deleteUnrestricted](#deleteUnrestricted-int-) | versi internal tanpa batasan dari Delete(index) |
| [dispose](#dispose--) | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mengatur ulang sumber daya yang tidak dikelola. |
| [get_Item](#get_Item-int-) | <p> Mendapatkan operator berdasarkan indeksnya. </p> <hr> Contoh menunjukkan cara mendapatkan operator dari konten halaman berdasarkan indeks. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Versi internal tanpa batasan dari pengindeks. |
| [insert](#insert-int-java.lang.Iterable-) | Menyisipkan operator pada posisi yang diberikan. |
| [insert](#insert-int-com.aspose.pdf.Operator-) | <p> Menyisipkan operator ke dalam koleksi. </p> <hr> <p> Contoh menunjukkan cara menyisipkan operator ke konten halaman. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p> |
| [insert](#insert-int-com.aspose.pdf.Operator:A-) | <p> Menyisipkan operator pada posisi yang diberikan. </p> <hr> <p> Contoh menunjukkan cara menyisipkan operator ke konten halaman. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [isBracketed](#isBracketed--) | Mendapatkan status berkurung dari urutan operator, yaitu apakah operator-operator ini berada di dalam blok q - Q. |
| [isCommandsParsed](#isCommandsParsed--) | Mendapatkan perintah yang diurai. |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Menunjukkan apakah koleksi dibatasi untuk ekstraksi teks cepat. |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only. |
| [iterator](#iterator--) | Mengembalikan enumerator untuk koleksi. |
| [precalculateOperatorsCount](#precalculateOperatorsCount--) | Mendapatkan jumlah operator yang mendeskripsikan konten halaman tanpa inisialisasi mereka. |
| [remove](#remove-com.aspose.pdf.Operator-) | Menghapus operator dari koleksi. |
| [replace](#replace-java.lang.Iterable-) | Mengganti operator dalam koleksi dengan operator lain. |
| [replace](#replace-com.aspose.pdf.Operator:A-) | Mengganti operator dalam koleksi dengan operator lain. |
| [resumeUpdate](#resumeUpdate--) | Melanjutkan pembaruan dokumen. Memperbarui aliran konten jika ada perubahan yang tertunda. |
| [resumeUpdate](#resumeUpdate-boolean-) | Melanjutkan pembaruan dokumen. Memperbarui aliran konten jika ada perubahan yang tertunda. Menandai semua operator sebagai "changed" jika parameter invalidate bernilai true. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Menetapkan operator berdasarkan indeksnya. |
| [size](#size--) | Mengambil jumlah operator dalam koleksi. |
| [suppressUpdate](#suppressUpdate--) | Menekan pembaruan data konten. Aliran konten tidak diperbarui sampai ResumeUpdate dipanggil. |
| [toList](#toList--) | Mengembalikan daftar operator. |
| [toString](#toString--) | Mengembalikan representasi teks dari operator. |
| [updateData](#updateData--) | Perbarui aliran objek. |
| [updateNormalizedData](#updateNormalizedData--) | Perbarui aliran objek dengan memperbaiki operator GSave/GRestore yang tidak ada. |

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
Hanya untuk penggunaan internal!

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-}
Hanya untuk penggunaan internal!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung IOperatorSelector untuk memproses operator.

### add {#add-java.lang.Iterable-}
Menambahkan ke koleksi semua operator dari koleksi lain.

### add {#add-com.aspose.pdf.Operator-}
<p> Menambahkan operator baru ke dalam koleksi. </p> <hr> <p> Contoh menunjukkan cara menambahkan operator ke akhir page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p>

### add {#add-com.aspose.pdf.Operator:A-}
<p> Menambahkan operator di akhir konten. </p> <hr> <p> Contoh menunjukkan cara menambahkan operator ke akhir konten halaman. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Membatalkan pembaruan terakhir. Metode ini dapat dipanggil ketika perubahan tidak seharusnya memicu pembaruan konten.

### clear {#clear--}
```
public void clear()
```

<p> Menghapus semua operator dari daftar. </p> <hr> <p> Contoh menunjukkan cara membersihkan konten halaman. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p>

### close {#close--}
```
public final void close()
```

Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mengatur ulang sumber daya yang tidak dikelola.

### contains {#contains-com.aspose.pdf.Operator-}
Mengembalikan true jika koleksi berisi operator yang diberikan.

### delete {#delete-int-}
```
public void delete(int index)
```

<p> Menghapus operator dari koleksi. </p> <hr> <p> Contoh menunjukkan cara menghapus operator berdasarkan indeksnya. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks operator yang harus dihapus. Penomoran operator dimulai dari 1. |

### delete {#delete-java.lang.Iterable-}
Menghapus operator dari koleksi.

### delete {#delete-com.aspose.pdf.Operator:A-}
<p> Menghapus operator dari koleksi. </p> <hr> <p> Contoh menunjukkan cara menghapus operator dari konten halaman. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p>

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

versi internal tanpa batasan dari Delete(index)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | nilai int |

### dispose {#dispose--}
```
public final void dispose()
```

Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau mengatur ulang sumber daya yang tidak dikelola.

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Mendapatkan operator berdasarkan indeksnya. </p> <hr> Contoh menunjukkan cara mendapatkan operator dari konten halaman berdasarkan indeks. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre>

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

Versi internal tanpa batasan dari pengindeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | nilai int |

**Returns:**
Objek operator

### insert {#insert-int-java.lang.Iterable-}
Menyisipkan operator pada posisi yang diberikan.

### insert {#insert-int-com.aspose.pdf.Operator-}
<p> Menyisipkan operator ke dalam koleksi. </p> <hr> <p> Contoh menunjukkan cara menyisipkan operator ke konten halaman. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p>

### insert {#insert-int-com.aspose.pdf.Operator:A-}
<p> Menyisipkan operator pada posisi yang diberikan. </p> <hr> <p> Contoh menunjukkan cara menyisipkan operator ke konten halaman. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### isBracketed {#isBracketed--}
```
public boolean isBracketed()
```

Mendapatkan status berkurung dari urutan operator, yaitu apakah operator-operator ini berada di dalam blok q - Q.

**Returns:**
nilai boolean

### isCommandsParsed {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```

Mendapatkan perintah yang diurai.

**Returns:**
nilai boolean

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Menunjukkan apakah koleksi dibatasi untuk ekstraksi teks cepat.

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
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Operator > iterator()
```

Mengembalikan enumerator untuk koleksi.

**Returns:**
Enumerator koleksi

### precalculateOperatorsCount {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```

Mendapatkan jumlah operator yang mendeskripsikan konten halaman tanpa inisialisasi mereka.

**Returns:**
nilai int

### remove {#remove-com.aspose.pdf.Operator-}
Menghapus operator dari koleksi.

### replace {#replace-java.lang.Iterable-}
Mengganti operator dalam koleksi dengan operator lain.

### replace {#replace-com.aspose.pdf.Operator:A-}
Mengganti operator dalam koleksi dengan operator lain.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Melanjutkan pembaruan dokumen. Memperbarui aliran konten jika ada perubahan yang tertunda.

### resumeUpdate {#resumeUpdate-boolean-}
```
public final void resumeUpdate(boolean updateAll)
```

Melanjutkan pembaruan dokumen. Memperbarui aliran konten jika ada perubahan yang tertunda. Menandai semua operator sebagai "changed" jika parameter invalidate bernilai true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| updateAll |  | Jika true, semua operator dalam koleksi ditandai sebagai diperbarui. |

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Menetapkan operator berdasarkan indeksnya.

### size {#size--}
```
public int size()
```

Mengambil jumlah operator dalam koleksi.

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

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi teks dari operator.

**Returns:**
Representasi teks dari operator.

### updateData {#updateData--}
```
public void updateData()
```

Perbarui aliran objek.

### updateNormalizedData {#updateNormalizedData--}
```
public void updateNormalizedData()
```

Perbarui aliran objek dengan memperbaiki operator GSave/GRestore yang tidak ada.

---
title: "CosPdfDictionary"
linktitle: "CosPdfDictionary"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas untuk mengakses kamus objek."
type: docs
weight: 20
url: /id/java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

Kelas untuk mengakses kamus objek.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | Membuat kamus dari sumber daya. @exception ArgumentNullException Sumber daya bernilai null. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Setel ICosPdfPrimitive ke kamus. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Setel {@link ICosPdfPrimitive} ke kamus. @exception ArgumentException Melempar pengecualian jika kunci/nilai tidak dapat diedit atau dihapus. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Tambahkan pasangan item. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Tambahkan item. |
| [clear](#clear--) | Menghapus semua item dari {@link CosPdfDictionary}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menentukan apakah CosPdfDictionary berisi nilai tertentu. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Kembalikan true jika berisi item |
| [containsKey](#containsKey-java.lang.String-) | Menentukan apakah {@link CosPdfDictionary} berisi elemen dengan kunci yang ditentukan. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Menyalin elemen-elemen CosPdfDictionary ke dalam Array, mulai dari indeks Array tertentu. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Salin ke Array |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | Membuat kamus kosong yang akan dilampirkan ke dokumen. |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | Membuat kamus kosong yang akan dilampirkan ke halaman. |
| [get_Item](#get_Item-java.lang.String-) | Mendapatkan atau mengatur elemen dengan kunci yang ditentukan. |
| [getAllKeys](#getAllKeys--) | Koleksi lengkap kunci. Berisi kunci yang dapat diedit dan tidak dapat diedit. |
| [getKeys](#getKeys--) | Koleksi kunci yang dapat diedit. |
| [getValues](#getValues--) | Mendapatkan {@link ICollection} yang berisi nilai-nilai dalam {@link CosPdfDictionary}. |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah {@link CosPdfDictionary} bersifat read-only. |
| [iterator](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menghapus kemunculan pertama dari objek tertentu dari CosPdfDictionary. |
| [remove](#remove-java.lang.String-) | Menghapus elemen dengan kunci yang ditentukan dari {@link CosPdfDictionary}. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Hapus Item |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Hapus item berdasarkan kunci. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Mendapatkan atau mengatur elemen dengan kunci yang ditentukan. @exception ArgumentNullException Kunci bernilai null. @exception KeyNotFoundException Properti diambil dan kunci tidak ditemukan. @exception ArgumentException Melempar pengecualian jika kunci tidak dapat diedit/diatur. |
| [size](#size--) | Mendapatkan jumlah elemen yang terdapat dalam {@link CosPdfDictionary}. |
| [toCosPdfDictionary](#toCosPdfDictionary--) | Mencoba meng-cast instance ini ke {@link CosPdfDictionary}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Untuk mengakses tipe data sederhana seperti string, nama, bool, number. Mengembalikan null untuk tipe lain. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Coba dapatkan nilai |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
Membuat kamus dari sumber daya. @exception ArgumentNullException Sumber daya bernilai null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Setel ICosPdfPrimitive ke kamus.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Setel {@link ICosPdfPrimitive} ke kamus. @exception ArgumentException Melempar pengecualian jika kunci/nilai tidak dapat diedit atau dihapus.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Tambahkan pasangan item.

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Tambahkan item.

### clear {#clear--}
```
public final void clear()
```

Menghapus semua item dari {@link CosPdfDictionary}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menentukan apakah CosPdfDictionary berisi nilai tertentu.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Kembalikan true jika berisi item

### containsKey {#containsKey-java.lang.String-}
Menentukan apakah {@link CosPdfDictionary} berisi elemen dengan kunci yang ditentukan.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Menyalin elemen-elemen CosPdfDictionary ke dalam Array, mulai dari indeks Array tertentu.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Salin ke Array

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
Membuat kamus kosong yang akan dilampirkan ke dokumen.

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
Membuat kamus kosong yang akan dilampirkan ke halaman.

### get_Item {#get_Item-java.lang.String-}
Mendapatkan atau mengatur elemen dengan kunci yang ditentukan.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Koleksi lengkap kunci. Berisi kunci yang dapat diedit dan tidak dapat diedit.

**Returns:**
Daftar nilai String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Koleksi kunci yang dapat diedit.

**Returns:**
Daftar nilai String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Mendapatkan {@link ICollection} yang berisi nilai-nilai dalam {@link CosPdfDictionary}.

**Returns:**
Daftar instance ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah {@link CosPdfDictionary} bersifat read-only.

**Returns:**
true jika {@link CosPdfDictionary} bersifat read-only; jika tidak, false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Returns:**
Enumerator yang dapat digunakan untuk mengiterasi koleksi.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menghapus kemunculan pertama dari objek tertentu dari CosPdfDictionary.

### remove {#remove-java.lang.String-}
Menghapus elemen dengan kunci yang ditentukan dari {@link CosPdfDictionary}.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Hapus Item

### removeItemByKey {#removeItemByKey-java.lang.String-}
Hapus item berdasarkan kunci.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Mendapatkan atau mengatur elemen dengan kunci yang ditentukan. @exception ArgumentNullException Kunci bernilai null. @exception KeyNotFoundException Properti diambil dan kunci tidak ditemukan. @exception ArgumentException Melempar pengecualian jika kunci tidak dapat diedit/diatur.

### size {#size--}
```
public final int size()
```

Mendapatkan jumlah elemen yang terdapat dalam {@link CosPdfDictionary}.

**Returns:**
nilai int

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

Mencoba meng-cast instance ini ke {@link CosPdfDictionary}.

**Returns:**
null jika instance bukan {@link CosPdfDictionary} else {@link CosPdfDictionary}.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Untuk mengakses tipe data sederhana seperti string, nama, bool, number. Mengembalikan null untuk tipe lain.

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Coba dapatkan nilai

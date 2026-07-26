---
title: "DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas untuk mengakses kamus pohon dokumen (kamus dokumen, kamus halaman, kamus sumber daya)."
type: docs
weight: 70
url: /id/java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

Kelas untuk mengakses kamus pohon dokumen (kamus dokumen, kamus halaman, kamus sumber daya).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException Sumber daya adalah null. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Setel ICosPdfPrimitive ke kamus. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Setel {@link ICosPdfPrimitive} ke kamus. |
| [clear](#clear--) | Menghapus semua item dari {@link DictionaryEditor}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menentukan apakah DictionaryEditor berisi nilai tertentu. |
| [containsKey](#containsKey-java.lang.String-) | Menentukan apakah {@link DictionaryEditor} berisi elemen dengan kunci yang ditentukan. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Menyalin elemen DictionaryEditor ke sebuah Array, dimulai pada indeks Array tertentu. |
| [get_Item](#get_Item-java.lang.String-) | Mendapatkan atau mengatur elemen dengan kunci yang ditentukan. |
| [getAllKeys](#getAllKeys--) | Koleksi lengkap kunci. Berisi kunci yang dapat diedit dan tidak dapat diedit. |
| [getKeys](#getKeys--) | Koleksi kunci yang dapat diedit. |
| [getValues](#getValues--) | Mendapatkan {@link ICollection} yang berisi nilai-nilai dalam {@link DictionaryEditor}. |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah {@link DictionaryEditor} bersifat read-only. |
| [iterator](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menghapus kemunculan pertama dari objek tertentu dari DictionaryEditor. |
| [remove](#remove-java.lang.String-) | Menghapus elemen dengan kunci yang ditentukan dari {@link DictionaryEditor}. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Mendapatkan atau mengatur elemen dengan kunci yang ditentukan. |
| [size](#size--) | Mendapatkan jumlah elemen yang terdapat dalam {@link DictionaryEditor}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Untuk mengakses tipe data sederhana seperti string, nama, bool, number. Mengembalikan null untuk tipe lain. |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException Sumber daya adalah null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Setel ICosPdfPrimitive ke kamus.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Setel {@link ICosPdfPrimitive} ke kamus.

### clear {#clear--}
```
public final void clear()
```

Menghapus semua item dari {@link DictionaryEditor}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menentukan apakah DictionaryEditor berisi nilai tertentu.

### containsKey {#containsKey-java.lang.String-}
Menentukan apakah {@link DictionaryEditor} berisi elemen dengan kunci yang ditentukan.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Menyalin elemen DictionaryEditor ke sebuah Array, dimulai pada indeks Array tertentu.

### get_Item {#get_Item-java.lang.String-}
Mendapatkan atau mengatur elemen dengan kunci yang ditentukan.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Koleksi lengkap kunci. Berisi kunci yang dapat diedit dan tidak dapat diedit.

**Returns:**
Iterabel dari instance String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Koleksi kunci yang dapat diedit.

**Returns:**
Iterabel dari instance String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Mendapatkan {@link ICollection} yang berisi nilai-nilai dalam {@link DictionaryEditor}.

**Returns:**
Iterabel dari instance ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah {@link DictionaryEditor} bersifat read-only.

**Returns:**
true jika {@link DictionaryEditor} bersifat read-only; jika tidak, false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Returns:**
Enumerator yang dapat digunakan untuk mengiterasi koleksi.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menghapus kemunculan pertama dari objek tertentu dari DictionaryEditor.

### remove {#remove-java.lang.String-}
Menghapus elemen dengan kunci yang ditentukan dari {@link DictionaryEditor}.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Mendapatkan atau mengatur elemen dengan kunci yang ditentukan.

### size {#size--}
```
public final int size()
```

Mendapatkan jumlah elemen yang terdapat dalam {@link DictionaryEditor}.

**Returns:**
nilai int

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Untuk mengakses tipe data sederhana seperti string, nama, bool, number. Mengembalikan null untuk tipe lain.

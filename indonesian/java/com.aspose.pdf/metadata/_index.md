---
title: "Metadata"
linktitle: "Metadata"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menyediakan akses ke aliran metadata XMP."
type: docs
weight: 3050
url: /id/java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class Metadata extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Menyediakan akses ke aliran metadata XMP.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menambahkan pasangan dengan kunci dan nilai ke dalam kamus. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Menambahkan nilai ke metadata. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | Menambahkan ekstensi pdf ke metadata. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Menambahkan nilai ke metadata. |
| [clear](#clear--) | Menghapus metadata. |
| [contains](#contains-java.lang.String-) | Memeriksa apakah kunci terdapat dalam metadata. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Memeriksa apakah pasangan kunci-nilai yang ditentukan terdapat dalam kamus. |
| [containsKey](#containsKey-java.lang.String-) | Menentukan apakah kamus ini berisi kunci yang ditentukan. |
| [copyTo](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin elemen koleksi ke dalam array. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Menyalin elemen koleksi ke dalam array. |
| [get_Item](#get_Item-java.lang.String-) | Mengambil data dari metadata. |
| [getExtensionFields_Internal](#getExtensionFields_Internal--) | Hanya untuk penggunaan internal. Mengambil kamus bidang ekstensi. |
| [getExtensionFields](#getExtensionFields--) | <p> Mengambil kamus bidang ekstensi. </p> |
| [getItem](#getItem-java.lang.String-) | Mengambil data dari metadata. |
| [getKeys](#getKeys--) | Mengambil koleksi kunci metadata. |
| [getNamespaceUriByPrefix](#getNamespaceUriByPrefix-java.lang.String-) | Mengembalikan URI namespace berdasarkan prefiks. |
| [getPrefixByNamespaceUri](#getPrefixByNamespaceUri-java.lang.String-) | Mengembalikan prefiks berdasarkan URI namespace. |
| [getSyncRoot](#getSyncRoot--) | Mengambil objek sinkronisasi koleksi. |
| [getValues](#getValues--) | Mengambil nilai dalam metadata. |
| [isFixedSize](#isFixedSize--) | Memeriksa apakah koleksi memiliki ukuran tetap. |
| [isReadOnly](#isReadOnly--) | Memeriksa apakah koleksi hanya-baca. |
| [isSynchronized](#isSynchronized--) | Memeriksa apakah koleksi disinkronkan. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Mengembalikan enumerator kamus. |
| [iteratorIE](#iteratorIE--) | Mengambil enumerator koleksi. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-) | Mendaftarkan URI namespace. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | Mendaftarkan URI namespace. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menghapus pasangan kunci/nilai dari koleksi. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Menghapus entri dari metadata. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | Mengatur data dari metadata. |
| [setItem](#setItem-java.lang.String-com.aspose.pdf.XmpValue-) | Mengatur data dari metadata. |
| [size](#size--) | Mendapatkan jumlah elemen dalam koleksi. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Mencoba menemukan kunci dalam kamus dan mengambil nilai jika ditemukan. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-) | Mencoba menemukan kunci dalam kamus dan mengambil nilai jika ditemukan. |

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menambahkan pasangan dengan kunci dan nilai ke dalam kamus.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Menambahkan nilai ke metadata.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
Menambahkan ekstensi pdf ke metadata.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
Menambahkan nilai ke metadata.

### clear {#clear--}
```
public void clear()
```

Menghapus metadata.

### contains {#contains-java.lang.String-}
Memeriksa apakah kunci terdapat dalam metadata.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Memeriksa apakah pasangan kunci-nilai yang ditentukan terdapat dalam kamus.

### containsKey {#containsKey-java.lang.String-}
Menentukan apakah kamus ini berisi kunci yang ditentukan.

### copyTo {#copyTo-com.aspose.ms.System.Array-int-}
Menyalin elemen koleksi ke dalam array.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Menyalin elemen koleksi ke dalam array.

### get_Item {#get_Item-java.lang.String-}
Mengambil data dari metadata.

### getExtensionFields_Internal {#getExtensionFields_Internal--}
```
public com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpPdfAExtensionSchema > getExtensionFields_Internal()
```

Hanya untuk penggunaan internal. Mengambil kamus bidang ekstensi.

**Returns:**
objek internal

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Mengambil kamus bidang ekstensi. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} objek

### getItem {#getItem-java.lang.String-}
Mengambil data dari metadata.

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Mengambil koleksi kunci metadata.

**Returns:**
objek ICollection

### getNamespaceUriByPrefix {#getNamespaceUriByPrefix-java.lang.String-}
Mengembalikan URI namespace berdasarkan prefiks.

### getPrefixByNamespaceUri {#getPrefixByNamespaceUri-java.lang.String-}
Mengembalikan prefiks berdasarkan URI namespace.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Mengambil objek sinkronisasi koleksi.

**Returns:**
Objek untuk sinkronisasi

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Mengambil nilai dalam metadata.

**Returns:**
objek ICollection

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Memeriksa apakah koleksi memiliki ukuran tetap.

**Returns:**
nilai boolean

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Memeriksa apakah koleksi hanya-baca.

**Returns:**
nilai boolean

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Memeriksa apakah koleksi disinkronkan.

**Returns:**
nilai boolean

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Mengembalikan enumerator kamus.

**Returns:**
Enumerator.

### iteratorIE {#iteratorIE--}
```
public Iterator <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iteratorIE()
```

Mengambil enumerator koleksi.

**Returns:**
IEnumerator objek @see IEnumerator

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-}
Mendaftarkan URI namespace.

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
Mendaftarkan URI namespace.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menghapus pasangan kunci/nilai dari koleksi.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Menghapus entri dari metadata.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
Mengatur data dari metadata.

### setItem {#setItem-java.lang.String-com.aspose.pdf.XmpValue-}
Mengatur data dari metadata.

### size {#size--}
```
public int size()
```

Mendapatkan jumlah elemen dalam koleksi.

**Returns:**
nilai int

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Mencoba menemukan kunci dalam kamus dan mengambil nilai jika ditemukan.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-}
Mencoba menemukan kunci dalam kamus dan mengambil nilai jika ditemukan.

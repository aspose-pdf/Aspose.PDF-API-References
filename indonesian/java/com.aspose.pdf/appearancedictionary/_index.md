---
title: "AppearanceDictionary"
linktitle: "AppearanceDictionary"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kamus tampilan anotasi yang menentukan bagaimana anotasi akan ditampilkan secara visual pada halaman."
type: docs
weight: 150
url: /id/java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AppearanceDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XForm >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>

```
public final class AppearanceDictionary extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XForm >
```

Kamus tampilan anotasi yang menentukan bagaimana anotasi akan ditampilkan secara visual pada halaman.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-java.lang.Object-java.lang.Object-) | Menambahkan elemen dengan kunci dan nilai yang diberikan. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menambahkan pasangan dengan kunci dan nilai ke dalam kamus. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XForm-) | Tambahkan X form untuk kunci yang ditentukan. |
| [clear](#clear--) | Menghapus semua elemen dari kamus. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Memeriksa apakah pasangan kunci-nilai yang ditentukan terdapat dalam kamus. |
| [containsKey](#containsKey-java.lang.String-) | Menentukan apakah kamus ini berisi kunci yang ditentukan. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | / * / * Mengembalikan objek IDictionaryEnumerator untuk kamus. / * / * / * |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Menyalin elemen ICollection ke dalam Array, mulai pada indeks Array tertentu. |
| [get_Item](#get_Item-java.lang.String-) | Mewakili bentuk yang nyaman untuk mendapatkan aliran tampilan. |
| [getDict](#getDict--) | Mendapatkan kamus pdf |
| [getKeys_](#getKeys_--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | Nilai .state D), di mana N - tampilan normal, R - tampilan rollover, D - tampilan turun dan state - nama status (misalnya On, Off untuk kotak centang). |
| [getKeys](#getKeys--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | Nilai .state D), di mana N - tampilan normal, R - tampilan rollover, D - tampilan turun dan state - nama status (misalnya On, Off untuk kotak centang). |
| [getSyncRoot](#getSyncRoot--) | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke kamus. |
| [getValues_](#getValues_--) | Mendapatkan daftar nilai kamus. Koleksi hasil berisi daftar objek XForm. |
| [getValues](#getValues--) | Mendapatkan daftar nilai kamus. Koleksi hasil berisi daftar objek XForm. |
| [isFixedSize](#isFixedSize--) | Mendapatkan nilai yang menunjukkan apakah kamus memiliki ukuran tetap. |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah kamus bersifat read-only. |
| [isSynchronized](#isSynchronized--) | Mendapatkan nilai yang menunjukkan apakah akses ke kamus disinkronkan (aman untuk thread). |
| [iterator__Rename_Namesake](#iterator__Rename_Namesake--) | Enumerator untuk koleksi. |
| [iterator](#iterator--) | Mengembalikan objek IDictionaryEnumerator untuk kamus. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menghapus pasangan kunci/nilai dari koleksi. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Menghapus kunci dari kamus. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size](#size--) | Mendapatkan jumlah elemen yang terdapat dalam kamus. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Mencoba menemukan kunci dalam kamus dan mengambil nilai jika ditemukan. |

### add {#add-java.lang.Object-java.lang.Object-}
Menambahkan elemen dengan kunci dan nilai yang diberikan.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menambahkan pasangan dengan kunci dan nilai ke dalam kamus.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XForm-}
Tambahkan X form untuk kunci yang ditentukan.

### clear {#clear--}
```
public void clear()
```

Menghapus semua elemen dari kamus.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Memeriksa apakah pasangan kunci-nilai yang ditentukan terdapat dalam kamus.

### containsKey {#containsKey-java.lang.String-}
Menentukan apakah kamus ini berisi kunci yang ditentukan.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
/ * / * Mengembalikan objek IDictionaryEnumerator untuk kamus. / * / * / *

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Menyalin elemen ICollection ke dalam Array, mulai pada indeks Array tertentu.

### get_Item {#get_Item-java.lang.String-}
Mewakili bentuk yang nyaman untuk mendapatkan aliran tampilan.

### getDict {#getDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getDict()
```

Mendapatkan kamus pdf

**Returns:**
objek IPdfDictionary

### getKeys_ {#getKeys_--}
```
public List < String > getKeys_()
```

Mendapatkan kunci kamus. Jika kamus tampilan memiliki subkamus, maka {@code Keys} berisi nilai (N|R|D).state, di mana N - tampilan normal, R - tampilan rollover, D - tampilan turun dan state - nama status (misalnya On, Off untuk kotak centang).

**Returns:**
Daftar nilai String

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Mendapatkan kunci kamus. Jika kamus tampilan memiliki subkamus, maka {@code Keys} berisi nilai (N|R|D).state, di mana N - tampilan normal, R - tampilan rollover, D - tampilan turun dan state - nama status (misalnya On, Off untuk kotak centang).

**Returns:**
Daftar nilai String

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke kamus.

**Returns:**
Objek untuk sinkronisasi

### getValues_ {#getValues_--}
```
public List < XForm > getValues_()
```

Mendapatkan daftar nilai kamus. Koleksi hasil berisi daftar objek XForm.

**Returns:**
Daftar nilai XForm

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XForm > getValues()
```

Mendapatkan daftar nilai kamus. Koleksi hasil berisi daftar objek XForm.

**Returns:**
Daftar nilai XForm

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Mendapatkan nilai yang menunjukkan apakah kamus memiliki ukuran tetap.

**Returns:**
nilai boolean

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah kamus bersifat read-only.

**Returns:**
nilai boolean

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Mendapatkan nilai yang menunjukkan apakah akses ke kamus disinkronkan (aman untuk thread).

**Returns:**
nilai boolean

### iterator__Rename_Namesake {#iterator__Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator__Rename_Namesake()
```

Enumerator untuk koleksi.

**Returns:**
enumerator dari item koleksi.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator()
```

Mengembalikan objek IDictionaryEnumerator untuk kamus.

**Returns:**
Enumerator kamus.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menghapus pasangan kunci/nilai dari koleksi.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Menghapus kunci dari kamus.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XForm-}


### size {#size--}
```
public int size()
```

Mendapatkan jumlah elemen yang terdapat dalam kamus.

**Returns:**
nilai int

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Mencoba menemukan kunci dalam kamus dan mengambil nilai jika ditemukan.

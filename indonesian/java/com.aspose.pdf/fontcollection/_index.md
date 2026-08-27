---
title: "FontCollection"
linktitle: "FontCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili koleksi font. </p> <hr> <pre> Contoh menunjukkan cara menjadikan semua font yang dideklarasikan pada halaman sebagai tertanam. // Buka dokumen Document doc = new."
type: docs
weight: 1670
url: /id/java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontCollection

**All Implemented Interfaces:**
Iterable < Font >

```
public final class FontCollection extends Object implements Iterable < Font >
```

<p> Mewakili koleksi font. </p> <hr> <pre> Contoh menunjukkan cara menjadikan semua font yang dideklarasikan pada halaman sebagai tertanam. // Buka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // pastikan semua font yang dideklarasikan pada sumber daya halaman tertanam // catat bahwa jika font dideklarasikan pada sumber daya formulir, mereka tidak dapat diakses dari sumber daya halaman for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\Tests\\input.pdf"); </pre> <hr> <p> Koleksi font yang direpresentasikan oleh kelas {@code FontCollection} digunakan dalam beberapa skenario. Misalnya, dalam sumber daya dengan properti {@code Resources.Fonts}. </p>

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.Font-) | Menambahkan Font ke dalam koleksi. |
| [add](#add-com.aspose.pdf.Font-java.lang.String:A-) | Menambahkan font baru ke sumber daya font dan mengembalikan nama sumber daya font yang ditetapkan secara otomatis. |
| [add](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | Menambahkan font baru ke koleksi font. |
| [add](#add-java.lang.String-java.lang.String-) | Menambahkan entri font baru ke sumber daya font dengan nama font dasar yang ditentukan. |
| [clear_Rename_Namesake](#clear_Rename_Namesake--) | / * / * Menambahkan Font ke dalam koleksi. / * / * |
| [contains](#contains-com.aspose.pdf.Font-) | Menentukan apakah koleksi berisi nilai tertentu. |
| [contains](#contains-java.lang.String-) | Memeriksa apakah font ada dalam koleksi font. |
| [copyTo](#copyTo-com.aspose.pdf.Font:A-int-) | Menyalin seluruh koleksi ke Array satu dimensi yang kompatibel, dimulai pada indeks yang ditentukan dari array target. |
| [delete](#delete-java.lang.String-) | Menghapus Font dengan nama sumber daya yang ditentukan |
| [get_Item](#get_Item-int-) | Mendapatkan elemen font pada indeks yang ditentukan. |
| [get_Item](#get_Item-java.lang.String-) | Mendapatkan font dari koleksi berdasarkan nama font. Pengecualian dilemparkan jika font tidak ditemukan. |
| [getFontsDictionary](#getFontsDictionary--) | Dapatkan objek IPdfDictionary |
| [getHash](#getHash--) |  |
| [getSyncRoot](#getSyncRoot--) | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi. |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only |
| [isSynchronized](#isSynchronized--) | Mendapatkan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Mengembalikan enumerator untuk seluruh koleksi. |
| [iterator](#iterator--) | Mengembalikan enumerator untuk seluruh koleksi. |
| [remove](#remove-com.aspose.pdf.Font-) | Menghapus item yang ditentukan dari koleksi. |
| [size](#size--) | Mendapatkan jumlah elemen objek {@code Font} yang sebenarnya terdapat dalam koleksi. |

### add {#add-com.aspose.pdf.Font-}
Menambahkan Font ke dalam koleksi.

### add {#add-com.aspose.pdf.Font-java.lang.String:A-}
Menambahkan font baru ke sumber daya font dan mengembalikan nama sumber daya font yang ditetapkan secara otomatis.

### add {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
Menambahkan font baru ke koleksi font.

### add {#add-java.lang.String-java.lang.String-}
Menambahkan entri font baru ke sumber daya font dengan nama font dasar yang ditentukan.

### clear_Rename_Namesake {#clear_Rename_Namesake--}
```
public void clear_Rename_Namesake()
```

/ * / * Menambahkan Font ke dalam koleksi. / * / *

### contains {#contains-com.aspose.pdf.Font-}
Menentukan apakah koleksi berisi nilai tertentu.

### contains {#contains-java.lang.String-}
Memeriksa apakah font ada dalam koleksi font.

### copyTo {#copyTo-com.aspose.pdf.Font:A-int-}
Menyalin seluruh koleksi ke Array satu dimensi yang kompatibel, dimulai pada indeks yang ditentukan dari array target.

### delete {#delete-java.lang.String-}
Menghapus Font dengan nama sumber daya yang ditentukan

### get_Item {#get_Item-int-}
```
public Font get_Item(int index)
```

Mendapatkan elemen font pada indeks yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks dalam koleksi. |

**Returns:**
Objek Font.

### get_Item {#get_Item-java.lang.String-}
Mendapatkan font dari koleksi berdasarkan nama font. Pengecualian dilemparkan jika font tidak ditemukan.

### getFontsDictionary {#getFontsDictionary--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getFontsDictionary()
```

Dapatkan objek IPdfDictionary

**Returns:**
objek IPdfDictionary

### getHash {#getHash--}
```
public com.aspose.pdf.engine.collections.HashDictionary< String , Font > getHash()
```



### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi.

**Returns:**
Objek untuk sinkronisasi

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only

**Returns:**
nilai boolean

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Mendapatkan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread).

**Returns:**
nilai boolean

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Mengembalikan enumerator untuk seluruh koleksi.

**Returns:**
Objek Enumerator.

### iterator {#iterator--}
```
public Iterator < Font > iterator()
```

Mengembalikan enumerator untuk seluruh koleksi.

**Returns:**
Objek Enumerator.

### remove {#remove-com.aspose.pdf.Font-}
Menghapus item yang ditentukan dari koleksi.

### size {#size--}
```
public int size()
```

Mendapatkan jumlah elemen objek {@code Font} yang sebenarnya terdapat dalam koleksi.

**Returns:**
nilai int

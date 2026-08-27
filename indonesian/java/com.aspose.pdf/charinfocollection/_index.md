---
title: "CharInfoCollection"
linktitle: "CharInfoCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili koleksi objek CharInfo. </p> <hr> <pre> Contoh ini menunjukkan cara mengiterasi semua karakter dan mengambil karakter //open document Document."
type: docs
weight: 570
url: /id/java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CharInfoCollection

**All Implemented Interfaces:**
Iterable < CharInfo >

```
public final class CharInfoCollection extends Object implements Iterable < CharInfo >
```

<p> Mewakili koleksi objek CharInfo. </p> <hr> <pre> The example demonstrates how to iterate thought all the characters and retrieve the character //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println(\"XIndent : \" + charInfo.getPosition().getXIndent()); System.out.println(\"YIndent : \" + charInfo.getPosition().getYIndent()); System.out.println(\"Width : \" + charInfo.getRectangle().getWidth()); System.out.println(\"Height : \" + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Menyediakan akses ke informasi penempatan karakter segmen teks. </p>

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.CharInfo-) | Belum didukung. Koleksi bersifat read-only, melempar pengecualian. |
| [clear](#clear--) | Belum didukung. Koleksi bersifat read-only. Selalu melempar NotImplementedException. |
| [contains](#contains-com.aspose.pdf.CharInfo-) | Menentukan apakah koleksi berisi nilai tertentu. |
| [copyTo](#copyTo-com.aspose.pdf.CharInfo:A-int-) | Menyalin seluruh koleksi ke Array satu dimensi yang kompatibel, dimulai pada indeks yang ditentukan dari array target. |
| [get_Item](#get_Item-int-) | Mendapatkan elemen CharInfo pada indeks yang ditentukan 1..n. |
| [getSyncRoot](#getSyncRoot--) | Mendapatkan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi. |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat read-only |
| [isSynchronized](#isSynchronized--) | Mendapatkan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman untuk thread). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Mengembalikan enumerator untuk seluruh koleksi. |
| [iterator](#iterator--) | Mengembalikan enumerator untuk seluruh koleksi. |
| [remove](#remove-com.aspose.pdf.CharInfo-) | Belum didukung. Koleksi bersifat read-only, melempar pengecualian. |
| [size](#size--) | Mendapatkan jumlah elemen objek {@code CharInfo} yang sebenarnya terdapat dalam koleksi. |

### add {#add-com.aspose.pdf.CharInfo-}
Belum didukung. Koleksi bersifat read-only, melempar pengecualian.

### clear {#clear--}
```
public void clear()
```

Belum didukung. Koleksi bersifat read-only. Selalu melempar NotImplementedException.

### contains {#contains-com.aspose.pdf.CharInfo-}
Menentukan apakah koleksi berisi nilai tertentu.

### copyTo {#copyTo-com.aspose.pdf.CharInfo:A-int-}
Menyalin seluruh koleksi ke Array satu dimensi yang kompatibel, dimulai pada indeks yang ditentukan dari array target.

### get_Item {#get_Item-int-}
```
public CharInfo get_Item(int index)
```

Mendapatkan elemen CharInfo pada indeks yang ditentukan 1..n.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks dalam koleksi. |

**Returns:**
Objek CharInfo.

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
public com.aspose.ms.System.Collections.IEnumerator< CharInfo > iterator()
```

Mengembalikan enumerator untuk seluruh koleksi.

**Returns:**
Objek Enumerator.

### remove {#remove-com.aspose.pdf.CharInfo-}
Belum didukung. Koleksi bersifat read-only, melempar pengecualian.

### size {#size--}
```
public int size()
```

Mendapatkan jumlah elemen objek {@code CharInfo} yang sebenarnya terdapat dalam koleksi.

**Returns:**
nilai int

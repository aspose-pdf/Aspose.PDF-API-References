---
title: "CharInfoCollection"
linktitle: "CharInfoCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> CharInfo nesneleri koleksiyonunu temsil eder. </p> <hr> <pre> Örnek, tüm karakterler üzerinde nasıl döngü yapılacağını ve karakterin nasıl alınacağını gösterir //open document Document."
type: docs
weight: 570
url: /tr/java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CharInfoCollection

**All Implemented Interfaces:**
Iterable < CharInfo >

```
public final class CharInfoCollection extends Object implements Iterable < CharInfo >
```

<p> CharInfo nesneleri koleksiyonunu temsil eder. </p> <hr> <pre> Örnek, tüm karakterler üzerinde nasıl döngü yapılacağını ve karakterin nasıl alınacağını gösterir. //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Metin segmenti karakterlerinin konumlandırma bilgisine erişim sağlar. </p>

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.CharInfo-) | Henüz desteklenmiyor. Koleksiyon yalnızca okunur, istisna fırlatır. |
| [clear](#clear--) | Henüz desteklenmiyor. Koleksiyon yalnızca okunur. Her zaman NotImplementedException fırlatır. |
| [contains](#contains-com.aspose.pdf.CharInfo-) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [copyTo](#copyTo-com.aspose.pdf.CharInfo:A-int-) | Tüm koleksiyonu, hedef dizinin belirtilen indeksinden başlayarak uyumlu tek boyutlu bir diziye kopyalar. |
| [get_Item](#get_Item-int-) | Belirtilen 1..n indeksindeki CharInfo öğesini alır. |
| [getSyncRoot](#getSyncRoot--) | Koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır |
| [isSynchronized](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Tüm koleksiyon için bir yineleyici döndürür. |
| [iterator](#iterator--) | Tüm koleksiyon için bir yineleyici döndürür. |
| [remove](#remove-com.aspose.pdf.CharInfo-) | Henüz desteklenmiyor. Koleksiyon yalnızca okunur, istisna fırlatır. |
| [size](#size--) | Koleksiyonda gerçekte bulunan {@code CharInfo} nesne öğelerinin sayısını alır. |

### add {#add-com.aspose.pdf.CharInfo-}
Henüz desteklenmiyor. Koleksiyon yalnızca okunur, istisna fırlatır.

### clear {#clear--}
```
public void clear()
```

Henüz desteklenmiyor. Koleksiyon yalnızca okunur. Her zaman NotImplementedException fırlatır.

### contains {#contains-com.aspose.pdf.CharInfo-}
Koleksiyonun belirli bir değeri içerip içermediğini belirler.

### copyTo {#copyTo-com.aspose.pdf.CharInfo:A-int-}
Tüm koleksiyonu, hedef dizinin belirtilen indeksinden başlayarak uyumlu tek boyutlu bir diziye kopyalar.

### get_Item {#get_Item-int-}
```
public CharInfo get_Item(int index)
```

Belirtilen 1..n indeksindeki CharInfo öğesini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Koleksiyon içindeki indeks. |

**Returns:**
CharInfo nesnesi.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesneyi alır.

**Returns:**
Eşitleme için nesne

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Tüm koleksiyon için bir yineleyici döndürür.

**Returns:**
Yineleyici nesnesi.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< CharInfo > iterator()
```

Tüm koleksiyon için bir yineleyici döndürür.

**Returns:**
Yineleyici nesnesi.

### remove {#remove-com.aspose.pdf.CharInfo-}
Henüz desteklenmiyor. Koleksiyon yalnızca okunur, istisna fırlatır.

### size {#size--}
```
public int size()
```

Koleksiyonda gerçekte bulunan {@code CharInfo} nesne öğelerinin sayısını alır.

**Returns:**
int değer

---
title: "TextSegmentCollection"
linktitle: "TextSegmentCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin segmentleri koleksiyonunu temsil eder"
type: docs
weight: 5310
url: /tr/java/com.aspose.pdf/textsegmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegmentCollection

**All Implemented Interfaces:**
Iterable < TextSegment >

```
public final class TextSegmentCollection extends Object implements Iterable < TextSegment >
```

Metin segmentleri koleksiyonunu temsil eder

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.TextSegment-) | Belirtilen indekste metin segment öğesini ekler. |
| [clear](#clear--) | Koleksiyondaki tüm öğeleri temizler. |
| [contains](#contains-com.aspose.pdf.TextSegment-) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [copyTo](#copyTo-com.aspose.pdf.TextSegment:A-int-) | Tüm koleksiyonu, hedef dizinin belirtilen indeksinden başlayarak uyumlu tek boyutlu bir diziye kopyalar. |
| [delete](#delete-int-) | Belirtilen indeksteki metin segment öğesini siler. |
| [get_Item](#get_Item-int-) | Belirtilen indeksteki metin segment öğesini alır. |
| [getSyncRoot](#getSyncRoot--) | Koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır |
| [isSynchronized](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır. |
| [iterator](#iterator--) | Tüm koleksiyon için bir yineleyici döndürür. |
| [remove](#remove-com.aspose.pdf.TextSegment-) | Belirtilen öğeyi koleksiyondan siler. |
| [size](#size--) | {@code TextSegment} nesne öğelerinin koleksiyonda gerçekte bulunan sayısını alır. |

### add {#add-com.aspose.pdf.TextSegment-}
Belirtilen indekste metin segment öğesini ekler.

### clear {#clear--}
```
public void clear()
```

Koleksiyondaki tüm öğeleri temizler.

### contains {#contains-com.aspose.pdf.TextSegment-}
Koleksiyonun belirli bir değeri içerip içermediğini belirler.

### copyTo {#copyTo-com.aspose.pdf.TextSegment:A-int-}
Tüm koleksiyonu, hedef dizinin belirtilen indeksinden başlayarak uyumlu tek boyutlu bir diziye kopyalar.

### delete {#delete-int-}
```
public void delete(int index)
```

Belirtilen indeksteki metin segment öğesini siler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | int değer |

### get_Item {#get_Item-int-}
```
public TextSegment get_Item(int index)
```

Belirtilen indeksteki metin segment öğesini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Koleksiyon içindeki indeks. |

**Returns:**
TextSegment nesnesi.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesneyi alır.

**Returns:**
Nesne öğesi

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

### iterator {#iterator--}
```
public Iterator < TextSegment > iterator()
```

Tüm koleksiyon için bir yineleyici döndürür.

**Returns:**
Yineleyici nesnesi.

### remove {#remove-com.aspose.pdf.TextSegment-}
Belirtilen öğeyi koleksiyondan siler.

### size {#size--}
```
public int size()
```

{@code TextSegment} nesne öğelerinin koleksiyonda gerçekte bulunan sayısını alır.

**Returns:**
int değer

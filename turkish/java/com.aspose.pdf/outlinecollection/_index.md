---
title: "OutlineCollection"
linktitle: "OutlineCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Belge taslak hiyerarşisini temsil eder."
type: docs
weight: 3260
url: /tr/java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineCollection extends Outlines
```

Belge taslak hiyerarşisini temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Koleksiyona anahat öğesi ekler. |
| [clear](#clear--) | Koleksiyondaki tüm öğeleri temizler. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Henüz desteklenmiyor. Koleksiyonun verilen öğeyi içerip içermediğini kontrol eder. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Anlatım öğelerini bir System.Array'e kopyalar, belirli bir System.Array indeksinden başlayarak. |
| [delete](#delete--) | Belge anahattından tüm anahat öğelerini siler. |
| [delete](#delete-java.lang.String-) | Belge anahattından tüm anahat öğelerini siler. |
| [get_Item](#get_Item-int-) | Koleksiyondan indeks ile anahat öğesini alır. |
| [getFirst](#getFirst--) | Anahattaki ilk üst düzey öğeyi temsil eden bir anahat öğesini alır. |
| [getLast](#getLast--) | Anahattaki son üst düzey öğeyi temsil eden bir anahat öğesini alır. |
| [getSyncRoot](#getSyncRoot--) | Bu koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [getVisibleCount](#getVisibleCount--) | Count, tüm seviyelerdeki görünür alt anahat öğelerinin sayısının toplamıdır. Not: Lütfen koleksiyondaki öğe sayısı olan Count ile karıştırmayın. |
| [hasNext](#hasNext--) |  |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır. |
| [isSynchronized](#isSynchronized--) | Bu koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır. |
| [iterator](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [next](#next--) |  |
| [remove](#remove-int-) | İndeks ile öğeyi kaldır. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Henüz desteklenmiyor. Her zaman bir istisna fırlatır |
| [size](#size--) | Belge anahattının tüm seviyelerindeki anahat öğelerinin (yer imleri) toplam sayısını alır. |

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Koleksiyona anahat öğesi ekler.

### clear {#clear--}
```
public void clear()
```

Koleksiyondaki tüm öğeleri temizler.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Henüz desteklenmiyor. Koleksiyonun verilen öğeyi içerip içermediğini kontrol eder.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Anlatım öğelerini bir System.Array'e kopyalar, belirli bir System.Array indeksinden başlayarak.

### delete {#delete--}
```
public void delete()
```

Belge anahattından tüm anahat öğelerini siler.

### delete {#delete-java.lang.String-}
Belge anahattından tüm anahat öğelerini siler.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Koleksiyondan indeks ile anahat öğesini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | İstenen öğenin indeksi. |

**Returns:**
OutlineItemCollection nesnesi

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Anahattaki ilk üst düzey öğeyi temsil eden bir anahat öğesini alır.

**Returns:**
OutlineItemCollection nesnesi

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Anahattaki son üst düzey öğeyi temsil eden bir anahat öğesini alır.

**Returns:**
OutlineItemCollection nesnesi

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Bu koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesneyi alır.

**Returns:**
Eşitleme için nesne

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Count, tüm seviyelerdeki görünür alt anahat öğelerinin sayısının toplamıdır. Not: Lütfen koleksiyondaki öğe sayısı olan Count ile karıştırmayın.

**Returns:**
int değer

### hasNext {#hasNext--}
```
public boolean hasNext()
```



### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Bu koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Returns:**
Koleksiyon içinde yineleme yapmak için kullanılabilecek bir System.Collections.IEnumerator nesnesi.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

İndeks ile öğeyi kaldır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Kaldırılacak öğenin indeksi. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Henüz desteklenmiyor. Her zaman bir istisna fırlatır

### size {#size--}
```
public int size()
```

Belge anahattının tüm seviyelerindeki anahat öğelerinin (yer imleri) toplam sayısını alır.

**Returns:**
int değer

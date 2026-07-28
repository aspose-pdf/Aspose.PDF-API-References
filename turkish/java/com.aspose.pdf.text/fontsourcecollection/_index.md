---
title: "FontSourceCollection"
linktitle: "FontSourceCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Yazı tipi kaynakları koleksiyonunu temsil eder."
type: docs
weight: 40
url: /tr/java/com.aspose.pdf.text/fontsourcecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSourceCollection

**All Implemented Interfaces:**
Iterable < FontSource >

```
public final class FontSourceCollection extends Object implements Iterable < FontSource >
```

Yazı tipi kaynakları koleksiyonunu temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CollectionChanged](#CollectionChanged) | CollectionChanged olayı |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontSourceCollection](#FontSourceCollection--) | Koleksiyon nesnesini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.FontSource-) | Yeni font kaynağı nesnesini koleksiyona ekler. |
| [clear](#clear--) | Font kaynağı koleksiyonunu temizler. |
| [contains](#contains-com.aspose.pdf.FontSource-) | Bir öğenin koleksiyonda olup olmadığını belirler. |
| [copyTo](#copyTo-com.aspose.pdf.FontSource:A-int-) | Tüm koleksiyonu, hedef dizinin belirtilen indeksinden başlayarak uyumlu tek boyutlu bir diziye kopyalar. |
| [delete](#delete-com.aspose.pdf.FontSource-) | Font kaynağı öğesini siler. |
| [getItem](#getItem-int-) | Belirtilen indeksteki yazı tipi öğesini alır. |
| [getSyncRoot](#getSyncRoot--) | Koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [isSynchronized](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır. |
| [iterator](#iterator--) | Tüm koleksiyon için bir yineleyici döndürür. |
| [remove](#remove-com.aspose.pdf.FontSource-) | Font kaynağı öğesini siler. |
| [size](#size--) | Koleksiyonda gerçekte bulunan Font nesnesi öğelerinin sayısını alır. |

### CollectionChanged {#CollectionChanged}
```
public final PdfEvent <com.aspose.ms.System.EventHandler> CollectionChanged
```

CollectionChanged olayı

### FontSourceCollection {#FontSourceCollection--}
```
public FontSourceCollection()
```

Koleksiyon nesnesini başlatır.

### add {#add-com.aspose.pdf.FontSource-}
Yeni font kaynağı nesnesini koleksiyona ekler.

### clear {#clear--}
```
public void clear()
```

Font kaynağı koleksiyonunu temizler.

### contains {#contains-com.aspose.pdf.FontSource-}
Bir öğenin koleksiyonda olup olmadığını belirler.

### copyTo {#copyTo-com.aspose.pdf.FontSource:A-int-}
Tüm koleksiyonu, hedef dizinin belirtilen indeksinden başlayarak uyumlu tek boyutlu bir diziye kopyalar.

### delete {#delete-com.aspose.pdf.FontSource-}
Font kaynağı öğesini siler.

### getItem {#getItem-int-}
```
public FontSource getItem(int index)
```

Belirtilen indeksteki yazı tipi öğesini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Koleksiyon içindeki indeks. |

**Returns:**
Font kaynağı nesnesi.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesneyi alır.

**Returns:**
Nesne öğesi

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator()
```

Tüm koleksiyon için bir yineleyici döndürür.

**Returns:**
Yineleyici nesnesi.

### remove {#remove-com.aspose.pdf.FontSource-}
Font kaynağı öğesini siler.

### size {#size--}
```
public int size()
```

Koleksiyonda gerçekte bulunan Font nesnesi öğelerinin sayısını alır.

**Returns:**
int değer

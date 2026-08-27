---
title: "GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Temsil eder {@link GraphicElement} koleksiyonunu."
type: docs
weight: 20
url: /tr/java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
Iterable < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

Temsil eder {@link GraphicElement} koleksiyonunu.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | Yeni koleksiyonu başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | Koleksiyona yeni bir {@link GraphicElement} ekler. Koleksiyondaki tüm öğeler aynı {@code GraphicElement.Parent}({@link GraphicElement#getParent}) değerine sahip olmalıdır. |
| [clear](#clear--) | Koleksiyonu temizler. |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | Bir öğenin koleksiyonda olup olmadığını belirler. |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | Tüm koleksiyonu, hedef dizinin belirtilen indeksinden başlayarak uyumlu tek boyutlu bir Array'e kopyalar. |
| [get_Item](#get_Item-int-) | Belirtilen indeksteki {@link GraphicElement} öğesini alır. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır. Her zaman false döndürür. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Tüm koleksiyon için bir yineleyici döndürür. |
| [iterator](#iterator--) | Tüm koleksiyon için bir yineleyici döndürür. |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) | {@link GraphicElement} öğesini siler. |
| [size](#size--) | Koleksiyonda gerçekte bulunan {@link GraphicElement} nesne öğelerinin sayısını alır. |
| [toList](#toList--) | Sınırsız yineleme için iç koleksiyonu döndürür. |
| [toString](#toString--) | Bu koleksiyonun bir dize temsilini alır. |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

Yeni koleksiyonu başlatır.

### add {#add-com.aspose.pdf.vector.GraphicElement-}
Koleksiyona yeni bir {@link GraphicElement} ekler. Koleksiyondaki tüm öğeler aynı {@code GraphicElement.Parent}({@link GraphicElement#getParent}) değerine sahip olmalıdır.

### clear {#clear--}
```
public final void clear()
```

Koleksiyonu temizler.

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
Bir öğenin koleksiyonda olup olmadığını belirler.

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
Tüm koleksiyonu, hedef dizinin belirtilen indeksinden başlayarak uyumlu tek boyutlu bir Array'e kopyalar.

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

Belirtilen indeksteki {@link GraphicElement} öğesini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Koleksiyon içindeki indeks. |

**Returns:**
{@link GraphicElement}.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır. Her zaman false döndürür.

**Returns:**
boolean değer

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Tüm koleksiyon için bir yineleyici döndürür.

**Returns:**
Yineleyici nesnesi.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

Tüm koleksiyon için bir yineleyici döndürür.

**Returns:**
Yineleyici nesnesi.

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
{@link GraphicElement} öğesini siler.

### size {#size--}
```
public final int size()
```

Koleksiyonda gerçekte bulunan {@link GraphicElement} nesne öğelerinin sayısını alır.

**Returns:**
int değer

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

Sınırsız yineleme için iç koleksiyonu döndürür.

**Returns:**
İç liste

### toString {#toString--}
```
public String toString()
```

Bu koleksiyonun bir dize temsilini alır.

**Returns:**
Dize.

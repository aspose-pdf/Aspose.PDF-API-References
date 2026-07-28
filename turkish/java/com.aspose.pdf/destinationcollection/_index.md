---
title: "DestinationCollection"
linktitle: "DestinationCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sınıf, tüm hedeflerin koleksiyonunu temsil eder (ad dizelerini hedeflere eşleyen bir ad ağacı (bkz. 12.3.2.3, \"Named Destinations\") ve (bkz. 7.7.4, \"Name Dictionary\")) içinde."
type: docs
weight: 960
url: /tr/java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DestinationCollection

**All Implemented Interfaces:**
Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, Object >>

```
public final class DestinationCollection extends Object implements Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >>
```

PDF belgesindeki tüm hedeflerin koleksiyonunu temsil eden sınıf (ad dizelerini hedeflere eşleyen bir ad ağacı (bkz. 12.3.2.3, "Named Destinations") ve (bkz. 7.7.4, "Name Dictionary"))

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Belirtilen öğeyi ekler. |
| [clear](#clear--) | Koleksiyon yalnızca okunur. Her zaman NotSupportedException istisnası fırlatır. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Bu örneğin nesneyi içerip içermediğini belirler. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Koleksiyonun öğelerini bir diziye kopyalar, belirli bir dizi indeksinden başlayarak. |
| [get_Item](#get_Item-int-) | Hedef nesnesini indeks ile alır. |
| [getExplicitDestination](#getExplicitDestination-java.lang.String-boolean-) | Adına göre açık hedefi döndürür. |
| [getPageNumber](#getPageNumber-java.lang.String-boolean-) | Adına göre hedefin sayfa numarasını döndürür. |
| [indexOf](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Koleksiyondaki hedefin indeksini döndürür. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır. |
| [iterator](#iterator--) | Yineleyiciyi döndürür. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Belirtilen öğeyi kaldırır. |
| [size](#size--) | Koleksiyonda bulunan öğe sayısını alır. |

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Belirtilen öğeyi ekler.

### clear {#clear--}
```
public void clear()
```

Koleksiyon yalnızca okunur. Her zaman NotSupportedException istisnası fırlatır.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Bu örneğin nesneyi içerip içermediğini belirler.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Koleksiyonun öğelerini bir diziye kopyalar, belirli bir dizi indeksinden başlayarak.

### get_Item {#get_Item-int-}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object > get_Item(int index)
```

Hedef nesnesini indeks ile alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Alınacak hedefin indeksi. |

**Returns:**
Hedef.

### getExplicitDestination {#getExplicitDestination-java.lang.String-boolean-}
Adına göre açık hedefi döndürür.

### getPageNumber {#getPageNumber-java.lang.String-boolean-}
Adına göre hedefin sayfa numarasını döndürür.

### indexOf {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Koleksiyondaki hedefin indeksini döndürür.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >> iterator()
```

Yineleyiciyi döndürür.

**Returns:**
Yineleyici.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Belirtilen öğeyi kaldırır.

### size {#size--}
```
public int size()
```

Koleksiyonda bulunan öğe sayısını alır.

**Returns:**
int değer

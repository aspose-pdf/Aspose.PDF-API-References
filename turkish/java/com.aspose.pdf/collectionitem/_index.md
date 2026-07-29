---
title: "CollectionItem"
linktitle: "CollectionItem"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir koleksiyon öğesi sınıfını temsil eder. Koleksiyon öğesi, koleksiyon şeması tarafından tanımlanan verileri içerir."
type: docs
weight: 640
url: /tr/java/com.aspose.pdf/collectionitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionItem

```
public class CollectionItem extends Object
```

Bir koleksiyon öğesi sınıfını temsil eder. Koleksiyon öğesi, koleksiyon şeması tarafından tanımlanan verileri içerir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAllNames](#getAllNames--) | Koleksiyon öğesi değerlerinin tüm adlarının bir koleksiyonunu alır. |
| [hasName](#hasName-java.lang.String-) | Verilen adın koleksiyon öğesinde mevcut olup olmadığını denetler. |
| [isEmpty](#isEmpty--) | Koleksiyon öğesinin boş olup olmadığını gösteren bir değeri alır. |
| [tryGetDateTimeValue](#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Belirtilen adla koleksiyon öğesinden DateTime türündeki değeri almaya çalışır. |
| [tryGetDoubleValue](#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Belirtilen ad için koleksiyon öğesinden double değeri almaya çalışır. |
| [tryGetIntValue](#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Belirtilen ad için koleksiyon öğesinden tam sayı değerini almaya çalışır. |
| [tryGetTextValue](#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Belirtilen adla koleksiyon öğesinden metin değerini almaya çalışır. |

### getAllNames {#getAllNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllNames()
```

Koleksiyon öğesi değerlerinin tüm adlarının bir koleksiyonunu alır.

**Returns:**
String listesi

### hasName {#hasName-java.lang.String-}
Verilen adın koleksiyon öğesinde mevcut olup olmadığını denetler.

### isEmpty {#isEmpty--}
```
public final boolean isEmpty()
```

Koleksiyon öğesinin boş olup olmadığını gösteren bir değeri alır.

**Returns:**
Koleksiyon öğesi boşsa true; aksi takdirde false. Bu özellik, koleksiyon öğesi string değerleri, double değerleri, tam sayı değerleri ve tarih değerleri dahil hiçbir değer içermiyorsa true döndürür. Bu değer türlerinden herhangi biri koleksiyon öğesinde mevcutsa, bu özellik false döndürür.

### tryGetDateTimeValue {#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Belirtilen adla koleksiyon öğesinden DateTime türündeki değeri almaya çalışır.

### tryGetDoubleValue {#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Belirtilen ad için koleksiyon öğesinden double değeri almaya çalışır.

### tryGetIntValue {#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Belirtilen ad için koleksiyon öğesinden tam sayı değerini almaya çalışır.

### tryGetTextValue {#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Belirtilen adla koleksiyon öğesinden metin değerini almaya çalışır.

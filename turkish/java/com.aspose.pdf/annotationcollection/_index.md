---
title: "AnnotationCollection"
linktitle: "AnnotationCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Açıklama koleksiyonunu temsil eden sınıf."
type: docs
weight: 80
url: /tr/java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationCollection

**All Implemented Interfaces:**
Iterable < Annotation >

```
public final class AnnotationCollection extends Object implements Iterable < Annotation >
```

Açıklama koleksiyonunu temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AnnotationCollection](#AnnotationCollection-com.aspose.pdf.Page-) | AnnotationCollection yapıcısı. Verilen sayfadaki açıklamalar için bir açıklama koleksiyonu oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Açıklamayı işlemek için ziyaretçiyi kabul eder. |
| [add](#add-com.aspose.pdf.Annotation-) | Açıklamayı koleksiyona ekler. |
| [add](#add-com.aspose.pdf.Annotation-boolean-) | Açıklamayı koleksiyona ekler. Sayfa döndürülmüşse, açıklama dikdörtgeni buna göre yeniden hesaplanacaktır. |
| [clear](#clear--) | Koleksiyondaki tüm açıklamaları siler. |
| [contains](#contains-com.aspose.pdf.Annotation-) | Belirtilen açıklamanın koleksiyona ait olup olmadığını kontrol eder. |
| [copyTo](#copyTo-com.aspose.pdf.Annotation:A-int-) | Açıklama dizisini koleksiyona kopyalar. |
| [delete](#delete--) | Koleksiyondaki tüm açıklamaları siler. |
| [delete](#delete-com.aspose.pdf.Annotation-) | Koleksiyondaki tüm açıklamaları siler. |
| [delete](#delete-int-) | Açıklamayı indeksine göre koleksiyondan siler. |
| [findByName](#findByName-java.lang.String-) | Açıklamayı adıyla döndürür. |
| [get_Item](#get_Item-int-) | Alınacak öğenin indeksi. |
| [getSyncRoot](#getSyncRoot--) | com.aspose.pdf.AnnotationCollection erişimini senkronize etmek için kullanılabilecek bir nesne alır. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değer alır. |
| [isSynchronized](#isSynchronized--) | com.aspose.pdf.AnnotationCollection erişiminin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer alır. |
| [iterator](#iterator--) | Koleksiyon yineleyicisini döndürür. |
| [remove](#remove-com.aspose.pdf.Annotation-) | Belirtilen açıklamayı koleksiyondan siler. |
| [size](#size--) | Koleksiyondaki açıklamaların sayısını alır. |

### AnnotationCollection {#AnnotationCollection-com.aspose.pdf.Page-}
AnnotationCollection yapıcısı. Verilen sayfadaki açıklamalar için bir açıklama koleksiyonu oluşturur.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Açıklamayı işlemek için ziyaretçiyi kabul eder.

### add {#add-com.aspose.pdf.Annotation-}
Açıklamayı koleksiyona ekler.

### add {#add-com.aspose.pdf.Annotation-boolean-}
Açıklamayı koleksiyona ekler. Sayfa döndürülmüşse, açıklama dikdörtgeni buna göre yeniden hesaplanacaktır.

### clear {#clear--}
```
public void clear()
```

Koleksiyondaki tüm açıklamaları siler.

### contains {#contains-com.aspose.pdf.Annotation-}
Belirtilen açıklamanın koleksiyona ait olup olmadığını kontrol eder.

### copyTo {#copyTo-com.aspose.pdf.Annotation:A-int-}
Açıklama dizisini koleksiyona kopyalar.

### delete {#delete--}
```
public void delete()
```

Koleksiyondaki tüm açıklamaları siler.

### delete {#delete-com.aspose.pdf.Annotation-}
Koleksiyondaki tüm açıklamaları siler.

### delete {#delete-int-}
```
public void delete(int index)
```

Açıklamayı indeksine göre koleksiyondan siler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Silinecek açıklamanın dizini. |

### findByName {#findByName-java.lang.String-}
Açıklamayı adıyla döndürür.

### get_Item {#get_Item-int-}
```
public Annotation get_Item(int index)
```

Alınacak öğenin indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Dizin değeri birden başlar. |

**Returns:**
Açıklama nesnesi

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

com.aspose.pdf.AnnotationCollection erişimini senkronize etmek için kullanılabilecek bir nesne alır.

**Returns:**
Senkronizasyon için nesne

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değer alır.

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

com.aspose.pdf.AnnotationCollection erişiminin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer alır.

**Returns:**
boolean değer

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Annotation > iterator()
```

Koleksiyon yineleyicisini döndürür.

**Returns:**
Yineleyici nesnesi

### remove {#remove-com.aspose.pdf.Annotation-}
Belirtilen açıklamayı koleksiyondan siler.

### size {#size--}
```
public int size()
```

Koleksiyondaki açıklamaların sayısını alır.

**Returns:**
int değer

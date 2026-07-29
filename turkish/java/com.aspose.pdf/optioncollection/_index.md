---
title: "OptionCollection"
linktitle: "OptionCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Seçim alanının seçenek koleksiyonunu temsil eden sınıf."
type: docs
weight: 3250
url: /tr/java/com.aspose.pdf/optioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OptionCollection

**All Implemented Interfaces:**
Iterable < Option >

```
public final class OptionCollection extends Object implements Iterable < Option >
```

Seçim alanının seçenek koleksiyonunu temsil eden sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.Option-) | Koleksiyona öğe ekler, hata fırlatır. Henüz uygulanmadı. |
| [clear](#clear--) | Koleksiyondan tüm öğeleri kaldırır. |
| [contains](#contains-com.aspose.pdf.Option-) | Koleksiyonda öğenin var olup olmadığını kontrol eder, hata fırlatır. Henüz uygulanmadı. |
| [deleteOption](#deleteOption-java.lang.String-) | Seçeneği adından siler. |
| [get_Item](#get_Item-int-) | Seçeneği indeksle alır. |
| [get_Item](#get_Item-java.lang.String-) | Seçeneği adından alır. |
| [get](#get-int-) | Seçeneği indeksle alır. |
| [get](#get-java.lang.String-) | Seçeneği koleksiyondan seçenek adıyla alır. |
| [getSyncRoot](#getSyncRoot--) | Koleksiyonun senkronizasyon nesnesi. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değer alır. |
| [isSynchronized](#isSynchronized--) | Nesne senkronize ise true döndürür. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Koleksiyondaki seçenekler için döngüleyiciyi döndürür. |
| [iterator](#iterator--) | Koleksiyondaki seçenekler için döngüleyiciyi döndürür. |
| [remove](#remove-com.aspose.pdf.Option-) | Koleksiyondan öğeyi kaldırır, hata fırlatır. Henüz uygulanmadı. |
| [size](#size--) | Seçenek sayısını alır. |

### add {#add-com.aspose.pdf.Option-}
Koleksiyona öğe ekler, hata fırlatır. Henüz uygulanmadı.

### clear {#clear--}
```
public void clear()
```

Koleksiyondan tüm öğeleri kaldırır.

### contains {#contains-com.aspose.pdf.Option-}
Koleksiyonda öğenin var olup olmadığını kontrol eder, hata fırlatır. Henüz uygulanmadı.

### deleteOption {#deleteOption-java.lang.String-}
Seçeneği adından siler.

### get_Item {#get_Item-int-}
```
public Option get_Item(int index)
```

Seçeneği indeksle alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Seçeneğin indeksi. |

**Returns:**
Belirtilen indeksteki seçenek.

### get_Item {#get_Item-java.lang.String-}
Seçeneği adından alır.

### get {#get-int-}
```
public Option get(int index)
```

Seçeneği indeksle alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Seçenek indeksi. İndeks [1..n] aralığında olmalıdır; n seçenek sayısıdır. |

**Returns:**
Alınan seçenek.

### get {#get-java.lang.String-}
Seçeneği koleksiyondan seçenek adıyla alır.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Koleksiyonun senkronizasyon nesnesi.

**Returns:**
Nesne öğesi

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

Nesne senkronize ise true döndürür.

**Returns:**
boolean değer

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Koleksiyondaki seçenekler için döngüleyiciyi döndürür.

**Returns:**
Seçenek döngüleyicisi.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Option > iterator()
```

Koleksiyondaki seçenekler için döngüleyiciyi döndürür.

**Returns:**
Seçenek döngüleyicisi.

### remove {#remove-com.aspose.pdf.Option-}
Koleksiyondan öğeyi kaldırır, hata fırlatır. Henüz uygulanmadı.

### size {#size--}
```
public int size()
```

Seçenek sayısını alır.

**Returns:**
int değer

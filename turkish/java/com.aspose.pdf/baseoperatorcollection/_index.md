---
title: "BaseOperatorCollection"
linktitle: "BaseOperatorCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Operatör koleksiyonu için temel sınıfı temsil eder."
type: docs
weight: 270
url: /tr/java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public abstract class BaseOperatorCollection extends Object implements Iterable < Operator >
```

Operatör koleksiyonu için temel sınıfı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BaseOperatorCollection](#BaseOperatorCollection--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Koleksiyona yeni bir operatör ekler. |
| [cancelUpdate](#cancelUpdate--) | Son güncellemeyi iptal eder. Bu yöntem, değişikliğin içerik güncellemesi tetiklememesi gerektiğinde çağrılabilir. |
| [clear](#clear--) | Koleksiyonu temizler. |
| [contains](#contains-com.aspose.pdf.Operator-) | Öğenin koleksiyonda olup olmadığını kontrol eder. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | dahili |
| [get_Item](#get_Item-int-) | Operatörü indeksine göre alır. |
| [getUnrestricted](#getUnrestricted-int-) | Yalnızca dahili kullanım için |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Operatörü koleksiyona ekler. |
| [isEmpty](#isEmpty--) | Koleksiyon boşsa TRUE döndürür. |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Koleksiyonun hızlı metin çıkarımına sınırlı olup olmadığını gösterir. |
| [isReadOnly](#isReadOnly--) | Koleksiyon yalnızca okunabilir ise true döndürür. |
| [iterator](#iterator--) | Koleksiyon için bir yineleyici döndürür. |
| [remove](#remove-com.aspose.pdf.Operator-) | Operatörü koleksiyondan kaldırır. |
| [resumeUpdate](#resumeUpdate--) | Belge güncellemesini sürdürür. Bekleyen değişiklikler varsa içerik akışını günceller. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Operatörü indeksine göre ayarlar. |
| [size](#size--) | Koleksiyondaki operatör sayısını alır. |
| [suppressUpdate](#suppressUpdate--) | İçerik güncelleme verilerini bastırır. İçerik akışı, ResumeUpdate çağrılana kadar güncellenmez. |
| [toList](#toList--) | Operatör listesini döndürür. |
| [updateData](#updateData--) | dahili |

### BaseOperatorCollection {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```



### add {#add-com.aspose.pdf.Operator-}
Koleksiyona yeni bir operatör ekler.

### cancelUpdate {#cancelUpdate--}
```
public abstract void cancelUpdate()
```

Son güncellemeyi iptal eder. Bu yöntem, değişikliğin içerik güncellemesi tetiklememesi gerektiğinde çağrılabilir.

### clear {#clear--}
```
public abstract void clear()
```

Koleksiyonu temizler.

### contains {#contains-com.aspose.pdf.Operator-}
Öğenin koleksiyonda olup olmadığını kontrol eder.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```

dahili

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | int değer |

### get_Item {#get_Item-int-}
```
public abstract Operator get_Item(int index)
```

Operatörü indeksine göre alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Operatör indeksi. Numara 1'den başlar. |

**Returns:**
İstenen indeksden operatör

### getUnrestricted {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```

Yalnızca dahili kullanım için

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | int değer |

**Returns:**
Operatör nesnesi

### insert {#insert-int-com.aspose.pdf.Operator-}
Operatörü koleksiyona ekler.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Koleksiyon boşsa TRUE döndürür.

**Returns:**
boolean değer

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```

Koleksiyonun hızlı metin çıkarımına sınırlı olup olmadığını gösterir.

**Returns:**
boolean değer

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

Koleksiyon yalnızca okunabilir ise true döndürür.

**Returns:**
boolean değer

### iterator {#iterator--}
```
public abstract Iterator < Operator > iterator()
```

Koleksiyon için bir yineleyici döndürür.

**Returns:**
Koleksiyon yineleyicisi

### remove {#remove-com.aspose.pdf.Operator-}
Operatörü koleksiyondan kaldırır.

### resumeUpdate {#resumeUpdate--}
```
public abstract void resumeUpdate()
```

Belge güncellemesini sürdürür. Bekleyen değişiklikler varsa içerik akışını günceller.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Operatörü indeksine göre ayarlar.

### size {#size--}
```
public abstract int size()
```

Koleksiyondaki operatör sayısını alır.

**Returns:**
tam sayı değeri

### suppressUpdate {#suppressUpdate--}
```
public abstract void suppressUpdate()
```

İçerik güncelleme verilerini bastırır. İçerik akışı, ResumeUpdate çağrılana kadar güncellenmez.

### toList {#toList--}
```
public abstract com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Operatör listesini döndürür.

**Returns:**
operatör listesi.

### updateData {#updateData--}
```
public abstract void updateData()
```

dahili

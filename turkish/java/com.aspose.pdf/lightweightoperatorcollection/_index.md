---
title: "LightweightOperatorCollection"
linktitle: "LightweightOperatorCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Hafif operatör koleksiyonu. Alt içerik akışı ekli olmadığında, yalnızca operatör koleksiyonunun gerektiği senaryolarda kullanılmak üzere tasarlanmıştır."
type: docs
weight: 2700
url: /tr/java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.LightweightOperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.LightweightOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

Hafif operatör koleksiyonu. Alt içerik akışı ekli olmadığında, yalnızca operatör koleksiyonunun gerektiği senaryolarda kullanılmak üzere tasarlanmıştır.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LightweightOperatorCollection](#LightweightOperatorCollection--) | Nesneyi başlat |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-) | Nesneyi başlat |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | Nesneyi başlat |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Operatör ekle |
| [addRange](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | LightweightOperatorCollection ekle |
| [cancelUpdate](#cancelUpdate--) | Son güncellemeyi iptal eder. Bu yöntem, değişikliğin içerik güncellemesi tetiklememesi gerektiğinde çağrılabilir. |
| [clear](#clear--) | Koleksiyonu temizler. |
| [contains](#contains-com.aspose.pdf.Operator-) | Öğenin koleksiyonda olup olmadığını kontrol eder. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | içsel sil Unrestrictedelement |
| [get_Item](#get_Item-int-) | <p> İndeksine göre operatörü alır. </p> <hr> <pre> Örnek, sayfa içeriğinin operatörünü indeksle nasıl alacağını gösterir. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | İç kullanım için getUnrestricted operatörü |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Operatör ekle |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Koleksiyonun hızlı metin çıkarımına sınırlı olup olmadığını gösterir. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır. |
| [iterator](#iterator--) | Yineleyiciyi döndür |
| [remove](#remove-com.aspose.pdf.Operator-) | Operatörü koleksiyondan kaldırır. |
| [resumeUpdate](#resumeUpdate--) | Belge güncellemesini sürdürür. Bekleyen değişiklikler varsa içerik akışını günceller. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | İndeksine göre operatörü ayarlar. <hr> <pre> Örnek, sayfa içeriğinin operatörünü indeksle nasıl alacağını gösterir. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [size](#size--) | Operatör sayısı |
| [suppressUpdate](#suppressUpdate--) | İçerik güncelleme verilerini bastırır. İçerik akışı, ResumeUpdate çağrılana kadar güncellenmez. |
| [toList](#toList--) | Operatör listesini döndürür. |
| [updateData](#updateData--) | dahili |

### LightweightOperatorCollection {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```

Nesneyi başlat

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-}
Nesneyi başlat

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
Nesneyi başlat

### add {#add-com.aspose.pdf.Operator-}
Operatör ekle

### addRange {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
LightweightOperatorCollection ekle

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Son güncellemeyi iptal eder. Bu yöntem, değişikliğin içerik güncellemesi tetiklememesi gerektiğinde çağrılabilir.

### clear {#clear--}
```
public void clear()
```

Koleksiyonu temizler.

### contains {#contains-com.aspose.pdf.Operator-}
Öğenin koleksiyonda olup olmadığını kontrol eder.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

içsel sil Unrestrictedelement

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | int değer |

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> İndeksine göre operatörü alır. </p> <hr> <pre> Örnek, sayfa içeriğinin operatörünü indeksle nasıl alacağını gösterir. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Operatör indeksi. Numara 1'den başlar. |

**Returns:**
İstenen indeksden operatör

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

İç kullanım için getUnrestricted operatörü

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | int değer |

**Returns:**
Operatör nesnesi

### insert {#insert-int-com.aspose.pdf.Operator-}
Operatör ekle

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Koleksiyonun hızlı metin çıkarımına sınırlı olup olmadığını gösterir.

**Returns:**
boolean değer

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### iterator {#iterator--}
```
public Iterator < Operator > iterator()
```

Yineleyiciyi döndür

**Returns:**
{@code IGenericEnumerator<Operator>} nesnesi

### remove {#remove-com.aspose.pdf.Operator-}
Operatörü koleksiyondan kaldırır.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Belge güncellemesini sürdürür. Bekleyen değişiklikler varsa içerik akışını günceller.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
İndeksine göre operatörü ayarlar. <hr> <pre> Örnek, sayfa içeriğinin operatörünü indeksle nasıl alacağını gösterir. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

### size {#size--}
```
public int size()
```

Operatör sayısı

**Returns:**
int değer

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

İçerik güncelleme verilerini bastırır. İçerik akışı, ResumeUpdate çağrılana kadar güncellenmez.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Operatör listesini döndürür.

**Returns:**
operatör listesi.

### updateData {#updateData--}
```
public void updateData()
```

dahili

---
title: "OperatorCollection"
linktitle: "OperatorCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sınıf, operatörlerin koleksiyonunu temsil eder"
type: docs
weight: 3190
url: /tr/java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.OperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.OperatorCollection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Iterable < Operator >

```
public class OperatorCollection extends BaseOperatorCollection implements com.aspose.ms.System.IDisposable
```

Sınıf, operatörlerin koleksiyonunu temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | Yalnızca dahili kullanım için! |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-) | Yalnızca dahili kullanım için! |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörleri işlemek için IOperatorSelector ziyaretçi nesnesini kabul eder. |
| [add](#add-java.lang.Iterable-) | Diğer koleksiyondan tüm operatörleri koleksiyona ekler. |
| [add](#add-com.aspose.pdf.Operator-) | <p> Koleksiyona yeni bir operatör ekler. </p> <hr> <p> Örnek, operatörlerin page.contents sonuna nasıl ekleneceğini gösterir. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p> |
| [add](#add-com.aspose.pdf.Operator:A-) | <p> İçerik operatörlerinin sonuna operatör ekler. </p> <hr> <p> Örnek, sayfa içeriğinin sonuna operatör eklemenin nasıl yapılacağını gösterir. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [cancelUpdate](#cancelUpdate--) | Son güncellemeyi iptal eder. Bu yöntem, değişikliğin içerik güncellemesi tetiklememesi gerektiğinde çağrılabilir. |
| [clear](#clear--) | <p> Listedeki tüm operatörleri kaldırır. </p> <hr> <p> Örnek, sayfa içeriğini nasıl temizleyeceğini gösterir. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p> |
| [close](#close--) | Yönetilmeyen kaynakların serbest bırakılması, salınması veya sıfırlanmasıyla ilgili uygulama tanımlı görevleri yürütür. |
| [contains](#contains-com.aspose.pdf.Operator-) | Koleksiyon verilen operatörü içeriyorsa true döndürür. |
| [delete](#delete-int-) | <p> Koleksiyondan operatörü siler. </p> <hr> <p> Örnek, operatörün indeksine göre nasıl silineceğini gösterir. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p> |
| [delete](#delete-java.lang.Iterable-) | Operatörleri koleksiyondan siler. |
| [delete](#delete-com.aspose.pdf.Operator:A-) | <p> Koleksiyondan operatörleri siler. </p> <hr> <p> Örnek, sayfa içeriğinden operatörün nasıl kaldırılacağını gösterir. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p> |
| [deleteUnrestricted](#deleteUnrestricted-int-) | Delete(index) yönteminin iç sınırsız sürümü |
| [dispose](#dispose--) | Yönetilmeyen kaynakların serbest bırakılması, salınması veya sıfırlanmasıyla ilgili uygulama tanımlı görevleri yürütür. |
| [get_Item](#get_Item-int-) | <p> Operatörü indeksine göre alır. </p> <hr> Example demonstrates how to get operator of page contents by index. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Dizinin iç sınırsız sürümü |
| [insert](#insert-int-java.lang.Iterable-) | Operatörleri verilen konuma ekle. |
| [insert](#insert-int-com.aspose.pdf.Operator-) | <p> Kolleksiyona operatör ekler. </p> <hr> <p> Örnek, operatörün sayfa içeriğine nasıl ekleneceğini gösterir. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p> |
| [insert](#insert-int-com.aspose.pdf.Operator:A-) | <p> Operatörleri verilen konuma ekle. </p> <hr> <p> Örnek, operatörün sayfa içeriğine nasıl ekleneceğini gösterir. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [isBracketed](#isBracketed--) | Operatör dizisinin parantezli durumunu alır; yani bu operatörlerin q - Q blokları içinde olup olmadığını belirler. |
| [isCommandsParsed](#isCommandsParsed--) | Ayrıştırılan komutları alır. |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Koleksiyonun hızlı metin çıkarımına sınırlı olup olmadığını gösterir. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır. |
| [iterator](#iterator--) | Koleksiyon için bir yineleyici döndürür. |
| [precalculateOperatorsCount](#precalculateOperatorsCount--) | Sayfa içeriğini tanımlayan, henüz başlatılmamış operatörlerin sayısını alır. |
| [remove](#remove-com.aspose.pdf.Operator-) | Operatörü koleksiyondan kaldır. |
| [replace](#replace-java.lang.Iterable-) | Koleksiyondaki operatörleri başka operatörlerle değiştir. |
| [replace](#replace-com.aspose.pdf.Operator:A-) | Koleksiyondaki operatörleri başka operatörlerle değiştir. |
| [resumeUpdate](#resumeUpdate--) | Belge güncellemesini sürdürür. Bekleyen değişiklikler varsa içerik akışını günceller. |
| [resumeUpdate](#resumeUpdate-boolean-) | Belge güncellemesini yeniden başlatır. Bekleyen değişiklikler varsa içerik akışını günceller. invalidate parametresi true ise tüm operatörleri "changed" olarak işaretler. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Operatörü indeksine göre ayarlar. |
| [size](#size--) | Koleksiyondaki operatör sayısını alır. |
| [suppressUpdate](#suppressUpdate--) | İçerik güncelleme verilerini bastırır. İçerik akışı, ResumeUpdate çağrılana kadar güncellenmez. |
| [toList](#toList--) | Operatör listesini döndürür. |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |
| [updateData](#updateData--) | Nesne akışını güncelle. |
| [updateNormalizedData](#updateNormalizedData--) | Eksik GSave/GRestore operatörlerini düzelterek nesne akışını güncelle. |

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
Yalnızca dahili kullanım için!

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-}
Yalnızca dahili kullanım için!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörleri işlemek için IOperatorSelector ziyaretçi nesnesini kabul eder.

### add {#add-java.lang.Iterable-}
Diğer koleksiyondan tüm operatörleri koleksiyona ekler.

### add {#add-com.aspose.pdf.Operator-}
<p> Koleksiyona yeni bir operatör ekler. </p> <hr> <p> Örnek, operatörlerin page.contents sonuna nasıl ekleneceğini gösterir. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p>

### add {#add-com.aspose.pdf.Operator:A-}
<p> İçerik operatörlerinin sonuna operatör ekler. </p> <hr> <p> Örnek, sayfa içeriğinin sonuna operatör eklemenin nasıl yapılacağını gösterir. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Son güncellemeyi iptal eder. Bu yöntem, değişikliğin içerik güncellemesi tetiklememesi gerektiğinde çağrılabilir.

### clear {#clear--}
```
public void clear()
```

<p> Listedeki tüm operatörleri kaldırır. </p> <hr> <p> Örnek, sayfa içeriğini nasıl temizleyeceğini gösterir. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p>

### close {#close--}
```
public final void close()
```

Yönetilmeyen kaynakların serbest bırakılması, salınması veya sıfırlanmasıyla ilgili uygulama tanımlı görevleri yürütür.

### contains {#contains-com.aspose.pdf.Operator-}
Koleksiyon verilen operatörü içeriyorsa true döndürür.

### delete {#delete-int-}
```
public void delete(int index)
```

<p> Koleksiyondan operatörü siler. </p> <hr> <p> Örnek, operatörün indeksine göre nasıl silineceğini gösterir. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Silinmesi gereken operatörün indeksi. Operatör numaralandırması 1'den başlar. |

### delete {#delete-java.lang.Iterable-}
Operatörleri koleksiyondan siler.

### delete {#delete-com.aspose.pdf.Operator:A-}
<p> Koleksiyondan operatörleri siler. </p> <hr> <p> Örnek, sayfa içeriğinden operatörün nasıl kaldırılacağını gösterir. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p>

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

Delete(index) yönteminin iç sınırsız sürümü

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | int değer |

### dispose {#dispose--}
```
public final void dispose()
```

Yönetilmeyen kaynakların serbest bırakılması, salınması veya sıfırlanmasıyla ilgili uygulama tanımlı görevleri yürütür.

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Operatörü indeksine göre alır. </p> <hr> Example demonstrates how to get operator of page contents by index. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre>

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

Dizinin iç sınırsız sürümü

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | int değer |

**Returns:**
Operatör nesnesi

### insert {#insert-int-java.lang.Iterable-}
Operatörleri verilen konuma ekle.

### insert {#insert-int-com.aspose.pdf.Operator-}
<p> Kolleksiyona operatör ekler. </p> <hr> <p> Örnek, operatörün sayfa içeriğine nasıl ekleneceğini gösterir. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p>

### insert {#insert-int-com.aspose.pdf.Operator:A-}
<p> Operatörleri verilen konuma ekle. </p> <hr> <p> Örnek, operatörün sayfa içeriğine nasıl ekleneceğini gösterir. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### isBracketed {#isBracketed--}
```
public boolean isBracketed()
```

Operatör dizisinin parantezli durumunu alır; yani bu operatörlerin q - Q blokları içinde olup olmadığını belirler.

**Returns:**
boolean değer

### isCommandsParsed {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```

Ayrıştırılan komutları alır.

**Returns:**
boolean değer

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
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Operator > iterator()
```

Koleksiyon için bir yineleyici döndürür.

**Returns:**
Koleksiyon yineleyicisi

### precalculateOperatorsCount {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```

Sayfa içeriğini tanımlayan, henüz başlatılmamış operatörlerin sayısını alır.

**Returns:**
int değer

### remove {#remove-com.aspose.pdf.Operator-}
Operatörü koleksiyondan kaldır.

### replace {#replace-java.lang.Iterable-}
Koleksiyondaki operatörleri başka operatörlerle değiştir.

### replace {#replace-com.aspose.pdf.Operator:A-}
Koleksiyondaki operatörleri başka operatörlerle değiştir.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Belge güncellemesini sürdürür. Bekleyen değişiklikler varsa içerik akışını günceller.

### resumeUpdate {#resumeUpdate-boolean-}
```
public final void resumeUpdate(boolean updateAll)
```

Belge güncellemesini yeniden başlatır. Bekleyen değişiklikler varsa içerik akışını günceller. invalidate parametresi true ise tüm operatörleri "changed" olarak işaretler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| updateAll |  | True ise, koleksiyondaki tüm operatörler güncellenmiş olarak işaretlenir. |

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Operatörü indeksine göre ayarlar.

### size {#size--}
```
public int size()
```

Koleksiyondaki operatör sayısını alır.

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

### toString {#toString--}
```
public String toString()
```

Operatörün metin temsilini döndürür.

**Returns:**
Operatörün metin temsili.

### updateData {#updateData--}
```
public void updateData()
```

Nesne akışını güncelle.

### updateNormalizedData {#updateNormalizedData--}
```
public void updateNormalizedData()
```

Eksik GSave/GRestore operatörlerini düzelterek nesne akışını güncelle.

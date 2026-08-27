---
title: "CosPdfDictionary"
linktitle: "CosPdfDictionary"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir nesnenin sözlüğüne erişmek için sınıf."
type: docs
weight: 20
url: /tr/java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

Bir nesnenin sözlüğüne erişmek için sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | Kaynaklardan bir sözlük oluşturur. @exception ArgumentNullException Kaynaklar null. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | ICosPdfPrimitive'i sözlüğe ayarla. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | {@link ICosPdfPrimitive}'i sözlüğe ayarlar. @exception ArgumentException Anahtar/değer düzenlenemiyor veya kaldırılamıyorsa istisna fırlatır. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Öğe çiftini ekle. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Öğe ekle. |
| [clear](#clear--) | {@link CosPdfDictionary}'den tüm öğeleri kaldırır. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | CosPdfDictionary'nin belirli bir değeri içerip içermediğini belirler. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Öğe içeriyorsa true döndür. |
| [containsKey](#containsKey-java.lang.String-) | {@link CosPdfDictionary}'nin belirtilen anahtara sahip bir öğe içerip içermediğini belirler. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | CosPdfDictionary öğelerini bir diziye kopyalar, belirli bir dizi indeksinden başlayarak. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Diziye Kopyala |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | Belgeye eklenecek boş bir sözlük oluşturur. |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | Sayfaya eklenecek boş bir sözlük oluşturur. |
| [get_Item](#get_Item-java.lang.String-) | Belirtilen anahtara sahip öğeyi alır veya ayarlar. |
| [getAllKeys](#getAllKeys--) | Anahtarların tam koleksiyonu. Düzenlenebilir ve düzenlenemez anahtarları içerir. |
| [getKeys](#getKeys--) | Düzenlenebilir anahtarların koleksiyonu. |
| [getValues](#getValues--) | {@link CosPdfDictionary} içindeki değerleri içeren bir {@link ICollection} alır. |
| [isReadOnly](#isReadOnly--) | {@link CosPdfDictionary} nesnesinin yalnızca okunur olup olmadığını gösteren bir değer alır. |
| [iterator](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | CosPdfDictionary'den belirli bir nesnenin ilk oluşumunu kaldırır. |
| [remove](#remove-java.lang.String-) | Belirtilen anahtara sahip öğeyi {@link CosPdfDictionary}'den kaldırır. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Öğeyi Kaldır |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Anahtara göre öğeyi kaldır. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Belirtilen anahtara sahip öğeyi alır veya ayarlar. @exception ArgumentNullException Anahtar nulldır. @exception KeyNotFoundException Özellik alındı ancak anahtar bulunamadı. @exception ArgumentException Anahtar düzenlenemiyor/ayarlanamıyorsa istisna fırlat. |
| [size](#size--) | {@link CosPdfDictionary} içinde bulunan öğe sayısını alır. |
| [toCosPdfDictionary](#toCosPdfDictionary--) | Bu örneği {@link CosPdfDictionary}'ye dönüştürmeye çalışır. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | String, name, bool, number gibi basit veri tiplerine erişim için. Diğer tipler için null döndürür. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Değeri almaya çalış. |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
Kaynaklardan bir sözlük oluşturur. @exception ArgumentNullException Kaynaklar null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
ICosPdfPrimitive'i sözlüğe ayarla.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
{@link ICosPdfPrimitive}'i sözlüğe ayarlar. @exception ArgumentException Anahtar/değer düzenlenemiyor veya kaldırılamıyorsa istisna fırlatır.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Öğe çiftini ekle.

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Öğe ekle.

### clear {#clear--}
```
public final void clear()
```

{@link CosPdfDictionary}'den tüm öğeleri kaldırır.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
CosPdfDictionary'nin belirli bir değeri içerip içermediğini belirler.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Öğe içeriyorsa true döndür.

### containsKey {#containsKey-java.lang.String-}
{@link CosPdfDictionary}'nin belirtilen anahtara sahip bir öğe içerip içermediğini belirler.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
CosPdfDictionary öğelerini bir diziye kopyalar, belirli bir dizi indeksinden başlayarak.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Diziye Kopyala

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
Belgeye eklenecek boş bir sözlük oluşturur.

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
Sayfaya eklenecek boş bir sözlük oluşturur.

### get_Item {#get_Item-java.lang.String-}
Belirtilen anahtara sahip öğeyi alır veya ayarlar.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Anahtarların tam koleksiyonu. Düzenlenebilir ve düzenlenemez anahtarları içerir.

**Returns:**
String değerlerinin listesi

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Düzenlenebilir anahtarların koleksiyonu.

**Returns:**
String değerlerinin listesi

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

{@link CosPdfDictionary} içindeki değerleri içeren bir {@link ICollection} alır.

**Returns:**
ICosPdfPrimitive örneklerinin listesi

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

{@link CosPdfDictionary} nesnesinin yalnızca okunur olup olmadığını gösteren bir değer alır.

**Returns:**
{@link CosPdfDictionary} yalnızca okunur ise true; aksi takdirde false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Returns:**
Koleksiyon üzerinde yineleme yapmak için kullanılabilecek bir enumerator.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
CosPdfDictionary'den belirli bir nesnenin ilk oluşumunu kaldırır.

### remove {#remove-java.lang.String-}
Belirtilen anahtara sahip öğeyi {@link CosPdfDictionary}'den kaldırır.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Öğeyi Kaldır

### removeItemByKey {#removeItemByKey-java.lang.String-}
Anahtara göre öğeyi kaldır.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Belirtilen anahtara sahip öğeyi alır veya ayarlar. @exception ArgumentNullException Anahtar nulldır. @exception KeyNotFoundException Özellik alındı ancak anahtar bulunamadı. @exception ArgumentException Anahtar düzenlenemiyor/ayarlanamıyorsa istisna fırlat.

### size {#size--}
```
public final int size()
```

{@link CosPdfDictionary} içinde bulunan öğe sayısını alır.

**Returns:**
int değer

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

Bu örneği {@link CosPdfDictionary}'ye dönüştürmeye çalışır.

**Returns:**
Örnek {@link CosPdfDictionary} değilse null, aksi takdirde {@link CosPdfDictionary}.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
String, name, bool, number gibi basit veri tiplerine erişim için. Diğer tipler için null döndürür.

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Değeri almaya çalış.

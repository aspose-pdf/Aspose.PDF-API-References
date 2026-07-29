---
title: "AppearanceDictionary"
linktitle: "AppearanceDictionary"
second_title: "Aspose.PDF for Java API Referansı"
description: "Açıklamanın sayfada görsel olarak nasıl sunulacağını belirten açıklama görünüm sözlüğü."
type: docs
weight: 150
url: /tr/java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AppearanceDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XForm >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>

```
public final class AppearanceDictionary extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XForm >
```

Açıklamanın sayfada görsel olarak nasıl sunulacağını belirten açıklama görünüm sözlüğü.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-java.lang.Object-java.lang.Object-) | Sağlanan anahtar ve değer ile bir öğe ekler. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Anahtar ve değer çifti sözlüğe ekler. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XForm-) | Belirtilen anahtar için X formu ekle. |
| [clear](#clear--) | Sözlükteki tüm öğeleri kaldırır. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Belirtilen anahtar-değer çiftinin sözlükte bulunup bulunmadığını kontrol eder. |
| [containsKey](#containsKey-java.lang.String-) | Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | / * / * Sözlük için bir IDictionaryEnumerator nesnesi döndürür. / * / * / * |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | ICollection öğelerini bir diziye kopyalar, belirli bir dizi indeksinden başlayarak. |
| [get_Item](#get_Item-java.lang.String-) | Görünüm akışlarını almayı sağlayan kullanışlı bir formu temsil eder. |
| [getDict](#getDict--) | pdf sözlüğünü alır |
| [getKeys_](#getKeys_--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state değerleri, burada N - normal görünüm, R - rollover görünüm, D - down görünüm ve state - durumun adı (ör. On, Off onay kutuları için). |
| [getKeys](#getKeys--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state değerleri, burada N - normal görünüm, R - rollover görünüm, D - down görünüm ve state - durumun adı (ör. On, Off onay kutuları için). |
| [getSyncRoot](#getSyncRoot--) | Sözlüğe erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [getValues_](#getValues_--) | Sözlüğün değer listesini alır. Sonuç koleksiyonu XForm nesnelerinin listesini içerir. |
| [getValues](#getValues--) | Sözlüğün değer listesini alır. Sonuç koleksiyonu XForm nesnelerinin listesini içerir. |
| [isFixedSize](#isFixedSize--) | Sözlüğün sabit boyuta sahip olup olmadığını gösteren bir değeri alır. |
| [isReadOnly](#isReadOnly--) | Sözlüğün yalnızca okunur olup olmadığını gösteren bir değeri alır. |
| [isSynchronized](#isSynchronized--) | Sözlüğe erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır. |
| [iterator__Rename_Namesake](#iterator__Rename_Namesake--) | Koleksiyon için Enumerator. |
| [iterator](#iterator--) | Sözlük için bir IDictionaryEnumerator nesnesi döndürür. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Koleksiyondan anahtar/değer çiftini kaldırır. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Sözlükten anahtarı kaldırır. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size](#size--) | Sözlükte bulunan öğe sayısını alır. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri getirir. |

### add {#add-java.lang.Object-java.lang.Object-}
Sağlanan anahtar ve değer ile bir öğe ekler.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Anahtar ve değer çifti sözlüğe ekler.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XForm-}
Belirtilen anahtar için X formu ekle.

### clear {#clear--}
```
public void clear()
```

Sözlükteki tüm öğeleri kaldırır.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Belirtilen anahtar-değer çiftinin sözlükte bulunup bulunmadığını kontrol eder.

### containsKey {#containsKey-java.lang.String-}
Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
/ * / * Sözlük için bir IDictionaryEnumerator nesnesi döndürür. / * / * / *

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
ICollection öğelerini bir diziye kopyalar, belirli bir dizi indeksinden başlayarak.

### get_Item {#get_Item-java.lang.String-}
Görünüm akışlarını almayı sağlayan kullanışlı bir formu temsil eder.

### getDict {#getDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getDict()
```

pdf sözlüğünü alır

**Returns:**
IPdfDictionary nesnesi

### getKeys_ {#getKeys_--}
```
public List < String > getKeys_()
```

Sözlüğün anahtarlarını alır. Eğer görünüm sözlüğünün alt sözlükleri varsa, {@code Keys} (N|R|D).state değerlerini içerir, burada N - normal görünüm, R - rollover görünüm, D - down görünüm ve state - durumun adı (ör. On, Off onay kutuları için).

**Returns:**
String değerlerinin listesi

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Sözlüğün anahtarlarını alır. Eğer görünüm sözlüğünün alt sözlükleri varsa, {@code Keys} (N|R|D).state değerlerini içerir, burada N - normal görünüm, R - rollover görünüm, D - down görünüm ve state - durumun adı (ör. On, Off onay kutuları için).

**Returns:**
String değerlerinin listesi

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Sözlüğe erişimi senkronize etmek için kullanılabilecek bir nesneyi alır.

**Returns:**
Eşitleme için nesne

### getValues_ {#getValues_--}
```
public List < XForm > getValues_()
```

Sözlüğün değer listesini alır. Sonuç koleksiyonu XForm nesnelerinin listesini içerir.

**Returns:**
XForm değerlerinin listesi

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XForm > getValues()
```

Sözlüğün değer listesini alır. Sonuç koleksiyonu XForm nesnelerinin listesini içerir.

**Returns:**
XForm değerlerinin listesi

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Sözlüğün sabit boyuta sahip olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Sözlüğün yalnızca okunur olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Sözlüğe erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### iterator__Rename_Namesake {#iterator__Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator__Rename_Namesake()
```

Koleksiyon için Enumerator.

**Returns:**
koleksiyon öğelerinin enumerator'ı.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator()
```

Sözlük için bir IDictionaryEnumerator nesnesi döndürür.

**Returns:**
Sözlüğün yineleyicisi.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Koleksiyondan anahtar/değer çiftini kaldırır.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Sözlükten anahtarı kaldırır.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XForm-}


### size {#size--}
```
public int size()
```

Sözlükte bulunan öğe sayısını alır.

**Returns:**
int değer

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri getirir.

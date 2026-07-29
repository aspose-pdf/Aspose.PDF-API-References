---
title: "Meta veri"
linktitle: "Meta veri"
second_title: "Aspose.PDF for Java API Referansı"
description: "XMP meta veri akışına erişim sağlar."
type: docs
weight: 3050
url: /tr/java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class Metadata extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

XMP meta veri akışına erişim sağlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Anahtar ve değer çifti sözlüğe ekler. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Değeri meta veriye ekler. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | PDF uzantısını meta veriye ekler. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Değeri meta veriye ekler. |
| [clear](#clear--) | Meta veriyi temizler. |
| [contains](#contains-java.lang.String-) | Anahtarın meta veride bulunup bulunmadığını kontrol eder. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Belirtilen anahtar-değer çiftinin sözlükte bulunup bulunmadığını kontrol eder. |
| [containsKey](#containsKey-java.lang.String-) | Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler. |
| [copyTo](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyonun öğelerini diziye kopyalar. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Koleksiyonun öğelerini diziye kopyalar. |
| [get_Item](#get_Item-java.lang.String-) | Meta veriden verileri alır. |
| [getExtensionFields_Internal](#getExtensionFields_Internal--) | Yalnızca dahili kullanım için. Uzantı alanlarının sözlüğünü alır. |
| [getExtensionFields](#getExtensionFields--) | <p> Uzantı alanlarının sözlüğünü alır. </p> |
| [getItem](#getItem-java.lang.String-) | Meta veriden verileri alır. |
| [getKeys](#getKeys--) | Meta veri anahtarlarının koleksiyonunu alır. |
| [getNamespaceUriByPrefix](#getNamespaceUriByPrefix-java.lang.String-) | Önek ile ad alanı URI'sını döndürür. |
| [getPrefixByNamespaceUri](#getPrefixByNamespaceUri-java.lang.String-) | Ad alanı URI'sına göre önek döndürür. |
| [getSyncRoot](#getSyncRoot--) | Koleksiyon senkronizasyon nesnesini alır. |
| [getValues](#getValues--) | Meta verideki değerleri alır. |
| [isFixedSize](#isFixedSize--) | Koleksiyonun sabit boyuta sahip olup olmadığını kontrol eder. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunabilir olup olmadığını kontrol eder. |
| [isSynchronized](#isSynchronized--) | Koleksiyonun senkronize olup olmadığını kontrol eder. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Sözlük yineleyicisini döndürür. |
| [iteratorIE](#iteratorIE--) | Koleksiyonun yineleyicisini alır. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-) | Ad alanı URI'sını kaydeder. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | Ad alanı URI'sını kaydeder. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Koleksiyondan anahtar/değer çiftini kaldırır. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Meta veriden girişi kaldırır. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | Meta veriden veriyi ayarlar. |
| [setItem](#setItem-java.lang.String-com.aspose.pdf.XmpValue-) | Meta veriden veriyi ayarlar. |
| [size](#size--) | Koleksiyondaki öğelerin sayısını alır. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri getirir. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-) | Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri getirir. |

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Anahtar ve değer çifti sözlüğe ekler.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Değeri meta veriye ekler.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
PDF uzantısını meta veriye ekler.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
Değeri meta veriye ekler.

### clear {#clear--}
```
public void clear()
```

Meta veriyi temizler.

### contains {#contains-java.lang.String-}
Anahtarın meta veride bulunup bulunmadığını kontrol eder.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Belirtilen anahtar-değer çiftinin sözlükte bulunup bulunmadığını kontrol eder.

### containsKey {#containsKey-java.lang.String-}
Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler.

### copyTo {#copyTo-com.aspose.ms.System.Array-int-}
Koleksiyonun öğelerini diziye kopyalar.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Koleksiyonun öğelerini diziye kopyalar.

### get_Item {#get_Item-java.lang.String-}
Meta veriden verileri alır.

### getExtensionFields_Internal {#getExtensionFields_Internal--}
```
public com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpPdfAExtensionSchema > getExtensionFields_Internal()
```

Yalnızca dahili kullanım için. Uzantı alanlarının sözlüğünü alır.

**Returns:**
dahili nesne

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Uzantı alanlarının sözlüğünü alır. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} nesnesi

### getItem {#getItem-java.lang.String-}
Meta veriden verileri alır.

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Meta veri anahtarlarının koleksiyonunu alır.

**Returns:**
ICollection nesnesi

### getNamespaceUriByPrefix {#getNamespaceUriByPrefix-java.lang.String-}
Önek ile ad alanı URI'sını döndürür.

### getPrefixByNamespaceUri {#getPrefixByNamespaceUri-java.lang.String-}
Ad alanı URI'sına göre önek döndürür.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Koleksiyon senkronizasyon nesnesini alır.

**Returns:**
Eşitleme için nesne

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Meta verideki değerleri alır.

**Returns:**
ICollection nesnesi

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Koleksiyonun sabit boyuta sahip olup olmadığını kontrol eder.

**Returns:**
boolean değer

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyonun yalnızca okunabilir olup olmadığını kontrol eder.

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Koleksiyonun senkronize olup olmadığını kontrol eder.

**Returns:**
boolean değer

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Sözlük yineleyicisini döndürür.

**Returns:**
Sıralayıcı.

### iteratorIE {#iteratorIE--}
```
public Iterator <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iteratorIE()
```

Koleksiyonun yineleyicisini alır.

**Returns:**
IEnumerator nesnesi @see IEnumerator

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-}
Ad alanı URI'sını kaydeder.

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
Ad alanı URI'sını kaydeder.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Koleksiyondan anahtar/değer çiftini kaldırır.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Meta veriden girişi kaldırır.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
Meta veriden veriyi ayarlar.

### setItem {#setItem-java.lang.String-com.aspose.pdf.XmpValue-}
Meta veriden veriyi ayarlar.

### size {#size--}
```
public int size()
```

Koleksiyondaki öğelerin sayısını alır.

**Returns:**
int değer

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri getirir.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-}
Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri getirir.

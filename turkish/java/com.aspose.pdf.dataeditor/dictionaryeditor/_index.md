---
title: "DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir belgenin ağaç sözlüğüne (belge sözlüğü, sayfa sözlüğü, kaynak sözlüğü) erişmek için sınıf."
type: docs
weight: 70
url: /tr/java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

Bir belgenin ağaç sözlüğüne (belge sözlüğü, sayfa sözlüğü, kaynak sözlüğü) erişmek için sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException Kaynaklar null. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | ICosPdfPrimitive'i sözlüğe ayarla. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Ayarla {@link ICosPdfPrimitive}'i sözlüğe. |
| [clear](#clear--) | Tüm öğeleri {@link DictionaryEditor}'dan kaldırır. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | DictionaryEditor'ın belirli bir değeri içerip içermediğini belirler. |
| [containsKey](#containsKey-java.lang.String-) | Belirtilen anahtara sahip bir öğenin {@link DictionaryEditor}'da bulunup bulunmadığını belirler. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | DictionaryEditor öğelerini bir diziye kopyalar, belirli bir dizi indeksinden başlayarak. |
| [get_Item](#get_Item-java.lang.String-) | Belirtilen anahtara sahip öğeyi alır veya ayarlar. |
| [getAllKeys](#getAllKeys--) | Anahtarların tam koleksiyonu. Düzenlenebilir ve düzenlenemez anahtarları içerir. |
| [getKeys](#getKeys--) | Düzenlenebilir anahtarların koleksiyonu. |
| [getValues](#getValues--) | {@link DictionaryEditor}'daki değerleri içeren bir {@link ICollection} alır. |
| [isReadOnly](#isReadOnly--) | {@link DictionaryEditor}'ın yalnızca okunur olup olmadığını gösteren bir değeri alır. |
| [iterator](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | DictionaryEditor'dan belirli bir nesnenin ilk oluşumunu kaldırır. |
| [remove](#remove-java.lang.String-) | Belirtilen anahtara sahip öğeyi {@link DictionaryEditor}'dan kaldırır. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Belirtilen anahtara sahip öğeyi alır veya ayarlar. |
| [size](#size--) | {@link DictionaryEditor}'da bulunan öğe sayısını alır. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | String, name, bool, number gibi basit veri tiplerine erişim için. Diğer tipler için null döndürür. |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException Kaynaklar null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
ICosPdfPrimitive'i sözlüğe ayarla.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Ayarla {@link ICosPdfPrimitive}'i sözlüğe.

### clear {#clear--}
```
public final void clear()
```

Tüm öğeleri {@link DictionaryEditor}'dan kaldırır.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
DictionaryEditor'ın belirli bir değeri içerip içermediğini belirler.

### containsKey {#containsKey-java.lang.String-}
Belirtilen anahtara sahip bir öğenin {@link DictionaryEditor}'da bulunup bulunmadığını belirler.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
DictionaryEditor öğelerini bir diziye kopyalar, belirli bir dizi indeksinden başlayarak.

### get_Item {#get_Item-java.lang.String-}
Belirtilen anahtara sahip öğeyi alır veya ayarlar.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Anahtarların tam koleksiyonu. Düzenlenebilir ve düzenlenemez anahtarları içerir.

**Returns:**
String örnekleri için yinelenebilir.

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Düzenlenebilir anahtarların koleksiyonu.

**Returns:**
String örnekleri için yinelenebilir.

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

{@link DictionaryEditor}'daki değerleri içeren bir {@link ICollection} alır.

**Returns:**
ICosPdfPrimitive örnekleri için yinelenebilir.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

{@link DictionaryEditor}'ın yalnızca okunur olup olmadığını gösteren bir değeri alır.

**Returns:**
{@link DictionaryEditor} yalnızca okunursa true; aksi takdirde false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Returns:**
Koleksiyon üzerinde yineleme yapmak için kullanılabilecek bir enumerator.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
DictionaryEditor'dan belirli bir nesnenin ilk oluşumunu kaldırır.

### remove {#remove-java.lang.String-}
Belirtilen anahtara sahip öğeyi {@link DictionaryEditor}'dan kaldırır.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Belirtilen anahtara sahip öğeyi alır veya ayarlar.

### size {#size--}
```
public final int size()
```

{@link DictionaryEditor}'da bulunan öğe sayısını alır.

**Returns:**
int değer

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
String, name, bool, number gibi basit veri tiplerine erişim için. Diğer tipler için null döndürür.

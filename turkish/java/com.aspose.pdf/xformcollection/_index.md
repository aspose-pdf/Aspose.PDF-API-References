---
title: "XFormCollection"
linktitle: "XFormCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "XFormCollection koleksiyonunu temsil eden sınıf."
type: docs
weight: 5600
url: /tr/java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFormCollection

**All Implemented Interfaces:**
Iterable < XForm >

```
public final class XFormCollection extends Object implements Iterable < XForm >
```

XFormCollection koleksiyonunu temsil eden sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.XForm-) | Koleksiyona yeni XForm ekler. |
| [clear](#clear--) | Koleksiyondaki tüm öğeleri temizler. |
| [contains](#contains-com.aspose.pdf.XForm-) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | XFormCollection'ı koleksiyona kopyalar. |
| [delete](#delete--) | Koleksiyondaki tüm XForm'ları siler. |
| [delete](#delete-int-) | Koleksiyondan XForm sil. |
| [delete](#delete-java.lang.String-) | Koleksiyondaki tüm XForm'ları siler. |
| [freeMemory](#freeMemory--) | Önbellekteki verileri temizler, belleği serbest bırakır vb. |
| [get_Item](#get_Item-int-) | İndexe göre XForm döndürür. |
| [get_Item](#get_Item-java.lang.String-) | İsmiyle XForm döndürür. Belirtilen isimde XForm bulunamazsa istisna fırlatılır. |
| [getFormName](#getFormName-com.aspose.pdf.XForm-) | Bu form koleksiyonundaki formun adını döndürür. |
| [getSyncRoot](#getSyncRoot--) | Eşitleme nesnesi. |
| [hasForm](#hasForm-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır. |
| [isSynchronized](#isSynchronized--) | Nesne eşitlenmiş ise true döndürür. |
| [iterator](#iterator--) | Koleksiyon yineleyicisini döndürür. |
| [remove](#remove-com.aspose.pdf.XForm-) | Belirtilen öğeyi koleksiyondan siler. |
| [size](#size--) | Koleksiyondaki XForm sayısını alır. |

### add {#add-com.aspose.pdf.XForm-}
Koleksiyona yeni XForm ekler.

### clear {#clear--}
```
public void clear()
```

Koleksiyondaki tüm öğeleri temizler.

### contains {#contains-com.aspose.pdf.XForm-}
Koleksiyonun belirli bir değeri içerip içermediğini belirler.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
XFormCollection'ı koleksiyona kopyalar.

### delete {#delete--}
```
public void delete()
```

Koleksiyondaki tüm XForm'ları siler.

### delete {#delete-int-}
```
public void delete(int index)
```

Koleksiyondan XForm sil.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Silinmesi gereken XForm'un indeksi |

### delete {#delete-java.lang.String-}
Koleksiyondaki tüm XForm'ları siler.

### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Önbellekteki verileri temizler, belleği serbest bırakır vb.

### get_Item {#get_Item-int-}
```
public XForm get_Item(int index)
```

İndexe göre XForm döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | XFormCollection'ın indeksi. XForm numaralandırması 1'den başlar. |

**Returns:**
Alınan XForm

### get_Item {#get_Item-java.lang.String-}
İsmiyle XForm döndürür. Belirtilen isimde XForm bulunamazsa istisna fırlatılır.

### getFormName {#getFormName-com.aspose.pdf.XForm-}
Bu form koleksiyonundaki formun adını döndürür.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Eşitleme nesnesi.

**Returns:**
Object

### hasForm {#hasForm-java.lang.String-}


### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Nesne eşitlenmiş ise true döndürür.

**Returns:**
boolean

### iterator {#iterator--}
```
public Iterator < XForm > iterator()
```

Koleksiyon yineleyicisini döndürür.

**Returns:**
Koleksiyon için Enumerator

### remove {#remove-com.aspose.pdf.XForm-}
Belirtilen öğeyi koleksiyondan siler.

### size {#size--}
```
public int size()
```

Koleksiyondaki XForm sayısını alır.

**Returns:**
int değer

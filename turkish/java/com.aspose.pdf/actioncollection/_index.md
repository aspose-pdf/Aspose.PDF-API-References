---
title: "ActionCollection"
linktitle: "ActionCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Eylemlerin koleksiyonu"
type: docs
weight: 40
url: /tr/java/com.aspose.pdf/actioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public final class ActionCollection extends Object implements Iterable < PdfAction >
```

Eylemlerin koleksiyonu

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | Koleksiyona yeni eylem ekler. |
| [clear](#clear--) | Koleksiyonu temizle. |
| [contains](#contains-com.aspose.pdf.PdfAction-) | Henüz desteklenmiyor. Koleksiyonda verilen öğe bulunuyorsa true döndürür. |
| [copyTo](#copyTo-com.aspose.pdf.PdfAction:A-int-) | Eylemler dizisini koleksiyona kopyalar. |
| [delete](#delete--) | Tüm eylemleri sil. |
| [delete](#delete-int-) | Koleksiyondan eylemi dizine göre kaldırır. |
| [get_Item](#get_Item-int-) | Eylemi indeksine göre alır. |
| [getSyncRoot](#getSyncRoot--) | Eşitleme nesnesini alır. |
| [isReadOnly](#isReadOnly--) | Koleksiyon yalnızca okunabilir ise true döndürür. |
| [isSynchronized](#isSynchronized--) | Nesne eşitlenmiş ise true döndürür. |
| [iterator](#iterator--) | / * / * Koleksiyon için dökümcü döndürür. / * / * / * |
| [remove](#remove-com.aspose.pdf.PdfAction-) | * Henüz desteklenmiyor. Koleksiyondan öğeyi kaldırır. |
| [size](#size--) | Koleksiyondaki eylem sayısı. |

### add {#add-com.aspose.pdf.PdfAction-}
Koleksiyona yeni eylem ekler.

### clear {#clear--}
```
public void clear()
```

Koleksiyonu temizle.

### contains {#contains-com.aspose.pdf.PdfAction-}
Henüz desteklenmiyor. Koleksiyonda verilen öğe bulunuyorsa true döndürür.

### copyTo {#copyTo-com.aspose.pdf.PdfAction:A-int-}
Eylemler dizisini koleksiyona kopyalar.

### delete {#delete--}
```
public void delete()
```

Tüm eylemleri sil.

### delete {#delete-int-}
```
public void delete(int index)
```

Koleksiyondan eylemi dizine göre kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Kaldırılacak eylemin indeksi. |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

Eylemi indeksine göre alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Eylemin dizini. |

**Returns:**
Alınan eylem.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Eşitleme nesnesini alır.

**Returns:**
Object değeri

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyon yalnızca okunabilir ise true döndürür.

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Nesne eşitlenmiş ise true döndürür.

**Returns:**
boolean değer

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator()
```

/ * / * Koleksiyon için dökümcü döndürür. / * / * / *

**Returns:**
Koleksiyon yineleyicisi. /

### remove {#remove-com.aspose.pdf.PdfAction-}
* Not supported yet. Removes item from collection.

### size {#size--}
```
public int size()
```

Koleksiyondaki eylem sayısı.

**Returns:**
int değer

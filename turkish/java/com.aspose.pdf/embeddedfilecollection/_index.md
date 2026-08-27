---
title: "EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Gömülü dosyalar koleksiyonunu temsil eden sınıf."
type: docs
weight: 1200
url: /tr/java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class EmbeddedFileCollection extends Object implements Iterable < FileSpecification >
```

Gömülü dosyalar koleksiyonunu temsil eden sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.FileSpecification-) | Gömülü dosya spesifikasyonunu koleksiyona ekler. |
| [add](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | Belirtilen anahtar ile dosyayı gömülü dosyalara ekler. |
| [clear](#clear--) | Belgeden tüm gömülü dosyaları kaldır. |
| [contains](#contains-com.aspose.pdf.FileSpecification-) | Koleksiyonun belirtilen FileSpecification'ı içerip içermediğini belirler. Desteklenmiyor. |
| [copyTo](#copyTo-com.aspose.pdf.FileSpecification:A-int-) | FileSpecification nesnesi dizisini colleciton içine kopyalar. |
| [delete](#delete--) | Belgeden tüm gömülü dosyaları kaldır. |
| [delete](#delete-java.lang.String-) | Belgeden tüm gömülü dosyaları kaldır. |
| [deleteByKey](#deleteByKey-java.lang.String-) | Dosyayı koleksiyondaki anahtarına göre koleksiyondan siler. |
| [findByName](#findByName-java.lang.String-) | Gömülü dosyayı adını kullanarak döndürür. |
| [get_Item](#get_Item-int-) | Gömülü dosyayı indeksine göre alır. |
| [get_Item](#get_Item-java.lang.String-) | Gömülü dosyayı adını kullanarak alır. |
| [getKeys](#getKeys--) | Dosya ekleme anahtarlarının listesini döndürür. |
| [getSyncRoot](#getSyncRoot--) | Bu koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [isEmbeddedFilesExist](#isEmbeddedFilesExist--) | Gömülü Dosyalar yapısının var olup olmadığını kontrol eder. Yapı mevcutsa TRUE, değilse FALSE döndürür. Belge hiç gömülü dosya içermemişse bu yapı oluşturulmamış ve yoktur. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını belirler. Her zaman false döndürür. |
| [isSynchronized](#isSynchronized--) | Bu koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Koleksiyon yineleyicisini döndürür. |
| [iterator](#iterator--) | Koleksiyon yineleyicisini döndürür. |
| [remove](#remove-com.aspose.pdf.FileSpecification-) | Belirtilen FileSpecification'ı koleksiyondan kaldırır. Desteklenmiyor. |
| [size](#size--) | Koleksiyondaki gömülü dosya sayısını alır. |

### add {#add-com.aspose.pdf.FileSpecification-}
Gömülü dosya spesifikasyonunu koleksiyona ekler.

### add {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
Belirtilen anahtar ile dosyayı gömülü dosyalara ekler.

### clear {#clear--}
```
public void clear()
```

Belgeden tüm gömülü dosyaları kaldır.

### contains {#contains-com.aspose.pdf.FileSpecification-}
Koleksiyonun belirtilen FileSpecification'ı içerip içermediğini belirler. Desteklenmiyor.

### copyTo {#copyTo-com.aspose.pdf.FileSpecification:A-int-}
FileSpecification nesnesi dizisini colleciton içine kopyalar.

### delete {#delete--}
```
public void delete()
```

Belgeden tüm gömülü dosyaları kaldır.

### delete {#delete-java.lang.String-}
Belgeden tüm gömülü dosyaları kaldır.

### deleteByKey {#deleteByKey-java.lang.String-}
Dosyayı koleksiyondaki anahtarına göre koleksiyondan siler.

### findByName {#findByName-java.lang.String-}
Gömülü dosyayı adını kullanarak döndürür.

### get_Item {#get_Item-int-}
```
public FileSpecification get_Item(int index)
```

Gömülü dosyayı indeksine göre alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Gömülü dosyanın indeksi. Numaralandırma 1'den başlar. |

**Returns:**
Alınan gömülü dosya özelliği

### get_Item {#get_Item-java.lang.String-}
Gömülü dosyayı adını kullanarak alır.

### getKeys {#getKeys--}
```
public final List < String > getKeys()
```

Dosya ekleme anahtarlarının listesini döndürür.

**Returns:**
String değerlerinin listesi

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Bu koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesneyi alır.

**Returns:**
Eşitleme için nesne

### isEmbeddedFilesExist {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```

Gömülü Dosyalar yapısının var olup olmadığını kontrol eder. Yapı mevcutsa TRUE, değilse FALSE döndürür. Belge hiç gömülü dosya içermemişse bu yapı oluşturulmamış ve yoktur.

**Returns:**
boolean değer

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyonun yalnızca okunur olup olmadığını belirler. Her zaman false döndürür.

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Bu koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< FileSpecification > iterator_Rename_Namesake()
```

Koleksiyon yineleyicisini döndürür.

**Returns:**
Koleksiyon yineleyicisi.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< FileSpecification > iterator()
```

Koleksiyon yineleyicisini döndürür.

**Returns:**
Koleksiyon yineleyicisi.

### remove {#remove-com.aspose.pdf.FileSpecification-}
Belirtilen FileSpecification'ı koleksiyondan kaldırır. Desteklenmiyor.

### size {#size--}
```
public int size()
```

Koleksiyondaki gömülü dosya sayısını alır.

**Returns:**
int değer

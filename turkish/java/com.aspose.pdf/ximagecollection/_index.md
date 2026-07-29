---
title: "XImageCollection"
linktitle: "XImageCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "XImage koleksiyonunu temsil eden sınıf."
type: docs
weight: 5630
url: /tr/java/com.aspose.pdf/ximagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImageCollection

**All Implemented Interfaces:**
Iterable < XImage >

```
public final class XImageCollection extends Object implements Iterable < XImage >
```

XImage koleksiyonunu temsil eden sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.BitmapInfo-) | Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir. |
| [add](#add-com.aspose.pdf.BitmapInfo-com.aspose.pdf.ImageFilterType-) | Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir. |
| [add](#add-java.awt.image.BufferedImage-) | Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir. |
| [add](#add-java.awt.image.BufferedImage-com.aspose.pdf.ImageFilterType-) | Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir. |
| [add](#add-java.io.InputStream-) | Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir. |
| [add](#add-java.io.InputStream-com.aspose.pdf.ImageFilterType-) | Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir. |
| [add](#add-java.io.InputStream-int-) | Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir. |
| [add](#add-com.aspose.pdf.XImage-) | Yeni resmi Image listesine ekler. Bu yöntem, resmi aynı PdfObject'e referans olarak ekler (bu, dosya boyutunun azalmasını sağlar) |
| [add](#add-com.aspose.pdf.engine.XImageAddingParams-java.lang.String:A-) |  |
| [addWithImageFilterType](#addWithImageFilterType-java.io.InputStream-com.aspose.pdf.ImageFilterType-) | Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir. |
| [clear](#clear--) | Koleksiyondaki tüm öğeleri temizler. |
| [contains](#contains-com.aspose.pdf.XImage-) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [copyTo](#copyTo-com.aspose.pdf.XImage:A-int-) | Görüntü dizisini koleksiyona kopyalar. |
| [delete](#delete--) | Koleksiyondan görüntüleri siler. |
| [delete](#delete-int-) | Koleksiyondan indeksi indeks kullanarak kaldırır. |
| [delete](#delete-int-int-) | Koleksiyondan indeksi, action parametresiyle belirtilen eylemi gerçekleştirerek kaldırır. |
| [delete](#delete-java.lang.String-) | Koleksiyondan görüntüleri siler. |
| [delete](#delete-java.lang.String-int-) | Koleksiyondan görüntüleri siler. |
| [get_Item](#get_Item-int-) | Koleksiyondan resmi indeksine göre alır. |
| [get_Item](#get_Item-java.lang.String-) | Koleksiyondan resmi adına göre alır. |
| [getImageName](#getImageName-com.aspose.pdf.XImage-) | Verilen resmin anahtarı olan, images listesinde ismi döndürür. |
| [getNames](#getNames--) | Resim adlarının dizisini alır. |
| [getSyncRoot](#getSyncRoot--) | Eşitleme nesnesini döndürür. |
| [hasImage](#hasImage-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır. |
| [isSynchronized](#isSynchronized--) | Nesne eşitlenmiş ise true döndürür. |
| [iterator](#iterator--) | Koleksiyon yineleyicisini döndürür. |
| [remove](#remove-com.aspose.pdf.XImage-) | Henüz desteklenmiyor, istisna fırlatır. Her zaman NotImplementedException fırlatır. |
| [replace](#replace-int-java.io.InputStream-) | Koleksiyondaki görüntüyü başka bir görüntüyle değiştir. |
| [replace](#replace-int-java.io.InputStream-int-) | Koleksiyondaki görüntüyü başka bir görüntüyle değiştir. |
| [replace](#replace-int-java.io.InputStream-int-boolean-) | Koleksiyondaki görüntüyü başka bir görüntüyle değiştir. |
| [saveJpxWithQuality](#saveJpxWithQuality-com.aspose.ms.System.Drawing.Image-) |  |
| [size](#size--) | Koleksiyondaki görüntü sayısı. |

### add {#add-com.aspose.pdf.BitmapInfo-}
Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir.

### add {#add-com.aspose.pdf.BitmapInfo-com.aspose.pdf.ImageFilterType-}
Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir.

### add {#add-java.awt.image.BufferedImage-}
Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir.

### add {#add-java.awt.image.BufferedImage-com.aspose.pdf.ImageFilterType-}
Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir.

### add {#add-java.io.InputStream-}
Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir.

### add {#add-java.io.InputStream-com.aspose.pdf.ImageFilterType-}
Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir.

### add {#add-java.io.InputStream-int-}
Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir.

### add {#add-com.aspose.pdf.XImage-}
Yeni resmi Image listesine ekler. Bu yöntem, resmi aynı PdfObject'e referans olarak ekler (bu, dosya boyutunun azalmasını sağlar)

### add {#add-com.aspose.pdf.engine.XImageAddingParams-java.lang.String:A-}


### addWithImageFilterType {#addWithImageFilterType-java.io.InputStream-com.aspose.pdf.ImageFilterType-}
Varlığı koleksiyonun sonuna ekler, böylece varlık son indeksle erişilebilir.

### clear {#clear--}
```
public void clear()
```

Koleksiyondaki tüm öğeleri temizler.

### contains {#contains-com.aspose.pdf.XImage-}
Koleksiyonun belirli bir değeri içerip içermediğini belirler.

### copyTo {#copyTo-com.aspose.pdf.XImage:A-int-}
Görüntü dizisini koleksiyona kopyalar.

### delete {#delete--}
```
public void delete()
```

Koleksiyondan görüntüleri siler.

### delete {#delete-int-}
```
public void delete(int index)
```

Koleksiyondan indeksi indeks kullanarak kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Resim indeksi. |

### delete {#delete-int-int-}
```
public final void delete(int index, int action)
```

Koleksiyondan indeksi, action parametresiyle belirtilen eylemi gerçekleştirerek kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Kaldırılacak resmin indeksi. |
| action |  | ImageDeleteAction öğesi. Görüntü silindikten sonra gerçekleştirilen Action. |

### delete {#delete-java.lang.String-}
Koleksiyondan görüntüleri siler.

### delete {#delete-java.lang.String-int-}
Koleksiyondan görüntüleri siler.

### get_Item {#get_Item-int-}
```
public XImage get_Item(int index)
```

Koleksiyondan resmi indeksine göre alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Resim indeksi |

**Returns:**
Alınan görüntü.

### get_Item {#get_Item-java.lang.String-}
Koleksiyondan resmi adına göre alır.

### getImageName {#getImageName-com.aspose.pdf.XImage-}
Verilen resmin anahtarı olan, images listesinde ismi döndürür.

### getNames {#getNames--}
```
public String [] getNames()
```

Resim adlarının dizisini alır.

**Returns:**
String[] dizi

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Eşitleme nesnesini döndürür.

**Returns:**
Nesne öğesi

### hasImage {#hasImage-java.lang.String-}


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
boolean değer

### iterator {#iterator--}
```
public Iterator < XImage > iterator()
```

Koleksiyon yineleyicisini döndürür.

**Returns:**
Koleksiyonun Enumerator'ı

### remove {#remove-com.aspose.pdf.XImage-}
Henüz desteklenmiyor, istisna fırlatır. Her zaman NotImplementedException fırlatır.

### replace {#replace-int-java.io.InputStream-}
Koleksiyondaki görüntüyü başka bir görüntüyle değiştir.

### replace {#replace-int-java.io.InputStream-int-}
Koleksiyondaki görüntüyü başka bir görüntüyle değiştir.

### replace {#replace-int-java.io.InputStream-int-boolean-}
Koleksiyondaki görüntüyü başka bir görüntüyle değiştir.

### saveJpxWithQuality {#saveJpxWithQuality-com.aspose.ms.System.Drawing.Image-}


### size {#size--}
```
public int size()
```

Koleksiyondaki görüntü sayısı.

**Returns:**
int değer

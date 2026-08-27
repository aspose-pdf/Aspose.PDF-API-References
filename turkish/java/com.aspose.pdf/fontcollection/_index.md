---
title: "FontCollection"
linktitle: "FontCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Font koleksiyonunu temsil eder. </p> <hr> <pre> Örnek, sayfada bildirilen tüm yazı tiplerinin gömülü olarak nasıl yapılacağını gösterir. // Open document Document doc = new.</pre>"
type: docs
weight: 1670
url: /tr/java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontCollection

**All Implemented Interfaces:**
Iterable < Font >

```
public final class FontCollection extends Object implements Iterable < Font >
```

<p> Font koleksiyonunu temsil eder. </p> <hr> <pre> Örnek, sayfada bildirilen tüm yazı tiplerinin gömülü olarak nasıl yapılacağını gösterir. // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // sayfa kaynaklarında bildirilen tüm yazı tiplerinin gömülü olduğundan emin olun // form kaynaklarında bildirilen yazı tiplerinin sayfa kaynaklarından erişilemediğini unutmayın for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\Tests\\input.pdf"); </pre> <hr> <p> Font koleksiyonları {@code FontCollection} sınıfı tarafından temsil edilir ve çeşitli senaryolarda kullanılır. Örneğin, {@code Resources.Fonts} özelliğine sahip kaynaklarda. </p>

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.Font-) | Yazı tipini koleksiyona ekler. |
| [add](#add-com.aspose.pdf.Font-java.lang.String:A-) | Yeni bir yazı tipini yazı tipi kaynaklarına ekler ve kaynak için otomatik olarak atanmış adı döndürür. |
| [add](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | Yeni bir yazı tipini yazı tipi koleksiyonuna ekle. |
| [add](#add-java.lang.String-java.lang.String-) | Belirtilen temel yazı tipi adıyla yeni bir yazı tipi girdisini yazı tipi kaynaklarına ekler. |
| [clear_Rename_Namesake](#clear_Rename_Namesake--) | / * / * Yazı tipini koleksiyona ekler. / * / * |
| [contains](#contains-com.aspose.pdf.Font-) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [contains](#contains-java.lang.String-) | Yazı tipinin koleksiyonda mevcut olup olmadığını kontrol eder. |
| [copyTo](#copyTo-com.aspose.pdf.Font:A-int-) | Tüm koleksiyonu, hedef dizinin belirtilen indeksinden başlayarak uyumlu tek boyutlu bir diziye kopyalar. |
| [delete](#delete-java.lang.String-) | Belirtilen kaynak adıyla Yazı tipini siler |
| [get_Item](#get_Item-int-) | Belirtilen indeksteki yazı tipi öğesini alır. |
| [get_Item](#get_Item-java.lang.String-) | Yazı tipini koleksiyondan yazı tipi adıyla alır. Yazı tipi bulunamazsa istisna fırlatılır. |
| [getFontsDictionary](#getFontsDictionary--) | IPdfDictionary nesnesini al |
| [getHash](#getHash--) |  |
| [getSyncRoot](#getSyncRoot--) | Koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesneyi alır. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır |
| [isSynchronized](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Tüm koleksiyon için bir yineleyici döndürür. |
| [iterator](#iterator--) | Tüm koleksiyon için bir yineleyici döndürür. |
| [remove](#remove-com.aspose.pdf.Font-) | Belirtilen öğeyi koleksiyondan siler. |
| [size](#size--) | Koleksiyonda gerçekte bulunan {@code Font} nesne öğelerinin sayısını alır. |

### add {#add-com.aspose.pdf.Font-}
Yazı tipini koleksiyona ekler.

### add {#add-com.aspose.pdf.Font-java.lang.String:A-}
Yeni bir yazı tipini yazı tipi kaynaklarına ekler ve kaynak için otomatik olarak atanmış adı döndürür.

### add {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
Yeni bir yazı tipini yazı tipi koleksiyonuna ekle.

### add {#add-java.lang.String-java.lang.String-}
Belirtilen temel yazı tipi adıyla yeni bir yazı tipi girdisini yazı tipi kaynaklarına ekler.

### clear_Rename_Namesake {#clear_Rename_Namesake--}
```
public void clear_Rename_Namesake()
```

/ * / * Yazı tipini koleksiyona ekler. / * / *

### contains {#contains-com.aspose.pdf.Font-}
Koleksiyonun belirli bir değeri içerip içermediğini belirler.

### contains {#contains-java.lang.String-}
Yazı tipinin koleksiyonda mevcut olup olmadığını kontrol eder.

### copyTo {#copyTo-com.aspose.pdf.Font:A-int-}
Tüm koleksiyonu, hedef dizinin belirtilen indeksinden başlayarak uyumlu tek boyutlu bir diziye kopyalar.

### delete {#delete-java.lang.String-}
Belirtilen kaynak adıyla Yazı tipini siler

### get_Item {#get_Item-int-}
```
public Font get_Item(int index)
```

Belirtilen indeksteki yazı tipi öğesini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Koleksiyon içindeki indeks. |

**Returns:**
Yazı tipi nesnesi.

### get_Item {#get_Item-java.lang.String-}
Yazı tipini koleksiyondan yazı tipi adıyla alır. Yazı tipi bulunamazsa istisna fırlatılır.

### getFontsDictionary {#getFontsDictionary--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getFontsDictionary()
```

IPdfDictionary nesnesini al

**Returns:**
IPdfDictionary nesnesi

### getHash {#getHash--}
```
public com.aspose.pdf.engine.collections.HashDictionary< String , Font > getHash()
```



### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Koleksiyona erişimi senkronize etmek için kullanılabilecek bir nesneyi alır.

**Returns:**
Eşitleme için nesne

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Tüm koleksiyon için bir yineleyici döndürür.

**Returns:**
Yineleyici nesnesi.

### iterator {#iterator--}
```
public Iterator < Font > iterator()
```

Tüm koleksiyon için bir yineleyici döndürür.

**Returns:**
Yineleyici nesnesi.

### remove {#remove-com.aspose.pdf.Font-}
Belirtilen öğeyi koleksiyondan siler.

### size {#size--}
```
public int size()
```

Koleksiyonda gerçekte bulunan {@code Font} nesne öğelerinin sayısını alır.

**Returns:**
int değer

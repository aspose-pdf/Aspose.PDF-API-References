---
title: "PageCollection"
linktitle: "PageCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belge sayfalarının koleksiyonu."
type: docs
weight: 3340
url: /tr/java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageCollection

**All Implemented Interfaces:**
Iterable < Page >

```
public final class PageCollection extends Object implements Iterable < Page >
```

PDF belge sayfalarının koleksiyonu.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | {@code AnnotationSelector} ziyaretçi nesnesini kabul eder ve ek açıklamalarla çalışmak için işlevsellik sağlar. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Görüntü yerleştirme nesneleriyle çalışmak için işlevsellik sağlayan {@code ImagePlacementAbsorber} ziyaretçi nesnesini kabul eder. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Metin nesneleriyle çalışmak için işlevsellik sağlayan {@code TextAbsorber} ziyaretçi nesnesini kabul eder. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Metin nesneleriyle çalışmak için işlevsellik sağlayan {@code TextFragmentAbsorber} ziyaretçi nesnesini kabul eder. |
| [add_Rename_Namesake](#add_Rename_Namesake-com.aspose.pdf.Page-) | Koleksiyona sayfa ekler. |
| [add](#add--) | Boş bir sayfa ekler. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık görülen sayfanın boyutu seçilir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılır. |
| [add](#add-java.lang.Iterable-) | Boş bir sayfa ekler. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık görülen sayfanın boyutu seçilir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılır. |
| [add](#add-java.util.List-) | Boş bir sayfa ekler. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık görülen sayfanın boyutu seçilir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılır. |
| [add](#add-com.aspose.pdf.Page-) | Boş bir sayfa ekler. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık görülen sayfanın boyutu seçilir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılır. |
| [add](#add-com.aspose.pdf.Page:A-) | Boş bir sayfa ekler. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık görülen sayfanın boyutu seçilir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılır. |
| [beginUpdate](#beginUpdate--) | Grup değişiklikleri başladığında günceller. |
| [clear](#clear--) | Sayfa koleksiyonunu temizler. |
| [contains](#contains-com.aspose.pdf.Page-) | Bu örneğin nesneyi içerip içermediğini belirler. |
| [copyTo](#copyTo-com.aspose.pdf.Page:A-int-) | Sayfaları belgeye kopyalar. |
| [delete](#delete--) | Koleksiyondan tüm sayfaları siler. |
| [delete](#delete-int-) | Belirtilen sayfayı sil. |
| [delete](#delete-java.lang.Integer:A-) | Koleksiyondan tüm sayfaları siler. |
| [endUpdate](#endUpdate--) | Grup değişiklikleri tamamlandığında günceller. |
| [findByPdfObject](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten](#flatten--) | Sayfalarda bulunan tüm alanları kaldırır ve yerine değerlerini yerleştirir. |
| [freeMemory](#freeMemory--) | Önbelleğe alınmış verileri temizler |
| [get_Item](#get_Item-int-) | İndexe göre sayfayı alır. |
| [getSyncRoot](#getSyncRoot--) | Koleksiyonun senkronizasyon nesnesini alır. |
| [getUnrestricted](#getUnrestricted-int-) | İndeksine göre sayfayı döndürür. {@code Page} |
| [indexOf](#indexOf-com.aspose.pdf.Page-) | <p> Belirtilen sayfanın indeksini döndürür. </p> |
| [insert](#insert-int-) | Belirtilen konuma koleksiyona boş bir sayfa ekler. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık görülen sayfanın boyutu seçilir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılır. |
| [insert](#insert-int-java.lang.Iterable-) | Koleksiyondan sayfaları belgeye ekler. |
| [insert](#insert-int-java.util.List-) | Koleksiyondan sayfaları belgeye ekler. |
| [insert](#insert-int-com.aspose.pdf.Page-) | Sayfayı belirtilen yere sayfa koleksiyonuna ekler. |
| [insert](#insert-int-com.aspose.pdf.Page:A-) | Dizinin sayfalarını belgeye ekler. |
| [isEmpty](#isEmpty--) | Koleksiyon boşsa TRUE döndürür. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olduğunu gösteren değeri alır. Her zaman false döndürür. |
| [isSynchronized](#isSynchronized--) | Nesne senkronize ise true döndürür. |
| [iterator](#iterator--) | Sayfaların enumerator'ını döndürür. |
| [remove](#remove-com.aspose.pdf.Page-) | Belirtilen öğeyi kaldırır, istisna fırlatır. |
| [size](#size--) | Belgedeki sayfaların sayısını alır. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
{@code AnnotationSelector} ziyaretçi nesnesini kabul eder ve ek açıklamalarla çalışmak için işlevsellik sağlar.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Görüntü yerleştirme nesneleriyle çalışmak için işlevsellik sağlayan {@code ImagePlacementAbsorber} ziyaretçi nesnesini kabul eder.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Metin nesneleriyle çalışmak için işlevsellik sağlayan {@code TextAbsorber} ziyaretçi nesnesini kabul eder.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Metin nesneleriyle çalışmak için işlevsellik sağlayan {@code TextFragmentAbsorber} ziyaretçi nesnesini kabul eder.

### add_Rename_Namesake {#add_Rename_Namesake-com.aspose.pdf.Page-}
Koleksiyona sayfa ekler.

### add {#add--}
```
public Page add()
```

Boş bir sayfa ekler. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık görülen sayfanın boyutu seçilir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılır.

**Returns:**
Sayfa eklendi.

### add {#add-java.lang.Iterable-}
Boş bir sayfa ekler. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık görülen sayfanın boyutu seçilir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılır.

**Returns:**
Sayfa eklendi.

### add {#add-java.util.List-}
Boş bir sayfa ekler. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık görülen sayfanın boyutu seçilir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılır.

**Returns:**
Sayfa eklendi.

### add {#add-com.aspose.pdf.Page-}
Boş bir sayfa ekler. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık görülen sayfanın boyutu seçilir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılır.

**Returns:**
Sayfa eklendi.

### add {#add-com.aspose.pdf.Page:A-}
Boş bir sayfa ekler. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık görülen sayfanın boyutu seçilir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılır.

**Returns:**
Sayfa eklendi.

### beginUpdate {#beginUpdate--}
```
public final void beginUpdate()
```

Grup değişiklikleri başladığında günceller.

### clear {#clear--}
```
public void clear()
```

Sayfa koleksiyonunu temizler.

### contains {#contains-com.aspose.pdf.Page-}
Bu örneğin nesneyi içerip içermediğini belirler.

### copyTo {#copyTo-com.aspose.pdf.Page:A-int-}
Sayfaları belgeye kopyalar.

### delete {#delete--}
```
public void delete()
```

Koleksiyondan tüm sayfaları siler.

### delete {#delete-int-}
```
public void delete(int index)
```

Belirtilen sayfayı sil.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Silinecek sayfanın numarası. Sayfa numaraları 1'den başlar. |

### delete {#delete-java.lang.Integer:A-}
Koleksiyondan tüm sayfaları siler.

### endUpdate {#endUpdate--}
```
public final void endUpdate()
```

Grup değişiklikleri tamamlandığında günceller.

### findByPdfObject {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}


### flatten {#flatten--}
```
public void flatten()
```

Sayfalarda bulunan tüm alanları kaldırır ve yerine değerlerini yerleştirir.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Önbelleğe alınmış verileri temizler

### get_Item {#get_Item-int-}
```
public Page get_Item(int index)
```

İndexe göre sayfayı alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Sayfa indeksi. |

**Returns:**
Alınan sayfa.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Koleksiyonun senkronizasyon nesnesini alır.

**Returns:**
Eşitleme için nesne

### getUnrestricted {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```

İndeksine göre sayfayı döndürür. {@code Page}

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Talep edilen sayfanın indeksi. Sayfalar 1'den numaralandırılır. |

**Returns:**
Talep edilen sayfa

### indexOf {#indexOf-com.aspose.pdf.Page-}
<p> Belirtilen sayfanın indeksini döndürür. </p>

### insert {#insert-int-}
```
public Page insert(int pageNumber)
```

Belirtilen konuma koleksiyona boş bir sayfa ekler. Belge zaten farklı boyutlarda sayfalar içeriyorsa, en sık görülen sayfanın boyutu seçilir. Sadece iki farklı sayfa varsa, ilk sayfanın boyutu kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Yeni sayfanın konumu. |

**Returns:**
Eklenen sayfa.

### insert {#insert-int-java.lang.Iterable-}
Koleksiyondan sayfaları belgeye ekler.

### insert {#insert-int-java.util.List-}
Koleksiyondan sayfaları belgeye ekler.

### insert {#insert-int-com.aspose.pdf.Page-}
Sayfayı belirtilen yere sayfa koleksiyonuna ekler.

### insert {#insert-int-com.aspose.pdf.Page:A-}
Dizinin sayfalarını belgeye ekler.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Koleksiyon boşsa TRUE döndürür.

**Returns:**
boolean değer

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyonun yalnızca okunur olduğunu gösteren değeri alır. Her zaman false döndürür.

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Nesne senkronize ise true döndürür.

**Returns:**
boolean değer

### iterator {#iterator--}
```
public Iterator < Page > iterator()
```

Sayfaların enumerator'ını döndürür.

**Returns:**
Sayfaların enumeratörü

### remove {#remove-com.aspose.pdf.Page-}
Belirtilen öğeyi kaldırır, istisna fırlatır.

### size {#size--}
```
public int size()
```

Belgedeki sayfaların sayısını alır.

**Returns:**
int değer

---
title: "OutlineItemCollection"
linktitle: "OutlineItemCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesinin taslak hiyerarşisindeki taslak girişini temsil eder."
type: docs
weight: 3270
url: /tr/java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineItemCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineItemCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineItemCollection extends Outlines
```

PDF belgesinin taslak hiyerarşisindeki taslak girişini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | Bu sınıfın yeni bir örneğini, dahili motor taslak girişi nesnesi kullanarak başlatır. |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | Kök hiyerarşi nesnesi kullanarak taslak öğesi örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Koleksiyona anahat öğesi ekler. |
| [clear](#clear--) | Koleksiyondaki tüm öğeleri temizler. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Henüz desteklenmiyor. Her zaman NotImplementedException fırlatır. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Taslak girişlerini bir System.Array'e kopyalar, belirli bir System.Array dizininden başlayarak. |
| [delete](#delete--) | Bu taslak öğesini belge taslak hiyerarşisinden siler. |
| [delete](#delete-java.lang.String-) | Bu taslak öğesini belge taslak hiyerarşisinden siler. |
| [get_Item](#get_Item-int-) | Koleksiyondan indeksi kullanarak taslak öğesini alır. |
| [getAction](#getAction--) | Bu taslak öğesi için eylemi alır. |
| [getBold](#getBold--) | Bu taslak öğesinin başlık metni için kalın bayrağını alır |
| [getColor](#getColor--) | Bu taslak öğesinin başlık metni için rengi alır. |
| [getDestination](#getDestination--) | Bu taslak öğesi için hedefi alır. |
| [getEngineDict](#getEngineDict--) | Yalnızca dahili |
| [getEngineObj](#getEngineObj--) | Yalnızca dahili |
| [getFirst](#getFirst--) | Taslak hiyerarşisindeki ilk üst düzey öğeyi temsil eden taslak öğesini alır. |
| [getItalic](#getItalic--) | Bu taslak öğesinin başlık metni için italik bayrağını alır |
| [getLast](#getLast--) | Taslak hiyerarşisindeki son üst düzey öğeyi temsil eden taslak öğesini alır. |
| [getLevel](#getLevel--) | Taslak öğesinin hiyerarşi seviyesini alır. |
| [getNext](#getNext--) | Taslak hiyerarşisinde bu öğeye göre bir sonraki öğeyi temsil eden taslak öğesini alır. |
| [getOpen](#getOpen--) | Taslak öğesi için açık durumunu (true/false) al. |
| [getParent](#getParent--) | Taslak hiyerarşisindeki bu taslak öğesinin üst nesnesini alır. |
| [getPrev](#getPrev--) | Taslak hiyerarşisinde bu öğeye göre önceki öğeyi temsil eden taslak öğesini alır. |
| [getSyncRoot](#getSyncRoot--) | Bu koleksiyona erişimi senkronize etmek için kullanılabilecek nesneyi alır. |
| [getTitle](#getTitle--) | Bu taslak öğesinin başlığını alır. |
| [getVisibleCount](#getVisibleCount--) | Belge taslak hiyerarşisindeki tüm seviyelerdeki taslak öğelerinin toplam sayısını alır. |
| [hasNext](#hasNext--) | Bu taslak hiyerarşisinde bu öğeye göreceli olarak bir sonraki öğeyi temsil eden taslak öğesini kontrol edin. |
| [insert](#insert-int-com.aspose.pdf.OutlineItemCollection-) | Taslak öğesini belirtilen konuma koleksiyona ekler. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren bir değeri alır. |
| [isSynchronized](#isSynchronized--) | Bu koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren değeri alır. |
| [iterator](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [next](#next--) |  |
| [remove](#remove-int-) | İndeks ile öğeyi kaldır. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Henüz desteklenmiyor. Her zaman NotImplementedException fırlatır. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Bu taslak öğesi için eylemi ayarlar. |
| [setBold](#setBold-boolean-) | Bu taslak öğesinin başlık metni için kalın bayrağını ayarlar |
| [setColor](#setColor-java.awt.Color-) | Bu taslak öğesinin başlık metni için rengi ayarlar. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Bu taslak öğesi için hedefi ayarlar. |
| [setItalic](#setItalic-boolean-) | Bu taslak öğesinin başlık metni için italik bayrağını ayarlar |
| [setOpen](#setOpen-boolean-) | Taslak öğesi için açık durumunu (true/false) ayarlar. |
| [setTitle](#setTitle-java.lang.String-) | Bu taslak öğesi için başlığı ayarlar. |
| [size](#size--) | Koleksiyon öğelerinin sayısı. Lütfen VisibleCount ile karıştırmayın: VisibleCount, tüm seviyelerdeki görünür taslak öğelerinin sayısını alır. |

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
Bu sınıfın yeni bir örneğini, dahili motor taslak girişi nesnesi kullanarak başlatır.

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
Kök hiyerarşi nesnesi kullanarak taslak öğesi örneğini başlatır.

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Koleksiyona anahat öğesi ekler.

### clear {#clear--}
```
public void clear()
```

Koleksiyondaki tüm öğeleri temizler.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Henüz desteklenmiyor. Her zaman NotImplementedException fırlatır.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Taslak girişlerini bir System.Array'e kopyalar, belirli bir System.Array dizininden başlayarak.

### delete {#delete--}
```
public void delete()
```

Bu taslak öğesini belge taslak hiyerarşisinden siler.

### delete {#delete-java.lang.String-}
Bu taslak öğesini belge taslak hiyerarşisinden siler.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Koleksiyondan indeksi kullanarak taslak öğesini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Koleksiyon içindeki indeks. |

**Returns:**
OutlineItemCollection nesnesi.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Bu taslak öğesi için eylemi alır.

**Returns:**
PdfAction değeri

### getBold {#getBold--}
```
public boolean getBold()
```

Bu taslak öğesinin başlık metni için kalın bayrağını alır

**Returns:**
boolean değer

### getColor {#getColor--}
```
public Color getColor()
```

Bu taslak öğesinin başlık metni için rengi alır.

**Returns:**
Renk değeri

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Bu taslak öğesi için hedefi alır.

**Returns:**
IAppointment değeri

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Yalnızca dahili

**Returns:**
IPdfDictionary nesnesi

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Yalnızca dahili

**Returns:**
IPdfObject nesnesi

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Taslak hiyerarşisindeki ilk üst düzey öğeyi temsil eden taslak öğesini alır.

**Returns:**
OutlineItemCollection değeri

### getItalic {#getItalic--}
```
public boolean getItalic()
```

Bu taslak öğesinin başlık metni için italik bayrağını alır

**Returns:**
boolean değer

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Taslak hiyerarşisindeki son üst düzey öğeyi temsil eden taslak öğesini alır.

**Returns:**
OutlineItemCollection değeri

### getLevel {#getLevel--}
```
public int getLevel()
```

Taslak öğesinin hiyerarşi seviyesini alır.

**Returns:**
int değer

### getNext {#getNext--}
```
public OutlineItemCollection getNext()
```

Taslak hiyerarşisinde bu öğeye göre bir sonraki öğeyi temsil eden taslak öğesini alır.

**Returns:**
OutlineItemCollection değeri

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Taslak öğesi için açık durumunu (true/false) al.

**Returns:**
boolean değer

### getParent {#getParent--}
```
public Outlines getParent()
```

Taslak hiyerarşisindeki bu taslak öğesinin üst nesnesini alır.

**Returns:**
Object değeri

### getPrev {#getPrev--}
```
public OutlineItemCollection getPrev()
```

Taslak hiyerarşisinde bu öğeye göre önceki öğeyi temsil eden taslak öğesini alır.

**Returns:**
OutlineItemCollection değeri

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Bu koleksiyona erişimi senkronize etmek için kullanılabilecek nesneyi alır.

**Returns:**
Object değeri

### getTitle {#getTitle--}
```
public String getTitle()
```

Bu taslak öğesinin başlığını alır.

**Returns:**
String değeri

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Belge taslak hiyerarşisindeki tüm seviyelerdeki taslak öğelerinin toplam sayısını alır.

**Returns:**
int değer

### hasNext {#hasNext--}
```
public final boolean hasNext()
```

Bu taslak hiyerarşisinde bu öğeye göreceli olarak bir sonraki öğeyi temsil eden taslak öğesini kontrol edin.

**Returns:**
boolean değer

### insert {#insert-int-com.aspose.pdf.OutlineItemCollection-}
Taslak öğesini belirtilen konuma koleksiyona ekler.

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

Bu koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren değeri alır.

**Returns:**
boolean değer

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Returns:**
Koleksiyon içinde yineleme yapmak için kullanılabilecek bir System.Collections.IEnumerator nesnesi.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

İndeks ile öğeyi kaldır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Silinecek öğenin indeksi. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Henüz desteklenmiyor. Her zaman NotImplementedException fırlatır.

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Bu taslak öğesi için eylemi ayarlar.

### setBold {#setBold-boolean-}
```
public void setBold(boolean value)
```

Bu taslak öğesinin başlık metni için kalın bayrağını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setColor {#setColor-java.awt.Color-}
Bu taslak öğesinin başlık metni için rengi ayarlar.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Bu taslak öğesi için hedefi ayarlar.

### setItalic {#setItalic-boolean-}
```
public void setItalic(boolean value)
```

Bu taslak öğesinin başlık metni için italik bayrağını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Taslak öğesi için açık durumunu (true/false) ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setTitle {#setTitle-java.lang.String-}
Bu taslak öğesi için başlığı ayarlar.

### size {#size--}
```
public int size()
```

Koleksiyon öğelerinin sayısı. Lütfen VisibleCount ile karıştırmayın: VisibleCount, tüm seviyelerdeki görünür taslak öğelerinin sayısını alır.

**Returns:**
int değer

---
title: "Alan"
linktitle: "Alan"
second_title: "Aspose.PDF for Java API Referansı"
description: "Acro form alanları için temel sınıf."
type: docs
weight: 1380
url: /tr/java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class Field extends WidgetAnnotation implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, Cloneable
```

Acro form alanları için temel sınıf.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [_FileSelect](#Z:Z_FileSelect) | _FileSelect |
| [_Password](#Z:Z_Password) | _Password |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Field](#Field-com.aspose.pdf.IDocument-) | Generator içinde kullanılmak üzere alan oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear](#clear--) |  |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo_Rename_Namesake](#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-) | Bu alanın alt alanlarını belirtilen indeksten başlayarak diziye kopyalar. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Bu alanın alt alanlarını belirtilen indeksten başlayarak diziye kopyalar. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) |  |
| [executeFieldJavaScript](#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-) | Alan için belirtilen bir JavaScript eylemini yürütür. |
| [flatten](#flatten--) | Bu alanı kaldırır ve değerini doğrudan sayfaya yerleştirir. |
| [get_Item](#get_Item-int-) | Bu alanda bulunan alt alanı indeksine göre alır. |
| [get_Item](#get_Item-java.lang.String-) | Bu alanda bulunan alt alanı alt alanın adına göre alır. |
| [getAlternateName](#getAlternateName--) | Alanının alternatif adını alır (Alanının gerçek adı yerine, kullanıcı arayüzünde alanın tanımlandığı her yerde kullanılacak alternatif bir alan adıdır). Alternatif ad, Adobe Acrobat'ta alan ipucu olarak kullanılır. |
| [getAnnotationIndex](#getAnnotationIndex--) | Bu anotation'ın sayfadaki indeksini alır. |
| [getMappingName](#getMappingName--) | Belgeden etkileşimli form alanı verileri dışa aktarılırken kullanılacak alanın eşleme adını alır. |
| [getMaxFontSize](#getMaxFontSize--) | Alan içeriği için kullanılabilecek azami yazı tipi boyutu. -1, boyutu kontrol etmemek için. |
| [getMinFontSize](#getMinFontSize--) | Alan içeriği için kullanılabilecek asgari yazı tipi boyutu. -1, boyutu kontrol etmemek için. |
| [getPageIndex](#getPageIndex--) | Bu alanı içeren sayfanın indeksini alır. |
| [getPartialName](#getPartialName--) | Alanının kısmi adını alır. |
| [getRect](#getRect--) | Alan dikdörtgenini alır. |
| [getSyncRoot](#getSyncRoot--) | Eşitleme nesnesi. |
| [getTabOrder](#getTabOrder--) | Alanının sekme sırasını alır veya ayarlar. |
| [getValue](#getValue--) | Alanın değerini alır. |
| [isFitIntoRectangle](#isFitIntoRectangle--) | Doğru ise, yazı tipi boyutu belirtilen dikdörtgene sığacak şekilde küçültülür. |
| [isGroup](#isGroup--) | Bu alanın uç olmayan alan (yani alan grubu) olup olmadığını gösteren boolean değeri alır. |
| [isReadOnly](#isReadOnly--) |  |
| [isSharedField](#isSharedField--) | Generator desteği için özellik. Alan başlık ya da alt bilgiye eklendiğinde kullanılır. Doğru ise, bu alan bir kez oluşturulur ve görünümü belgenin tüm sayfalarında görünür. Yanlış ise, her belge sayfası için ayrı bir alan oluşturulur. |
| [isSynchronized](#isSynchronized--) | Sözlük eşitlenmişse doğru döndürür. |
| [iterator](#iterator--) | İçerilen alanların dökümcüsünü döndürür. |
| [recalculate](#recalculate--) | Formdaki tüm hesaplanmış alanları yeniden hesaplar. |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setAlternateName](#setAlternateName-java.lang.String-) | Alan için alternatif adı ayarlar (Alan adı, kullanıcı arayüzünde alanın tanımlandığı her yerde gerçek alan adının yerine kullanılacak alternatif bir alandır). Alternatif ad, Adobe Acrobat'ta alan ipucu olarak kullanılır. |
| [setAnnotationIndex](#setAnnotationIndex-int-) | Bu açıklamanın sayfadaki indeksini ayarlar. |
| [setFitIntoRectangle](#setFitIntoRectangle-boolean-) | Doğru ise, yazı tipi boyutu belirtilen dikdörtgene sığacak şekilde küçültülür. |
| [setMappingName](#setMappingName-java.lang.String-) | Belgeden etkileşimli form alanı verileri dışa aktarılırken kullanılacak alanın eşleme adını ayarlar. |
| [setMaxFontSize](#setMaxFontSize-double-) | Alan içeriği için kullanılabilecek azami yazı tipi boyutu. -1, boyutu kontrol etmemek için. |
| [setMinFontSize](#setMinFontSize-double-) | Alan içeriği için kullanılabilecek asgari yazı tipi boyutu. -1, boyutu kontrol etmemek için. |
| [setPartialName](#setPartialName-java.lang.String-) | Alanının kısmi adını ayarlar. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Alan konumunu ayarlar. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Alan dikdörtgenini ayarlar. |
| [setSharedField](#setSharedField-boolean-) | Generator desteği için özellik. Alan başlık ya da alt bilgiye eklendiğinde kullanılır. Doğru ise, bu alan bir kez oluşturulur ve görünümü belgenin tüm sayfalarında görünür. Yanlış ise, her belge sayfası için ayrı bir alan oluşturulur. |
| [setTabOrder](#setTabOrder-int-) | Alanının sekme sırasını alır veya ayarlar. |
| [setValue](#setValue-java.lang.String-) | Değeri ayarlar. |
| [size](#size--) | Bu alandaki alt alanların sayısını alır. (Örneğin radyo düğmesi alanındaki öğe sayısı). |
| [updateAppearances](#updateAppearances--) | Görünüm değerini günceller. |

### _FileSelect {#Z:Z_FileSelect}
```
public static final int _FileSelect
```

_FileSelect

### _Password {#Z:Z_Password}
```
public static final int _Password
```

_Password

### Field {#Field-com.aspose.pdf.IDocument-}
Generator içinde kullanılmak üzere alan oluşturur.

### add {#add-com.aspose.pdf.WidgetAnnotation-}


### clear {#clear--}
```
public void clear()
```



### contains {#contains-com.aspose.pdf.WidgetAnnotation-}


### copyTo_Rename_Namesake {#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-}
Bu alanın alt alanlarını belirtilen indeksten başlayarak diziye kopyalar.

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Bu alanın alt alanlarını belirtilen indeksten başlayarak diziye kopyalar.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}


### executeFieldJavaScript {#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-}
Alan için belirtilen bir JavaScript eylemini yürütür.

### flatten {#flatten--}
```
public void flatten()
```

Bu alanı kaldırır ve değerini doğrudan sayfaya yerleştirir.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Bu alanda bulunan alt alanı indeksine göre alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | İstenen alt alanın indeksi. |

**Returns:**
Alan örneği.

### get_Item {#get_Item-java.lang.String-}
Bu alanda bulunan alt alanı alt alanın adına göre alır.

### getAlternateName {#getAlternateName--}
```
public String getAlternateName()
```

Alanının alternatif adını alır (Alanının gerçek adı yerine, kullanıcı arayüzünde alanın tanımlandığı her yerde kullanılacak alternatif bir alan adıdır). Alternatif ad, Adobe Acrobat'ta alan ipucu olarak kullanılır.

**Returns:**
String değeri

### getAnnotationIndex {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```

Bu anotation'ın sayfadaki indeksini alır.

**Returns:**
int değer

### getMappingName {#getMappingName--}
```
public String getMappingName()
```

Belgeden etkileşimli form alanı verileri dışa aktarılırken kullanılacak alanın eşleme adını alır.

**Returns:**
String değeri

### getMaxFontSize {#getMaxFontSize--}
```
public static double getMaxFontSize()
```

Alan içeriği için kullanılabilecek azami yazı tipi boyutu. -1, boyutu kontrol etmemek için.

**Returns:**
double değer

### getMinFontSize {#getMinFontSize--}
```
public static double getMinFontSize()
```

Alan içeriği için kullanılabilecek asgari yazı tipi boyutu. -1, boyutu kontrol etmemek için.

**Returns:**
double değer

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Bu alanı içeren sayfanın indeksini alır.

**Returns:**
int değer

### getPartialName {#getPartialName--}
```
public String getPartialName()
```

Alanının kısmi adını alır.

**Returns:**
String değeri

### getRect {#getRect--}
```
public Rectangle getRect()
```

Alan dikdörtgenini alır.

**Returns:**
alan dikdörtgeni.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Eşitleme nesnesi.

**Returns:**
nesne değeri

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Alanının sekme sırasını alır veya ayarlar.

**Returns:**
int değer

### getValue {#getValue--}
```
public String getValue()
```

Alanın değerini alır.

**Returns:**
String değeri

### isFitIntoRectangle {#isFitIntoRectangle--}
```
public static boolean isFitIntoRectangle()
```

Doğru ise, yazı tipi boyutu belirtilen dikdörtgene sığacak şekilde küçültülür.

**Returns:**
boolean değer

### isGroup {#isGroup--}
```
public boolean isGroup()
```

Bu alanın uç olmayan alan (yani alan grubu) olup olmadığını gösteren boolean değeri alır.

**Returns:**
boolean değer

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```



### isSharedField {#isSharedField--}
```
public boolean isSharedField()
```

Generator desteği için özellik. Alan başlık ya da alt bilgiye eklendiğinde kullanılır. Doğru ise, bu alan bir kez oluşturulur ve görünümü belgenin tüm sayfalarında görünür. Yanlış ise, her belge sayfası için ayrı bir alan oluşturulur.

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Sözlük eşitlenmişse doğru döndürür.

**Returns:**
boolean değer

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

İçerilen alanların dökümcüsünü döndürür.

**Returns:**
Yineleyici nesnesi.

### recalculate {#recalculate--}
```
public boolean recalculate()
```

Formdaki tüm hesaplanmış alanları yeniden hesaplar.

**Returns:**
Yeniden hesaplama sırasında alan değeri değiştirildiyse doğru.

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}


### setAlternateName {#setAlternateName-java.lang.String-}
Alan için alternatif adı ayarlar (Alan adı, kullanıcı arayüzünde alanın tanımlandığı her yerde gerçek alan adının yerine kullanılacak alternatif bir alandır). Alternatif ad, Adobe Acrobat'ta alan ipucu olarak kullanılır.

### setAnnotationIndex {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```

Bu açıklamanın sayfadaki indeksini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setFitIntoRectangle {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```

Doğru ise, yazı tipi boyutu belirtilen dikdörtgene sığacak şekilde küçültülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMappingName {#setMappingName-java.lang.String-}
Belgeden etkileşimli form alanı verileri dışa aktarılırken kullanılacak alanın eşleme adını ayarlar.

### setMaxFontSize {#setMaxFontSize-double-}
```
public static void setMaxFontSize(double value)
```

Alan içeriği için kullanılabilecek azami yazı tipi boyutu. -1, boyutu kontrol etmemek için.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setMinFontSize {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```

Alan içeriği için kullanılabilecek asgari yazı tipi boyutu. -1, boyutu kontrol etmemek için.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setPartialName {#setPartialName-java.lang.String-}
Alanının kısmi adını ayarlar.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Alan konumunu ayarlar.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Alan dikdörtgenini ayarlar.

### setSharedField {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```

Generator desteği için özellik. Alan başlık ya da alt bilgiye eklendiğinde kullanılır. Doğru ise, bu alan bir kez oluşturulur ve görünümü belgenin tüm sayfalarında görünür. Yanlış ise, her belge sayfası için ayrı bir alan oluşturulur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Alanının sekme sırasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setValue {#setValue-java.lang.String-}
Değeri ayarlar.

### size {#size--}
```
public int size()
```

Bu alandaki alt alanların sayısını alır. (Örneğin radyo düğmesi alanındaki öğe sayısı).

**Returns:**
int değer

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Görünüm değerini günceller.

---
title: "Yer imi"
linktitle: "Yer imi"
second_title: "Aspose.PDF for Java API Referansı"
description: "Yer işaretini temsil eder."
type: docs
weight: 60
url: /tr/java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Bookmark

```
public final class Bookmark extends Object
```

Yer işaretini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Bookmark](#Bookmark--) | Yeni bir {@code Bookmark} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAction](#getAction--) | Yer imiyle bağlanan eylemi alır. PageNumber sunulmuşsa eylem belirtilemez. Eylem türleri şunları içerir: "GoTo", "GoToR", "Launch", "Named". |
| [getBoldFlag](#getBoldFlag--) | Yer imi başlığının kalın bayrağını alır. |
| [getChildItem](#getChildItem--) | Yer iminin alt öğelerini alır. Obsolete("Use getChildItems() property instead of this one.") |
| [getChildItems](#getChildItems--) | Yer iminin alt öğelerini alır. |
| [getCustomAcorbatViewerMenuActionName](#getCustomAcorbatViewerMenuActionName--) | Henüz desteklenmiyor. Acrobat görüntüleyicide bir menü öğesini çalıştırmaya karşılık gelen eylem adı. |
| [getDestination](#getDestination--) | Yer iminin hedef sayfasını alır. Eylem "" olarak ayarlandıysa gereklidir. |
| [getItalicFlag](#getItalicFlag--) | Yer imi başlığının italik bayrağını alır. |
| [getLevel](#getLevel--) | Yer iminin hiyerarşi seviyesini alır. |
| [getPageDisplay_Bottom](#getPageDisplay_Bottom--) | Sayfa görüntüsünün alt koordinatını alır. |
| [getPageDisplay_Left](#getPageDisplay_Left--) | Sayfa görüntüsünün sol koordinatını alır. |
| [getPageDisplay_Right](#getPageDisplay_Right--) | Sayfa görüntüsünün sağ koordinatını alır. |
| [getPageDisplay_Top](#getPageDisplay_Top--) | Sayfa görüntüsünün üst koordinatını alır. |
| [getPageDisplay_Zoom](#getPageDisplay_Zoom--) | Sayfa görüntüsünün yakınlaştırma faktörünü alır. |
| [getPageDisplay](#getPageDisplay--) | Görüntü yer iminin hedef sayfasının tipini alır. |
| [getPageNumber](#getPageNumber--) | Yer iminin hedef sayfasının numarasını alır. |
| [getRemoteFile](#getRemoteFile--) | Yer imi için "GoToR" eylemi gerektiren dosyayı (yolu) alır. |
| [getTitle](#getTitle--) | Yer iminin başlığını alır. |
| [getTitleColor](#getTitleColor--) | Yer imi başlığının rengini alır. |
| [isOpen](#isOpen--) | Yer imi durumunu (açık, kapalı) alır. |
| [setAction](#setAction-java.lang.String-) | Yer imine bağlanan eylemi ayarlar. PageNumber sunulmuşsa eylem belirtilemez. Eylem türleri şunları içerir: "GoTo", "GoToR", "Launch", "Named". |
| [setBoldFlag](#setBoldFlag-boolean-) | Yer imi başlığının kalın bayrağını ayarlar. |
| [setChildItem](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | Yer iminin alt öğelerini ayarlar. Eski("Bu yerine setChildItems() özelliğini kullanın.") |
| [setChildItems](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | Yer iminin alt öğelerini ayarlar. |
| [setCustomAcorbatViewerMenuActionName](#setCustomAcorbatViewerMenuActionName-int:A-) | Henüz desteklenmiyor. Acrobat görüntüleyicide bir menü öğesini çalıştırmaya karşılık gelen eylem adını ayarlar. |
| [setDestination](#setDestination-java.lang.String-) | Yer iminin hedef sayfasını ayarlar. Eylem "" olarak ayarlandıysa gereklidir. |
| [setItalicFlag](#setItalicFlag-boolean-) | Yer imi başlığının italik bayrağını ayarlar. |
| [setLevel](#setLevel-int-) | Yer iminin hiyerarşi seviyesini ayarlar. |
| [setOpen](#setOpen-boolean-) | Yer imi durumunu (açık, kapalı) ayarlar. |
| [setPageDisplay_Bottom](#setPageDisplay_Bottom-int-) | Sayfa görüntüsünün alt koordinatını ayarlar. |
| [setPageDisplay_Left](#setPageDisplay_Left-int-) | Sayfa görüntüsünün sol koordinatını ayarlar. |
| [setPageDisplay_Right](#setPageDisplay_Right-int-) | Sayfa görüntüsünün sağ koordinatını ayarlar. |
| [setPageDisplay_Top](#setPageDisplay_Top-int-) | Sayfa görüntüsünün üst koordinatını ayarlar. |
| [setPageDisplay_Zoom](#setPageDisplay_Zoom-int-) | Sayfa görüntüsünün yakınlaştırma faktörünü ayarlar. |
| [setPageDisplay](#setPageDisplay-java.lang.String-) | Görüntü yer iminin hedef sayfasının türünü ayarlar. |
| [setPageNumber](#setPageNumber-int-) | Yer iminin hedef sayfasının numarasını ayarlar. |
| [setRemoteFile](#setRemoteFile-java.lang.String-) | Yer imi için "GoToR" eylemi gerektiren dosyayı (yolu) ayarlar. |
| [setTitle](#setTitle-java.lang.String-) | Yer işaretinin başlığını ayarlar. |
| [setTitleColor](#setTitleColor-java.awt.Color-) | Yer işaretinin başlığının rengini ayarlar. |
| [toOutlineItemCollection](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | OutlineItemCollection'a dönüştür |

### Bookmark {#Bookmark--}
```
public Bookmark()
```

Yeni bir {@code Bookmark} sınıfı örneği başlatır.

### getAction {#getAction--}
```
public String getAction()
```

Yer imiyle bağlanan eylemi alır. PageNumber sunulmuşsa eylem belirtilemez. Eylem türleri şunları içerir: "GoTo", "GoToR", "Launch", "Named".

**Returns:**
String değeri

### getBoldFlag {#getBoldFlag--}
```
public boolean getBoldFlag()
```

Yer imi başlığının kalın bayrağını alır.

**Returns:**
boolean değer

### getChildItem {#getChildItem--}
```
@Deprecated public Bookmarks getChildItem()
```

Yer iminin alt öğelerini alır. Obsolete("Use getChildItems() property instead of this one.")

**Returns:**
Yer işaretleri öğesi

### getChildItems {#getChildItems--}
```
public Bookmarks getChildItems()
```

Yer iminin alt öğelerini alır.

**Returns:**
yer işaretinin alt öğeleri.

### getCustomAcorbatViewerMenuActionName {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```

Henüz desteklenmiyor. Acrobat görüntüleyicide bir menü öğesini çalıştırmaya karşılık gelen eylem adı.

**Returns:**
int değer dizisi

### getDestination {#getDestination--}
```
public String getDestination()
```

Yer iminin hedef sayfasını alır. Eylem "" olarak ayarlandıysa gereklidir.

**Returns:**
String değeri

### getItalicFlag {#getItalicFlag--}
```
public boolean getItalicFlag()
```

Yer imi başlığının italik bayrağını alır.

**Returns:**
boolean değer

### getLevel {#getLevel--}
```
public int getLevel()
```

Yer iminin hiyerarşi seviyesini alır.

**Returns:**
int değer

### getPageDisplay_Bottom {#getPageDisplay_Bottom--}
```
public int getPageDisplay_Bottom()
```

Sayfa görüntüsünün alt koordinatını alır.

**Returns:**
int değer

### getPageDisplay_Left {#getPageDisplay_Left--}
```
public int getPageDisplay_Left()
```

Sayfa görüntüsünün sol koordinatını alır.

**Returns:**
int değer

### getPageDisplay_Right {#getPageDisplay_Right--}
```
public int getPageDisplay_Right()
```

Sayfa görüntüsünün sağ koordinatını alır.

**Returns:**
int değer

### getPageDisplay_Top {#getPageDisplay_Top--}
```
public int getPageDisplay_Top()
```

Sayfa görüntüsünün üst koordinatını alır.

**Returns:**
int değer

### getPageDisplay_Zoom {#getPageDisplay_Zoom--}
```
public int getPageDisplay_Zoom()
```

Sayfa görüntüsünün yakınlaştırma faktörünü alır.

**Returns:**
int değer

### getPageDisplay {#getPageDisplay--}
```
public String getPageDisplay()
```

Görüntü yer iminin hedef sayfasının tipini alır.

**Returns:**
String değeri

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Yer iminin hedef sayfasının numarasını alır.

**Returns:**
int değer

### getRemoteFile {#getRemoteFile--}
```
public String getRemoteFile()
```

Yer imi için "GoToR" eylemi gerektiren dosyayı (yolu) alır.

**Returns:**
String değeri

### getTitle {#getTitle--}
```
public String getTitle()
```

Yer iminin başlığını alır.

**Returns:**
String değeri

### getTitleColor {#getTitleColor--}
```
public Color getTitleColor()
```

Yer imi başlığının rengini alır.

**Returns:**
Renk öğesi

### isOpen {#isOpen--}
```
public boolean isOpen()
```

Yer imi durumunu (açık, kapalı) alır.

**Returns:**
boolean değer

### setAction {#setAction-java.lang.String-}
Yer imine bağlanan eylemi ayarlar. PageNumber sunulmuşsa eylem belirtilemez. Eylem türleri şunları içerir: "GoTo", "GoToR", "Launch", "Named".

### setBoldFlag {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```

Yer imi başlığının kalın bayrağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setChildItem {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
Yer iminin alt öğelerini ayarlar. Eski("Bu yerine setChildItems() özelliğini kullanın.")

### setChildItems {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
Yer iminin alt öğelerini ayarlar.

### setCustomAcorbatViewerMenuActionName {#setCustomAcorbatViewerMenuActionName-int:A-}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```

Henüz desteklenmiyor. Acrobat görüntüleyicide bir menü öğesini çalıştırmaya karşılık gelen eylem adını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer dizisi |

### setDestination {#setDestination-java.lang.String-}
Yer iminin hedef sayfasını ayarlar. Eylem "" olarak ayarlandıysa gereklidir.

### setItalicFlag {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```

Yer imi başlığının italik bayrağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

Yer iminin hiyerarşi seviyesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Yer imi durumunu (açık, kapalı) ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setPageDisplay_Bottom {#setPageDisplay_Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```

Sayfa görüntüsünün alt koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setPageDisplay_Left {#setPageDisplay_Left-int-}
```
public void setPageDisplay_Left(int value)
```

Sayfa görüntüsünün sol koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setPageDisplay_Right {#setPageDisplay_Right-int-}
```
public void setPageDisplay_Right(int value)
```

Sayfa görüntüsünün sağ koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setPageDisplay_Top {#setPageDisplay_Top-int-}
```
public void setPageDisplay_Top(int value)
```

Sayfa görüntüsünün üst koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setPageDisplay_Zoom {#setPageDisplay_Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```

Sayfa görüntüsünün yakınlaştırma faktörünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setPageDisplay {#setPageDisplay-java.lang.String-}
Görüntü yer iminin hedef sayfasının türünü ayarlar.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Yer iminin hedef sayfasının numarasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setRemoteFile {#setRemoteFile-java.lang.String-}
Yer imi için "GoToR" eylemi gerektiren dosyayı (yolu) ayarlar.

### setTitle {#setTitle-java.lang.String-}
Yer işaretinin başlığını ayarlar.

### setTitleColor {#setTitleColor-java.awt.Color-}
Yer işaretinin başlığının rengini ayarlar.

### toOutlineItemCollection {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
OutlineItemCollection'a dönüştür

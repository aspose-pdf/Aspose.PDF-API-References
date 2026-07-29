---
title: "HeadingLevels"
linktitle: "HeadingLevels"
second_title: "Aspose.PDF for Java API Referansı"
description: "Yazı tipi boyutuna göre başlık seviyeleriyle çalışmak için bir sınıfı temsil eder."
type: docs
weight: 20
url: /tr/java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

Yazı tipi boyutuna göre başlık seviyeleriyle çalışmak için bir sınıfı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | HeadingLevels sınıfının yeni bir örneğini oluşturur. |
| [HeadingLevels](#HeadingLevels-double-) | HeadingLevels sınıfının yeni bir örneğini oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | Başlık seviyelerini ekler. |
| [estimateLevel](#estimateLevel-double-) | Olası başlık seviyesini tahmin eder. fontSize seviyeler listesinde bulunamazsa, bu yazı tipi boyutu değerine en yakın seviye döndürülür. fontSize belirtilen minimum ve maksimum başlık seviyelerinin dışındaysa, yöntem false döndürür. |
| [findLevel](#findLevel-double-int:A-) | İlgili yazı tipi boyutu için seviyeyi bulur. Tam eşleşme aranıyor. |
| [getAllLevels](#getAllLevels--) | Tüm başlık seviyelerini alır. |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

HeadingLevels sınıfının yeni bir örneğini oluşturur.

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

HeadingLevels sınıfının yeni bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| eşik |  | Yazı tipi boyutlarını karşılaştırmak için eşik değeri. Eşik içinde, başlık seviyeleri aynıdır. Eşik varsayılan değeri 0.01'dir. |

### addLevels {#addLevels-java.lang.Iterable-}
Başlık seviyelerini ekler.

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

Olası başlık seviyesini tahmin eder. fontSize seviyeler listesinde bulunamazsa, bu yazı tipi boyutu değerine en yakın seviye döndürülür. fontSize belirtilen minimum ve maksimum başlık seviyelerinin dışındaysa, yöntem false döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontSize |  | Yazı tipi boyutu. |

**Returns:**
Başlık seviyesi.

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

İlgili yazı tipi boyutu için seviyeyi bulur. Tam eşleşme aranıyor.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontSize |  | Yazı tipi boyutu. |
| seviye |  | Verilen yazı tipi boyutu için karşılık gelen başlık seviyesi. |

**Returns:**
False Eğer fontSize belirtilen aralıkta değilse.

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

Tüm başlık seviyelerini alır.

**Returns:**
Double tipinde IEnumerable

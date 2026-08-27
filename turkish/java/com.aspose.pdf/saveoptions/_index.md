---
title: "SaveOptions"
linktitle: "SaveOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "SaveOptions türü, bireysel kaydetme seçenekleri üzerinde soyutlama seviyesini tutar."
type: docs
weight: 4370
url: /tr/java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions

```
public abstract class SaveOptions extends Object
```

SaveOptions türü, bireysel kaydetme seçenekleri üzerinde soyutlama seviyesini tutar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSaveFormat](#getSaveFormat--) | Veri kaydetme biçimi. |
| [getWarningHandler](#getWarningHandler--) | Oluşturulan uyarıları işlemek için geri çağırma. WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. Continue varsayılan eylemdir ve Save işlemi devam eder, ancak kullanıcı Abort döndürürse Save işlemi durmalıdır. |
| [isCacheGlyphs](#isCacheGlyphs--) | Font gliflerinin aps sayfaları hazırlanırken önbelleğe alınıp alınmayacağını gösteren boolean değeri alır veya ayarlar. PDF'nin diğer formatlara dönüştürülmesinin performansını artırır ancak bellek tüketimini yükseltir. |
| [isCloseResponse](#isCloseResponse--) | Belge yanıt içine kaydedildikten sonra Response nesnesinin kapatılıp kapatılmayacağını gösteren boolean değeri alır. |
| [setCacheGlyphs](#setCacheGlyphs-boolean-) | Font gliflerinin aps sayfaları hazırlanırken önbelleğe alınıp alınmayacağını gösteren boolean değeri alır veya ayarlar. PDF'nin diğer formatlara dönüştürülmesinin performansını artırır ancak bellek tüketimini yükseltir. |
| [setCloseResponse](#setCloseResponse-boolean-) | Belge yanıt içine kaydedildikten sonra Response nesnesinin kapatılıp kapatılmayacağını gösteren boolean değeri ayarlar. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Oluşturulan uyarıları işlemek için geri çağırma. WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. Continue varsayılan eylemdir ve Save işlemi devam eder, ancak kullanıcı Abort döndürürse Save işlemi durmalıdır. |

### getSaveFormat {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```

Veri kaydetme biçimi.

**Returns:**
SaveFormat değeri @see SaveFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Oluşturulan uyarıları işlemek için geri çağırma. WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. Continue varsayılan eylemdir ve Save işlemi devam eder, ancak kullanıcı Abort döndürürse Save işlemi durmalıdır.

**Returns:**
IWarningCallback değeri

### isCacheGlyphs {#isCacheGlyphs--}
```
public final boolean isCacheGlyphs()
```

Font gliflerinin aps sayfaları hazırlanırken önbelleğe alınıp alınmayacağını gösteren boolean değeri alır veya ayarlar. PDF'nin diğer formatlara dönüştürülmesinin performansını artırır ancak bellek tüketimini yükseltir.

**Returns:**
boolean değer

### isCloseResponse {#isCloseResponse--}
```
public boolean isCloseResponse()
```

Belge yanıt içine kaydedildikten sonra Response nesnesinin kapatılıp kapatılmayacağını gösteren boolean değeri alır.

**Returns:**
boolean değer

### setCacheGlyphs {#setCacheGlyphs-boolean-}
```
public final void setCacheGlyphs(boolean value)
```

Font gliflerinin aps sayfaları hazırlanırken önbelleğe alınıp alınmayacağını gösteren boolean değeri alır veya ayarlar. PDF'nin diğer formatlara dönüştürülmesinin performansını artırır ancak bellek tüketimini yükseltir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setCloseResponse {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```

Belge yanıt içine kaydedildikten sonra Response nesnesinin kapatılıp kapatılmayacağını gösteren boolean değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Oluşturulan uyarıları işlemek için geri çağırma. WarningHandler, Continue veya Abort belirten ReturnAction enum öğesini döndürür. Continue varsayılan eylemdir ve Save işlemi devam eder, ancak kullanıcı Abort döndürürse Save işlemi durmalıdır.

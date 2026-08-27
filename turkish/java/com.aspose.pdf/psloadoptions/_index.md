---
title: "PsLoadOptions"
linktitle: "PsLoadOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: ".mht dosyasının pdf belgesine yüklenmesi/içe aktarılması seçeneklerini temsil eder."
type: docs
weight: 4060
url: /tr/java/com.aspose.pdf/psloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PsLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PsLoadOptions

```
public final class PsLoadOptions extends LoadOptions
```

.mht dosyasının pdf belgesine yüklenmesi/içe aktarılması seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PsLoadOptions](#PsLoadOptions--) | Boş temel yol ile PostScript'i pdf belgesine dönüştürmek için yükleme seçenekleri oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFontsFolders](#getFontsFolders--) | Yazı tipi klasör yollarını alır. Dönüştürme için ek yazı tipleri içeren klasörler. |
| [isConvertFontsToTTF](#isConvertFontsToTTF--) | TrueType olmayan yazı tiplerinin TTF olarak kaydedilip kaydedilmeyeceğini belirtir. PS'den PDF'ye dönüşümde ortaya çıkan belgenin boyutunu önemli ölçüde azaltır ve TrueType olmayan yazı tiplerinde büyük miktarda metin içeren PS dosyalarının herhangi bir çıktı formatına dönüşüm hızını artırır. Ancak, PostSctipt dosyasını görüntüye dönüştürürken metinde küçük bir dikey kayma olur. |
| [setConvertFontsToTTF](#setConvertFontsToTTF-boolean-) | TrueType olmayan yazı tiplerinin TTF olarak kaydedilip kaydedilmeyeceğini belirtir. PS'den PDF'ye dönüşümde ortaya çıkan belgenin boyutunu önemli ölçüde azaltır ve TrueType olmayan yazı tiplerinde büyük miktarda metin içeren PS dosyalarının herhangi bir çıktı formatına dönüşüm hızını artırır. Ancak, PostSctipt dosyasını görüntüye dönüştürürken metinde küçük bir dikey kayma olur. |
| [setFontsFolders](#setFontsFolders-java.lang.String:A-) | Yazı tipi klasör yollarını ayarlar. Dönüştürme için ek yazı tipleri içeren klasörler. |

### PsLoadOptions {#PsLoadOptions--}
```
public PsLoadOptions()
```

Boş temel yol ile PostScript'i pdf belgesine dönüştürmek için yükleme seçenekleri oluşturur.

### getFontsFolders {#getFontsFolders--}
```
public String [] getFontsFolders()
```

Yazı tipi klasör yollarını alır. Dönüştürme için ek yazı tipleri içeren klasörler.

**Returns:**
String değerlerinin dizisi

### isConvertFontsToTTF {#isConvertFontsToTTF--}
```
public final boolean isConvertFontsToTTF()
```

TrueType olmayan yazı tiplerinin TTF olarak kaydedilip kaydedilmeyeceğini belirtir. PS'den PDF'ye dönüşümde ortaya çıkan belgenin boyutunu önemli ölçüde azaltır ve TrueType olmayan yazı tiplerinde büyük miktarda metin içeren PS dosyalarının herhangi bir çıktı formatına dönüşüm hızını artırır. Ancak, PostSctipt dosyasını görüntüye dönüştürürken metinde küçük bir dikey kayma olur.

**Returns:**
boolean değer

### setConvertFontsToTTF {#setConvertFontsToTTF-boolean-}
```
public final void setConvertFontsToTTF(boolean value)
```

TrueType olmayan yazı tiplerinin TTF olarak kaydedilip kaydedilmeyeceğini belirtir. PS'den PDF'ye dönüşümde ortaya çıkan belgenin boyutunu önemli ölçüde azaltır ve TrueType olmayan yazı tiplerinde büyük miktarda metin içeren PS dosyalarının herhangi bir çıktı formatına dönüşüm hızını artırır. Ancak, PostSctipt dosyasını görüntüye dönüştürürken metinde küçük bir dikey kayma olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setFontsFolders {#setFontsFolders-java.lang.String:A-}
Yazı tipi klasör yollarını ayarlar. Dönüştürme için ek yazı tipleri içeren klasörler.

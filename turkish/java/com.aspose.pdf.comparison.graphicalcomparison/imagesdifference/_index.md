---
title: "ImagesDifference"
linktitle: "ImagesDifference"
second_title: "Aspose.PDF for Java API Referansı"
description: "İki PDF sayfasını karşılaştırmanın sonuç sınıfını temsil eder."
type: docs
weight: 20
url: /tr/java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

İki PDF sayfasını karşılaştırmanın sonuç sınıfını temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Belirtilen renkleri kullanarak fark dizisini bir bitmap görüntüsüne dönüştürür. |
| [dispose](#dispose--) | Nesne yok edilmeden önce gerekli temizlik işlemlerini gerçekleştirir. |
| [getDestinationImage](#getDestinationImage--) | Fark dizisini kaynak görüntüye uygulayarak hedef görüntüyü temsil eden yeni bir bitmap döndürür. |
| [getDifference](#getDifference--) | Fark dizisini alır. Bu dizi, LockBits yöntemi sonucunda elde edilen orijinal görüntü veri dizisine benzer. |
| [getHeight](#getHeight--) | Fark yüksekliği. |
| [getSourceImage](#getSourceImage--) | İlk karşılaştırılan sayfanın görüntüsünü alır. Görüntünün piksel formatı 24bpp'dir. |
| [getStride](#getStride--) | Fark görüntü verisinin satır genişliği. |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Belirtilen renkleri kullanarak fark dizisini bir bitmap görüntüsüne dönüştürür.

### dispose {#dispose--}
```
public final void dispose()
```

Nesne yok edilmeden önce gerekli temizlik işlemlerini gerçekleştirir.

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

Fark dizisini kaynak görüntüye uygulayarak hedef görüntüyü temsil eden yeni bir bitmap döndürür.

**Returns:**
Bir hedef görüntü.

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

Fark dizisini alır. Bu dizi, LockBits yöntemi sonucunda elde edilen orijinal görüntü veri dizisine benzer.

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

Fark yüksekliği.

**Returns:**
int değer

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

İlk karşılaştırılan sayfanın görüntüsünü alır. Görüntünün piksel formatı 24bpp'dir.

**Returns:**
BufferedImage instance

### getStride {#getStride--}
```
public final int getStride()
```

Fark görüntü verisinin satır genişliği.

**Returns:**
int değer

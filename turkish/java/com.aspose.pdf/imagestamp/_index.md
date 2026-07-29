---
title: "ImageStamp"
linktitle: "ImageStamp"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir grafik damgasını temsil eder."
type: docs
weight: 2360
url: /tr/java/com.aspose.pdf/imagestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.ImageStamp, com.aspose.pdf.Stamp, com.aspose.pdf.ImageStamp

```
public final class ImageStamp extends Stamp
```

Bir grafik damgasını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageStamp](#ImageStamp-java.io.InputStream-) | Yeni bir {@code ImageStamp} sınıfı örneğini başlatır. |
| [ImageStamp](#ImageStamp-java.lang.String-) | Belirtilen dosyadaki görüntü ile bir görüntü damgası oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close](#close--) | Bu örneği kapatır |
| [getAlternativeText](#getAlternativeText--) | Görüntü damgası için Alternatif Metni alır. |
| [getHeight](#getHeight--) | Görüntü yüksekliğini alır. Bu görüntüyü ayarlamak, görüntüyü dikey olarak ölçeklendirmeyi sağlar. |
| [getImage](#getImage--) | Damga için kullanılan görüntü akışını alır. |
| [getQuality](#getQuality--) | Görüntü damgasının kalitesini yüzde olarak alır. Geçerli değerler 0..100%. |
| [getWidth](#getWidth--) | Görüntü genişliğini alır. Bu özelliği ayarlamak, görüntüyü yatay olarak ölçeklendirmeyi sağlar. |
| [getXIndent](#getXIndent--) | Soldan başlayarak yatay damga koordinatını alır ve ayarlar. |
| [getYIndent](#getYIndent--) | Alttan başlayarak dikey damga koordinatını alır ve ayarlar. |
| [put](#put-com.aspose.pdf.Page-) | Sayfaya grafik damgası ekler. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Görüntü damgası için Alternatif Metni ayarlar. |
| [setHeight](#setHeight-double-) | Görüntü yüksekliğini ayarlar. Bu görüntüyü ayarlamak, görüntüyü dikey olarak ölçeklendirmeyi sağlar. |
| [setQuality](#setQuality-int-) | Görüntü damgasının kalitesini yüzde olarak ayarlar. Geçerli değerler 0..100%. |
| [setWidth](#setWidth-double-) | Görüntü genişliğini ayarlar. Bu özelliği ayarlamak, görüntüyü yatay olarak ölçeklendirmeyi sağlar. |
| [setXIndent](#setXIndent-double-) | Soldan başlayarak yatay damga koordinatını alır ve ayarlar. |
| [setYIndent](#setYIndent-double-) | Alttan başlayarak dikey damga koordinatını alır ve ayarlar. |

### ImageStamp {#ImageStamp-java.io.InputStream-}
Yeni bir {@code ImageStamp} sınıfı örneğini başlatır.

### ImageStamp {#ImageStamp-java.lang.String-}
Belirtilen dosyadaki görüntü ile bir görüntü damgası oluşturur.

### close {#close--}
```
public void close()
```

Bu örneği kapatır

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Görüntü damgası için Alternatif Metni alır.

**Returns:**
String değeri

### getHeight {#getHeight--}
```
public double getHeight()
```

Görüntü yüksekliğini alır. Bu görüntüyü ayarlamak, görüntüyü dikey olarak ölçeklendirmeyi sağlar.

**Returns:**
double değer

### getImage {#getImage--}
```
public InputStream getImage()
```

Damga için kullanılan görüntü akışını alır.

**Returns:**
InputStream nesnesi

### getQuality {#getQuality--}
```
public int getQuality()
```

Görüntü damgasının kalitesini yüzde olarak alır. Geçerli değerler 0..100%.

**Returns:**
int değer

### getWidth {#getWidth--}
```
public double getWidth()
```

Görüntü genişliğini alır. Bu özelliği ayarlamak, görüntüyü yatay olarak ölçeklendirmeyi sağlar.

**Returns:**
double değer

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Soldan başlayarak yatay damga koordinatını alır ve ayarlar.

**Returns:**
double değer

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Alttan başlayarak dikey damga koordinatını alır ve ayarlar.

**Returns:**
double değer

### put {#put-com.aspose.pdf.Page-}
Sayfaya grafik damgası ekler.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Görüntü damgası için Alternatif Metni ayarlar.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Görüntü yüksekliğini ayarlar. Bu görüntüyü ayarlamak, görüntüyü dikey olarak ölçeklendirmeyi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Görüntü damgasının kalitesini yüzde olarak ayarlar. Geçerli değerler 0..100%.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Görüntü genişliğini ayarlar. Bu özelliği ayarlamak, görüntüyü yatay olarak ölçeklendirmeyi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Soldan başlayarak yatay damga koordinatını alır ve ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Alttan başlayarak dikey damga koordinatını alır ve ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

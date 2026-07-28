---
title: "Görüntü"
linktitle: "Görüntü"
second_title: "Aspose.PDF for Java API Referansı"
description: "Görüntüyü temsil eder."
type: docs
weight: 2280
url: /tr/java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Image, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Image

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Image extends BaseParagraph
```

Görüntüyü temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Image](#Image--) | varsayılan yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [convertToJpeg](#convertToJpeg-java.io.InputStream-) | bmp/png/gif/tiff görüntüsü içeren akışı JPG formatındaki görüntü akışına dönüştürmeyi deneyin. |
| [deepClone](#deepClone--) | Görüntüyü kopyala. |
| [getBitmapInfo](#getBitmapInfo--) | Sıkıştırılmamış görüntü baytlarını alır veya ayarlar. |
| [getBitmapSize](#getBitmapSize--) | Görüntünün bitmap boyutunu alır. |
| [getBufferedImage](#getBufferedImage--) | java awt görüntüsünü alır. |
| [getFile](#getFile--) | Görüntü dosyasını alır. |
| [getFileType](#getFileType--) | Görüntü dosyası türünü alır. |
| [getFixHeight](#getFixHeight--) | Görüntü yüksekliğini alır. |
| [getFixWidth](#getFixWidth--) | Görüntü genişliğini alır. |
| [getImageScale](#getImageScale--) | Görüntü ölçeğini alır. |
| [getImageStream](#getImageStream--) | Görüntü akışını alır. |
| [getMimeType](#getMimeType-com.aspose.ms.System.Drawing.Image-) | Görüntü için mime türünü döndürür. |
| [getTitle](#getTitle--) | Görüntünün başlığını belirten bir dize değeri alır. |
| [isApplyResolution](#isApplyResolution--) | Görüntünün oluşturma sırasında çözünürlük kullanıp kullanmadığını belirten bir bool değeri alır veya ayarlar |
| [isBlackWhite](#isBlackWhite--) | Görüntünün siyah-beyaz olmasına zorlanıp zorlanmadığını belirten bir bool değeri alır. CCITT alt formatında TIFF görüntüsü kullanılırsa, bu özellik true olarak ayarlanmalıdır. |
| [isBlackWhiteForGrayScale](#isBlackWhiteForGrayScale--) | Gri tonlamalı görüntüler için 1bpp kodlamasını algılamaya ve kullanmaya çalışır. Varsayılan değer == FALSE |
| [setApplyResolution](#setApplyResolution-boolean-) | Görüntünün oluşturma sırasında çözünürlük kullanıp kullanmadığını belirten bir bool değeri alır veya ayarlar |
| [setBitmapInfo](#setBitmapInfo-com.aspose.pdf.BitmapInfo-) | Sıkıştırılmamış görüntü baytlarını alır veya ayarlar. |
| [setBlackWhite](#setBlackWhite-boolean-) | Görüntünün siyah-beyaz olmasına zorlanıp zorlanmadığını belirten bir bool değeri ayarlar. CCITT alt formatında TIFF görüntüsü kullanılırsa, bu özellik true olarak ayarlanmalıdır. |
| [setBlackWhiteForGrayScale](#setBlackWhiteForGrayScale-boolean-) | Gri tonlamalı görüntüler için 1bpp kodlamasını algılamaya ve kullanmaya çalışır. Varsayılan değer == FALSE |
| [setBufferedImage](#setBufferedImage-java.awt.image.BufferedImage-) | Java AWT görüntüsünü ayarlar. |
| [setFile](#setFile-java.lang.String-) | Görüntü dosyasını ayarlar. |
| [setFileType](#setFileType-com.aspose.pdf.ImageFileType-) | Görüntü dosyası türünü ayarlar. |
| [setFixHeight](#setFixHeight-double-) | Görüntü yüksekliğini ayarlar. |
| [setFixWidth](#setFixWidth-double-) | Görüntü genişliğini ayarlar. |
| [setImageScale](#setImageScale-double-) | Görüntü ölçeğini ayarlar. |
| [setImageStream](#setImageStream-java.io.InputStream-) | Görüntü akışını ayarlar. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Görüntünün başlığını belirten bir dize değeri ayarlar. |

### Image {#Image--}
```
public Image()
```

varsayılan yapıcı

### convertToJpeg {#convertToJpeg-java.io.InputStream-}
bmp/png/gif/tiff görüntüsü içeren akışı JPG formatındaki görüntü akışına dönüştürmeyi deneyin.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Görüntüyü kopyala.

**Returns:**
Klonlanmış nesne

### getBitmapInfo {#getBitmapInfo--}
```
public final BitmapInfo getBitmapInfo()
```

Sıkıştırılmamış görüntü baytlarını alır veya ayarlar.

**Returns:**
BitmapInfo örneği

### getBitmapSize {#getBitmapSize--}
```
public final Rectangle getBitmapSize()
```

Görüntünün bitmap boyutunu alır.

**Returns:**
Dikdörtgen örneği

### getBufferedImage {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```

java awt görüntüsünü alır.

**Returns:**
BufferedImage nesnesi

### getFile {#getFile--}
```
public String getFile()
```

Görüntü dosyasını alır.

**Returns:**
String değeri

### getFileType {#getFileType--}
```
public ImageFileType getFileType()
```

Görüntü dosyası türünü alır.

**Returns:**
int değer @see ImageFileType

### getFixHeight {#getFixHeight--}
```
public double getFixHeight()
```

Görüntü yüksekliğini alır.

**Returns:**
double değer

### getFixWidth {#getFixWidth--}
```
public double getFixWidth()
```

Görüntü genişliğini alır.

**Returns:**
double değer

### getImageScale {#getImageScale--}
```
public double getImageScale()
```

Görüntü ölçeğini alır.

**Returns:**
double değer

### getImageStream {#getImageStream--}
```
public InputStream getImageStream()
```

Görüntü akışını alır.

**Returns:**
InputStream nesnesi

### getMimeType {#getMimeType-com.aspose.ms.System.Drawing.Image-}
Görüntü için mime türünü döndürür.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Görüntünün başlığını belirten bir dize değeri alır.

**Returns:**
TextFragment değeri

### isApplyResolution {#isApplyResolution--}
```
public boolean isApplyResolution()
```

Görüntünün oluşturma sırasında çözünürlük kullanıp kullanmadığını belirten bir bool değeri alır veya ayarlar

**Returns:**
boolean değer

### isBlackWhite {#isBlackWhite--}
```
public boolean isBlackWhite()
```

Görüntünün siyah-beyaz olmasına zorlanıp zorlanmadığını belirten bir bool değeri alır. CCITT alt formatında TIFF görüntüsü kullanılırsa, bu özellik true olarak ayarlanmalıdır.

**Returns:**
boolean değer

### isBlackWhiteForGrayScale {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```

Gri tonlamalı görüntüler için 1bpp kodlamasını algılamaya ve kullanmaya çalışır. Varsayılan değer == FALSE

**Returns:**
boolean değer

### setApplyResolution {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```

Görüntünün oluşturma sırasında çözünürlük kullanıp kullanmadığını belirten bir bool değeri alır veya ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setBitmapInfo {#setBitmapInfo-com.aspose.pdf.BitmapInfo-}
Sıkıştırılmamış görüntü baytlarını alır veya ayarlar.

### setBlackWhite {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```

Görüntünün siyah-beyaz olmasına zorlanıp zorlanmadığını belirten bir bool değeri ayarlar. CCITT alt formatında TIFF görüntüsü kullanılırsa, bu özellik true olarak ayarlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setBlackWhiteForGrayScale {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```

Gri tonlamalı görüntüler için 1bpp kodlamasını algılamaya ve kullanmaya çalışır. Varsayılan değer == FALSE

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| blackWhiteForGrayScale |  | boolean değer |

### setBufferedImage {#setBufferedImage-java.awt.image.BufferedImage-}
Java AWT görüntüsünü ayarlar.

### setFile {#setFile-java.lang.String-}
Görüntü dosyasını ayarlar.

### setFileType {#setFileType-com.aspose.pdf.ImageFileType-}
Görüntü dosyası türünü ayarlar.

### setFixHeight {#setFixHeight-double-}
```
public void setFixHeight(double value)
```

Görüntü yüksekliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setFixWidth {#setFixWidth-double-}
```
public void setFixWidth(double value)
```

Görüntü genişliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setImageScale {#setImageScale-double-}
```
public void setImageScale(double value)
```

Görüntü ölçeğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setImageStream {#setImageStream-java.io.InputStream-}
Görüntü akışını ayarlar.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Görüntünün başlığını belirten bir dize değeri ayarlar.

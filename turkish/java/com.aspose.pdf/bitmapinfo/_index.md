---
title: "BitmapInfo"
linktitle: "BitmapInfo"
second_title: "Aspose.PDF for Java API Referansı"
description: "Piksel dizisi ve bitmap bilgisi içeren nesne."
type: docs
weight: 300
url: /tr/java/com.aspose.pdf/bitmapinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BitmapInfo

```
public class BitmapInfo extends Object
```

Piksel dizisi ve bitmap bilgisi içeren nesne.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BitmapInfo](#BitmapInfo-byte:A-int-int-int-) | Sınıfın yeni bir örneğini oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat](#getFormat--) | Bitmap'in piksel biçimini alır. |
| [getHeight](#getHeight--) | Bitmap'in yüksekliğini alır. |
| [getPixelBytes](#getPixelBytes--) | Piksel dizisini alır. |
| [getWidth](#getWidth--) | Bitmap'in genişliğini alır. |

### BitmapInfo {#BitmapInfo-byte:A-int-int-int-}
```
public BitmapInfo(byte[] pixelBytes, int width, int height, int format)
```

Sınıfın yeni bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelBytes |  | Piksel dizisi. |
| genişlik |  | Bitmap genişliği. |
| yükseklik |  | Bitmap yüksekliği. |
| format |  | Bitmap'in piksel biçimi. @see BitmapInfo |

### getFormat {#getFormat--}
```
public final int getFormat()
```

Bitmap'in piksel biçimini alır.

**Returns:**
int değer PixelFormat öğesi

### getHeight {#getHeight--}
```
public final int getHeight()
```

Bitmap'in yüksekliğini alır.

**Returns:**
int değer

### getPixelBytes {#getPixelBytes--}
```
public final byte[] getPixelBytes()
```

Piksel dizisini alır.

**Returns:**
byte[] dizi

### getWidth {#getWidth--}
```
public final int getWidth()
```

Bitmap'in genişliğini alır.

**Returns:**
int değer

---
title: "PngDevice"
linktitle: "PngDevice"
second_title: "Aspose.PDF for Java API Referansı"
description: "Pdf belge sayfalarını png formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder."
type: docs
weight: 160
url: /tr/java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PngDevice

```
public final class PngDevice extends ImageDevice
```

Pdf belge sayfalarını png formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PngDevice](#PngDevice--) | Varsayılan çözünürlük ile {@code PngDevice} sınıfının yeni bir örneğini başlatır. |
| [PngDevice](#PngDevice-int-int-) | Sağlanan görüntü boyutlarıyla, varsayılan çözünürlük (=150) ile {@code PngDevice} sınıfının yeni bir örneğini başlatır. |
| [PngDevice](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | Varsayılan çözünürlük ile {@code PngDevice} sınıfının yeni bir örneğini başlatır. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-) | Varsayılan çözünürlük ile {@code PngDevice} sınıfının yeni bir örneğini başlatır. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Varsayılan çözünürlük ile {@code PngDevice} sınıfının yeni bir örneğini başlatır. |
| [PngDevice](#PngDevice-com.aspose.pdf.devices.Resolution-) | Varsayılan çözünürlük ile {@code PngDevice} sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isTransparentBackground](#isTransparentBackground--) | Görüntünün şeffaf arka plana sahip olup olmadığını alır veya ayarlar. |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Sayfayı png formatına dönüştürür ve çıktı akışına kaydeder. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Sayfayı png formatına dönüştürür ve çıktı akışına kaydeder. |
| [processToBufferedImage](#processToBufferedImage-com.aspose.pdf.Page-) | Sayfayı BufferedImage nesnesine dönüştürür. |
| [processToBufferedImageBinarized](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | Sayfayı Bradley ikileştirme ile BufferedImage nesnesine dönüştürür. |
| [setTransparentBackground](#setTransparentBackground-boolean-) | Görüntünün şeffaf arka plana sahip olup olmadığını alır veya ayarlar. |

### PngDevice {#PngDevice--}
```
public PngDevice()
```

Varsayılan çözünürlük ile {@code PngDevice} sınıfının yeni bir örneğini başlatır.

### PngDevice {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```

Sağlanan görüntü boyutlarıyla, varsayılan çözünürlük (=150) ile {@code PngDevice} sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik |  | Görüntü çıkış genişliği. |
| yükseklik |  | Görüntü çıkış yüksekliği. |

### PngDevice {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
Varsayılan çözünürlük ile {@code PngDevice} sınıfının yeni bir örneğini başlatır.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-}
Varsayılan çözünürlük ile {@code PngDevice} sınıfının yeni bir örneğini başlatır.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Varsayılan çözünürlük ile {@code PngDevice} sınıfının yeni bir örneğini başlatır.

### PngDevice {#PngDevice-com.aspose.pdf.devices.Resolution-}
Varsayılan çözünürlük ile {@code PngDevice} sınıfının yeni bir örneğini başlatır.

### isTransparentBackground {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```

Görüntünün şeffaf arka plana sahip olup olmadığını alır veya ayarlar.

**Returns:**
boolean değer

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Sayfayı png formatına dönüştürür ve çıktı akışına kaydeder.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Sayfayı png formatına dönüştürür ve çıktı akışına kaydeder.

### processToBufferedImage {#processToBufferedImage-com.aspose.pdf.Page-}
Sayfayı BufferedImage nesnesine dönüştürür.

### processToBufferedImageBinarized {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
Sayfayı Bradley ikileştirme ile BufferedImage nesnesine dönüştürür.

### setTransparentBackground {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```

Görüntünün şeffaf arka plana sahip olup olmadığını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

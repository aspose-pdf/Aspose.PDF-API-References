---
title: "JpegDevice"
linktitle: "JpegDevice"
second_title: "Aspose.PDF for Java API Referansı"
description: "Pdf belge sayfalarını jpeg formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder."
type: docs
weight: 130
url: /tr/java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.JpegDevice

```
public final class JpegDevice extends ImageDevice
```

Pdf belge sayfalarını jpeg formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [JpegDevice](#JpegDevice--) | Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır. |
| [JpegDevice](#JpegDevice-int-) | Yeni bir {@code JpegDevice} sınıfı örneğini başlatır. |
| [JpegDevice](#JpegDevice-int-int-) | Sağlanan görüntü boyutları, varsayılan çözünürlük (=150) ve maksimum kalite ile {@code JpegDevice} sınıfının yeni bir örneğini başlatır. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-) | Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-) | Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Sayfayı jpeg formatına dönüştürür ve çıktı akışına kaydeder. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Sayfayı jpeg formatına dönüştürür ve çıktı akışına kaydeder. |

### JpegDevice {#JpegDevice--}
```
public JpegDevice()
```

Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır.

### JpegDevice {#JpegDevice-int-}
```
public JpegDevice(int quality)
```

Yeni bir {@code JpegDevice} sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kalite |  | Bir görüntünün sıkıştırma seviyesini belirler. Kalite için kullanılabilir değer aralığı 0 ile 100 arasındadır. Belirtilen sayı ne kadar düşük olursa, sıkıştırma o kadar yüksek olur ve bu da görüntünün kalitesinin daha düşük olmasına neden olur. Sıfır en düşük kaliteyi, 100 ise en yüksek kaliteyi verir. |

### JpegDevice {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```

Sağlanan görüntü boyutları, varsayılan çözünürlük (=150) ve maksimum kalite ile {@code JpegDevice} sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik |  | Görüntü çıkış genişliği. |
| yükseklik |  | Görüntü çıkış yüksekliği. |

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır.

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-}
Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-}
Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
Yeni bir {@code JpegDevice} sınıfı örneğini varsayılan çözünürlük ve maksimum kalite ile başlatır.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Sayfayı jpeg formatına dönüştürür ve çıktı akışına kaydeder.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Sayfayı jpeg formatına dönüştürür ve çıktı akışına kaydeder.

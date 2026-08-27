---
title: "TiffDevice"
linktitle: "TiffDevice"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu sınıf, pdf belge sayfalarını tek bir tiff görüntüsüne sayfa sayfa kaydetmeye yardımcı olur."
type: docs
weight: 210
url: /tr/java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.TiffDevice

```
public final class TiffDevice extends DocumentDevice
```

Bu sınıf, pdf belge sayfalarını tek bir tiff görüntüsüne sayfa sayfa kaydetmeye yardımcı olur.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffDevice](#TiffDevice--) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-int-int-) | Yeni bir {@code TiffDevice} sınıfı örneğini başlatır. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [binarizeBradley](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | Giriş akışı için Bradley ikileştirmesi yapar. |
| [getCropRectangle](#getCropRectangle--) | Resme dönüştürülecek alanı tanımlayan dikdörtgeni al. Varsayılan değer null'dır; bu durumda tüm görüntü bir sayfaya dönüştürülür. |
| [getFormPresentationMode](#getFormPresentationMode--) | Form sunum modunu alır. |
| [getHeight](#getHeight--) | Görüntü çıkış yüksekliğini alır. |
| [getRenderingOptions](#getRenderingOptions--) | Renderleme seçeneklerini alır. |
| [getResolution](#getResolution--) | Görüntü çözünürlüğünü alır. |
| [getSettings](#getSettings--) | PDF'i TIFF görüntüsüne eşlemek için ayarları alır. |
| [getWidth](#getWidth--) | Görüntü çıkış genişliğini alır. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Belirli belge sayfalarını TIFF'e dönüştürür ve çıkış akışına kaydeder. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Belirli belge sayfalarını TIFF'e dönüştürür ve çıkış akışına kaydeder. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Verilen sayfada bazı işlemler gerçekleştirir, örn. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Resme dönüştürülecek alanı tanımlayan dikdörtgeni ayarla. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Form sunum modunu alır. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Renderleme seçeneklerini ayarlar. |

### TiffDevice {#TiffDevice--}
```
public TiffDevice()
```

Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```

Yeni bir {@code TiffDevice} sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik |  | Görüntü çıkış genişliği. |
| yükseklik |  | Görüntü çıkış yüksekliği. |

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Varsayılan ayarlarla {@code TiffDevice} sınıfının yeni bir örneğini başlatır.

### binarizeBradley {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
Giriş akışı için Bradley ikileştirmesi yapar.

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Resme dönüştürülecek alanı tanımlayan dikdörtgeni al. Varsayılan değer null'dır; bu durumda tüm görüntü bir sayfaya dönüştürülür.

**Returns:**
Rectangle nesnesi

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Form sunum modunu alır.

**Returns:**
FormPresentationMode değeri @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

Görüntü çıkış yüksekliğini alır.

**Returns:**
int değer

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Renderleme seçeneklerini alır.

**Returns:**
renderleme seçenekleri.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Görüntü çözünürlüğünü alır.

**Returns:**
Çözünürlük öğesi

### getSettings {#getSettings--}
```
public TiffSettings getSettings()
```

PDF'i TIFF görüntüsüne eşlemek için ayarları alır.

**Returns:**
TiffSettings öğesi

### getWidth {#getWidth--}
```
public int getWidth()
```

Görüntü çıkış genişliğini alır.

**Returns:**
int değer

### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Belirli belge sayfalarını TIFF'e dönüştürür ve çıkış akışına kaydeder.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Belirli belge sayfalarını TIFF'e dönüştürür ve çıkış akışına kaydeder.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Verilen sayfada bazı işlemler gerçekleştirir, örn.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Resme dönüştürülecek alanı tanımlayan dikdörtgeni ayarla.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Form sunum modunu alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Renderleme seçeneklerini ayarlar.

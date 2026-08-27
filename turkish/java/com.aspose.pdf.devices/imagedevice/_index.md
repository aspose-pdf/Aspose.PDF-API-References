---
title: "ImageDevice"
linktitle: "ImageDevice"
second_title: "Aspose.PDF for Java API Referansı"
description: "Görüntü cihazları için soyut bir sınıf."
type: docs
weight: 110
url: /tr/java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice

```
public abstract class ImageDevice extends PageDevice
```

Görüntü cihazları için soyut bir sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageDevice](#ImageDevice--) | Soyut başlatıcı {@code ImageDevice} nesilleri için, çözünürlüğü 150x150 olarak ayarlar. |
| [ImageDevice](#ImageDevice-int-int-) | Sağlanan görüntü boyutları ve varsayılan çözünürlük (=150) ile {@code JpegDevice} sınıfının yeni bir örneğini başlatır. |
| [ImageDevice](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | Soyut başlatıcı {@code ImageDevice} nesilleri için, çözünürlüğü 150x150 olarak ayarlar. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-) | Soyut başlatıcı {@code ImageDevice} nesilleri için, çözünürlüğü 150x150 olarak ayarlar. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Soyut başlatıcı {@code ImageDevice} nesilleri için, çözünürlüğü 150x150 olarak ayarlar. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.devices.Resolution-) | Soyut başlatıcı {@code ImageDevice} nesilleri için, çözünürlüğü 150x150 olarak ayarlar. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitmap](#getBitmap-com.aspose.pdf.Page-) | Sayfayı {@link java.awt.image.BufferedImage} nesnesine dönüştürür. |
| [getCoordinateType](#getCoordinateType--) | Sayfa koordinat tipini alır (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [getCropRectangle](#getCropRectangle--) | Resme dönüştürülecek alanı tanımlayan dikdörtgeni alır. Varsayılan değer null'dur; bu durumda tüm sayfa bir görüntüye dönüştürülür. |
| [getFormPresentationMode](#getFormPresentationMode--) | Form sunum modunu alır. |
| [getHeight](#getHeight--) | Görüntü çıkış yüksekliğini alır. |
| [getRenderingOptions](#getRenderingOptions--) | Renderleme seçeneklerini alır. |
| [getResolution](#getResolution--) | Görüntü çözünürlüğünü alır. |
| [getWidth](#getWidth--) | Görüntü çıkış genişliğini alır. |
| [isShadingPerformanceHigh](#isShadingPerformanceHigh--) | Gölgeleme işlemlerinin performansı Yüksek mi? Varsayılan olarak doğrudur. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Sayfa koordinat tipini ayarlar (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Resme dönüştürülecek alanı tanımlayan dikdörtgeni ayarla. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Form sunum modunu ayarlar. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Renderleme seçeneklerini ayarlar. |
| [setShadingPerformanceHigh](#setShadingPerformanceHigh-boolean-) | Gölgeleme işlemlerinin performansını Yüksek olarak ayarlar veya değil. |

### ImageDevice {#ImageDevice--}
```
public ImageDevice()
```

Soyut başlatıcı {@code ImageDevice} nesilleri için, çözünürlüğü 150x150 olarak ayarlar.

### ImageDevice {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```

Sağlanan görüntü boyutları ve varsayılan çözünürlük (=150) ile {@code JpegDevice} sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik |  | Görüntü çıkış genişliği. |
| yükseklik |  | Görüntü çıkış yüksekliği. |

### ImageDevice {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
Soyut başlatıcı {@code ImageDevice} nesilleri için, çözünürlüğü 150x150 olarak ayarlar.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-}
Soyut başlatıcı {@code ImageDevice} nesilleri için, çözünürlüğü 150x150 olarak ayarlar.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Soyut başlatıcı {@code ImageDevice} nesilleri için, çözünürlüğü 150x150 olarak ayarlar.

### ImageDevice {#ImageDevice-com.aspose.pdf.devices.Resolution-}
Soyut başlatıcı {@code ImageDevice} nesilleri için, çözünürlüğü 150x150 olarak ayarlar.

### getBitmap {#getBitmap-com.aspose.pdf.Page-}
Sayfayı {@link java.awt.image.BufferedImage} nesnesine dönüştürür.

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Sayfa koordinat tipini alır (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır.

**Returns:**
PageCoordinateType öğesi @see PageCoordinateType

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Resme dönüştürülecek alanı tanımlayan dikdörtgeni alır. Varsayılan değer null'dur; bu durumda tüm sayfa bir görüntüye dönüştürülür.

**Returns:**
Rectangle nesnesi

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Form sunum modunu alır.

**Returns:**
FormPresentationMode öğesi @see FormPresentationMode

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
RenderingOptions öğesi

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Görüntü çözünürlüğünü alır.

**Returns:**
Çözünürlük öğesi

### getWidth {#getWidth--}
```
public int getWidth()
```

Görüntü çıkış genişliğini alır.

**Returns:**
int değer

### isShadingPerformanceHigh {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```

Gölgeleme işlemlerinin performansı Yüksek mi? Varsayılan olarak doğrudur.

**Returns:**
boolean değer

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Sayfa koordinat tipini ayarlar (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Resme dönüştürülecek alanı tanımlayan dikdörtgeni ayarla.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Form sunum modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | FormPresentationMode öğesi @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Renderleme seçeneklerini ayarlar.

### setShadingPerformanceHigh {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```

Gölgeleme işlemlerinin performansını Yüksek olarak ayarlar veya değil.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ImageDevice sınıfı. Görüntü cihazları için soyut bir sınıf
type: docs
weight: 3610
url: /tr/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice sınıfı

Görüntü cihazları için soyut bir sınıf.

```csharp
public abstract class ImageDevice : PageDevice
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | `ImageDevice` soyut sınıfı için başlatıcı, çözünürlüğü 150x150 olarak ayarlar. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Sağlanan görüntü boyutları ve varsayılan çözünürlük (=150) ile [`JpegDevice`](../jpegdevice/) sınıfının yeni bir örneğini başlatır. |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | `ImageDevice` soyut sınıfı için başlatıcı. Sonuç görüntü dosyası için çözünürlük, bkz. [`Resolution`](./resolution/) sınıfı. |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Sağlanan görüntü boyutları ve varsayılan çözünürlük (=150) ile [`JpegDevice`](../jpegdevice/) sınıfının yeni bir örneğini başlatır. |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Sağlanan görüntü boyutları ve çözünürlüğü ile [`JpegDevice`](../jpegdevice/) sınıfının yeni bir örneğini başlatır. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Sağlanan görüntü boyutları ve çözünürlüğü ile [`JpegDevice`](../jpegdevice/) sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Sayfa koordinat türünü alır veya ayarlar (Medya/Kırpma kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Form sunum modunu alır veya ayarlar. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Görüntü çıktı yüksekliğini alır. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | İşleme seçeneklerini alır veya ayarlar. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Görüntü çözünürlüğünü alır. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Görüntü çıktı genişliğini alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Verilen sayfa üzerinde bazı işlemler gerçekleştirir, örneğin sayfayı grafik görüntüsüne dönüştürür. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Verilen sayfa üzerinde bazı işlemler gerçekleştirir ve sonuçları dosyaya kaydeder. |

### Ayrıca Bakınız

* sınıf [PageDevice](../pagedevice/)
* ad alanı [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* derleme [Aspose.PDF](../../)
---
title: Class ThumbnailDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ThumbnailDevice sınıfı. PDF belge sayfalarını Thumbnail görüntü olarak kaydeden görüntü cihazını temsil eder.
type: docs
weight: 3690
url: /tr/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice sınıfı

PDF belge sayfalarını Thumbnail görüntü olarak kaydeden görüntü cihazını temsil eder.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Thumbnail görüntü için varsayılan boyut (200x200 piksel) ile `ThumbnailDevice` sınıfının yeni bir örneğini başlatır. |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | `ThumbnailDevice` sınıfının yeni bir örneğini başlatır. |

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
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Sayfayı thumbnail görüntü png'ye dönüştürür ve çıktı akışında kaydeder. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Verilen sayfa üzerinde bazı işlemler gerçekleştirir ve sonuçları dosyaya kaydeder. |

### Ayrıca Bakınız

* sınıf [ImageDevice](../imagedevice/)
* ad alanı [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* derleme [Aspose.PDF](../../)
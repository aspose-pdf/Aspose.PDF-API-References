---
title: EmfDevice
second_title: Aspose.PDF for .NET API Referansı
description: Pdf belge sayfalarını emfye kaydetmeye yardımcı olan görüntü aygıtını temsil eder.
type: docs
weight: 1680
url: /tr/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

Pdf belge sayfalarını emf'ye kaydetmeye yardımcı olan görüntü aygıtını temsil eder.

```csharp
public sealed class EmfDevice : ImageDevice
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfDevice](emfdevice#constructor)() | Yeni bir örneğini başlatır[`EmfDevice`](../emfdevice) emf. 'ye yazılan raster görüntünün varsayılan çözünürlüğüne sahip sınıf |
| [EmfDevice](emfdevice#constructor_2)(PageSize) | Yeni bir örneğini başlatır[`EmfDevice`](../emfdevice) emf (=150) 'ye yazılan raster görüntü için sağlanan sayfa boyutu, ve varsayılan çözünürlük ile sınıf |
| [EmfDevice](emfdevice#constructor_1)(Resolution) | Yeni bir örneğini başlatır[`EmfDevice`](../emfdevice) sınıf.  emf'ye yazılan raster görüntü için çözünürlük, bkz.[`Resolution`](../resolution) sınıf. |
| [EmfDevice](emfdevice#constructor_4)(int, int) | Yeni bir örneğini başlatır[`EmfDevice`](../emfdevice) emf (=150) 'ye yazılan raster görüntü için sağlanan görüntü boyutları, ve varsayılan çözünürlük ile sınıf |
| [EmfDevice](emfdevice#constructor_3)(PageSize, Resolution) | Yeni bir örneğini başlatır[`JpegDevice`](../jpegdevice)emf. öğesine yazılan tarama görüntüsü için sağlanan sayfa boyutu, ve çözünürlük ile sınıf |
| [EmfDevice](emfdevice#constructor_5)(int, int, Resolution) | Yeni bir örneğini başlatır[`JpegDevice`](../jpegdevice) emf. öğesine yazılan raster görüntü için sağlanan görüntü boyutları, ve çözünürlük ile sınıf |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype) { get; set; } | Sayfa koordinat türünü alır veya ayarlar (Medya/Kırpma kutuları). CropBox değeri varsayılan olarak kullanılır. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode) { get; set; } | Form sunum modunu alır veya ayarlar. |
| [Height](../../aspose.pdf.devices/imagedevice/height) { get; } | Görüntü çıktı yüksekliğini alır. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions) { get; set; } | Oluşturma seçeneklerini alır veya ayarlar. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution) { get; } | Görüntü çözünürlüğünü alır. |
| [Width](../../aspose.pdf.devices/imagedevice/width) { get; } | Görüntü çıktı genişliğini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Process](../../aspose.pdf.devices/emfdevice/process#process)(Page, Stream) | Sayfayı emf'ye dönüştürür ve çıktı akışına kaydeder. |
| [Process](../../aspose.pdf.devices/pagedevice/process)(Page, string) | Verilen sayfada bazı işlemler gerçekleştirir ve sonuçları dosyaya kaydeder. |

### Ayrıca bakınız

* class [ImageDevice](../imagedevice)
* ad alanı [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->

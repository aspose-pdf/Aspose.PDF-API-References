---
title: Class DicomDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.DicomDevice sınıfı. PDF belge sayfalarını Dicom formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder.
type: docs
weight: 3560
url: /tr/net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice Sınıfı

PDF belge sayfalarını Dicom formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Varsayılan çözünürlük ile `DicomDevice` sınıfının yeni bir örneğini başlatır. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Sağlanan sayfa boyutu ile varsayılan çözünürlük (=150) ile `DicomDevice` sınıfının yeni bir örneğini başlatır. |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | `DicomDevice` sınıfının yeni bir örneğini başlatır. Sonuç görüntü dosyası için çözünürlük, [`Resolution`](../resolution/) sınıfına bakın. |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Sağlanan görüntü boyutları ile varsayılan çözünürlük (=150) ile `DicomDevice` sınıfının yeni bir örneğini başlatır. |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Sağlanan sayfa boyutu ve çözünürlük ile `DicomDevice` sınıfının yeni bir örneğini başlatır. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Sağlanan görüntü boyutları ve çözünürlük ile `DicomDevice` sınıfının yeni bir örneğini başlatır. |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Sayfayı Dicom'a dönüştürür ve çıktıyı akışa kaydeder. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Verilen sayfa üzerinde bazı işlemler gerçekleştirir ve sonuçları dosyaya kaydeder. |

### Ayrıca Bakınız

* sınıf [ImageDevice](../imagedevice/)
* ad alanı [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* derleme [Aspose.PDF](../../)
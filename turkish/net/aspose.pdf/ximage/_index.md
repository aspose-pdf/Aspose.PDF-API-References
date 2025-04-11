---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XImage sınıfı. Resim XObject'i temsil eden sınıf
type: docs
weight: 11350
url: /tr/net/aspose.pdf/ximage/
---
## XImage sınıfı

Resim X-Object'i temsil eden sınıf.

```csharp
public sealed class XImage
```

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Resim transparan içeriyorsa true; aksi takdirde false döner. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Resim filtre türünü alır. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Resmin gri tonlamalı versiyonunu alır. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Resmin yüksekliğini alır. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Resmin bir resim maskesi olarak muamele edilip edilmeyeceğini belirten bir bayrak alır (bkz. 8.9.6, "Maskelenmiş Resimler"). Bu bayrak true ise, BitsPerComponent değeri 1 olmalı ve Mask ve ColorSpace belirtilmemelidir; maskelenmemiş alanlar mevcut nonstroking renk ile boyanmalıdır. Varsayılan değer: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Resmin meta verileri. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Resim adını alır veya ayarlar. Lütfen, sayfa içeriklerinde referansları olan bir resmin adını değiştirirseniz, belgenin yanlış hale gelebileceğini unutmayın. Bu durumda XImage.Rename yöntemini kullanın. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Resmin genişliğini alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | XImage'e bir stencil maskesi ekler. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Resmin renk türünü döner. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Koleksiyonundaki resmin adını döner. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Kaynak resimden ham resim verilerini alır. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Her iki resim aynı nesneye referans veriyorsa true döner. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Resmi yeniden adlandırır ve resmi yeni ad ile tüm referansları değiştirir. |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Resim verilerini akışa JPEG resmi olarak kaydeder. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Resmi istenen formatta akışa kaydeder. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Belirtilen çözünürlükte JPEG resmi olarak akışa resim verilerini kaydeder. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Belirtilen çözünürlükte istenen formatta akışa resmi kaydeder. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Orijinal resim akışını döner. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)
---
title: XImage
second_title: Aspose.PDF for .NET API Referansı
description: X-Object görüntüsünü temsil eden sınıf.
type: docs
weight: 7400
url: /tr/net/aspose.pdf/ximage/
---
## XImage class

X-Object görüntüsünü temsil eden sınıf.

```csharp
public sealed class XImage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency) { get; } | Görüntü, true döndürmekten daha şeffaflık içeriyorsa; aksi takdirde, false. |
| [FilterType](../../aspose.pdf/ximage/filtertype) { get; } | Görüntü filtresi türünü alır. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled) { get; } | Resmin gri tonlamalı sürümünü alır. |
| [Height](../../aspose.pdf/ximage/height) { get; } | Resmin yüksekliğini alır. |
| [Metadata](../../aspose.pdf/ximage/metadata) { get; } | Resmin meta verileri. |
| [Name](../../aspose.pdf/ximage/name) { get; set; } | Görüntü adını alır veya ayarlar. Sayfa içeriğinde referansları olan görselin adını değiştirirseniz belgenin hatalı olabileceğini lütfen unutmayınız. Lütfen bu durumda XImage.Rename yöntemini kullanın. |
| [Width](../../aspose.pdf/ximage/width) { get; } | Resmin genişliğini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [GetColorType](../../aspose.pdf/ximage/getcolortype)() | Resmin renk türünü döndürür. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection)() | ints koleksiyonundaki görüntünün adını döndürür. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject)(XImage) | Her iki görüntü de aynı nesneye başvuruyorsa true değerini döndürür. |
| [Rename](../../aspose.pdf/ximage/rename)(string) | Resmi yeniden adlandırır ve resme yapılan tüm referansları yeni ad ile değiştirir |
| [Save](../../aspose.pdf/ximage/save#save)(Stream) | Görüntü verilerini akışa JPEG görüntüsü olarak kaydeder. |
| [Save](../../aspose.pdf/ximage/save#save_2)(Stream, ImageFormat) | Görüntüyü istenen formatta akışa kaydeder. |
| [Save](../../aspose.pdf/ximage/save#save_1)(Stream, int) | Görüntü verilerini belirtilen çözünürlükte JPEG görüntüsü olarak akışa kaydeder. |
| [Save](../../aspose.pdf/ximage/save#save_3)(Stream, ImageFormat, int) | Görüntüyü belirtilen çözünürlükte istenen formatta akışa kaydeder. |
| [ToStream](../../aspose.pdf/ximage/tostream)() | Orijinal görüntü akışını döndürür. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype)(Bitmap) | Resmin renk türünü döndürür. |

### Ayrıca bakınız

* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->

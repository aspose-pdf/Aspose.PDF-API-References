---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacementAbsorber sınıfı. Görüntü yerleştirme nesnelerinin bir emici nesnesini temsil eder. Görüntü kullanımlarını arar ve arama sonuçlarına [`ImagePlacements`](./imageplacements/) koleksiyonu aracılığıyla erişim sağlar.
type: docs
weight: 5910
url: /tr/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber sınıfı

Görüntü yerleştirme nesnelerinin bir emici nesnesini temsil eder. Görüntü kullanımlarını arar ve arama sonuçlarına [`ImagePlacements`](./imageplacements/) koleksiyonu aracılığıyla erişim sağlar.

```csharp
public sealed class ImagePlacementAbsorber
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | [`ImagePlacement`](../imageplacement/) nesneleri ile sunulan görüntü yerleştirme olaylarının koleksiyonunu alır. |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Ayrıştırma işlemleri koleksiyonu için yalnızca okunur modu alır/ayarlar. Bellek yetersizliği istisnalarına karşı yardımcı olabilir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Belirtilen belgede arama yapar. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Belirtilen sayfada arama yapar. |

## Açıklamalar

`ImagePlacementAbsorber` nesnesi esasen görüntü arama senaryosunda kullanılır. Arama tamamlandığında, olaylar [`ImagePlacement`](../imageplacement/) nesneleri ile temsil edilir ve [`ImagePlacements`](./imageplacements/) koleksiyonunu içerir. [`ImagePlacement`](../imageplacement/) nesnesi, görüntü yerleştirme özelliklerine erişim sağlar: boyutlar, çözünürlük vb. Görüntü pozitif rotasyonu saat yönünün tersine, sayfa için ise saat yönündedir. Burada, görüntü döndürme açısını temsil etmemiz gerekiyor, bu nedenle sayfa açısını görüntü açısından çıkarıyoruz.

## Örnekler

Örnek, ilk PDF belgesi sayfasındaki görüntüleri bulmayı ve görüntü yerleştirme özelliklerini almayı gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Display image placement properties for all placements
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{     
    Console.Out.WriteLine("image width:" + imagePlacement.Rectangle.Width);
    Console.Out.WriteLine("image height:" + imagePlacement.Rectangle.Height);
    Console.Out.WriteLine("image LLX:" + imagePlacement.Rectangle.LLX);
    Console.Out.WriteLine("image LLY:" + imagePlacement.Rectangle.LLY);
    Console.Out.WriteLine("image horizontal resolution:" + imagePlacement.Resolution.X);
    Console.Out.WriteLine("image vertical resolution:" + imagePlacement.Resolution.Y);
}
```

### Ayrıca Bakınız

* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)
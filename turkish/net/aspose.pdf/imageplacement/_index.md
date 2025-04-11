---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacement sınıfı. Pdf belge sayfasına yerleştirilen bir resmin özelliklerini temsil eder.
type: docs
weight: 5900
url: /tr/net/aspose.pdf/imageplacement/
---
## ImagePlacement sınıfı

Pdf belge sayfasına yerleştirilen bir resmin özelliklerini temsil eder.

```csharp
public sealed class ImagePlacement
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Sayfaya yerleştirilen resim için aktif grafik durumunun bileşim parametrelerini alır. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | İlgili XImage kaynak nesnesini alır. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Bu resim için mevcut dönüşüm matrisini alır. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Resmi görüntülemek için kullanılan operatörü alır. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Resmi içeren sayfayı alır. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Resmin dikdörtgenini alır. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Resmin çözünürlüğünü alır. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Resmin döndürme açısını alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Resmi sayfadan siler. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Koleksiyondaki resmi başka bir resimle değiştirir. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Resmi ilgili dönüşümlerle kaydeder: ölçeklendirme, döndürme ve çözünürlük. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Resmi ilgili dönüşümlerle kaydeder: ölçeklendirme, döndürme ve çözünürlük. |

## Açıklamalar

Bir resim bir sayfaya yerleştirildiğinde, [`Resources`](../resources/) içinde tanımlanan fiziksel boyutlardan farklı boyutlara sahip olabilir. `ImagePlacement` nesnesi, boyutlar, çözünürlük gibi bilgileri sağlamak için tasarlanmıştır.

## Örnekler

Örnek, ilk PDF belge sayfasındaki resimleri bulmayı ve görünür boyutlarla bitmap olarak almayı göstermektedir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Retrieve images with visible dimensions
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Retrieve image from resources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Create new bitmap with actual dimensions
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)
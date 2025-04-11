---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.ImagePlacement. تمثل خصائص الصورة الموضوعة في صفحة مستند Pdf
type: docs
weight: 5900
url: /ar/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

تمثل خصائص الصورة الموضوعة في صفحة مستند Pdf.

```csharp
public sealed class ImagePlacement
```

## Properties

| Name | Description |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | يحصل على معلمات التركيب لحالة الرسومات النشطة للصورة الموضوعة على الصفحة. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | يحصل على كائن مورد XImage المرتبط. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | مصفوفة التحويل الحالية لهذه الصورة. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | المشغل المستخدم لعرض الصورة. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | يحصل على الصفحة التي تحتوي على الصورة. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | يحصل على مستطيل الصورة. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | يحصل على دقة الصورة. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | يحصل على زاوية دوران الصورة. |

## Methods

| Name | Description |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | يحذف الصورة من الصفحة. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | يستبدل الصورة في المجموعة بصورة أخرى. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | يحفظ الصورة مع التحويلات المقابلة: التحجيم، الدوران والدقة. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | يحفظ الصورة مع التحويلات المقابلة: التحجيم، الدوران والدقة. |

## Remarks

عند وضع صورة على صفحة، قد تكون لها أبعاد غير الأبعاد الفيزيائية المحددة في [`Resources`](../resources/). الكائن `ImagePlacement` مصمم لتوفير مثل هذه المعلومات مثل الأبعاد والدقة وما إلى ذلك.

## Examples

المثال يوضح كيفية العثور على الصور في الصفحة الأولى من مستند PDF والحصول على الصور كصور نقطية بأبعاد مرئية.

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

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)
---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.ImagePlacementAbsorber. تمثل كائن ماص لكائنات وضع الصورة. تقوم بالبحث عن استخدامات الصور وتوفر الوصول إلى نتائج البحث عبر مجموعة ImagePlacements
type: docs
weight: 5910
url: /ar/net/aspose.pdf/imageplacementabsorber/
---
## فئة ImagePlacementAbsorber

تمثل كائن ماص لكائنات وضع الصورة. تقوم بالبحث عن استخدامات الصور وتوفر الوصول إلى نتائج البحث عبر مجموعة [`ImagePlacements`](./imageplacements/) .

```csharp
public sealed class ImagePlacementAbsorber
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | يحصل على مجموعة من حالات وضع الصورة التي يتم تقديمها مع كائنات [`ImagePlacement`](../imageplacement/) . |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | يحصل على/يحدد وضع القراءة فقط لمجموعة عمليات التحليل. قد يساعد ذلك في تجنب استثناءات نفاد الذاكرة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | يقوم بالبحث في المستند المحدد. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | يقوم بالبحث في الصفحة المحددة. |

## ملاحظات

يتم استخدام كائن `ImagePlacementAbsorber` بشكل أساسي في سيناريو بحث الصور. عند الانتهاء من البحث، يتم تمثيل الحالات مع كائنات [`ImagePlacement`](../imageplacement/) التي تحتوي عليها مجموعة [`ImagePlacements`](./imageplacements/). يوفر كائن [`ImagePlacement`](../imageplacement/) الوصول إلى خصائص وضع الصورة: الأبعاد، الدقة، إلخ. دوران الصورة الإيجابي يكون عكس عقارب الساعة، بينما بالنسبة للصفحة، يكون مع عقارب الساعة. هنا، نحتاج إلى تمثيل زاوية دوران الصورة، لذا نقوم بطرح زاوية الصفحة من زاوية الصورة.

## أمثلة

توضح المثال كيفية العثور على الصور في الصفحة الأولى من مستند PDF والحصول على خصائص وضع الصورة.

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

### انظر أيضًا

* مساحة الاسم [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)
---
title: "الفئة ImagePlacementAbsorber"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.ImagePlacementAbsorber. تمثل كائن ماص لأجسام وضع الصور. يقوم بالبحث عن استخدامات الصور ويوفر الوصول إلى نتائج البحث عبر مجموعة ImagePlacements."
type: docs
weight: 6040
url: /ar/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class

تمثل كائن ماص لأجسام وضع الصور. يقوم بالبحث عن استخدامات الصور ويوفر الوصول إلى نتائج البحث عبر مجموعة [`ImagePlacements`](./imageplacements/).

```csharp
public sealed class ImagePlacementAbsorber
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | يحصل على مجموعة من حالات وضع الصورة التي تُعرض باستخدام كائنات [`ImagePlacement`](../imageplacement/). |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | يحصل/يضبط وضع القراءة فقط لمجموعة عمليات التحليل. قد يساعد ذلك في تجنب استثناءات نفاد الذاكرة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | ينفّذ البحث على المستند المحدد. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | ينفّذ البحث على الصفحة المحددة. |

## ملاحظات

كائن `ImagePlacementAbsorber` يُستخدم أساسًا في سيناريو البحث عن الصور. عند اكتمال البحث يتم تمثيل الحالات بكائنات [`ImagePlacement`](../imageplacement/) التي يحتويها مجموعة [`ImagePlacements`](./imageplacements/). يوفر كائن [`ImagePlacement`](../imageplacement/) إمكانية الوصول إلى خصائص وضع الصورة: الأبعاد، الدقة، إلخ. دوران الصورة الإيجابي يكون عكس اتجاه عقارب الساعة، أما للصفحة فيكون مع اتجاه عقارب الساعة. هنا، نحتاج إلى تمثيل زاوية دوران الصورة، لذا نطرح زاوية الصفحة من زاوية الصورة.

## أمثلة

يوضح المثال كيفية العثور على الصور في الصفحة الأولى من مستند PDF والحصول على خصائص وضع الصورة.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن ImagePlacementAbsorber لإجراء بحث عن وضع الصورة
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(abs);

// عرض خصائص وضع الصورة لجميع المواضعات.
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

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)



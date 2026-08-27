---
title: "الفئة ImagePlacement"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.ImagePlacement. تمثل خصائص صورة موضوعة في صفحة مستند Pdf"
type: docs
weight: 6030
url: /ar/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

يمثل خصائص صورة موضوعة في صفحة مستند Pdf.

```csharp
public sealed class ImagePlacement
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | يحصل على معلمات التركيب لحالة الرسومات النشطة للصورة الموضوعة في الصفحة. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | يحصل على كائن مورد XImage المرتبط. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | مصفوفة التحويل الحالية لهذه الصورة. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | المعامل المستخدم لعرض الصورة. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | يحصل على الصفحة التي تحتوي على الصورة. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | يحصل على مستطيل الصورة. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | يحصل على دقة الصورة. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | يحصل على زاوية دوران الصورة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | حذف الصورة من الصفحة. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | استبدل الصورة في المجموعة بصورة أخرى. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | يحفظ الصورة مع التحولات المقابلة: التحجيم، الدوران والدقة. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | يحفظ الصورة مع التحولات المقابلة: التحجيم، الدوران والدقة. |

## ملاحظات

عند وضع صورة على صفحة قد تكون أبعادها مختلفة عن الأبعاد الفيزيائية المحددة في [`Resources`](../resources/). الكائن `ImagePlacement` يهدف إلى توفير مثل هذه المعلومات مثل الأبعاد، الدقة وما إلى ذلك.

## أمثلة

يوضح المثال كيفية العثور على الصور في الصفحة الأولى من مستند PDF والحصول على الصور كصور نقطية بأبعاد مرئية.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن ImagePlacementAbsorber لإجراء بحث عن وضع الصورة
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(abs);

// استرجاع الصور بأبعاد مرئية
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // استرجاع الصورة من الموارد
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // إنشاء صورة نقطية جديدة بالأبعاد الفعلية
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)



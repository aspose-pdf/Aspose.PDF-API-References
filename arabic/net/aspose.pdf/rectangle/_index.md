---
title: Class Rectangle
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Rectangle. تمثل الفئة مستطيل
type: docs
weight: 9750
url: /ar/net/aspose.pdf/rectangle/
---
## فئة المستطيل

تمثل الفئة مستطيل.

```csharp
public sealed class Rectangle : ICloneable
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | مُنشئ المستطيل. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | مستطيل فارغ |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | يُهيئ مستطيل تافه أي مستطيل بموقع وحجم صفر. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | ارتفاع المستطيل. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | يتحقق مما إذا كان المستطيل فارغًا. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | يتحقق مما إذا كان المستطيل نقطة أي أن LLX يساوي URX و LLY يساوي URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | يتحقق مما إذا كان المستطيل تافهًا أي له حجم وموقع صفر. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | إحداثي X للزاوية السفلى اليسرى. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | إحداثي Y للزاوية السفلى اليسرى. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | إحداثي X للزاوية العليا اليمنى. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | إحداثي Y للزاوية العليا اليمنى. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | عرض المستطيل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | يُهيئ مستطيل جديد من مثيل مُعطى من System.Drawing.Rectangle. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | يُهيئ مستطيل جديد من مثيل مُعطى من System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | يحاول تحليل السلسلة واستخراج مكونات المستطيل منها llx، lly، urx، ury. |
| [Center](../../aspose.pdf/rectangle/center/)() | يُرجع إحداثيات مركز المستطيل. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | يُنسخ كائن المستطيل. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | يحدد ما إذا كانت النقطة المعطاة داخل المستطيل. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | يحدد ما إذا كان المستطيل يحتوي على خط ممثل بنقطتين. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | يحدد ما إذا كانت النقطة المعطاة موجودة داخل المستطيل. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | يتحقق مما إذا كانت المستطيلات متساوية أي لها نفس الموقع والأحجام. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | يتقاطع مع المستطيلات. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | يحدد ما إذا كان هذا المستطيل يتقاطع مع مستطيل آخر. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | ينضم إلى المستطيلات. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | ينقل المستطيل بواسطة دلتا المحددة. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | يتحقق مما إذا كانت المستطيلات متقاربة في التساوي أي لها نفس الموقع والأحجام تقريبًا (حتى دلتا). |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | يدور المستطيل بالزاوية المحددة. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | يدور المستطيل بالزاوية المحددة. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | يحول المستطيل إلى مصفوفة من النقاط ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | يحول المستطيل إلى مثيل من System.Drawing.Rectangle. يتم تقليم المواقع والأحجام العائمة. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | يحصل على تمثيل سلسلة للمستطيل. |

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)
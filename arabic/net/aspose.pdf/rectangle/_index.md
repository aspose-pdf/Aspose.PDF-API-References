---
title: "الفئة Rectangle"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Rectangle. الفئة تمثل مستطيل"
type: docs
weight: 9900
url: /ar/net/aspose.pdf/rectangle/
---
## Rectangle class

الفئة تمثل مستطيل.

```csharp
public sealed class Rectangle : ICloneable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | منشئ Rectangle. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | مستطيل فارغ |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | يُنشئ مستطيلًا بسيطًا أي مستطيل بموقع وحجم صفر. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | ارتفاع المستطيل. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | يتحقق مما إذا كان المستطيل فارغًا. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | يتحقق مما إذا كان المستطيل نقطة أي أن LLX يساوي URX و LLY يساوي URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | يتحقق مما إذا كان المستطيل بسيطًا أي أنه لا يمتلك حجمًا أو موضعًا. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | الإحداثي X للزاوية السفلية اليسرى. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | الإحداثي Y للزاوية السفلية اليسرى. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | الإحداثي X للزاوية العليا اليمنى. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | الإحداثي Y للزاوية العليا اليمنى. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | عرض المستطيل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | يُنشئ مستطيلًا جديدًا من نسخة معطاة من System.Drawing.Rectangle. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | يُنشئ مستطيلًا جديدًا من نسخة معطاة من System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | حاول تحليل السلسلة واستخراج مكوّنات المستطيل llx و lly و urx و ury منها. |
| [Center](../../aspose.pdf/rectangle/center/)() | يرجع إحداثيات مركز المستطيل. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | ينسخ كائن Rectangle. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | يحدد ما إذا كانت النقطة المعطاة داخل المستطيل. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | يحدد ما إذا كان المستطيل يحتوي على خط ممثل بنقطتين. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | يحدد ما إذا كانت النقطة المعطاة موجودة داخل المستطيل. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | تحقق مما إذا كان المستطيلان متساويين أي لهما نفس الموضع والحجم. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | يتقاطع مع المستطيلات. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | يحدد ما إذا كان هذا المستطيل يتقاطع مع مستطيل آخر. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | يجمع المستطيلات. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | يُحرك المستطيل بالتحولات المحددة. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | تحقق مما إذا كان المستطيلان متقاربين تقريبًا أي لهما موضعًا وحجمًا متقاربًا (حتى دلتا). |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | يدور المستطيل بالزاوية المحددة. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | يدور المستطيل بالزاوية المحددة. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | يحوّل المستطيل إلى مصفوفة من النقاط ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | يحوّل المستطيل إلى نسخة من System.Drawing.Rectangle. يتم تقصير المواضع والأحجام ذات الفاصلة العائمة. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | يحصل على تمثيل السلسلة للمستطيل. |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)



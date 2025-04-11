---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Stamp. فئة مجردة لمختلف أنواع الطوابع التي تأتي كأبناء
type: docs
weight: 10130
url: /ar/net/aspose.pdf/stamp/
---
## فئة الطابع

فئة مجردة لمختلف أنواع الطوابع التي تأتي كأبناء.

```csharp
public abstract class Stamp
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [الخلفية](../../aspose.pdf/stamp/background/) { get; set; } | تعيين أو الحصول على قيمة بوليانية تشير إلى أن المحتوى تم ختمه كخلفية. إذا كانت القيمة صحيحة، يتم وضع محتوى الطابع في الأسفل. بشكل افتراضي، تكون القيمة خاطئة، يتم وضع محتوى الطابع في الأعلى. |
| [هامش السفلي](../../aspose.pdf/stamp/bottommargin/) { get; set; } | الحصول على أو تعيين الهامش السفلي للطابع. |
| virtual [الارتفاع](../../aspose.pdf/stamp/height/) { get; set; } | الارتفاع المرغوب للطابع على الصفحة. |
| [محاذاة أفقية](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | الحصول على أو تعيين المحاذاة الأفقية للطابع على الصفحة. |
| [هامش الأيسر](../../aspose.pdf/stamp/leftmargin/) { get; set; } | الحصول على أو تعيين الهامش الأيسر للطابع. |
| [الشفافية](../../aspose.pdf/stamp/opacity/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى شفافية الطابع. القيمة تتراوح من 0.0 إلى 1.0. بشكل افتراضي، تكون القيمة 1.0. |
| [شفافية الحدود](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى شفافية حدود الطابع. القيمة تتراوح من 0.0 إلى 1.0. بشكل افتراضي، تكون القيمة 1.0. |
| [عرض الحدود](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | الحصول على أو تعيين قيمة عرض حدود الطابع. بشكل افتراضي، تكون القيمة 1.0. |
| [هامش الأيمن](../../aspose.pdf/stamp/rightmargin/) { get; set; } | الحصول على أو تعيين الهامش الأيمن للطابع. |
| [تدوير](../../aspose.pdf/stamp/rotate/) { get; set; } | تعيين أو الحصول على تدوير محتوى الطابع وفقًا لقيم [`Rotation`](../rotation/). ملاحظة. هذه الخاصية مخصصة لتعيين الزوايا التي هي مضاعفات 90 درجة (0، 90، 180، 270 درجة). لتعيين زاوية عشوائية، استخدم خاصية RotateAngle. إذا كانت الزاوية المعينة بواسطة ArbitraryAngle ليست مضاعفًا لـ 90، فإن خاصية Rotate تعيد Rotation.None. |
| [زاوية التدوير](../../aspose.pdf/stamp/rotateangle/) { get; set; } | الحصول على أو تعيين زاوية التدوير للطابع بالدرجات. هذه الخاصية تسمح بتعيين زاوية تدوير عشوائية. |
| [هامش العلوي](../../aspose.pdf/stamp/topmargin/) { get; set; } | الحصول على أو تعيين الهامش العلوي للطابع. |
| [محاذاة عمودية](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | الحصول على أو تعيين المحاذاة العمودية للطابع على الصفحة. |
| virtual [العرض](../../aspose.pdf/stamp/width/) { get; set; } | العرض المرغوب للطابع على الصفحة. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | إحداثي الطابع الأفقي، بدءًا من اليسار. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | إحداثي الطابع العمودي، بدءًا من الأسفل. |
| [تكبير](../../aspose.pdf/stamp/zoom/) { get; set; } | عامل تكبير الطابع. يسمح بتغيير حجم الطابع. يرجى ملاحظة أن زوج الخصائص ZoomX و ZoomY يسمح بتعيين عامل التكبير لكل محور بشكل منفصل. تعيين هذه الخاصية يغير كل من خصائص ZoomX و ZoomY. إذا كانت ZoomX و ZoomY مختلفتين، فإن خاصية Zoom تعيد قيمة ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | عامل التكبير الأفقي للطابع. يسمح بتغيير حجم الطابع أفقيًا. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | عامل التكبير العمودي للطابع. يسمح بتغيير حجم الطابع عموديًا. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | يعيد معرف الطابع. |
| abstract [Put](../../aspose.pdf/stamp/put/)(Page) | يضيف الطابع على الصفحة. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | يعين معرف الطابع. |

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)
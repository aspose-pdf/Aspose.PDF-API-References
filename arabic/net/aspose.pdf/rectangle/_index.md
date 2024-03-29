---
title: Rectangle
second_title: Aspose.PDF لمرجع .NET API
description: الفئة تمثل المستطيل .
type: docs
weight: 6190
url: /ar/net/aspose.pdf/rectangle/
---
## Rectangle class

الفئة تمثل المستطيل .

```csharp
public sealed class Rectangle : ICloneable
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Rectangle](rectangle)(double, double, double, double) | منشئ المستطيل . |

## الخصائص

| اسم | وصف |
| --- | --- |
| static [Trivial](../../aspose.pdf/rectangle/trivial) { get; } | يقوم بتهيئة مستطيل تافه أي مستطيل به موضع وحجم صفر. |
| [Height](../../aspose.pdf/rectangle/height) { get; } | ارتفاع المستطيل . |
| [IsEmpty](../../aspose.pdf/rectangle/isempty) { get; } | للتحقق مما إذا كان المستطيل فارغًا. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint) { get; } | للتحقق مما إذا كان المستطيل هو النقطة ، أي أن LLX يساوي URX و LLY يساوي URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial) { get; } | للتحقق مما إذا كان المستطيل تافهًا ، أي أن حجمه وموضعه صفر. |
| [LLX](../../aspose.pdf/rectangle/llx) { get; set; } | إحداثيات X للزاوية اليسرى السفلية. |
| [LLY](../../aspose.pdf/rectangle/lly) { get; set; } | Y - تنسيق الزاوية اليسرى السفلية . |
| [URX](../../aspose.pdf/rectangle/urx) { get; set; } | X - تنسيق الزاوية اليمنى العلوية . |
| [URY](../../aspose.pdf/rectangle/ury) { get; set; } | Y - تنسيق الركن الأيمن العلوي. |
| [Width](../../aspose.pdf/rectangle/width) { get; } | عرض المستطيل . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect)(Rectangle) | يقوم بتهيئة مستطيل جديد من مثيل معين لـ System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse)(string) | حاول تحليل السلسلة واستخراج مكونات المستطيل منها llx ، lly ، urx ، ury. |
| [Center](../../aspose.pdf/rectangle/center)() | إرجاع إحداثيات مركز المستطيل. |
| [Clone](../../aspose.pdf/rectangle/clone)() | استنساخ الكائن المستطيل. |
| [Contains](../../aspose.pdf/rectangle/contains)(Point) | لتحديد ما إذا كانت نقطة معينة داخل المستطيل. |
| [Equals](../../aspose.pdf/rectangle/equals#equals)(Rectangle) | تحقق مما إذا كانت المستطيلات متساوية ، أي لها نفس الموضع والأحجام. |
| [Intersect](../../aspose.pdf/rectangle/intersect)(Rectangle) | يتقاطع مع المستطيلات. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect)(Rectangle) | لتحديد ما إذا كان هذا المستطيل يتقاطع مع مستطيل آخر. |
| [Join](../../aspose.pdf/rectangle/join)(Rectangle) | ربط المستطيلات . |
| [NearEquals](../../aspose.pdf/rectangle/nearequals)(Rectangle, double) | تحقق مما إذا كانت المستطيلات متساوية تقريبًا ، أي لها نفس الموضع والأحجام تقريبًا (حتى دلتا). |
| [Rotate](../../aspose.pdf/rectangle/rotate#rotate_1)(int) | تدوير المستطيل بالزاوية المحددة. |
| [Rotate](../../aspose.pdf/rectangle/rotate#rotate)(Rotation) | تدوير المستطيل بالزاوية المحددة. |
| [ToPoints](../../aspose.pdf/rectangle/topoints)() | تحويل المستطيل إلى مصفوفة من النقاط ("النقاط الرباعية") . |
| [ToRect](../../aspose.pdf/rectangle/torect)() | تحويل المستطيل إلى مثيل System.Drawing.Rectangle. يتم اقتطاع مواضع النقطة العائمة وحجمها. |
| override [ToString](../../aspose.pdf/rectangle/tostring)() | يحصل على تمثيل سلسلة المستطيل . |

## مجالات

| اسم | وصف |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty) | مستطيل فارغ |

### أنظر أيضا

* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->

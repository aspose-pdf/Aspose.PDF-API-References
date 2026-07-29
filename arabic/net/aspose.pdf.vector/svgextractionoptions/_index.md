---
title: "الفئة SvgExtractionOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Vector.SvgExtractionOptions. تمثل فئة خيارات لاستخراج الرسومات المتجهة من صفحة مستند pdf."
type: docs
weight: 11430
url: /ar/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class

يمثل فئة خيارات لاستخراج الرسومات المتجهة من صفحة مستند pdf.

```csharp
public class SvgExtractionOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | يحصل أو يعيّن الخيار لتجميع الـ subpaths تلقائيًا إلى صور. هذا الخيار يستثني خيار [`GroupStrength`](./groupstrength/). |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | يحصل أو يعيّن الخيار لاستخراج كل subpath من مستند PDF إلى صور SVG منفصلة. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | يحصل أو يعيّن المستطيل المحيط الذي يحدد منطقة الاستخراج لاستخراج SVG. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | يحصل أو يعيّن خيار قوة تجميع الـ subpaths إلى صور. يسمح لك بتكوين درجة تجميع الـ subpaths. تتراوح القيمة من 0 إلى 1. القيمة 0 تعني تمكين خيار [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/). القيمة 1 ستنشئ صورة واحدة لجميع المسارات المتجهة على الصفحة. يكون لهذا الخيار تأثير عندما يكون [`AutoGrouping`](./autogrouping/) غير مفعّل. القيمة الافتراضية هي `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | يحصل أو يعيّن الحد الأدنى لعرض الخط الذي سيُستخدم في SVG الناتج. إذا كان PDF يستخدم عرض خط أرق، سيتم استبداله بهذا العرض. القيمة الافتراضية هي 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | يحصل أو يعيّن خيارًا لتحديد ما إذا كان يتم فحص بدقة ما إذا كانت الـ subpaths داخل المستطيل المحدد في [`ExtractionAreaBound`](./extractionareabound/). إذا تم تعيينه إلى false، فإن الـ subpaths التي لا تُدرج بالكامل في [`ExtractionAreaBound`](./extractionareabound/) سيتم استخراجها. القيمة الافتراضية هي `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | يحصل أو يعيّن علامة تحدد ما إذا كان يجب فك ضغط XFrom الموجودة على الصفحات أم لا. يمكن أن تنتهي عناصر XFrom في ملفات SVG مختلفة. يتم فك ضغط فقط XForms التي يتم عرضها بواسطة عبارات Do من محتوى الصفحة. XForms المتداخلة لا يتم فك ضغطها. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | يحصل أو يعيّن الخيار لفك ضغط XForm فقط المتطابق مع الشرط المحدد. |

### انظر أيضًا

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)



---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Vector.SvgExtractionOptions. تمثل فئة خيارات لاستخراج الرسومات المتجهة من صفحة مستند PDF
type: docs
weight: 11240
url: /ar/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class

تمثل فئة خيارات لاستخراج الرسومات المتجهة من صفحة مستند PDF.

```csharp
public class SvgExtractionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | يحصل على الخيار ويضبطه لتجميع المسارات الفرعية تلقائيًا في صور. يستثني هذا الخيار خيار [`GroupStrength`](./groupstrength/). |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | يحصل على الخيار ويضبطه لاستخراج كل مسار فرعي من مستند PDF إلى صور SVG منفصلة. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | يحصل على المستطيل المحيط ويضبطه الذي يحدد منطقة الاستخراج لاستخراج SVG. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | يحصل على الخيار ويضبطه لقوة تجميع المسارات الفرعية في صور. يسمح لك بتكوين درجة تجميع المسارات الفرعية. تتراوح القيمة من 0 إلى 1. قيمة 0 تعني تمكين خيار [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/). قيمة 1 ستخلق صورة واحدة لجميع المسارات المتجهة على الصفحة. يكون للخيار تأثير عندما يكون [`AutoGrouping`](./autogrouping/) خاطئًا. القيمة الافتراضية هي `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | يحصل على الحد الأدنى لعرض الخط أو يضبطه الذي سيتم استخدامه في SVG الناتج. إذا استخدم PDF عرض خط أرق، فسيتم استبداله بهذا العرض. القيمة الافتراضية هي 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | يحصل على الخيار ويضبطه لتعريف التحقق بدقة مما إذا كانت المسارات الفرعية ضمن المستطيل المحدد في [`ExtractionAreaBound`](./extractionareabound/). إذا تم تعيينه على خاطئ، فسيتم استخراج المسارات الفرعية التي ليست بالكامل ضمن [`ExtractionAreaBound`](./extractionareabound/). القيمة الافتراضية هي `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | يحصل على الخيار ويضبطه لتحديد ما إذا كان يجب فك XForm الموجود على الصفحات أم لا. يمكن أن تنتهي عناصر XForm في ملفات SVG مختلفة. يتم فك XForms فقط التي يتم عرضها بواسطة عبارات Do من محتوى الصفحة. لا يتم فك XForms المتداخلة. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | يحصل على الخيار ويضبطه لفك XForm فقط الذي يتوافق مع الشرط المحدد. |

### See Also

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)
---
title: "الفئة RenderingOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.RenderingOptions. تمثل خيارات العرض"
type: docs
weight: 9910
url: /ar/net/aspose.pdf/renderingoptions/
---
## RenderingOptions class

يمثل خيارات العرض.

```csharp
public sealed class RenderingOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | يستبدل الخطوط حسب الحاجة لضمان إمكانية عرض جميع الأحرف في النص. تتبع خوارزمية استبدال الخطوط الخطوات التالية: 1. إذا قام المستخدم بتعيين خاصية DefaultFontName صراحةً، تحقق مما إذا كان الخط المحدد يمكنه عرض الأحرف المطلوبة. 2. إذا لم يتم تعيين خط من قبل المستخدم، ابحث عبر الخطوط المضافة عبر !:FontRepository.Sources. 3. حلل النص لتحديد أبجديته أو خطه واقترح أسماء الخطوط وفقًا لذلك. حاول العثور على هذه الخطوط واستخدامها من النظام. 4. كإجراء احتياطي، ابحث في النظام عن أي خط قادر على عرض الأحرف المطلوبة. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | يحصل أو يضبط وضع تحسين الباركود. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | يشير إلى أن جميع الخطوط سيتم تحويلها إلى إصدارات TTF يونيكود. هذا مفيد لأسباب التوافق ولتحسين استخدام الخطوط، حيث أن كل خط TTF جديد سيحتوي ليس على جميع الرموز من الخط الأصلي، بل فقط على الرموز المستخدمة في النص. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | يحصل/يضبط الاسم الافتراضي للخط المستخدم كبديل للخطوط المفقودة. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | يحصل أو يضبط قيمة تُستخدم لزيادة أو تقليل عرض المستطيل لمعامل AppendRectangle. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | يحصل أو يضبط إشارة إلى أن الأخطاء المتعلقة بغياب الخط سيتم تجاهلها. true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false بشكل افتراضي |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | يحصل أو يضبط وضع الجودة العالية للتقريب. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | العدد الأقصى للخطوط في ذاكرة التخزين المؤقت للخطوط. القيمة الافتراضية هي 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | العدد الأقصى للرموز في ذاكرة التخزين المؤقت للرموز. القيمة الافتراضية هي 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | يحصل أو يضبط وضع تحسين الأبعاد. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | يحصل أو يضبط وضع يتم فيه عرض خطوط النظام أصليًا. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | استخدام هذه العلامة يُفعل آلية تحسين تلميحات الخط. تحسين تلميحات الخط هو استخدام تعليمات رياضية لضبط عرض الخط الخارطي. في بعض الحالات قد يحل تشغيل هذه العلامة مشاكل وضوح النص. في الوقت الحالي، يمكن أن يؤثر استخدام هذه العلامة فقط على خطوط TTF إذا تم استخدام هذه الخطوط في المستند الأصلي. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | يحصل أو يضبط قيمة تُستخدم لزيادة أو تقليل عرض المستطيل لمعامل AppendRectangle. |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)



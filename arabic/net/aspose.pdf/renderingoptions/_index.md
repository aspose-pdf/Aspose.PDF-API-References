---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.RenderingOptions. تمثل خيارات العرض
type: docs
weight: 9760
url: /ar/net/aspose.pdf/renderingoptions/
---
## فئة RenderingOptions

تمثل خيارات العرض.

```csharp
public sealed class RenderingOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | يستبدل الخطوط حسب الحاجة لضمان عرض جميع الأحرف في النص. يتبع خوارزمية استبدال الخطوات التالية: 1. إذا قام المستخدم بتعيين خاصية DefaultFontName بشكل صريح، تحقق مما إذا كان الخط المحدد يمكنه عرض الأحرف المطلوبة. 2. إذا لم يتم تعيين خط محدد من قبل المستخدم، ابحث في الخطوط المضافة عبر !:FontRepository.Sources. 3. تحليل النص لتحديد الأبجدية أو الكتابة الخاصة به واقتراح أسماء الخطوط وفقًا لذلك. حاول تحديد واستخدام هذه الخطوط من النظام. 4. كخيار احتياطي، ابحث في النظام عن أي خط قادر على عرض الأحرف المطلوبة. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | يحصل أو يحدد وضع تحسين رمز الشريط. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | يشير إلى أنه سيتم تحويل جميع الخطوط إلى إصدارات TTF unicode. هذا مفيد لأسباب التوافق ولتحسين استخدام الخطوط، لأن كل خط TTF جديد لن يحتوي على جميع الرموز من الخط المصدر، ولكن فقط الرموز المستخدمة في النص. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | يحصل/يحدد الاسم الافتراضي للخط المستخدم لاستبدال الخطوط المفقودة. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | يحصل أو يحدد قيمة تستخدم لزيادة أو تقليل عرض المستطيل لعملية AppendRectangle. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | يحصل أو يحدد إشارة تفيد بأنه سيتم تجاهل الأخطاء المتعلقة بغياب الخط. true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false بشكل افتراضي |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | يحصل أو يحدد وضع الجودة العالية للتداخل. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | الحد الأقصى لعدد الخطوط في ذاكرة التخزين المؤقت للخطوط. القيمة الافتراضية هي 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | الحد الأقصى لعدد الرموز في ذاكرة التخزين المؤقت للرموز. القيمة الافتراضية هي 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | يحصل أو يحدد وضع تحسين الأبعاد. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | يحصل أو يحدد وضع حيث يتم عرض الخطوط النظامية بشكل أصلي. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | استخدام هذه العلامة يشغل آلية تلميح الخط. تلميح الخط هو استخدام التعليمات الرياضية لضبط عرض خط المخطط. في بعض الحالات، قد يؤدي تشغيل هذه العلامة إلى حل مشاكل قابلية قراءة النص. في الوقت الحالي، يمكن أن تعطي استخدام هذه العلامة تأثيرًا فقط على خطوط TTF، إذا كانت هذه الخطوط مستخدمة في الوثيقة المصدر. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | يحصل أو يحدد قيمة تستخدم لزيادة أو تقليل عرض المستطيل لعملية AppendRectangle. |

### انظر أيضًا

* مساحة الاسم [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)
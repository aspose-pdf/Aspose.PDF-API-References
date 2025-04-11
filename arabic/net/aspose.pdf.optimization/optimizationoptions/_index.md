---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Optimization.OptimizationOptions. فئة تصف خوارزمية تحسين المستند. يمكن استخدام مثيل هذه الفئة كمعامل لطريقة OptimizeResources
type: docs
weight: 7980
url: /ar/net/aspose.pdf.optimization/optimizationoptions/
---
## فئة OptimizationOptions

فئة تصف خوارزمية تحسين المستند. يمكن استخدام مثيل هذه الفئة كمعامل لطريقة OptimizeResources().

```csharp
public class OptimizationOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | إذا كانت القيمة صحيحة، سيتم إعادة استخدام محتويات الصفحة عند تحسين المستند لصفحات متساوية. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | إذا كانت هذه العلامة مضبوطة على `true`، سيتم تعبئة كائنات Pdf في تدفقات الكائنات وضغطها لتقليل حجم ملف pdf. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | مجموعة من الخيارات التي تصف ما إذا كانت الصور في المستند ستضغط ومعلمات الضغط. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | ترميز الصورة الذي سيتم استخدامه. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | إذا كانت هذه العلامة مضبوطة على true، سيتم تحليل تدفقات الموارد. إذا تم العثور على تدفقات مكررة (أي إذا كانت محتويات التدفق متساوية)، فسيتم تخزين هذه التدفقات ككائن واحد. هذا يسمح بتقليل حجم المستند في بعض الحالات (على سبيل المثال، عندما تم دمج نفس المستند عدة مرات). |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | مستوى الفحص. الفحوصات الأعمق (قيمة أعلى) تستغرق وقتًا أطول ولكن قد تنتج ملفات نتائج أصغر. القيمة الافتراضية: 10. |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | يحدد الحد الأقصى لدقة الصور. إذا كانت الصورة ذات دقة أعلى، فسيتم تغيير حجمها |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | إزالة المعلومات الخاصة (معلومات قطعة الصفحة). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | إذا كانت هذه العلامة مضبوطة على true، سيتم فحص جميع كائنات المستند وإزالة الكائنات غير المستخدمة (أي الكائنات التي لا تحتوي على أي مرجع) من المستند. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | إذا كانت هذه العلامة مضبوطة على true، يتم فحص كل مورد لاستخدامه. إذا لم يتم استخدام المورد أبدًا، فسيتم إزالة المورد. قد يقلل هذا من حجم المستند على سبيل المثال عندما تم استخراج الصفحات من المستند. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | سيتم تحويل الخطوط إلى مجموعات فرعية إذا تم ضبطها على true. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | جعل الخطوط غير مضمنة إذا تم ضبطها على true. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | ينشئ استراتيجية تحسين مع تفعيل جميع الخيارات. يرجى ملاحظة أنه يتم تفعيل الخيارات فقط التي لا تغير أي وظيفة من وظائف المستند. أي أن ضغط الصور وإلغاء تضمين الخطوط لن يتم تفعيله (ويمكن تضمينه يدويًا). |

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* التجميع [Aspose.PDF](../../)
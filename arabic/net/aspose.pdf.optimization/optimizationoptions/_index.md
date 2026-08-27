---
title: "الفئة OptimizationOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Optimization.OptimizationOptions الفئة. الفئة التي تصف خوارزمية تحسين المستند. يمكن استخدام نسخة من هذه الفئة كمعامل لطريقة OptimizeResources."
type: docs
weight: 8120
url: /ar/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class

الفئة التي تصف خوارزمية تحسين المستند. يمكن استخدام نسخة من هذه الفئة كمعامل لطريقة OptimizeResources().

```csharp
public class OptimizationOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | إذا كان true ستتم إعادة استخدام محتويات الصفحة عندما يتم تحسين المستند للصفحات المتساوية. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | إذا تم تعيين هذه العلامة إلى `true`، سيتم تجميع كائنات Pdf في تدفقات Objest وضغطها لتقليل حجم ملف pdf. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | مجموعة من الخيارات التي تصف ما إذا كانت الصور في المستند سيتم ضغطها ومعلمات الضغط. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | ترميز Image الذي سيُستخدم. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | إذا تم تعيين هذه العلامة إلى true، سيتم تحليل تدفقات Resource. إذا تم العثور على تدفقات مكررة (أي إذا كان محتوى التدفق متساويًا)، فسيتم تخزين هذه التدفقات ككائن واحد. هذا يسمح بتقليل حجم المستند في بعض الحالات (على سبيل المثال، عندما تم دمج نفس المستند عدة مرات). |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | يحدد الحد الأقصى لدقة images. إذا كانت الصورة ذات دقة أعلى فسيتم تحجيمها. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | إزالة المعلومات الخاصة (page piece info). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | إذا تم تعيين هذه العلامة إلى true، سيتم فحص جميع كائنات document وإزالة الكائنات غير المستخدمة (أي الكائنات التي لا تحتوي على أي إشارة) من document. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | إذا تم تعيين هذه العلامة إلى true، يتم فحص كل resource على استخدامه. إذا لم يُستخدم resource أبداً، يتم إزالة resource. قد يؤدي ذلك إلى تقليل حجم المستند على سبيل المثال عندما تم استخراج pages من المستند. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Fonts سيتم تحويلها إلى مجموعات فرعية إذا تم تعيينها إلى true. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | اجعل fonts غير مضمنة إذا تم تعيينها إلى true. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | ينشئ استراتيجية تحسين مع تفعيل جميع الخيارات. يرجى ملاحظة أن يتم تفعيل الخيارات التي لا تغير أي وظيفة في المستند فقط. على سبيل المثال، ضغط image وإلغاء تضمين الخطوط لن يتم تفعيلهما (ويمكن تضمينهما يدويًا). |

### انظر أيضًا

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)



---
title: "الفئة PdfFileEditor.ContentsResizeParameters"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters. فئة لتحديد معلمات تغيير حجم الصفحة. تسمح بتعيين المعلمات التالية: حجم الصفحة الناتجة (العرض، الارتفاع) بوحدات المساحة الافتراضية أو كنسبة مئوية من حجم الصفحات الأصلية؛ الهوامش اليسرى، العليا، السفلية واليمنى بوحدات المساحة الافتراضية أو كنسبة مئوية من حجم الصفحة الأصلية. قد تُترك بعض القيم فارغة للحساب التلقائي. سيتم حساب هذه القيم من باقي حجم الصفحة بعد حساب القيم المحددة صراحة. على سبيل المثال، إذا كان عرض الصفحة 100 ووُحدد عرض صفحة جديد 60 وحدة، فإن الهوامش اليسرى واليمنى تُحسب تلقائياً كـ (100 - 60) / 2 = 15. تُستخدم هذه الفئة في طريقة ResizeContents."
type: docs
weight: 4600
url: /ar/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

فئة لتحديد معلمات تغيير حجم الصفحة. تسمح بتعيين المعلمات التالية: حجم الصفحة الناتجة (العرض، الارتفاع) بوحدات المساحة الافتراضية أو كنسبة مئوية من حجم الصفحات الأصلية؛ الهوامش اليسرى، العليا، السفلية واليمنى بوحدات المساحة الافتراضية أو كنسبة مئوية من حجم الصفحة الأصلية؛ قد تُترك بعض القيم فارغة للحساب التلقائي. سيتم حساب هذه القيم من باقي حجم الصفحة بعد حساب القيم المحددة صراحة. على سبيل المثال: إذا كان عرض الصفحة = 100 وتم تحديد عرض صفحة جديد 60 وحدة، فإن الهوامش اليسرى واليمنى تُحسب تلقائياً: (100 - 60) / 2 = 15. تُستخدم هذه الفئة في طريقة ResizeContents.

```csharp
public class ContentsResizeParameters
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | ينشئ معلمات تغيير الحجم حيث تُضبط جميع القيم إلى "auto". يمكن تحديد الهوامش وحجم المحتوى لاحقاً إذا لزم الأمر. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | ينشئ معلمات تغيير الحجم بقيم هوامش محددة وحجم المحتوى. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | يحصل أو يضبط الهامش السفلي في الصفحة الناتجة. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | يحصل أو يضبط ارتفاع محتوى الصفحة المصدر في الصفحة الناتجة. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | يحصل أو يضبط عرض محتوى الصفحة المصدر في الصفحة الناتجة. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | يحصل أو يضبط الهامش الأيسر في الصفحة الناتجة. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | يحصل أو يضبط الهامش الأيمن على الصفحة الناتجة. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | يحصل أو يضبط الهامش العلوي على الصفحة الناتجة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | ينشئ معلمات تغيير الحجم بالحجم المحدد للمحتوى. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | ينشئ معلمات تغيير الحجم بالحجم المحدد للمحتوى كنسبة مئوية من حجم الصفحة الأولية. يتم حساب الهوامش تلقائيًا. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | ينشئ معلمات تغيير الحجم بقيمة الهوامش المحددة. يتم حساب حجم المحتوى تلقائيًا. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | ينشئ معلمات تغيير الحجم. يتم تحديد الهوامش كنسبة مئوية من حجم الصفحة الأولية. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | ينشئ معلمات تغيير الحجم لإعادة تحجيم الصفحة. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | ينشئ معلمات تغيير الحجم لإعادة تحجيم الصفحة. يتم تحديد الأحجام الجديدة كنسبة مئوية. |

### انظر أيضًا

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)



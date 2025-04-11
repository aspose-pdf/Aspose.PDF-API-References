---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters. فئة لتحديد معلمات تغيير حجم الصفحة. يسمح بتعيين المعلمات التالية: حجم الصفحة الناتجة (العرض، الارتفاع) بوحدات الفضاء الافتراضية أو كنسب مئوية من حجم الصفحات الأولية؛ الهوامش اليسرى، العليا، السفلى واليمنى بوحدات الفضاء الافتراضية أو كنسب مئوية من حجم الصفحة الأولية؛ يمكن ترك بعض القيم فارغة للحساب التلقائي. سيتم حساب هذه القيم من بقية حجم الصفحة بعد حساب القيم المحددة صراحة. على سبيل المثال: إذا كان عرض الصفحة = 100 وتم تحديد عرض الصفحة الجديدة 60 وحدة، فإن الهوامش اليسرى واليمنى يتم حسابها تلقائيًا: (100 - 60) / 2 = 15. تُستخدم هذه الفئة في طريقة ResizeContents.
type: docs
weight: 4480
url: /ar/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

فئة لتحديد معلمات تغيير حجم الصفحة. يسمح بتعيين المعلمات التالية: حجم الصفحة الناتجة (العرض، الارتفاع) بوحدات الفضاء الافتراضية أو كنسب مئوية من حجم الصفحات الأولية؛ الهوامش اليسرى، العليا، السفلى واليمنى بوحدات الفضاء الافتراضية أو كنسب مئوية من حجم الصفحة الأولية؛ يمكن ترك بعض القيم فارغة للحساب التلقائي. سيتم حساب هذه القيم من بقية حجم الصفحة بعد حساب القيم المحددة صراحة. على سبيل المثال: إذا كان عرض الصفحة = 100 وتم تحديد عرض الصفحة الجديدة 60 وحدة، فإن الهوامش اليسرى واليمنى يتم حسابها تلقائيًا: (100 - 60) / 2 = 15. تُستخدم هذه الفئة في طريقة ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | ينشئ معلمات تغيير الحجم حيث يتم تعيين جميع القيم إلى "تلقائي". يمكن تحديد الهوامش وحجم المحتوى لاحقًا إذا لزم الأمر. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | ينشئ معلمات تغيير الحجم مع قيم الهوامش المحددة وحجم المحتوى. |

## Properties

| Name | Description |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | يحصل على أو يحدد الهامش السفلي في الصفحة الناتجة. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | يحصل على أو يحدد ارتفاع محتوى الصفحة المصدر في الصفحة الناتجة. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | يحصل على أو يحدد عرض محتوى الصفحة المصدر في الصفحة الناتجة. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | يحصل على أو يحدد الهامش الأيسر في الصفحة الناتجة. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | يحصل على أو يحدد الهامش الأيمن في الصفحة الناتجة. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | يحصل على أو يحدد الهامش العلوي في الصفحة الناتجة. |

## Methods

| Name | Description |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | ينشئ معلمات تغيير الحجم مع حجم المحتوى المحدد. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | ينشئ معلمات تغيير الحجم مع حجم المحتوى المحدد كنسب مئوية من حجم الصفحة الأولية. يتم حساب الهوامش تلقائيًا. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | ينشئ معلمات تغيير الحجم مع قيمة الهوامش المحددة. يتم حساب حجم المحتوى تلقائيًا. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | ينشئ معلمات تغيير الحجم. يتم تحديد الهوامش كنسب مئوية من حجم الصفحة الأولية. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | ينشئ معلمات تغيير الحجم لتغيير حجم الصفحة. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | ينشئ معلمات تغيير الحجم لتغيير حجم الصفحة. يتم تحديد الأحجام الجديدة كنسب مئوية. |

### See Also

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)
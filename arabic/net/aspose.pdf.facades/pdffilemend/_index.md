---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.PdfFileMend. تمثل فئة لإضافة النصوص والصور على صفحات مستند PDF الموجود
type: docs
weight: 4530
url: /ar/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class

تمثل فئة لإضافة النصوص والصور على صفحات مستند PDF الموجود.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | المُنشئ. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | يقوم بتهيئة كائن `PdfFileMend` جديد بناءً على *المستند*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يعمل عليها. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | يحدد قيمة بوليانية تشير إلى التفاف الكلمات في طرق AddText. إذا كانت القيمة صحيحة، فإن النص في FormattedText سيتلف. بشكل افتراضي، تكون القيمة خاطئة. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | يحدد أو يحصل على استراتيجية وضع النص. [`PositioningMode`](../positioningmode/) الوضع الافتراضي هو Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | يحدد أو يحصل على خوارزمية التفاف الكلمات. انظر WordWrapMode و IsWordWrap. |

## Methods

| Name | Description |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | غير مُنفذ. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | غير مُنفذ. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | غير مُنفذ. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يقوم بتهيئة الواجهة. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | يغلق كائن PdfFileMend. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | يحفظ مستند PDF إلى التدفق المحدد. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | يحفظ مستند PDF إلى الملف المحدد. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)
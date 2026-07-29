---
title: "الفئة PdfFileMend"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Facades.PdfFileMend class. تمثل فئة لإضافة النصوص والصور على صفحات مستند PDF موجود"
type: docs
weight: 4650
url: /ar/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class

يمثل فئة لإضافة نصوص وصور على صفحات مستند PDF الموجود.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | منشئ. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | يُهيئ كائن `PdfFileMend` جديد على أساس *document*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | يضبط قيمة منطقية تشير إلى التفاف الكلمات في طرق AddText. إذا كانت القيمة true، سيتفاف النص في FormattedText. بشكل افتراضي، القيمة false. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | يضبط أو يحصل على استراتيجية تموضع النص. [`PositioningMode`](../positioningmode/) الوضع الافتراضي هو Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | يضبط أو يحصل على خوارزمية التفاف الكلمات. راجع WordWrapMode و IsWordWrap. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | غير مُنفّذ. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | غير مُنفّذ. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | غير مُنفّذ. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يُهيئ الواجهة. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | يغلق كائن PdfFileMend. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | يحفظ مستند PDF إلى الدفق المحدد. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | يحفظ مستند PDF إلى الملف المحدد. |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)



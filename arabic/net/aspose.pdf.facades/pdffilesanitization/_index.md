---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.PdfFileSanitization. تمثل واجهة برمجة التطبيقات للتعقيم والاسترداد. استخدمها إذا لم تتمكن من إنشاء/فتح المستندات بأي طريقة أخرى
type: docs
weight: 4540
url: /ar/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class

تمثل واجهة برمجة التطبيقات للتعقيم والاسترداد. استخدمها إذا لم تتمكن من إنشاء/فتح المستندات بأي طريقة أخرى.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يعمل عليها. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | بعد حفظ الملف يمكنك التحقق مما تم فعله بالملف. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | يسمح بإنشاء xref و trailer جديدين للمستند. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | يسمح بإزالة البيانات بعد بيانات PDF |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | يسمح بإزالة البيانات قبل بيانات PDF. |

## Methods

| Name | Description |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | يقوم بتهيئة الواجهة. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | يربط تدفق PDF للتعقيم. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | يربط ملف PDF للتعقيم. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | يغلق الواجهة. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | يزيل xref القديم مع trailer وينشئ xref جديد مع trailer. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | يستعيد المستند. استخدم الخصائص للتخصيص. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | يحفظ PDF الناتج إلى التدفق. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | يحفظ PDF الناتج إلى ملف. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | يزيل البيانات بعد آخر %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | يزيل البيانات قبل %PDF. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)
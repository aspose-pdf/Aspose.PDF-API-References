---
title: "الفئة PdfFileSanitization"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfFileSanitization. تمثل واجهة برمجة تطبيقات التنظيف والاستعادة. استخدمها إذا لم تستطع إنشاء/فتح المستندات بأي طريقة أخرى."
type: docs
weight: 4660
url: /ar/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class

يمثل واجهة برمجة تطبيقات للتنقية والاستعادة. استخدمها إذا لم تتمكن من إنشاء/فتح المستندات بأي طريقة أخرى.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | بعد حفظ الملف يمكنك التحقق مما تم عمله على الملف. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | يسمح بإنشاء xref جديد وملحق (trailer) للمستند. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | يسمح بإزالة البيانات بعد بيانات pdf |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | يسمح بإزالة البيانات قبل بيانات pdf. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | يُهيئ الواجهة. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | يربط تدفق Pdf للتنظيف. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | يربط ملف Pdf للتنظيف. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | يغلق الواجهة. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | يزيل xref القديم مع الملحق (trailer) وينشئ xref جديدًا مع الملحق. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | يستعيد المستند. استخدم الخصائص للتخصيص. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | يحفظ ملف PDF الناتج إلى تدفق. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | يحفظ ملف PDF الناتج إلى ملف. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | يزيل البيانات بعد آخر %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | يزيل البيانات قبل %PDF. |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)



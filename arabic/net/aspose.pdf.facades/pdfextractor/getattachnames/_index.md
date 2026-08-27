---
title: "PdfExtractor.GetAttachNames"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfExtractor. تُرجع قائمة المرفقات في ملف PDF. ملاحظة: يجب استدعاء ExtractAttachments قبل استخدام هذه الطريقة"
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames method

يرجع قائمة المرفقات في ملف PDF. ملاحظة: يجب استدعاء ExtractAttachments قبل استخدام هذه الطريقة.

```csharp
public IList<string> GetAttachNames()
```

### قيمة الإرجاع

قائمة المرفقات

## أمثلة

يوضح المثال كيفية استخراج أسماء المرفقات من ملف PDF.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)



---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfExtractor. تُرجع قائمة بالمرفقات في ملف PDF. ملاحظة: يجب استدعاء ExtractAttachments قبل استخدام هذه الطريقة
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## طريقة PdfExtractor.GetAttachNames

تُرجع قائمة بالمرفقات في ملف PDF. ملاحظة: يجب استدعاء ExtractAttachments قبل استخدام هذه الطريقة.

```csharp
public IList<string> GetAttachNames()
```

### قيمة الإرجاع

قائمة بالمرفقات

## أمثلة

المثال يوضح كيفية استخراج أسماء المرفقات من ملف PDF.

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
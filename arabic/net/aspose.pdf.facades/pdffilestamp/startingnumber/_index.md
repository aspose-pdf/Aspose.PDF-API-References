---
title: "PdfFileStamp.StartingNumber"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية PdfFileStamp. تحصل أو تعين الرقم الابتدائي للصفحة الأولى في ملف الإدخال. سيتم ترقيم الصفحات التالية بدءًا من هذه القيمة. على سبيل المثال إذا تم ضبط StartingNumber على 100 فإن صفحات المستند ستحصل على الأرقام 100 101 102."
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber property

يحصل أو يعيّن الرقم الابتدائي للصفحة الأولى في ملف الإدخال. سيتم ترقيم الصفحات التالية بدءًا من هذه القيمة. على سبيل المثال إذا تم تعيين StartingNumber إلى 100، ستحصل صفحات المستند على الأرقام 100، 101، 102...

```csharp
public int StartingNumber { get; set; }
```

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)



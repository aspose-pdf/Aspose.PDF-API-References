---
title: "PdfExtractor.StartPage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية PdfExtractor. يحصل أو يحدد الصفحة البداية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج"
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage property

يحصل أو يضبط صفحة البداية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 5;
ext.ExtractText();
```

```csharp
public int StartPage { get; set; }
```

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)



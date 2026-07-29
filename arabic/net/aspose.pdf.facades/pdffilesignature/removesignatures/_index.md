---
title: "PdfFileSignature.RemoveSignatures"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSignature. يزيل جميع التوقيعات."
type: docs
weight: 260
url: /ar/net/aspose.pdf.facades/pdffilesignature/removesignatures/
---
## PdfFileSignature.RemoveSignatures method

يزيل جميع التوقيعات.

```csharp
public void RemoveSignatures()
```

## أمثلة

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
var pdfSign = new PdfFileSignature();
pdfSign.BindPdf(inFile); 
pdfSign.RemoveSignatures();
pdfSign.Save(TestPath + "signed_removed.pdf");
[Visual Basic]
Dim pdfSign as PdfFileSignature = new PdfFileSignature
pdfSign.BindPdf(inFile)
pdfSign.RemoveSignatures()
pdfSign.Save(TestPath + "signed_removed.pdf")
```

### انظر أيضًا

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)



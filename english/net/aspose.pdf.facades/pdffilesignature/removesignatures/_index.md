---
title: "PdfFileSignature.RemoveSignatures"
linktitle: "RemoveSignatures"
articleTitle: "RemoveSignatures"
second_title: "Aspose.PDF for .NET"
description: "Removes all signatures."
type: docs
weight: 370
url: "/net/aspose.pdf.facades/pdffilesignature/removesignatures/"
product_version: "26.9.0"
---
## RemoveSignatures() {#removesignatures}

Removes all signatures.

```csharp
public void RemoveSignatures()
```

## Examples

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

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


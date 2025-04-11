---
title: PdfFileSignature.RemoveSignatures
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileSignature. Rimuove tutte le firme
type: docs
weight: 260
url: /it/net/aspose.pdf.facades/pdffilesignature/removesignatures/
---
## Metodo PdfFileSignature.RemoveSignatures

Rimuove tutte le firme.

```csharp
public void RemoveSignatures()
```

## Esempi

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

### Vedi Anche

* classe [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
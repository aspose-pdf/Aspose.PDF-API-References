---
title: PdfFileSignature.RemoveSignatures
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSignature. Elimina todas las firmas
type: docs
weight: 260
url: /es/net/aspose.pdf.facades/pdffilesignature/removesignatures/
---
## Método PdfFileSignature.RemoveSignatures

Elimina todas las firmas.

```csharp
public void RemoveSignatures()
```

## Ejemplos

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

### Ver También

* clase [PdfFileSignature](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)
---
title: PdfFileSignature.RemoveSignatures
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileSignature. Supprime toutes les signatures
type: docs
weight: 260
url: /fr/net/aspose.pdf.facades/pdffilesignature/removesignatures/
---
## Méthode PdfFileSignature.RemoveSignatures

Supprime toutes les signatures.

```csharp
public void RemoveSignatures()
```

## Exemples

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

### Voir aussi

* classe [PdfFileSignature](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
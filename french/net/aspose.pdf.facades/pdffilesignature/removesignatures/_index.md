---
title: "PdfFileSignature.RemoveSignatures"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileSignature. Supprime toutes les signatures."
type: docs
weight: 260
url: /fr/net/aspose.pdf.facades/pdffilesignature/removesignatures/
---
## PdfFileSignature.RemoveSignatures method

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

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)



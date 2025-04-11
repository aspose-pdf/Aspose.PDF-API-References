---
title: PdfFileSignature.RemoveSignatures
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileSignature. Menghapus semua tanda tangan
type: docs
weight: 260
url: /id/net/aspose.pdf.facades/pdffilesignature/removesignatures/
---
## Metode PdfFileSignature.RemoveSignatures

Menghapus semua tanda tangan.

```csharp
public void RemoveSignatures()
```

## Contoh

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

### Lihat Juga

* kelas [PdfFileSignature](../)
* ruang nama [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)
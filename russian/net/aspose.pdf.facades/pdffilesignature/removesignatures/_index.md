---
title: PdfFileSignature.RemoveSignatures
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfFileSignature. Удаляет все подписи
type: docs
weight: 260
url: /ru/net/aspose.pdf.facades/pdffilesignature/removesignatures/
---
## Метод PdfFileSignature.RemoveSignatures

Удаляет все подписи.

```csharp
public void RemoveSignatures()
```

## Примеры

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

### См. также

* класс [PdfFileSignature](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)
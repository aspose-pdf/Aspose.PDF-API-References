---
title: PdfFileSignature.RemoveSignatures
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature 메서드. 모든 서명을 제거합니다
type: docs
weight: 260
url: /ko/net/aspose.pdf.facades/pdffilesignature/removesignatures/
---
## PdfFileSignature.RemoveSignatures 메서드

모든 서명을 제거합니다.

```csharp
public void RemoveSignatures()
```

## 예제

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

### 참조

* 클래스 [PdfFileSignature](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)
---
title: "PdfFileSignature.RemoveSignatures"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileSignature メソッド。すべての署名を削除します。"
type: docs
weight: 260
url: /ja/net/aspose.pdf.facades/pdffilesignature/removesignatures/
---
## PdfFileSignature.RemoveSignatures method

すべての署名を削除します。

```csharp
public void RemoveSignatures()
```

## 例

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

### 関連項目

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)



---
title: "PdfFileSignature.RemoveSignatures"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileSignature 方法。移除所有签名"
type: docs
weight: 260
url: /zh/net/aspose.pdf.facades/pdffilesignature/removesignatures/
---
## PdfFileSignature.RemoveSignatures method

删除所有签名。

```csharp
public void RemoveSignatures()
```

## 示例

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

### 另请参见

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)



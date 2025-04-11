---
title: PdfFileStamp.PageWidth
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 속성. 입력 파일의 첫 페이지 너비를 가져옵니다.
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/pdffilestamp/pagewidth/
---
## PdfFileStamp.PageWidth 속성

입력 파일의 첫 페이지 너비를 가져옵니다.

```csharp
public float PageWidth { get; }
```

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Console.WriteLine("Width = " + fileStamp.PageWidth);
fileStamp.Close();
```

### 참조

* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)
---
title: PdfFileStamp.PageHeight
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 속성. 원본 파일의 첫 페이지 높이를 가져옵니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf.facades/pdffilestamp/pageheight/
---
## PdfFileStamp.PageHeight 속성

원본 파일의 첫 페이지 높이를 가져옵니다.

```csharp
public float PageHeight { get; }
```

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Console.WriteLine("Height = " + fileStamp.PageHeight);
fileStamp.Close();
```

### 참조

* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)
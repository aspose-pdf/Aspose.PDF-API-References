---
title: PdfXmpMetadata.Count
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata 속성. 컬렉션의 항목 수를 가져옵니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/count/
---
## PdfXmpMetadata.Count 속성

컬렉션의 항목 수를 가져옵니다.

```csharp
public int Count { get; }
```

## 예제

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine("Count = " + pxm.Count);
```

### 참조

* 클래스 [PdfXmpMetadata](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)
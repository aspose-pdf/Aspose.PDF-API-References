---
title: PdfFileStamp.StartingNumber
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp 속성. 입력 파일의 첫 페이지에 대한 시작 번호를 가져오거나 설정합니다. 다음 페이지는 이 값부터 번호가 매겨집니다. 예를 들어 StartingNumber가 100으로 설정되면 문서 페이지는 100, 101, 102의 번호를 가집니다.
type: docs
weight: 100
url: /ko/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber 속성

입력 파일의 첫 페이지에 대한 시작 번호를 가져오거나 설정합니다. 다음 페이지는 이 값부터 번호가 매겨집니다. 예를 들어 StartingNumber가 100으로 설정되면 문서 페이지는 100, 101, 102...의 번호를 가집니다.

```csharp
public int StartingNumber { get; set; }
```

## 예제

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### 참조

* 클래스 [PdfFileStamp](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)
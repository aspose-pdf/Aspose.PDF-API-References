---
title: "PdfFileStamp.StartingNumber"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileStamp 속성. 입력 파일의 첫 페이지에 대한 시작 번호를 가져오거나 설정합니다. 이후 페이지는 이 값부터 번호가 매겨집니다. 예를 들어 StartingNumber가 100으로 설정되면 문서 페이지 번호는 100 101 102가 됩니다."
type: docs
weight: 100
url: /ko/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.StartingNumber property

입력 파일에서 첫 번째 페이지의 시작 번호를 가져오거나 설정합니다. 이후 페이지는 이 값부터 번호가 매겨집니다. 예를 들어 StartingNumber가 100으로 설정되면 문서 페이지 번호는 100, 101, 102...이 됩니다.

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

### 또 보기

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)



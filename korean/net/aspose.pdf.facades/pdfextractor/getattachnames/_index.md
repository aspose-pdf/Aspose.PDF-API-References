---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 메서드. PDF 파일의 첨부 파일 목록을 반환합니다. 주의 이 메서드를 사용하기 전에 ExtractAttachments를 호출해야 합니다.
type: docs
weight: 160
url: /ko/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames 메서드

PDF 파일의 첨부 파일 목록을 반환합니다. 주의: 이 메서드를 사용하기 전에 ExtractAttachments를 호출해야 합니다.

```csharp
public IList<string> GetAttachNames()
```

### 반환 값

첨부 파일 목록

## 예제

예제는 PDF 파일에서 첨부 파일 이름을 추출하는 방법을 보여줍니다.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### 참조

* 클래스 [PdfExtractor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)
---
title: "PdfExtractor.GetAttachNames"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfExtractor 메서드. PDF 파일의 첨부 파일 목록을 반환합니다. 이 메서드를 사용하기 전에 ExtractAttachments를 호출해야 합니다."
type: docs
weight: 160
url: /ko/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames method

PDF 파일의 첨부 파일 목록을 반환합니다. 참고: 이 메서드를 사용하기 전에 ExtractAttachments를 호출해야 합니다.

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

### 또 보기

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)



---
title: "PdfExtractor.EndPage"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfExtractor 속성. 추출 작업이 수행될 페이지 범위의 끝 페이지를 가져오거나 설정합니다."
type: docs
weight: 20
url: /ko/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage property

추출 작업이 수행될 페이지 범위의 끝 페이지를 가져오거나 설정합니다.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 3;
ext.ExtractText();
```

```csharp
public int EndPage { get; set; }
```

### 또 보기

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)



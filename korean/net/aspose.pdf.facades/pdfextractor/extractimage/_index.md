---
title: "PdfExtractor.ExtractImage"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfExtractor 메서드. PDF 파일에서 이미지를 추출합니다"
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage method

PDF 파일에서 이미지를 추출합니다.

```csharp
public void ExtractImage()
```

## 예제

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### 또 보기

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)



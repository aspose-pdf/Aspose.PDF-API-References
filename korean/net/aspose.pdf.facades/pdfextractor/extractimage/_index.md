---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 메서드. PDF 파일에서 이미지 추출
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage 메서드

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

### 참조

* 클래스 [PdfExtractor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)
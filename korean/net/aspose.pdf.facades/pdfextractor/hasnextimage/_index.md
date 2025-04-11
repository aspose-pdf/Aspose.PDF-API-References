---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 메서드. PDF 문서에서 더 많은 이미지에 접근할 수 있는지 확인합니다. 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다.
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage 메서드

PDF 문서에서 더 많은 이미지에 접근할 수 있는지 확인합니다. 주의: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다.

```csharp
public bool HasNextImage()
```

### 반환 값

더 많은 이미지에 접근할 수 있으면 true입니다.

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
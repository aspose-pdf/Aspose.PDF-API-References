---
title: "PdfExtractor.HasNextImage"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfExtractor 메서드. PDF 문서에서 더 많은 이미지에 접근할 수 있는지 확인합니다. 참고: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다."
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage method

PDF 문서에서 더 많은 이미지에 접근할 수 있는지 확인합니다. 참고: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다.

```csharp
public bool HasNextImage()
```

### 반환 값

이미지가 더 접근 가능한 경우 true

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



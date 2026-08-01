---
title: "PdfExtractor.ExtractTextMode"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfExtractor 속성. 텍스트 추출 결과의 모드를 설정합니다."
type: docs
weight: 40
url: /ko/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode property

텍스트 추출 결과의 모드를 설정합니다.

```csharp
public int ExtractTextMode { get; set; }
```

### Property Value

0은 순수 텍스트 모드이고 1은 원시 순서 모드입니다. 기본값은 0입니다.

## 예제

예제는 텍스트 추출 시나리오에서 `ExtractTextMode` 속성 사용을 보여줍니다.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### 또 보기

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)



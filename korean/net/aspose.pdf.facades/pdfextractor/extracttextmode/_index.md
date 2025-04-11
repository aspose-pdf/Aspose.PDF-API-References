---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 속성. 텍스트 추출 결과의 모드를 설정합니다.
type: docs
weight: 40
url: /ko/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode 속성

텍스트 추출 결과의 모드를 설정합니다.

```csharp
public int ExtractTextMode { get; set; }
```

### 속성 값

0은 순수 텍스트 모드이고 1은 원시 정렬 모드입니다. 기본값은 0입니다.

## 예제

이 예제는 텍스트 추출 시나리오에서 `ExtractTextMode` 속성 사용을 보여줍니다.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### 참조

* 클래스 [PdfExtractor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)
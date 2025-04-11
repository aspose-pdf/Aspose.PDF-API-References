---
title: PdfAOptionsBase.ExcludeFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase 속성. PDF/A 변환 과정에서 출력 파일 크기를 최소화하기 위해 글꼴을 제거하는 전략을 가져오거나 설정합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy 속성

PDF/A 변환 과정에서 출력 파일 크기를 최소화하기 위해 글꼴을 제거하는 전략을 가져오거나 설정합니다.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### 속성 값

글꼴을 제거하는 전략입니다. 이는 [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/) 열거형의 값 중 하나일 수 있습니다. 기본값은 SubsetFonts와 RemoveDuplicatedFonts의 조합입니다.

## 비고

이 속성은 변환 과정에서 글꼴이 처리되는 방식을 제어할 수 있게 해줍니다. 중복된 글꼴을 제거하거나, 너비가 다른 유사한 글꼴을 제거하거나, 글꼴을 서브셋할 수 있습니다.

### 참조

* 열거형 [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* 클래스 [PdfAOptionsBase](../)
* 네임스페이스 [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../../)
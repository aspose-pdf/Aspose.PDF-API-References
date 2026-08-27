---
title: "PdfAOptionsBase.ExcludeFontsStrategy"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfAOptionsBase 속성. PDF/A 변환 과정에서 출력 파일 크기를 최소화하기 위해 글꼴을 제거하는 전략을 가져오거나 설정합니다."
type: docs
weight: 30
url: /ko/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy property

PDF/A 변환 과정에서 출력 파일 크기를 최소화하기 위해 글꼴을 제거하는 전략을 가져오거나 설정합니다.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Property Value

글꼴을 제거하는 전략입니다. 이는 [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/) 열거형의 값 중 하나일 수 있습니다. 기본값은 SubsetFonts와 RemoveDuplicatedFonts의 조합입니다.

## 비고

이 속성을 사용하면 변환 과정에서 글꼴이 처리되는 방식을 제어할 수 있습니다. 중복된 글꼴을 제거하거나, 너비가 다른 유사한 글꼴을 제거하거나, 글꼴을 서브셋팅하는 것을 선택할 수 있습니다.

### 또 보기

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)



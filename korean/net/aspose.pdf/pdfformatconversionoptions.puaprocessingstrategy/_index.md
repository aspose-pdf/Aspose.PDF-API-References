---
title: "열거형 PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy 열거형. 일부 PDF 문서에는 Private Use Area(PUA)에 속하는 특수 유니코드 기호가 있습니다. 자세한 내용은 https//en.wikipedia.org/wiki/Private_Use_Areas 를 참조하십시오. 이러한 기호는 \"Text is mapped to Unicode Private Use Area but no ActualText entry is present\"와 같은 PDF/A 호환 오류를 일으킵니다. 이 열거형은 PUA 기호를 처리하는 데 사용할 수 있는 전략을 선언합니다."
type: docs
weight: 8530
url: /ko/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy enumeration

일부 PDF 문서에는 Private Use Area(PUA)에 속하는 특수 유니코드 기호가 있습니다. 자세한 내용은 https://en.wikipedia.org/wiki/Private_Use_Areas 를 참조하십시오. 이러한 기호는 "Text is mapped to Unicode Private Use Area but no ActualText entry is present"와 같은 PDF/A 호환 오류를 일으킵니다. 이 열거형은 PUA 기호를 처리하는 데 사용할 수 있는 전략을 선언합니다.

```csharp
public enum PuaProcessingStrategy
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | PUA 기호 처리를 비활성화합니다. 이 전략은 Level B 적합성을 가진 PDF/A 문서에 기본적으로 사용됩니다. |
| SurroundPuaTextWithEmptyActualText | `1` | 빈 텍스트를 포함하는 ActualText 항목이 있는 표시된 콘텐츠 블록을 삽입합니다. 이 전략은 표시된 콘텐츠 블록이 없는 문서에서 좋은 결과를 제공합니다. Level A 적합성을 가진 PDF/A 문서에 기본적으로 사용됩니다. |
| SubstitutePuaSymbols | `2` | 이 전략은 'SurroundPuaTextWithEmptyActualText'보다 느리게 작동하지만 SurroundPuaTextWithEmptyActualText로 제대로 처리할 수 없는 문서의 PUA 호환 오류를 제거할 수 있습니다. PUA 기호는 'space' 기호나 특수 유니코드(일부 PUA 기호는 유니코드 대응이 있음)로 대체됩니다. 대체는 문서 텍스트가 아니라 글꼴의 내부 데이터인 ToUnicode에 적용되므로 기호의 시각에는 영향을 주지 않지만 복사/붙여넣기 작업 시스템 버퍼에서 기호의 표시에는 영향을 줍니다. |

### 또 보기

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)



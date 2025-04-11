---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy 열거형. 일부 PDF 문서에는 Private Use Area PUA에 속하는 특수 유니코드 기호가 있습니다. 자세한 내용은 https//en.wikipedia.org/wiki/Private_Use_Areas를 참조하십시오. 이 기호는 "텍스트가 유니코드 개인 사용 영역에 매핑되지만 ActualText 항목이 없습니다"와 같은 PDF/A 준수 오류를 발생시킵니다. 이 열거형은 PUA 기호를 처리하는 데 사용할 수 있는 전략을 선언합니다.
type: docs
weight: 8390
url: /ko/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy 열거형

일부 PDF 문서에는 Private Use Area (PUA)에 속하는 특수 유니코드 기호가 있습니다. 자세한 내용은 https://en.wikipedia.org/wiki/Private_Use_Areas을 참조하십시오. 이 기호는 "텍스트가 유니코드 개인 사용 영역에 매핑되지만 ActualText 항목이 없습니다"와 같은 PDF/A 준수 오류를 발생시킵니다. 이 열거형은 PUA 기호를 처리하는 데 사용할 수 있는 전략을 선언합니다.

```csharp
public enum PuaProcessingStrategy
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | PUA 기호 처리를 비활성화합니다. 이 전략은 Level B 준수 PDF/A 문서에 대해 기본적으로 사용됩니다. |
| SurroundPuaTextWithEmptyActualText | `1` | 빈 텍스트를 포함하는 ActualText 항목이 있는 마크된 콘텐츠 블록을 삽입합니다. 이 전략은 마크된 콘텐츠 블록이 없는 문서에 대해 좋은 결과를 제공합니다. Level A 준수 PDF/A 문서에 대해 기본적으로 사용됩니다. |
| SubstitutePuaSymbols | `2` | 이 전략은 'SurroundPuaTextWithEmptyActualText'보다 느리게 작동하지만, SurroundPuaTextWithEmptyActualText로 제대로 처리할 수 없는 문서의 PUA 준수 오류를 제거할 수 있습니다. PUA 기호는 기호 '공백' 또는 특수 유니코드로 대체됩니다(일부 PUA 기호는 유니코드 아날로그가 있습니다). 대체는 문서의 텍스트가 아니라 글꼴의 내부 데이터 ToUnicode에 적용되므로 기호의 시각에는 영향을 미치지 않지만 복사/붙여넣기 작업 시스템 버퍼에서 기호의 표현에는 영향을 미칩니다. |

### 참조

* 클래스 [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)
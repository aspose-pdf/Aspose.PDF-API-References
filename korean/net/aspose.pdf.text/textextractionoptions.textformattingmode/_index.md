---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode 열거형. PDF 문서를 텍스트로 변환할 때 사용할 수 있는 다양한 모드를 정의합니다. TextDevice 클래스를 참조하십시오.
type: docs
weight: 10900
url: /ko/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode 열거형

PDF 문서를 텍스트로 변환할 때 사용할 수 있는 다양한 모드를 정의합니다. !:TextDevice 클래스를 참조하십시오.

```csharp
public enum TextFormattingMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Pure | `0` | 약간의 형식화 루틴으로 PDF 콘텐츠를 나타냅니다. |
| Raw | `1` | 형식 없이 PDF 콘텐츠를 있는 그대로 나타냅니다. |
| Flatten | `2` | 좌표에 따라 텍스트 조각의 위치를 지정하여 PDF 콘텐츠를 나타냅니다. 기본적으로 "Raw" 모드와 유사합니다. 그러나 "Raw"는 문서 내 텍스트 조각(연산자)의 구조를 보존하는 데 중점을 두는 반면, "Flatten"은 읽는 순서대로 텍스트를 유지하는 데 중점을 둡니다. |
| MemorySaving | `3` | 메모리 절약을 위한 추출입니다. 'Raw' 모드와 거의 동일하지만 약간 더 빠르게 작동하고 메모리를 덜 사용합니다. |

### 참조

* 클래스 [TextExtractionOptions](../textextractionoptions/)
* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)
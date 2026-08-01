---
title: "열거형 TextExtractionOptions.TextFormattingMode"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode 열거형. PDF 문서를 텍스트로 변환할 때 사용할 수 있는 다양한 모드를 정의합니다. TextDevice 클래스를 참조하십시오."
type: docs
weight: 11080
url: /ko/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode enumeration

PDF 문서를 텍스트로 변환할 때 사용할 수 있는 다양한 모드를 정의합니다. !:TextDevice 클래스를 참조하십시오.

```csharp
public enum TextFormattingMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Pure | `0` | 약간의 포맷팅 루틴을 사용하여 PDF 콘텐츠를 나타냅니다. |
| Raw | `1` | PDF 콘텐츠를 그대로, 즉 포맷팅 없이 나타냅니다. |
| Flatten | `2` | 좌표에 따라 텍스트 조각을 배치하여 PDF 콘텐츠를 나타냅니다. 이는 기본적으로 "Raw" 모드와 유사합니다. 하지만 "Raw"는 문서에서 텍스트 조각(연산자)의 구조를 보존하는 데 중점을 두는 반면, "Flatten"은 텍스트가 읽히는 순서를 유지하는 데 중점을 둡니다. |
| MemorySaving | `3` | 메모리를 절약하는 추출입니다. 이는 'Raw' 모드와 거의 동일하지만 약간 더 빠르게 작동하고 메모리 사용량이 적습니다. |

### 또 보기

* class [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)



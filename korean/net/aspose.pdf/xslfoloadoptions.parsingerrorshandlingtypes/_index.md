---
title: Enum XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes 열거형. 원본 XSLFO 문서에는 형식 오류가 포함될 수 있습니다. 이 열거형은 이러한 형식 오류를 처리하는 가능한 전략을 나열합니다.
type: docs
weight: 11540
url: /ko/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes 열거형

원본 XSLFO 문서에는 형식 오류가 포함될 수 있습니다. 이 열거형은 이러한 형식 오류를 처리하는 가능한 전략을 나열합니다.

```csharp
public enum ParsingErrorsHandlingTypes
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| TryIgnore | `0` | 이 경우 변환기는 변환을 진행하고 발견된 형식 오류를 무시하도록 지시받습니다. 이 경우 성공이 보장되지 않으며, 변환기에서 심각한 문제가 발생할 수 있으며, 그런 경우 발견된 형식 오류 목록과 함께 예외가 발생합니다. |
| ThrowExceptionImmediately | `1` | 이 경우 변환은 즉시 중단되며 첫 번째 형식 오류가 감지된 후 즉시 예외가 발생합니다. |
| InvokeCustomHandler | `2` | 이것은 가장 민첩한 방법입니다 - 사용자 정의 코드는 형식 오류가 감지될 때 호출될 특별한 핸들러를 (WarningCallback 속성에) 제공해야 합니다. 그 핸들러는 예를 들어 오류를 기록하거나 세는 등의 작업을 수행할 수 있으며, 이 오류에 대해 처리를 계속할 수 있는지 여부에 대한 결정을 제공합니다. |

### 참조

* 클래스 [XslFoLoadOptions](../xslfoloadoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)
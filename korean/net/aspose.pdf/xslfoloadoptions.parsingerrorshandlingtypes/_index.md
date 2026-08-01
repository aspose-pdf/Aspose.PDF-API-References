---
title: "열거형 XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes 열거형. 소스 XSLFO 문서는 서식 오류를 포함할 수 있습니다. 이 열거형은 이러한 서식 오류를 처리하는 가능한 전략을 나열합니다."
type: docs
weight: 11730
url: /ko/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

Source XSLFO 문서는 서식 오류를 포함할 수 있습니다. 이 열거형은 이러한 서식 오류를 처리하기 위한 가능한 전략을 나열합니다.

```csharp
public enum ParsingErrorsHandlingTypes
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| TryIgnore | `0` | 이 경우 변환기는 변환을 시도하고 발견된 서식 오류를 무시하도록 지시됩니다. 이 경우 성공이 보장되지 않으며, 변환기에서 심각한 문제가 나중에 발생할 수 있고, 이러한 경우 발견된 서식 오류 목록이 포함된 예외가 발생합니다. |
| ThrowExceptionImmediately | `1` | 이 경우 변환이 즉시 중단되고 첫 번째 서식 오류를 감지한 직후 예외가 발생합니다. |
| InvokeCustomHandler | `2` | 이것이 가장 유연한 방법입니다 - 사용자 코드는 (WarningCallback 속성에서) 서식 오류가 감지될 때 호출되는 특수 핸들러를 제공해야 합니다. 해당 핸들러는 예를 들어 오류를 기록하거나 개수를 셀 수 있으며, 이 오류 또는 저 오류에 대해 처리를 계속할지 여부를 결정합니다. |

### 또 보기

* class [XslFoLoadOptions](../xslfoloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)



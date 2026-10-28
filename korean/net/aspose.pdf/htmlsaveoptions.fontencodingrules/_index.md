---
title: "열거형 HtmlSaveOptions.FontEncodingRules"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.HtmlSaveOptionsFontEncodingRules 열거형. 이 열거형은 인코딩 로직을 조정하는 규칙을 정의합니다."
type: docs
weight: 5750
url: /ko/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules enumeration

이 열거형은 인코딩 로직을 조정하는 규칙을 정의합니다.

```csharp
public enum FontEncodingRules : byte
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Default | `0` | 인코딩 로직을 "그대로" 유지하십시오 - PDF 사양에 따라 |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode는 입력 코드를 유니코드 기호로 디코딩하는 데 도움이 되는 특수 메커니즘입니다. 사양에 따르면 특정 입력 코드에 대한 유니코드 기호를 얻기 위해 가장 먼저 사용해야 하는 메커니즘이어야 합니다. 그러나 일부 문서는 비표준 글꼴을 사용하고 이러한 문서를 올바르게 변환하려면 ToUnicode의 우선순위를 낮추고 다른 메커니즘을 사용하여 입력 코드를 디코딩해야 할 수도 있습니다. |

### 또 보기

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)



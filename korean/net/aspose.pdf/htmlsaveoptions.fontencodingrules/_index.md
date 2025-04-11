---
title: Enum HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsFontEncodingRules 열거형. 이 열거형은 인코딩 로직을 조정하는 규칙을 정의합니다.
type: docs
weight: 5620
url: /ko/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules 열거형

이 열거형은 인코딩 로직을 조정하는 규칙을 정의합니다.

```csharp
public enum FontEncodingRules : byte
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Default | `0` | 인코딩 로직을 "있는 그대로" 유지 - PDF 사양에 따라 |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode는 입력 코드를 유니코드 기호로 디코딩하는 데 도움을 주는 특별한 메커니즘입니다. 사양에 따르면 특정 입력 코드에 대한 유니코드 기호를 얻기 위해 가장 먼저 사용해야 하는 메커니즘입니다. 그러나 일부 문서는 비표준 글꼴을 가지고 있으며 이러한 문서를 올바르게 변환하려면 ToUnicode 우선 순위를 낮추고 입력 코드를 디코딩하기 위해 다른 메커니즘을 사용할 필요가 있을 수 있습니다. |

### 참조

* 클래스 [HtmlSaveOptions](../htmlsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)
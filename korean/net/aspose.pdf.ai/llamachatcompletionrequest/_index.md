---
title: Class LlamaChatCompletionRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaChatCompletionRequest 클래스. ChatGPT API 요청을 위한 요청 본문을 나타냅니다.
type: docs
weight: 680
url: /ko/net/aspose.pdf.ai/llamachatcompletionrequest/
---
## LlamaChatCompletionRequest 클래스

ChatGPT API 요청을 위한 요청 본문을 나타냅니다.

```csharp
public class LlamaChatCompletionRequest
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LlamaChatCompletionRequest](llamachatcompletionrequest/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/llamachatcompletionrequest/frequencypenalty/) { get; set; } | 샘플링 중 사용할 빈도 패널티를 설정하거나 가져옵니다. |
| [LogitBias](../../aspose.pdf.ai/llamachatcompletionrequest/logitbias/) { get; set; } | 샘플링 중 사용할 로짓 편향을 설정하거나 가져옵니다. |
| [MaxTokens](../../aspose.pdf.ai/llamachatcompletionrequest/maxtokens/) { get; set; } | 채팅 완료에서 생성할 최대 토큰 수를 설정하거나 가져옵니다. 기본값은 null이며, 이는 무한을 의미합니다. |
| [Messages](../../aspose.pdf.ai/llamachatcompletionrequest/messages/) { get; set; } | 대화를 구성하는 메시지 목록을 설정하거나 가져옵니다. |
| [Model](../../aspose.pdf.ai/llamachatcompletionrequest/model/) { get; set; } | 사용할 모델의 ID를 설정하거나 가져옵니다. |
| [NumberOfChoices](../../aspose.pdf.ai/llamachatcompletionrequest/numberofchoices/) { get; set; } | 각 입력 메시지에 대해 생성할 채팅 완료 선택 수를 설정하거나 가져옵니다. |
| [PresencePenalty](../../aspose.pdf.ai/llamachatcompletionrequest/presencepenalty/) { get; set; } | 샘플링 중 사용할 존재 패널티를 설정하거나 가져옵니다. |
| [Stream](../../aspose.pdf.ai/llamachatcompletionrequest/stream/) { get; set; } | 응답을 스트리밍할지 여부를 설정하거나 가져옵니다. |
| [Temperature](../../aspose.pdf.ai/llamachatcompletionrequest/temperature/) { get; set; } | 사용할 샘플링 온도를 설정하거나 가져옵니다. 범위는 0에서 2 사이입니다. 0.8과 같은 높은 값은 출력을 더 무작위로 만들고, 0.2와 같은 낮은 값은 더 집중적이고 결정론적으로 만듭니다. 기본값은 1입니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)
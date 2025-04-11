---
title: Class LlamaClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaClient 클래스. Llama API와 상호작용하기 위한 클라이언트를 나타냅니다.
type: docs
weight: 700
url: /ko/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient 클래스

Llama API와 상호작용하기 위한 클라이언트를 나타냅니다.

Llama API와 상호작용하기 위한 클라이언트를 나타냅니다.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | 백오프 지연 시간을 초 단위로 가져오거나 설정합니다. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | 최대 HTTP 요청 재시도 횟수를 가져오거나 설정합니다. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | 폴링 간격을 초 단위로 가져오거나 설정합니다. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | 폴링 타임아웃을 초 단위로 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Llama 서비스에서 채팅 완료 요청을 생성합니다. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | [`AIClientBase`](../aiclientbase/)에서 사용하는 리소스를 해제합니다. |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | 지정된 옵션으로 [`ISummaryCopilot`](../isummarycopilot/)의 인스턴스를 가져옵니다. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | 제공된 API 키로 [`Builder`](../llamaclient.builder/)의 새 인스턴스를 생성합니다. |

## 기타 구성원

| 이름 | 설명 |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | `LlamaClient`의 인스턴스를 생성하기 위한 빌더 클래스입니다. |

### 참조

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)
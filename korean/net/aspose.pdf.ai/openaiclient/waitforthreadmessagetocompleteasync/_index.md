---
title: OpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 특정 스레드 메시지가 비동기적으로 완료될 때까지 기다립니다.
type: docs
weight: 480
url: /ko/net/aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/
---
## OpenAIClient.WaitForThreadMessageToCompleteAsync 메서드

특정 스레드 메시지가 비동기적으로 완료될 때까지 기다립니다.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 메시지를 포함하는 스레드의 ID입니다. |
| threadMessageId | String | 완료될 때까지 모니터링할 메시지의 ID입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 태스크입니다. 태스크 결과에는 메시지의 최종 상태가 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | 스레드 메시지 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [ThreadMessageResponse](../../threadmessageresponse/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
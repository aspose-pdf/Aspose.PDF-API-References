---
title: "OpenAIClient.WaitForThreadMessageToCompleteAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OpenAIClient 메서드. 특정 스레드 메시지가 비동기적으로 완료될 때까지 기다립니다."
type: docs
weight: 490
url: /ko/net/aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/
---
## OpenAIClient.WaitForThreadMessageToCompleteAsync method

특정 스레드 메시지가 완료될 때까지 비동기적으로 기다립니다.

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

비동기 작업을 나타내는 작업입니다. 작업 결과에는 메시지의 최종 상태가 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | thread message Id가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



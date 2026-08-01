---
title: "IOpenAIClient.WaitForAssistantMessageAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IOpenAIClient 메서드. 스레드 내에서 어시스턴트의 첫 번째 메시지를 비동기적으로 기다립니다."
type: docs
weight: 430
url: /ko/net/aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/
---
## IOpenAIClient.WaitForAssistantMessageAsync method

스레드 내에서 어시스턴트의 첫 번째 메시지를 비동기적으로 기다립니다.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 첫 번째 어시스턴트 메시지를 모니터링할 스레드의 ID. |
| queryParameters | ThreadMessageListQueryParameters | 메시지 목록을 필터링하기 위한 선택적 쿼리 매개변수입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 스레드 내 첫 번째 어시스턴트 메시지가 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



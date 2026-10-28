---
title: "IOpenAIClient.GetThreadMessageAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IOpenAIClient 메서드. 스레드 내 특정 메시지의 세부 정보를 비동기적으로 조회합니다"
type: docs
weight: 280
url: /ko/net/aspose.pdf.ai/iopenaiclient/getthreadmessageasync/
---
## IOpenAIClient.GetThreadMessageAsync method

스레드 내 특정 메시지의 세부 정보를 비동기적으로 가져옵니다.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 메시지를 포함하는 스레드의 ID입니다. |
| threadMessageId | String | 검색할 메시지의 ID. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 스레드 메시지의 세부 정보가 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | thread message Id가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [ThreadMessageResponse](../../threadmessageresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



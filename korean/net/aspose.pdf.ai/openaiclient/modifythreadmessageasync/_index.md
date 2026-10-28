---
title: "OpenAIClient.ModifyThreadMessageAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OpenAIClient 메서드. 스레드 내 기존 메시지를 비동기적으로 수정합니다."
type: docs
weight: 430
url: /ko/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## OpenAIClient.ModifyThreadMessageAsync method

스레드 내 기존 메시지를 비동기적으로 수정합니다.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 수정할 메시지를 포함하는 스레드의 ID입니다. |
| threadMessageId | String | 수정할 메시지의 ID입니다. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | 메시지 수정을 위한 요청 세부 정보입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 메시지 수정에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | thread message Id가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



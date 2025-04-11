---
title: OpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 스레드 내의 기존 메시지를 비동기적으로 수정합니다.
type: docs
weight: 420
url: /ko/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## OpenAIClient.ModifyThreadMessageAsync 메서드

스레드 내의 기존 메시지를 비동기적으로 수정합니다.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 수정할 메시지를 포함하는 스레드의 ID입니다. |
| threadMessageId | String | 수정할 메시지의 ID입니다. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | 메시지를 수정하기 위한 요청 세부정보입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 메시지 수정에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | 스레드 메시지 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [ThreadMessageResponse](../../threadmessageresponse/)
* 클래스 [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
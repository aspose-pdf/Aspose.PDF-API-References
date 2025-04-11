---
title: IOpenAIClient.DeleteThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 메서드. 스레드 내에서 메시지를 비동기적으로 삭제합니다.
type: docs
weight: 160
url: /ko/net/aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/
---
## IOpenAIClient.DeleteThreadMessageAsync 메서드

스레드 내에서 메시지를 비동기적으로 삭제합니다.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 삭제할 메시지가 포함된 스레드의 ID입니다. |
| threadMessageId | String | 삭제할 메시지의 ID입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 태스크입니다. 태스크 결과에는 삭제 작업의 상태가 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | 스레드 메시지 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [DeleteStatusResponse](../../deletestatusresponse/)
* 인터페이스 [IOpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
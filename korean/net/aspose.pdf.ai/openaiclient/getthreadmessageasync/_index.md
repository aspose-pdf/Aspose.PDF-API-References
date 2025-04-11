---
title: OpenAIClient.GetThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 스레드 내 특정 메시지의 세부 정보를 비동기적으로 검색합니다.
type: docs
weight: 310
url: /ko/net/aspose.pdf.ai/openaiclient/getthreadmessageasync/
---
## OpenAIClient.GetThreadMessageAsync 메서드

스레드 내 특정 메시지의 세부 정보를 비동기적으로 검색합니다.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | 문자열 | 메시지를 포함하는 스레드의 ID입니다. |
| threadMessageId | 문자열 | 검색할 메시지의 ID입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 태스크입니다. 태스크 결과에는 스레드 메시지의 세부 정보가 포함됩니다.

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
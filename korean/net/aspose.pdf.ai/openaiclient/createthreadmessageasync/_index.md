---
title: "OpenAIClient.CreateThreadMessageAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OpenAIClient 메서드. 스레드 내에서 새 메시지를 비동기적으로 생성합니다."
type: docs
weight: 80
url: /ko/net/aspose.pdf.ai/openaiclient/createthreadmessageasync/
---
## OpenAIClient.CreateThreadMessageAsync method

스레드 내 새 메시지를 비동기적으로 생성합니다.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 메시지가 생성될 스레드의 ID입니다. |
| threadMessageRequest | ThreadMessageCreateRequest | 메시지 생성을 위한 요청 세부 정보입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다. 작업 결과에는 메시지 생성에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



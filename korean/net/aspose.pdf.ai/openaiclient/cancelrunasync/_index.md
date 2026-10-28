---
title: "OpenAIClient.CancelRunAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OpenAIClient 메서드. 스레드 내 기존 실행을 비동기적으로 취소합니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf.ai/openaiclient/cancelrunasync/
---
## OpenAIClient.CancelRunAsync method

스레드 내 기존 실행을 비동기적으로 취소합니다.

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 취소할 실행이 포함된 스레드의 ID입니다. |
| runId | String | 취소할 실행의 ID입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 태스크입니다. 태스크 결과에는 실행 취소에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | run Id가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [RunResponse](../../runresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



---
title: OpenAIClient.GetRunAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 스레드 내에서 특정 실행의 세부 정보를 비동기적으로 검색합니다.
type: docs
weight: 250
url: /ko/net/aspose.pdf.ai/openaiclient/getrunasync/
---
## OpenAIClient.GetRunAsync 메서드

스레드 내에서 특정 실행의 세부 정보를 비동기적으로 검색합니다.

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 실행이 포함된 스레드의 ID입니다. |
| runId | String | 검색할 실행의 ID입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 태스크입니다. 태스크 결과에는 실행의 세부 정보가 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | 실행 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [RunResponse](../../runresponse/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
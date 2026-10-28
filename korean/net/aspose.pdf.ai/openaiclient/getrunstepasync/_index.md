---
title: "OpenAIClient.GetRunStepAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OpenAIClient 메서드. 실행 내 특정 단계의 세부 정보를 비동기적으로 가져옵니다"
type: docs
weight: 280
url: /ko/net/aspose.pdf.ai/openaiclient/getrunstepasync/
---
## OpenAIClient.GetRunStepAsync method

실행 내 특정 단계의 세부 정보를 비동기적으로 가져옵니다.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 실행을 포함하는 스레드의 ID입니다. |
| runId | String | 단계를 포함하는 실행의 ID입니다. |
| runStepId | String | 가져올 실행 단계의 ID입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 실행 단계의 세부 정보가 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | run Id가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | run step Id가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [RunStepResponse](../../runstepresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



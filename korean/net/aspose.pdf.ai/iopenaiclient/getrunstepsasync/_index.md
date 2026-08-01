---
title: "IOpenAIClient.GetRunStepsAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IOpenAIClient 메서드. 스레드 내 특정 실행에 대한 단계 목록을 비동기적으로 조회합니다"
type: docs
weight: 260
url: /ko/net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## IOpenAIClient.GetRunStepsAsync method

스레드 내 특정 실행에 대한 단계 목록을 비동기적으로 가져옵니다.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 실행을 포함하는 스레드의 ID입니다. |
| runId | String | 단계를 검색할 실행의 ID. |
| queryParameters | RunStepListQueryParameters | 실행 단계 목록을 필터링하기 위한 선택적 쿼리 매개변수. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다. 작업 결과에는 실행 단계 목록이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | run Id가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [RunStepListResponse](../../runsteplistresponse/)
* class [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



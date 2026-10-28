---
title: "IOpenAIClient.ModifyRunAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IOpenAIClient 메서드. 스레드 내 기존 실행을 비동기적으로 수정합니다"
type: docs
weight: 370
url: /ko/net/aspose.pdf.ai/iopenaiclient/modifyrunasync/
---
## IOpenAIClient.ModifyRunAsync method

스레드 내 기존 실행을 비동기적으로 수정합니다.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 실행을 포함하는 스레드의 ID입니다. |
| runId | String | 수정할 실행의 ID. |
| assistantModifyRequest | RunModifyRequest | 실행을 수정하기 위한 요청 세부 정보. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 실행 수정에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | run Id가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [RunResponse](../../runresponse/)
* class [RunModifyRequest](../../runmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



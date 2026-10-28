---
title: "IOpenAIClient.ModifyAssistantAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IOpenAIClient 메서드. 기존 어시스턴트를 비동기적으로 수정합니다"
type: docs
weight: 360
url: /ko/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## IOpenAIClient.ModifyAssistantAsync method

기존 어시스턴트를 비동기적으로 수정합니다.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| assistantId | String | 수정할 어시스턴트의 ID입니다. |
| assistantModifyRequest | AssistantModifyRequest | 수정 세부 정보를 포함하는 요청 객체입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다. 작업 결과에는 어시스턴트 수정에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | assistant Id가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [AssistantResponse](../../assistantresponse/)
* class [AssistantModifyRequest](../../assistantmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



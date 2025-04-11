---
title: OpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 기존 어시스턴트를 비동기적으로 수정합니다.
type: docs
weight: 390
url: /ko/net/aspose.pdf.ai/openaiclient/modifyassistantasync/
---
## OpenAIClient.ModifyAssistantAsync 메서드

기존 어시스턴트를 비동기적으로 수정합니다.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| assistantId | String | 수정할 어시스턴트의 ID입니다. |
| assistantModifyRequest | AssistantModifyRequest | 수정 세부정보를 포함하는 요청 객체입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 태스크입니다. 태스크 결과에는 어시스턴트 수정에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 어시스턴트 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [AssistantResponse](../../assistantresponse/)
* 클래스 [AssistantModifyRequest](../../assistantmodifyrequest/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
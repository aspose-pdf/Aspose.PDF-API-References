---
title: OpenAIClient.CreateAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 비동기적으로 새로운 어시스턴트를 생성합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf.ai/openaiclient/createassistantasync/
---
## OpenAIClient.CreateAssistantAsync 메서드

비동기적으로 새로운 어시스턴트를 생성합니다.

```csharp
public Task<AssistantResponse> CreateAssistantAsync(AssistantCreateRequest assistantCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| assistantCreateRequest | AssistantCreateRequest | 어시스턴트를 생성하기 위한 세부 정보를 포함하는 요청 객체입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 태스크입니다. 태스크 결과는 어시스턴트 생성에 대한 응답을 포함합니다.

### 참조

* 클래스 [AssistantResponse](../../assistantresponse/)
* 클래스 [AssistantCreateRequest](../../assistantcreaterequest/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
---
title: OpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 비동기적으로 어시스턴트 목록을 검색합니다.
type: docs
weight: 200
url: /ko/net/aspose.pdf.ai/openaiclient/getassistantsasync/
---
## OpenAIClient.GetAssistantsAsync 메서드

비동기적으로 어시스턴트 목록을 검색합니다.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | 어시스턴트 목록을 필터링하기 위한 선택적 쿼리 매개변수입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 어시스턴트 목록이 포함됩니다.

### 참조

* 클래스 [AssistantListResponse](../../assistantlistresponse/)
* 클래스 [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
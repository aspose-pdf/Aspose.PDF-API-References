---
title: OpenAIClient.ModifyThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 기존 스레드를 비동기적으로 수정합니다.
type: docs
weight: 410
url: /ko/net/aspose.pdf.ai/openaiclient/modifythreadasync/
---
## OpenAIClient.ModifyThreadAsync 메서드

기존 스레드를 비동기적으로 수정합니다.

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 수정할 스레드의 ID입니다. |
| threadModifyRequest | ThreadModifyRequest | 수정 세부정보를 포함하는 요청 객체입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 스레드 수정에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [ThreadResponse](../../threadresponse/)
* 클래스 [ThreadModifyRequest](../../threadmodifyrequest/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
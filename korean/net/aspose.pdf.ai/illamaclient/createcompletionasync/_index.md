---
title: ILlamaClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: ILlamaClient 메서드. Llama 서비스에서 채팅 완료 요청을 생성합니다.
type: docs
weight: 10
url: /ko/net/aspose.pdf.ai/illamaclient/createcompletionasync/
---
## ILlamaClient.CreateCompletionAsync 메서드

Llama 서비스에서 채팅 완료 요청을 생성합니다.

```csharp
public Task<LlamaChatCompletionResponse> CreateCompletionAsync(
    LlamaChatCompletionRequest chatCompletionRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| chatCompletionRequest | LlamaChatCompletionRequest | 채팅 완료 요청. |
| cancellationToken | Nullable`1 | 취소 토큰. |

### 반환 값

채팅 완료 응답.

### 참조

* 클래스 [LlamaChatCompletionResponse](../../llamachatcompletionresponse/)
* 클래스 [LlamaChatCompletionRequest](../../llamachatcompletionrequest/)
* 인터페이스 [ILlamaClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
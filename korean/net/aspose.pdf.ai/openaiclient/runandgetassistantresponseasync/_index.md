---
title: OpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 지정된 threadId와 runCreateRequest로 어시스턴트를 실행하고 비동기적으로 어시스턴트 응답을 가져옵니다.
type: docs
weight: 440
url: /ko/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## OpenAIClient.RunAndGetAssistantResponseAsync 메서드

지정된 threadId와 runCreateRequest로 어시스턴트를 실행하고 비동기적으로 어시스턴트 응답을 가져옵니다.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | 문자열 | 스레드의 ID. |
| runCreateRequest | RunCreateRequest | 실행 생성 요청. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항). |

### 반환 값

어시스턴트 응답 문자열을 포함하는 비동기 작업을 나타냅니다.

### 참조

* 클래스 [RunCreateRequest](../../runcreaterequest/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
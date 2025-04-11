---
title: IOpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 메서드. 지정된 스레드 내에서 비동기적으로 실행을 생성합니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.ai/iopenaiclient/createrunasync/
---
## IOpenAIClient.CreateRunAsync 메서드

지정된 스레드 내에서 비동기적으로 실행을 생성합니다.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 실행이 생성될 스레드의 ID입니다. |
| runCreateRequest | RunCreateRequest | 실행 생성을 위한 요청 세부정보입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 실행 생성에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [RunResponse](../../runresponse/)
* 클래스 [RunCreateRequest](../../runcreaterequest/)
* 인터페이스 [IOpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
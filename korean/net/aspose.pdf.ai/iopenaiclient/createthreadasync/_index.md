---
title: IOpenAIClient.CreateThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 메서드. 새 스레드를 비동기적으로 생성합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.ai/iopenaiclient/createthreadasync/
---
## IOpenAIClient.CreateThreadAsync 메서드

새 스레드를 비동기적으로 생성합니다.

```csharp
public Task<ThreadResponse> CreateThreadAsync(ThreadCreateRequest threadCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadCreateRequest | ThreadCreateRequest | 스레드를 생성하기 위한 세부 정보를 포함하는 요청 객체입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 스레드 생성에 대한 응답이 포함됩니다.

### 참조

* 클래스 [ThreadResponse](../../threadresponse/)
* 클래스 [ThreadCreateRequest](../../threadcreaterequest/)
* 인터페이스 [IOpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
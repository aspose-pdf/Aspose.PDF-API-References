---
title: OpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 비동기적으로 스레드와 그 안에서 실행을 생성합니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf.ai/openaiclient/createthreadandrunasync/
---
## OpenAIClient.CreateThreadAndRunAsync 메서드

비동기적으로 스레드와 그 안에서 실행을 생성합니다.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | 스레드와 실행을 생성하기 위한 요청 세부정보입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 태스크입니다. 태스크 결과에는 스레드 및 실행 생성에 대한 응답이 포함됩니다.

### 참조

* 클래스 [RunResponse](../../runresponse/)
* 클래스 [RunThreadCreateRequest](../../runthreadcreaterequest/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
---
title: OpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 지정된 스레드에 대한 실행 목록을 비동기적으로 검색합니다.
type: docs
weight: 260
url: /ko/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## OpenAIClient.GetRunsAsync 메서드

지정된 스레드에 대한 실행 목록을 비동기적으로 검색합니다.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | 문자열 | 실행을 검색할 스레드의 ID입니다. |
| queryParameters | RunListQueryParameters | 실행 목록을 필터링하기 위한 선택적 쿼리 매개변수입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 실행 목록이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [RunListResponse](../../runlistresponse/)
* 클래스 [RunListQueryParameters](../../runlistqueryparameters/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
---
title: "OpenAIClient.GetThreadAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OpenAIClient 메서드. 특정 스레드의 세부 정보를 비동기적으로 가져옵니다."
type: docs
weight: 310
url: /ko/net/aspose.pdf.ai/openaiclient/getthreadasync/
---
## OpenAIClient.GetThreadAsync method

특정 스레드의 세부 정보를 비동기적으로 가져옵니다.

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadId | String | 가져올 스레드의 ID입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 태스크입니다. 태스크 결과에는 스레드의 세부 정보가 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 스레드 ID가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [ThreadResponse](../../threadresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



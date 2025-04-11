---
title: OpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 특정 벡터 저장소 파일 배치를 비동기적으로 취소합니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/
---
## OpenAIClient.CancelVectorStoreFileBatchAsync 메서드

특정 벡터 저장소 파일 배치를 비동기적으로 취소합니다.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreId | String | 취소할 파일 배치를 포함하는 벡터 저장소의 ID입니다. |
| fileBatchId | String | 취소할 파일 배치의 ID입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 태스크입니다. 태스크 결과는 파일 배치를 취소한 응답을 포함합니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 벡터 저장소 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | 벡터 저장소 파일 배치 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
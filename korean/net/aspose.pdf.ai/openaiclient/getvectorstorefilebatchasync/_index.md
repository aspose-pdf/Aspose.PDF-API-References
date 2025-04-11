---
title: OpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 특정 벡터 저장소 파일 배치의 세부 정보를 비동기적으로 검색합니다.
type: docs
weight: 350
url: /ko/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/
---
## OpenAIClient.GetVectorStoreFileBatchAsync 메서드

특정 벡터 저장소 파일 배치의 세부 정보를 비동기적으로 검색합니다.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreId | 문자열 | 파일 배치를 포함하는 벡터 저장소의 ID입니다. |
| fileBatchId | 문자열 | 검색할 파일 배치의 ID입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 파일 배치의 세부 정보가 포함됩니다.

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
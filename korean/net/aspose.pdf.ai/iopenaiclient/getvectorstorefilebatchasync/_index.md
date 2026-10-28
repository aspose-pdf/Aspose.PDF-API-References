---
title: "IOpenAIClient.GetVectorStoreFileBatchAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IOpenAIClient 메서드. 특정 벡터 스토어 파일 배치를 비동기적으로 조회합니다"
type: docs
weight: 320
url: /ko/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/
---
## IOpenAIClient.GetVectorStoreFileBatchAsync method

특정 벡터 스토어 파일 배치의 세부 정보를 비동기적으로 가져옵니다.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreId | String | 파일 배치를 포함하는 벡터 스토어의 ID. |
| fileBatchId | String | 검색할 파일 배치의 ID. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다. 작업 결과에는 파일 배치의 세부 정보가 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 벡터 저장소 Id가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | 벡터 스토어 파일 배치 Id가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



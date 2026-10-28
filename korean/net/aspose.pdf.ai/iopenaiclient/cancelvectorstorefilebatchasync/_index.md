---
title: "IOpenAIClient.CancelVectorStoreFileBatchAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IOpenAIClient 메서드. 특정 벡터 스토어 파일 배치를 비동기적으로 취소합니다"
type: docs
weight: 20
url: /ko/net/aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/
---
## IOpenAIClient.CancelVectorStoreFileBatchAsync method

특정 벡터 저장소 파일 배치를 비동기적으로 취소합니다.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreId | String | 취소할 파일 배치를 포함하는 벡터 스토어의 ID. |
| fileBatchId | String | 취소할 파일 배치의 ID. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 파일 배치를 취소한 응답이 포함됩니다.

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



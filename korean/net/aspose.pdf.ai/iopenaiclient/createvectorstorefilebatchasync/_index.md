---
title: "IOpenAIClient.CreateVectorStoreFileBatchAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IOpenAIClient 메서드. 새로운 벡터 스토어 파일 배치를 비동기적으로 생성합니다"
type: docs
weight: 120
url: /ko/net/aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/
---
## IOpenAIClient.CreateVectorStoreFileBatchAsync method

새 벡터 저장소 파일 배치를 비동기적으로 생성합니다.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreId | String | 파일 배치가 생성될 벡터 스토어의 ID입니다. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | 파일 배치를 생성하기 위한 세부 정보를 포함하는 요청 객체입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다. 작업 결과에는 파일 배치 생성에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 벡터 저장소 Id가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



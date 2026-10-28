---
title: "IOpenAIClient.GetVectorStoresAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IOpenAIClient 메서드. 벡터 스토어 목록을 비동기적으로 검색합니다"
type: docs
weight: 350
url: /ko/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## IOpenAIClient.GetVectorStoresAsync method

벡터 스토어 목록을 비동기적으로 가져옵니다.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | 벡터 스토어 목록을 필터링하기 위한 선택적 쿼리 매개변수입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다. 작업 결과에는 벡터 스토어 목록이 포함됩니다.

### 또 보기

* class [VectorStoreListResponse](../../vectorstorelistresponse/)
* class [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



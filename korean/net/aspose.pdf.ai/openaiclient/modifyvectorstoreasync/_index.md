---
title: "OpenAIClient.ModifyVectorStoreAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OpenAIClient 메서드. 기존 벡터 저장소를 비동기적으로 수정합니다."
type: docs
weight: 440
url: /ko/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/
---
## OpenAIClient.ModifyVectorStoreAsync method

기존 벡터 저장소를 비동기적으로 수정합니다.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreId | String | 수정할 벡터 저장소의 ID입니다. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | 수정 세부 정보를 포함하는 요청 객체입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다. 작업 결과에는 벡터 저장소 수정에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 벡터 저장소 Id가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



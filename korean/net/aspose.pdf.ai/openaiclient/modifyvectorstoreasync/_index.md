---
title: OpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 기존 벡터 저장소를 비동기적으로 수정합니다.
type: docs
weight: 430
url: /ko/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/
---
## OpenAIClient.ModifyVectorStoreAsync 메서드

기존 벡터 저장소를 비동기적으로 수정합니다.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreId | 문자열 | 수정할 벡터 저장소의 ID입니다. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | 수정 세부정보를 포함하는 요청 객체입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 벡터 저장소 수정에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 벡터 저장소 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [VectorStoreResponse](../../vectorstoreresponse/)
* 클래스 [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
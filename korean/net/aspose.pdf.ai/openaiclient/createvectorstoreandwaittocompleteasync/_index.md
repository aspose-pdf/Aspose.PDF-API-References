---
title: OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 새로운 벡터 저장소를 생성하고 비동기적으로 완료될 때까지 기다립니다.
type: docs
weight: 90
url: /ko/net/aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/
---
## OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync 메서드

새로운 벡터 저장소를 생성하고 비동기적으로 완료될 때까지 기다립니다.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | 벡터 저장소 생성을 위한 세부 정보를 포함하는 요청 객체입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 태스크입니다. 태스크 결과는 완료 후 벡터 저장소 생성의 응답을 포함합니다.

### 참조

* 클래스 [VectorStoreResponse](../../vectorstoreresponse/)
* 클래스 [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
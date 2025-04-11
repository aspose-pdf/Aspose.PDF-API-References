---
title: IOpenAIClient.CreateVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 메서드. 새로운 벡터 저장소를 비동기적으로 생성합니다.
type: docs
weight: 100
url: /ko/net/aspose.pdf.ai/iopenaiclient/createvectorstoreasync/
---
## IOpenAIClient.CreateVectorStoreAsync 메서드

새로운 벡터 저장소를 비동기적으로 생성합니다.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | 벡터 저장소 생성을 위한 세부 정보를 포함하는 요청 객체입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 벡터 저장소 생성에 대한 응답이 포함됩니다.

### 참조

* 클래스 [VectorStoreResponse](../../vectorstoreresponse/)
* 클래스 [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* 인터페이스 [IOpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
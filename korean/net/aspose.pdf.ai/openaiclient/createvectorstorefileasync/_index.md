---
title: "OpenAIClient.CreateVectorStoreFileAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OpenAIClient 메서드. 새 벡터 저장소 파일을 비동기적으로 생성합니다"
type: docs
weight: 110
url: /ko/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/
---
## OpenAIClient.CreateVectorStoreFileAsync method

새 벡터 저장소 파일을 비동기적으로 생성합니다.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreId | String | 파일이 생성될 벡터 저장소의 ID. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | 파일 생성을 위한 세부 정보를 포함하는 요청 객체. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 파일 생성에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 벡터 저장소 Id가 null이거나 비어 있을 때 발생합니다. |

### 또 보기

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



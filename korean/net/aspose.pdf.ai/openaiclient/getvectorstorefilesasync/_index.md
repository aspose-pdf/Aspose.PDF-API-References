---
title: OpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 특정 벡터 저장소 내의 파일 목록을 비동기적으로 검색합니다.
type: docs
weight: 370
url: /ko/net/aspose.pdf.ai/openaiclient/getvectorstorefilesasync/
---
## OpenAIClient.GetVectorStoreFilesAsync 메서드

특정 벡터 저장소 내의 파일 목록을 비동기적으로 검색합니다.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreId | 문자열 | 파일이 포함된 벡터 저장소의 ID입니다. |
| queryParameters | VectorStoreFileListQueryParameters | 파일 목록을 필터링하기 위한 선택적 쿼리 매개변수입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 벡터 저장소 내의 파일 목록이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 벡터 저장소 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* 클래스 [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
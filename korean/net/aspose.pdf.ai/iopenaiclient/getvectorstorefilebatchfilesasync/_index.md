---
title: IOpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 메서드. 특정 벡터 저장소 파일 배치 내의 파일 목록을 비동기적으로 검색합니다.
type: docs
weight: 330
url: /ko/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## IOpenAIClient.GetVectorStoreFileBatchFilesAsync 메서드

특정 벡터 저장소 파일 배치 내의 파일 목록을 비동기적으로 검색합니다.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreId | 문자열 | 파일 배치를 포함하는 벡터 저장소의 ID입니다. |
| fileBatchId | 문자열 | 파일을 검색할 파일 배치의 ID입니다. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | 파일 목록을 필터링하기 위한 선택적 쿼리 매개변수입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 파일 배치 내의 파일 목록이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 벡터 저장소 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | 벡터 저장소 파일 배치 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* 클래스 [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* 인터페이스 [IOpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
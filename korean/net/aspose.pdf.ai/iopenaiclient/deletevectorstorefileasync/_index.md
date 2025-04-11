---
title: IOpenAIClient.DeleteVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 메서드. 벡터 저장소 내의 파일을 비동기적으로 삭제합니다.
type: docs
weight: 180
url: /ko/net/aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/
---
## IOpenAIClient.DeleteVectorStoreFileAsync 메서드

벡터 저장소 내의 파일을 비동기적으로 삭제합니다.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vectorStoreId | 문자열 | 삭제할 파일이 포함된 벡터 저장소의 ID입니다. |
| fileId | 문자열 | 삭제할 파일의 ID입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 삭제 작업의 상태가 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 벡터 저장소 ID가 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | 파일 ID가 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [DeleteStatusResponse](../../deletestatusresponse/)
* 인터페이스 [IOpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
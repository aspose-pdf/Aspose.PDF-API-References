---
title: OpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 메서드. 지정된 목적에 따라 비동기적으로 파일 목록을 검색합니다.
type: docs
weight: 230
url: /ko/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## OpenAIClient.GetFilesAsync 메서드

지정된 목적에 따라 비동기적으로 파일 목록을 검색합니다.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| purpose | String | 선택 사항. 검색할 파일의 목적입니다. null인 경우 모든 목적의 파일이 검색됩니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 파일 목록이 포함됩니다.

### 참조

* 클래스 [FileListResponse](../../filelistresponse/)
* 클래스 [OpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
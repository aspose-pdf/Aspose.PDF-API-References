---
title: "IOpenAIClient.GetFilesAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IOpenAIClient 메서드. 지정된 목적에 따라 파일 목록을 비동기적으로 검색합니다."
type: docs
weight: 220
url: /ko/net/aspose.pdf.ai/iopenaiclient/getfilesasync/
---
## IOpenAIClient.GetFilesAsync method

지정된 목적에 따라 파일 목록을 비동기적으로 가져옵니다.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| purpose | String | 옵션. 가져올 파일의 목적입니다. null이면 모든 목적의 파일을 가져옵니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 파일 목록이 포함됩니다.

### 또 보기

* class [FileListResponse](../../filelistresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



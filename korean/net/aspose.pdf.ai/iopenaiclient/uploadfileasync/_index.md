---
title: IOpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 메서드. OpenAI 서버에 파일을 비동기적으로 업로드합니다.
type: docs
weight: 420
url: /ko/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## IOpenAIClient.UploadFileAsync 메서드

OpenAI 서버에 파일을 비동기적으로 업로드합니다.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| purpose | String | 파일 업로드의 목적, 일반적으로 파일이 어떻게 사용될지를 설명합니다. |
| fileName | String | 업로드할 파일의 이름입니다. |
| fileBytes | Byte[] | 파일 데이터를 포함하는 바이트 배열입니다. |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 태스크입니다. 태스크 결과에는 파일 업로드에 대한 응답이 포함됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 파일 목적이 null이거나 비어 있을 때 발생합니다. |
| [AIClientException](../../aiclientexception/) | 파일 이름이 null이거나 비어 있을 때 발생합니다. |

### 참조

* 클래스 [FileResponse](../../fileresponse/)
* 인터페이스 [IOpenAIClient](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
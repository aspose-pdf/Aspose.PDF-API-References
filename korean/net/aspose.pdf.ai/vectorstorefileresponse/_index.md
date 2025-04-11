---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileResponse 클래스. 벡터 저장소 파일 응답
type: docs
weight: 1350
url: /ko/net/aspose.pdf.ai/vectorstorefileresponse/
---
## VectorStoreFileResponse 클래스

벡터 저장소 파일 응답.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | 벡터 저장소 파일이 생성된 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 응답 세부 정보를 가져오거나 설정합니다. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 응답 오류를 가져오거나 설정합니다. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 오류 정보를 가져오거나 설정합니다. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 응답 헤더를 가져오거나 설정합니다. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP 상태 코드를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | API 엔드포인트에서 참조할 수 있는 식별자를 가져오거나 설정합니다. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 응답이 성공적이었는지 여부를 나타냅니다. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | 이 벡터 저장소 파일과 관련된 마지막 오류를 가져오거나 설정합니다. 오류가 없으면 null입니다. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | 항상 vector_store.file인 객체 유형을 가져오거나 설정합니다. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 오류 이유 구문을 가져옵니다. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | 벡터 저장소 파일의 상태를 가져오거나 설정합니다. 상태는 in_progress, completed, cancelled 또는 failed일 수 있습니다. 상태 completed는 벡터 저장소 파일이 사용 준비가 되었음을 나타냅니다. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | 총 벡터 저장소 사용량(바이트 단위)을 가져오거나 설정합니다. 이는 원본 파일 크기와 다를 수 있습니다. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | 파일이 연결된 벡터 저장소의 ID를 가져오거나 설정합니다. |

### 참조

* 클래스 [BaseResponse](../baseresponse/)
* 인터페이스 [IStatus](../istatus/)
* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)
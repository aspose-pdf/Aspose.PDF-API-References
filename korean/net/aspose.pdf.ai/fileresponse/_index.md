---
title: Class FileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.FileResponse 클래스. FileResponse 객체는 OpenAI에 업로드된 문서를 나타냅니다.
type: docs
weight: 400
url: /ko/net/aspose.pdf.ai/fileresponse/
---
## FileResponse 클래스

FileResponse 객체는 OpenAI에 업로드된 문서를 나타냅니다.

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FileResponse](fileresponse/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | 파일의 크기를 바이트 단위로 가져오거나 설정합니다. |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | 파일이 생성된 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 응답 세부 정보를 가져오거나 설정합니다. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 응답 오류를 가져오거나 설정합니다. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 오류 정보를 가져옵니다. |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | 파일의 이름을 가져오거나 설정합니다. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 응답 헤더를 가져오거나 설정합니다. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP 상태 코드를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | API 엔드포인트에서 참조할 수 있는 파일 식별자를 가져오거나 설정합니다. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 응답이 성공적이었는지 여부를 나타냅니다. |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | 항상 파일인 객체 유형을 가져오거나 설정합니다. |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | 파일의 의도된 목적을 가져오거나 설정합니다. 지원되는 값은 assistants, assistants_output, batch, batch_output, fine-tune, fine-tune-results 및 vision입니다. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 오류 이유 구문을 가져옵니다. |

### 참조

* 클래스 [BaseResponse](../baseresponse/)
* 인터페이스 [IEntityId](../ientityid/)
* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)
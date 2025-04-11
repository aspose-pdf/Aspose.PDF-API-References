---
title: Class ThreadResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadResponse 클래스. 메시지를 포함하는 스레드를 나타냅니다.
type: docs
weight: 1180
url: /ko/net/aspose.pdf.ai/threadresponse/
---
## ThreadResponse 클래스

메시지를 포함하는 스레드를 나타냅니다.

```csharp
public class ThreadResponse : BaseResponse
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ThreadResponse](threadresponse/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | 스레드가 생성된 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 응답 세부 정보를 가져오거나 설정합니다. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 응답 오류를 가져오거나 설정합니다. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 오류 정보를 가져오거나 설정합니다. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 응답 헤더를 가져오거나 설정합니다. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP 상태 코드를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | API 엔드포인트에서 참조할 수 있는 식별자를 가져오거나 설정합니다. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 응답이 성공적이었는지를 나타냅니다. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | 객체에 첨부할 수 있는 16개의 키-값 쌍을 가져오거나 설정합니다. 이는 객체에 대한 추가 정보를 구조화된 형식으로 저장하는 데 유용할 수 있습니다. 키는 최대 64자 길이일 수 있으며 값은 최대 512자 길이일 수 있습니다. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | 항상 스레드인 객체 유형을 가져오거나 설정합니다. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 오류 이유 구문을 가져옵니다. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | 이 스레드에서 도우미 도구에 제공되는 리소스 집합을 가져오거나 설정합니다. 리소스는 도구 유형에 따라 다릅니다. 예를 들어, code_interpreter 도구는 파일 ID 목록이 필요하고, file_search 도구는 벡터 저장소 ID 목록이 필요합니다. |

### 참조

* 클래스 [BaseResponse](../baseresponse/)
* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)
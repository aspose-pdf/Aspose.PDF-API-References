---
title: "클래스 ThreadMessageResponse"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.ThreadMessageResponse 클래스. 스레드 내의 메시지를 나타냅니다"
type: docs
weight: 1250
url: /ko/net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse class

스레드 내의 메시지를 나타냅니다.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | 해당되는 경우, 이 메시지를 작성한 어시스턴트의 ID를 가져오거나 설정합니다. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | 메시지에 첨부된 파일 목록을 가져오거나 설정합니다. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | 메시지가 완료된 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | 메시지의 내용을 텍스트 및/또는 이미지 배열로 가져오거나 설정합니다. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | 메시지가 생성된 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 응답 세부 정보를 가져오거나 설정합니다. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 응답 오류를 가져오거나 설정합니다. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 오류 정보를 가져오거나 설정합니다. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 응답 헤더를 가져오거나 설정합니다. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP 상태 코드를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | API 엔드포인트에서 참조할 수 있는 식별자를 가져오거나 설정합니다. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | 메시지가 미완료로 표시된 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | 미완료 메시지를 가져오거나 설정합니다. 메시지가 미완료인 이유에 대한 세부 정보입니다. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 응답이 성공했는지 여부를 나타냅니다. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | 객체에 첨부할 수 있는 16개의 키-값 쌍을 가져오거나 설정합니다. 이는 객체에 대한 추가 정보를 구조화된 형식으로 저장하는 데 유용합니다. 키는 최대 64자, 값은 최대 512자까지 가능합니다. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | 객체 유형을 가져오거나 설정합니다. 항상 "thread.message"입니다. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 오류 이유 구문을 가져옵니다. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | 메시지를 생성한 엔터티를 가져오거나 설정합니다. "user" 또는 "assistant" 중 하나입니다. |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | 이 메시지 생성과 연관된 실행의 ID를 가져오거나 설정합니다. 메시지를 수동으로 생성할 경우 값은 null입니다. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | 메시지의 상태를 가져오거나 설정합니다. queued, in_progress, requires_action, completed 중 하나입니다. |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | 이 메시지가 속한 스레드의 ID를 가져오거나 설정합니다. |

### 또 보기

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)



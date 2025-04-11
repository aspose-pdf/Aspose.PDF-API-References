---
title: Class ThreadMessageResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ThreadMessageResponse 클래스. 스레드 내의 메시지를 나타냅니다.
type: docs
weight: 1160
url: /ko/net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse 클래스

스레드 내의 메시지를 나타냅니다.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | 이 메시지를 작성한 어시스턴트의 ID를 가져오거나 설정합니다. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | 메시지에 첨부된 파일 목록을 가져오거나 설정합니다. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | 메시지가 완료된 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | 텍스트 및/또는 이미지 배열로 메시지의 내용을 가져오거나 설정합니다. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | 메시지가 생성된 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 응답 세부 정보를 가져오거나 설정합니다. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 응답 오류를 가져오거나 설정합니다. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 오류 정보를 가져옵니다. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 응답 헤더를 가져오거나 설정합니다. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP 상태 코드를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | API 엔드포인트에서 참조할 수 있는 식별자를 가져오거나 설정합니다. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | 메시지가 불완전하다고 표시된 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | 불완전한 메시지와 메시지가 불완전한 이유에 대한 세부 정보를 가져오거나 설정합니다. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 응답이 성공적이었는지를 나타냅니다. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | 객체에 첨부할 수 있는 16개의 키-값 쌍을 가져오거나 설정합니다. 이는 객체에 대한 추가 정보를 구조화된 형식으로 저장하는 데 유용할 수 있습니다. 키는 최대 64자, 값은 최대 512자까지 가능합니다. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | 항상 "thread.message"인 객체 유형을 가져오거나 설정합니다. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 오류 이유 구문을 가져옵니다. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | 메시지를 생성한 엔티티를 가져오거나 설정합니다. "user" 또는 "assistant" 중 하나입니다. |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | 이 메시지 생성과 관련된 실행의 ID를 가져오거나 설정합니다. 메시지가 수동으로 생성될 때 값은 null입니다. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | 메시지의 상태를 가져오거나 설정합니다. queued, in_progress, requires_action 또는 completed 중 하나입니다. |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | 이 메시지가 속한 스레드의 ID를 가져오거나 설정합니다. |

### 참조

* 클래스 [BaseResponse](../baseresponse/)
* 인터페이스 [IStatus](../istatus/)
* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)
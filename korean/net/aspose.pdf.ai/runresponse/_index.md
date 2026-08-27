---
title: "클래스 RunResponse"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.RunResponse 클래스. 스레드에서 실행되는 실행을 나타냅니다."
type: docs
weight: 1100
url: /ko/net/aspose.pdf.ai/runresponse/
---
## RunResponse class

스레드에서 실행되는 런을 나타냅니다.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RunResponse](runresponse/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | 이 실행을 수행하는 데 사용된 어시스턴트의 ID를 가져오거나 설정합니다. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | 실행이 취소된 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | 실행이 완료된 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | 실행이 생성된 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 응답 세부 정보를 가져오거나 설정합니다. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 응답 오류를 가져오거나 설정합니다. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 오류 정보를 가져오거나 설정합니다. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | 실행이 만료될 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | 실행이 실패한 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 응답 헤더를 가져오거나 설정합니다. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP 상태 코드를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | API 엔드포인트에서 참조할 수 있는 식별자를 가져오거나 설정합니다. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | 실행이 불완전한 이유에 대한 세부 정보를 가져오거나 설정합니다. 실행이 불완전하지 않은 경우 null이 됩니다. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | 이 실행에 대해 어시스턴트가 사용한 지시사항을 가져오거나 설정합니다. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 응답이 성공했는지 여부를 나타냅니다. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | 이 실행과 연결된 마지막 오류를 가져오거나 설정합니다. 오류가 없으면 null이 됩니다. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | 실행 동안 사용된 것으로 지정된 최대 완료 토큰 수를 가져오거나 설정합니다. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | 실행 동안 사용된 것으로 지정된 최대 프롬프트 토큰 수를 가져오거나 설정합니다. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | 객체에 첨부할 수 있는 16개의 키-값 쌍을 가져오거나 설정합니다. 이는 객체에 대한 추가 정보를 구조화된 형식으로 저장하는 데 유용합니다. 키는 최대 64자, 값은 최대 512자까지 가능합니다. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | 이 실행에 대해 어시스턴트가 사용한 모델을 가져오거나 설정합니다. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | 객체 유형을 가져오거나 설정합니다. 이 값은 항상 thread.run입니다. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 오류 이유 구문을 가져옵니다. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | 런을 계속하기 위해 필요한 작업에 대한 세부 정보를 가져오거나 설정합니다. 작업이 필요하지 않으면 null이 됩니다. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | 모델이 출력해야 하는 형식을 가져오거나 설정합니다. GPT-4o, GPT-4 Turbo 및 gpt-3.5-turbo-1106 이후의 모든 GPT-3.5 Turbo 모델과 호환됩니다. { \"type\": \"json_object\" } 로 설정하면 JSON 모드가 활성화되어 모델이 생성하는 메시지가 유효한 JSON임을 보장합니다. 중요: JSON 모드를 사용할 때는 시스템 또는 사용자 메시지를 통해 모델에게 직접 JSON을 생성하도록 지시해야 합니다. 이를 하지 않으면 모델이 토큰 제한에 도달할 때까지 공백 스트림을 무한히 생성할 수 있어 요청이 오래 지속되고 \"멈춘\" 것처럼 보일 수 있습니다. 또한 finish_reason=\"length\"인 경우 메시지 내용이 부분적으로 잘릴 수 있는데, 이는 생성이 max_tokens를 초과했거나 대화가 최대 컨텍스트 길이를 초과했음을 나타냅니다. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | 런이 시작된 시점을 나타내는 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | 런의 상태를 가져오거나 설정합니다. 상태는 queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete, 또는 expired 중 하나가 될 수 있습니다. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | 이 런에 사용되는 샘플링 온도를 가져오거나 설정합니다. 설정하지 않으면 기본값은 1입니다. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | 이 런의 일부로 실행된 스레드의 ID를 가져오거나 설정합니다. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | 모델이 호출하는 도구(있는 경우)를 가져오거나 설정합니다. none은 모델이 도구를 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 기본값이며 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것을 선택할 수 있음을 의미합니다. required는 모델이 사용자에게 응답하기 전에 하나 이상의 도구를 반드시 호출해야 함을 의미합니다. {\"type\": \"file_search\"} 또는 {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}}와 같이 특정 도구를 지정하면 모델이 해당 도구를 호출하도록 강제합니다. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | 이 런에서 어시스턴트가 사용한 도구 목록을 가져오거나 설정합니다. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | 이 런에 사용되는 누클리어 샘플링 값을 가져오거나 설정합니다. 설정하지 않으면 기본값은 1입니다. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | 런 전에 스레드가 어떻게 잘릴지를 제어하는 트렁케이션 전략을 가져오거나 설정합니다. 이를 사용하여 런의 초기 컨텍스트 윈도우를 제어합니다. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | 런과 관련된 사용 통계를 가져오거나 설정합니다. 런이 종료 상태가 아니면(예: in_progress, queued 등) 이 값은 null이 됩니다. |

### 또 보기

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)



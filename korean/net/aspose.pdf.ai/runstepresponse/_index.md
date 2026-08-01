---
title: "클래스 RunStepResponse"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.RunStepResponse 클래스. 실행의 단계를 나타냅니다."
type: docs
weight: 1140
url: /ko/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse class

런 실행 중의 단계를 나타냅니다.

```csharp
public class RunStepResponse : BaseResponse
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | 실행 단계와 연결된 어시스턴트의 ID를 가져오거나 설정합니다. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | 실행 단계가 취소된 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | 실행 단계가 완료된 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | 실행 단계가 생성된 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 응답 세부 정보를 가져오거나 설정합니다. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 응답 오류를 가져오거나 설정합니다. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 오류 정보를 가져오거나 설정합니다. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | 실행 단계가 만료된 Unix 타임스탬프(초)를 가져오거나 설정합니다. 단계는 상위 실행이 만료된 경우 만료된 것으로 간주됩니다. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | 실행 단계가 실패한 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 응답 헤더를 가져오거나 설정합니다. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP 상태 코드를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | API 엔드포인트에서 참조할 수 있는 실행 단계의 식별자를 가져오거나 설정합니다. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 응답이 성공했는지 여부를 나타냅니다. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | 이 실행 단계와 관련된 마지막 오류를 가져오거나 설정합니다. 오류가 없으면 null이 됩니다. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | 객체에 첨부할 수 있는 16개의 키-값 쌍을 가져오거나 설정합니다. 이는 객체에 대한 추가 정보를 구조화된 형식으로 저장하는 데 유용합니다. 키는 최대 64자, 값은 최대 512자까지 가능합니다. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | 객체 유형을 가져오거나 설정합니다. 이 값은 항상 thread.run.step입니다. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 오류 이유 구문을 가져옵니다. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | 이 실행 단계가 속한 실행의 ID를 가져오거나 설정합니다. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | 실행 단계 유형을 가져오거나 설정합니다. 이 값은 message_creation 또는 tool_calls 중 하나일 수 있습니다. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | 실행 단계의 상태를 가져오거나 설정합니다. 상태는 in_progress, cancelled, failed, completed, 또는 expired 중 하나일 수 있습니다. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | 실행 단계의 세부 정보를 가져오거나 설정합니다. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | 실행된 스레드의 ID를 가져오거나 설정합니다. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | 실행 단계와 관련된 사용 통계를 가져오거나 설정합니다. 실행 단계의 상태가 in_progress인 동안 이 값은 null이 됩니다. |

### 또 보기

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)



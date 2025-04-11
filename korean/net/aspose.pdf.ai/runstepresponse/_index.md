---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunStepResponse 클래스. 실행 단계의 단계를 나타냅니다.
type: docs
weight: 1060
url: /ko/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse 클래스

실행 단계의 단계를 나타냅니다.

```csharp
public class RunStepResponse : BaseResponse
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | 실행 단계와 관련된 보조자의 ID를 가져오거나 설정합니다. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | 실행 단계가 취소된 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | 실행 단계가 완료된 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | 실행 단계가 생성된 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 응답 세부 정보를 가져오거나 설정합니다. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 응답 오류를 가져오거나 설정합니다. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 오류 정보를 가져옵니다. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | 실행 단계가 만료된 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. 부모 실행이 만료된 경우 단계는 만료된 것으로 간주됩니다. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | 실행 단계가 실패한 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 응답 헤더를 가져오거나 설정합니다. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP 상태 코드를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | API 엔드포인트에서 참조할 수 있는 실행 단계의 식별자를 가져오거나 설정합니다. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 응답이 성공적인지 여부를 나타냅니다. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | 이 실행 단계와 관련된 마지막 오류를 가져오거나 설정합니다. 오류가 없으면 null입니다. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | 객체에 첨부할 수 있는 16개의 키-값 쌍을 가져오거나 설정합니다. 이는 객체에 대한 추가 정보를 구조화된 형식으로 저장하는 데 유용할 수 있습니다. 키는 최대 64자, 값은 최대 512자까지 가능합니다. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | 항상 thread.run.step인 객체 유형을 가져오거나 설정합니다. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 오류 이유 구문을 가져옵니다. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | 이 실행 단계가 속한 실행의 ID를 가져오거나 설정합니다. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | 실행 단계의 유형을 가져오거나 설정합니다. 유형은 message_creation 또는 tool_calls일 수 있습니다. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | 실행 단계의 상태를 가져오거나 설정합니다. 상태는 in_progress, cancelled, failed, completed 또는 expired일 수 있습니다. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | 실행 단계의 세부 정보를 가져오거나 설정합니다. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | 실행된 스레드의 ID를 가져오거나 설정합니다. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | 실행 단계와 관련된 사용 통계를 가져오거나 설정합니다. 실행 단계의 상태가 in_progress인 동안 이 값은 null입니다. |

### 참조

* 클래스 [BaseResponse](../baseresponse/)
* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)
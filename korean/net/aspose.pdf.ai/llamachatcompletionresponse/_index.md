---
title: Class LlamaChatCompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaChatCompletionResponse 클래스. 제공된 입력을 기반으로 모델에 의해 반환된 채팅 완료 응답을 나타냅니다.
type: docs
weight: 690
url: /ko/net/aspose.pdf.ai/llamachatcompletionresponse/
---
## LlamaChatCompletionResponse 클래스

제공된 입력을 기반으로 모델에 의해 반환된 채팅 완료 응답을 나타냅니다.

```csharp
public class LlamaChatCompletionResponse : BaseResponse
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LlamaChatCompletionResponse](llamachatcompletionresponse/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Choices](../../aspose.pdf.ai/llamachatcompletionresponse/choices/) { get; set; } | 채팅 완료 선택 목록을 가져오거나 설정합니다. n이 1보다 크면 여러 개일 수 있습니다. |
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | 채팅 완료가 생성된 Unix 타임스탬프(초 단위)를 가져오거나 설정합니다. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 응답 세부 정보를 가져오거나 설정합니다. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 응답 오류를 가져오거나 설정합니다. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 오류 정보를 가져오거나 설정합니다. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 응답 헤더를 가져오거나 설정합니다. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP 상태 코드를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | 채팅 완료에 대한 고유 식별자를 가져오거나 설정합니다. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 응답이 성공적이었는지 여부를 나타냅니다. |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | 채팅 완료에 사용된 모델을 가져오거나 설정합니다. |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | 항상 chat.completion인 객체 유형을 가져오거나 설정합니다. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 오류 이유 구문을 가져옵니다. |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | 모델이 실행되는 백엔드 구성을 나타내는 지문을 가져오거나 설정합니다. |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | 완료 요청에 대한 사용 통계를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | 첫 번째 선택의 문자열 표현을 반환합니다. |

### 참조

* 클래스 [BaseResponse](../baseresponse/)
* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)
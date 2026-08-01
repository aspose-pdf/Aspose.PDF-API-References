---
title: "클래스 CompletionResponse"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.CompletionResponse 클래스. 제공된 입력을 기반으로 모델이 반환하는 채팅 완료 응답을 나타냅니다."
type: docs
weight: 250
url: /ko/net/aspose.pdf.ai/completionresponse/
---
## CompletionResponse class

제공된 입력을 기반으로 모델이 반환한 채팅 완성 응답을 나타냅니다.

```csharp
public class CompletionResponse : BaseResponse
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CompletionResponse](completionresponse/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | 채팅 완료 선택 목록을 가져오거나 설정합니다. n이 1보다 크면 하나 이상일 수 있습니다. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | 채팅 완료가 생성된 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 응답 세부 정보를 가져오거나 설정합니다. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 응답 오류를 가져오거나 설정합니다. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 오류 정보를 가져오거나 설정합니다. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 응답 헤더를 가져오거나 설정합니다. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP 상태 코드를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | 채팅 완료에 대한 고유 식별자를 가져오거나 설정합니다. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 응답이 성공했는지 여부를 나타냅니다. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | 채팅 완료에 사용되는 모델을 가져오거나 설정합니다. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | 객체 유형을 가져오거나 설정합니다. 이 값은 항상 chat.completion입니다. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 오류 이유 구문을 가져옵니다. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | 모델이 실행되는 백엔드 구성을 나타내는 지문을 가져오거나 설정합니다. 이는 시드 요청 매개변수와 함께 사용하여 결정성에 영향을 줄 수 있는 백엔드 변경이 언제 발생했는지 이해하는 데 활용될 수 있습니다. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | 완료 요청에 대한 사용 통계를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | 첫 번째 선택의 내용을 문자열로 반환합니다. |

### 또 보기

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)



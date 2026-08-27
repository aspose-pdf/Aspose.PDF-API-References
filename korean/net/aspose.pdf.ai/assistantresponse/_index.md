---
title: "클래스 AssistantResponse"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.AssistantResponse 클래스. 모델을 호출하고 도구를 사용할 수 있는 어시스턴트를 나타냅니다."
type: docs
weight: 140
url: /ko/net/aspose.pdf.ai/assistantresponse/
---
## AssistantResponse class

모델을 호출하고 도구를 사용할 수 있는 어시스턴트를 나타냅니다.

```csharp
public class AssistantResponse : BaseResponse
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | 어시스턴트가 생성된 시점의 Unix 타임스탬프(초)를 가져오거나 설정합니다. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | 어시스턴트의 설명을 가져오거나 설정합니다. 최대 길이는 512자입니다. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 응답 세부 정보를 가져오거나 설정합니다. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | HTTP 응답 오류를 가져오거나 설정합니다. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 오류 정보를 가져오거나 설정합니다. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | HTTP 응답 헤더를 가져오거나 설정합니다. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | HTTP 상태 코드를 가져오거나 설정합니다. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | API 엔드포인트에서 참조할 수 있는 식별자를 가져오거나 설정합니다. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | 어시스턴트가 사용하는 시스템 지시문을 가져오거나 설정합니다. 최대 길이는 256,000자입니다. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 응답이 성공했는지 여부를 나타냅니다. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | 객체에 첨부할 수 있는 16개의 키-값 쌍을 가져오거나 설정합니다. 이는 객체에 대한 추가 정보를 구조화된 형식으로 저장하는 데 유용합니다. 키는 최대 64자, 값은 최대 512자까지 가능합니다. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | 사용할 모델의 ID를 가져오거나 설정합니다. 사용 가능한 모든 모델을 보려면 List models API를 사용하거나 모델 개요에서 해당 모델에 대한 설명을 확인할 수 있습니다. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | 어시스턴트의 이름을 가져오거나 설정합니다. 최대 길이는 256자입니다. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | 객체 유형을 가져오거나 설정합니다. 이 값은 항상 assistant입니다. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 오류 이유 구문을 가져옵니다. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | 모델이 출력해야 하는 형식을 가져오거나 설정합니다. GPT-4o, GPT-4 Turbo 및 gpt-3.5-turbo-1106 이후의 모든 GPT-3.5 Turbo 모델과 호환됩니다. { "type": "json_object" } 로 설정하면 JSON 모드가 활성화되어 모델이 생성하는 메시지가 유효한 JSON임을 보장합니다. 중요: JSON 모드를 사용할 때는 시스템 또는 사용자 메시지를 통해 모델에게 JSON을 생성하도록 지시해야 합니다. 이를 하지 않으면 모델이 토큰 제한에 도달할 때까지 공백을 무한히 생성하여 오래 걸리고 "멈춘" 것처럼 보이는 요청이 발생할 수 있습니다. 또한 finish_reason="length"인 경우 메시지 내용이 부분적으로 잘릴 수 있으며, 이는 생성이 max_tokens를 초과했거나 대화가 최대 컨텍스트 길이를 초과했음을 나타냅니다. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | 0에서 2 사이의 샘플링 온도를 가져오거나 설정합니다. 0.8과 같은 높은 값은 출력을 더 무작위로 만들고, 0.2와 같은 낮은 값은 더 집중되고 결정적으로 만듭니다. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | assistant 도구에서 사용하는 리소스 집합을 가져오거나 설정합니다. 리소스는 도구 유형에 따라 다릅니다. 예를 들어, code_interpreter 도구는 파일 ID 목록이 필요하고, file_search 도구는 벡터 스토어 ID 목록이 필요합니다. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | 어시스턴트에 활성화된 도구 목록을 가져오거나 설정합니다. 어시스턴트당 최대 128개의 도구가 허용됩니다. 도구는 code_interpreter, file_search 또는 function 유형일 수 있습니다. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | 온도 샘플링의 대안인 핵심 샘플링을 가져오거나 설정합니다. 모델은 top_p 확률 질량을 가진 토큰 결과를 고려합니다. 따라서 0.1은 상위 10% 확률 질량을 가진 토큰만 고려한다는 의미입니다. 일반적으로 이 값이나 온도 중 하나만 조정하고 둘 다 조정하지 않는 것을 권장합니다. |

### 또 보기

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)



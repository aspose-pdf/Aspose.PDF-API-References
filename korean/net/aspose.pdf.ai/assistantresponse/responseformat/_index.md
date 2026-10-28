---
title: "AssistantResponse.ResponseFormat"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "AssistantResponse 속성. 모델이 출력해야 하는 형식을 가져오거나 설정합니다. GPT4o, GPT4 Turbo 및 gpt3.5turbo1106 이후의 모든 GPT3.5 Turbo 모델과 호환됩니다. type json_object 로 설정하면 JSON 모드가 활성화되어 모델이 생성하는 메시지가 유효한 JSON임을 보장합니다. JSON 모드를 사용할 때는 시스템 또는 사용자 메시지를 통해 모델에게 직접 JSON을 생성하도록 지시해야 합니다. 이를 하지 않으면 모델이 토큰 제한에 도달할 때까지 공백을 무한히 생성하여 오래 실행되고 멈춘 것처럼 보이는 요청이 발생할 수 있습니다. 또한 finish_reasonlength가 발생하면 메시지 내용이 일부 잘릴 수 있는데, 이는 생성이 max_tokens를 초과했거나 대화가 max context length를 초과했음을 나타냅니다."
type: docs
weight: 100
url: /ko/net/aspose.pdf.ai/assistantresponse/responseformat/
---
## AssistantResponse.ResponseFormat property

모델이 출력해야 하는 형식을 가져오거나 설정합니다. GPT-4o, GPT-4 Turbo 및 gpt-3.5-turbo-1106 이후의 모든 GPT-3.5 Turbo 모델과 호환됩니다. { "type": "json_object" } 로 설정하면 JSON 모드가 활성화되어 모델이 생성하는 메시지가 유효한 JSON임을 보장합니다. 중요: JSON 모드를 사용할 때는 시스템 또는 사용자 메시지를 통해 모델에게 JSON을 생성하도록 지시해야 합니다. 이를 하지 않으면 모델이 토큰 제한에 도달할 때까지 공백을 무한히 생성하여 오래 걸리고 "멈춘" 것처럼 보이는 요청이 발생할 수 있습니다. 또한 finish_reason="length"인 경우 메시지 내용이 부분적으로 잘릴 수 있으며, 이는 생성이 max_tokens를 초과했거나 대화가 최대 컨텍스트 길이를 초과했음을 나타냅니다.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### 또 보기

* class [ResponseFormat](../../responseformat/)
* class [AssistantResponse](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



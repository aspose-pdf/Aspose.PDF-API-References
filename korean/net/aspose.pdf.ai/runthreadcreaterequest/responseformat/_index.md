---
title: RunThreadCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: RunThreadCreateRequest 속성. 모델이 출력해야 하는 형식을 가져오거나 설정합니다. gpt3.5turbo1106 이후의 GPT-4o, GPT-4 Turbo 및 모든 GPT-3.5 Turbo 모델과 호환됩니다. "type": "json_object" 로 설정하면 JSON 모드가 활성화되어 모델이 생성하는 메시지가 유효한 JSON임을 보장합니다. 중요: JSON 모드를 사용할 때는 시스템 또는 사용자 메시지를 통해 모델이 JSON을 생성하도록 지시해야 합니다. 그렇지 않으면 모델이 공백의 끝없는 스트림을 생성할 수 있으며, 생성이 토큰 한도에 도달할 때까지 계속되어 긴 실행 시간과 "멈춘" 요청이 발생할 수 있습니다. 또한 finish_reason="length"인 경우 메시지 내용이 부분적으로 잘릴 수 있으며, 이는 생성이 max_tokens를 초과했거나 대화가 최대 컨텍스트 길이를 초과했음을 나타냅니다.
type: docs
weight: 80
url: /ko/net/aspose.pdf.ai/runthreadcreaterequest/responseformat/
---
## RunThreadCreateRequest.ResponseFormat 속성

모델이 출력해야 하는 형식을 가져오거나 설정합니다. gpt-3.5-turbo-1106 이후의 GPT-4o, GPT-4 Turbo 및 모든 GPT-3.5 Turbo 모델과 호환됩니다. { "type": "json_object" }로 설정하면 JSON 모드가 활성화되어 모델이 생성하는 메시지가 유효한 JSON임을 보장합니다. 중요: JSON 모드를 사용할 때는 시스템 또는 사용자 메시지를 통해 모델이 JSON을 생성하도록 지시해야 합니다. 그렇지 않으면 모델이 공백의 끝없는 스트림을 생성할 수 있으며, 생성이 토큰 한도에 도달할 때까지 계속되어 긴 실행 시간과 "멈춘" 요청이 발생할 수 있습니다. 또한 finish_reason="length"인 경우 메시지 내용이 부분적으로 잘릴 수 있으며, 이는 생성이 max_tokens를 초과했거나 대화가 최대 컨텍스트 길이를 초과했음을 나타냅니다.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### 참조

* 클래스 [ResponseFormat](../../responseformat/)
* 클래스 [RunThreadCreateRequest](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)
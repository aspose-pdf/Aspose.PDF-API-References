---
title: CompletionCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: CompletionCreateRequest 속성. 모델이 호출하는 도구가 있는지 제어하는 객체를 가져오거나 설정합니다. none은 모델이 어떤 도구도 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것 중에서 선택할 수 있음을 의미합니다. required는 모델이 하나 이상의 도구를 호출해야 함을 의미합니다. "type" "function", "function" "name" "my_function" 를 통해 특정 도구를 지정하면 모델이 해당 도구를 호출하도록 강제합니다. 도구가 없을 때 none이 기본값입니다. 도구가 있을 경우 auto가 기본값입니다.
type: docs
weight: 150
url: /ko/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## CompletionCreateRequest.ToolChoice 속성

모델이 호출하는 도구가 있는지 제어하는 객체를 가져오거나 설정합니다. none은 모델이 어떤 도구도 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것 중에서 선택할 수 있음을 의미합니다. required는 모델이 하나 이상의 도구를 호출해야 함을 의미합니다. {"type": "function", "function": {"name": "my_function"}}를 통해 특정 도구를 지정하면 모델이 해당 도구를 호출하도록 강제합니다. 도구가 없을 때 none이 기본값입니다. 도구가 있을 경우 auto가 기본값입니다.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### 참조

* class [ToolChoice](../../toolchoice/)
* class [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)
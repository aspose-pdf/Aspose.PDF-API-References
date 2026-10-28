---
title: "CompletionCreateRequest.ToolChoice"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "CompletionCreateRequest 속성. 모델이 호출할 도구를 제어하는 객체를 가져오거나 설정합니다. none은 모델이 도구를 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것을 선택할 수 있음을 의미합니다. required는 모델이 하나 이상의 도구를 반드시 호출해야 함을 의미합니다. type function function name my_function 과 같이 특정 도구를 지정하면 모델이 해당 도구를 호출하도록 강제합니다. 도구가 없을 때는 none이 기본값이며, 도구가 존재할 경우 auto가 기본값입니다."
type: docs
weight: 150
url: /ko/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## CompletionCreateRequest.ToolChoice property

모델이 호출할 도구(있는 경우)를 제어하는 객체를 가져오거나 설정합니다. none은 모델이 도구를 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것을 선택할 수 있음을 의미합니다. required는 모델이 하나 이상의 도구를 반드시 호출해야 함을 의미합니다. {"type": "function", "function": {"name": "my_function"}}와 같이 특정 도구를 지정하면 모델이 해당 도구를 호출하도록 강제합니다. 도구가 없을 때는 none이 기본값이며, 도구가 있을 경우 auto가 기본값입니다.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### 또 보기

* class [ToolChoice](../../toolchoice/)
* class [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)



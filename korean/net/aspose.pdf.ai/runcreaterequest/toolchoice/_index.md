---
title: RunCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: RunCreateRequest 속성. 모델이 호출하는 도구가 있는 경우（있는 경우） 설정하거나 가져옵니다. none은 모델이 도구를 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 기본값이며 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것 중에서 선택할 수 있음을 의미합니다. required는 모델이 사용자에게 응답하기 전에 하나 이상의 도구를 호출해야 함을 의미합니다. "type" "file_search" 또는 "type" "function", "function" "name" "my_function" 와 같은 특정 도구를 지정하면 모델이 해당 도구를 호출하도록 강제합니다.
type: docs
weight: 130
url: /ko/net/aspose.pdf.ai/runcreaterequest/toolchoice/
---
## RunCreateRequest.ToolChoice 속성

모델이 호출하는 도구가 있는 경우(있는 경우) 설정하거나 가져옵니다. none은 모델이 도구를 호출하지 않고 대신 메시지를 생성함을 의미합니다. auto는 기본값이며 모델이 메시지를 생성하거나 하나 이상의 도구를 호출하는 것 중에서 선택할 수 있음을 의미합니다. required는 모델이 사용자에게 응답하기 전에 하나 이상의 도구를 호출해야 함을 의미합니다. {"type": "file_search"} 또는 {"type": "function", "function": {"name": "my_function"}}와 같은 특정 도구를 지정하면 모델이 해당 도구를 호출하도록 강제합니다.

```csharp
public string ToolChoice { get; set; }
```

### 참조

* 클래스 [RunCreateRequest](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)